source 'https://rubygems.org'
group :jekyll_plugins do
  gem "github-pages"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
end

gem "webrick", "~> 1.7"

#  Windows에서 Jekyll 파일 변경 감지 빠름 ( 로컬 개발 속도 개선 )
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# Hot Reload처럼 보이지만, 실제로는 Hot Reload(HMR) 와는 조금 다른 개념
# Jekyll의 파일 변경을 감지해서 브라우저를 자동으로 새로고침해주는 기능 - "Live Reload (자동 새로고침)" 기능
gem 'jekyll-livereload'
