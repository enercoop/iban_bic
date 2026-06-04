# frozen_string_literal: true

source "https://rubygems.org"
ruby file: ".ruby-version"

# Declare your gem's dependencies in iban_bic.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

group :development, :test do
  gem "byebug", platform: :mri

  gem "benchmark"
  gem "bigdecimal"
  gem "drb"
  gem "mutex_m"
  gem "ostruct"
end
