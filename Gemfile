source 'https://rubygems.org'

gem "docker-api", :git => "https://github.com/mastahyeti/docker-api", :branch => "build_from_tar"

gemspec

# Load dependency Gemfile if present.
inmate_gemfile = File.join(File.dirname(__FILE__), 'inmate', 'Gemfile')
if File.exist? inmate_gemfile
  eval(IO.read(inmate_gemfile), binding)
end
