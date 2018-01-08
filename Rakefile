task default: %w[lint]

task :lint do
  exec 'find . -name -path ./vendor -prune -o -name "*.md" | xargs mdl'
end

