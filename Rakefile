require 'html-proofer'

task default: %w[lint]

task :lint do
  exec 'find . -name "*.md" | grep -v "^.\/vendor\/" | xargs mdl'
end

task :htmlproofer do
  options = { :only_4xx => true, :url_ignore => [/github\.com\/pages/] }
  HTMLProofer.check_directory("./_build/html", options).run
end
