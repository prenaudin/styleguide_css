# guard 'sass', :input => 'sass', :output => 'build', :compass => true

guard "hologram", config_path: "hologram.yml" do
  watch('assets/css/styles.css')
  watch('assets/css/vendors.css')
  watch(%r{doc_assets/.+})
  watch('sass/index.md')
end

guard 'livereload' do
  watch(%r{styleguide/.+\.(html|png|css)})
  watch(%r{styleguide/.+\.(html|png|css)})
end

guard 'compass', configuration_file: 'config.rb'
