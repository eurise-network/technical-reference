task default: %w[lint]

task :lint do
  exec 'find . -name "*.md" | grep -v "^.\/vendor\/" | xargs mdl'
end

