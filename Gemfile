source "https://rubygems.org"
gem "jekyll-theme-clean-blog"

#gem "jekyll", "~> 3.6.0"
#uncomment the below line to run on GitHub pages
gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate", "~> 1.1.0"
  gem "jekyll-admin"
  gem "addressable", "~> 2.4.0"
end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end
