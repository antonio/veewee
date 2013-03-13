#if RUBY_VERSION =~ /1.9/
    #Encoding.default_external = Encoding::UTF_8
    #Encoding.default_internal = Encoding::UTF_8
#end

source "http://rubygems.org"

gem 'fog', :git => 'https://github.com/calavera/fog.git'
gem 'vagrant', :git => 'https://github.com/calavera/vagrant.git'

group :kvm do
  gem "ruby-libvirt"
end

group :test do
  gem "rake"
  gem "em-winrm", :git => 'https://github.com/hh/em-winrm.git', :ref => '31745601d3'
end

gemspec
