source "https://rubygems.org"

gem "jekyll", "~> 4.4.1"
gem "no-style-please", "~> 0.1.0"
# gem "minima", "~> 2.5"      # ← no-style-please만 쓸 거면 이 줄은 주석 처리하세요.

# Jekyll 플러그인
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jektex"
end

# 마크다운 파서(GitHub 스타일)
gem "kramdown-parser-gfm"

# Jekyll 4.x에서는 webrick 필요 (서버 실행용)
gem "webrick"

# Ruby 표준 라이브러리 보조 Gem
gem "csv"
gem "bigdecimal"
gem "base64"
gem "logger"

# 플랫폼별 추가 Gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Gemfile에 gemspec 줄은 필요 없다면 생략 가능 (테마 개발자가 아니면)
# gemspec
