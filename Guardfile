guard :rspec do
  watch(%r{^spec/unit/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})     { |m| "spec/unit/lib/#{m[1]}_spec.rb" }
  watch('spec/spec_helper.rb')  { "spec" }
end

