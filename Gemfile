# frozen_string_literal: true

source "https://rubygems.org"
gemspec
git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", "~> 4.3"
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
gem "jekyll-last-modified-at", git: "https://github.com/maximevaillancourt/jekyll-last-modified-at", branch: "add-support-for-files-in-git-submodules"
gem "webrick", "~> 1.8"
gem "nokogiri"
