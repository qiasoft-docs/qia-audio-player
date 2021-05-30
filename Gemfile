source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "just-the-docs"

group :jekyll_plugins do
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
