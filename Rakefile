task default: :test

desc "Test website"
task :test do
  require "html-proofer"
  sh "bundle exec jekyll build"
  HTMLProofer.check_directory("./_site", assume_extension: true).run
end
