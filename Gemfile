source "https://rubygems.org"

# GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Webrick for Ruby 3.x compatibility
gem "webrick", "~> 1.7"

# Windows and JRuby compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.3", :platforms => [:jruby] 