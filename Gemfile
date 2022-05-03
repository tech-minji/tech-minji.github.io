source "https://rubygems.org"
gemspec
gem "webrick", "~> 1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# 'bundle update' 생략이 문제인지 몰랐음
# gem 'tzinfo'
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
# https://jekyllrb.com/docs/installation/windows/
# 아래 라인 추가하고 'bundle update' 실행 뒤에 'bundle exec jekyll serve' 하니 잘 됨
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
  end