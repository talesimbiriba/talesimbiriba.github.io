



desc "Preview _site/"
task :preview do
  puts "\n## Opening _site/ in browser"
  status = system("google-chrome http://0.0.0.0:4000/")
  puts status ? "Success" : "Failed"
end


desc "Clean _site/"
task :clean do
  puts "\n## building using jekyll"
  status = system("rm -rf _site")
  puts status ? "Success" : "Failed"
  message = "Build site at #{Time.now.utc}"
end


desc "Build _site/"
task :build do
  puts "\n## building using jekyll"
  status = system("bundle exec jekyll build")
  puts status ? "Success" : "Failed"
  message = "Build site at #{Time.now.utc}"
end

desc "Commit site changes"
task :commit do
  puts "\n## Staging modified files"
  status = system("git add -A")
  puts status ? "Success" : "Failed"
  puts "\n## Committing a site build at #{Time.now.utc}"
  message = "Build site at #{Time.now.utc}"
  status = system("git commit -m \"#{message}\"")
  puts status ? "Success" : "Failed"
  puts "\n## Pushing commits to remote"
  status = system("git push origin source")
  puts status ? "Success" : "Failed"
end

desc "Deploy _site/ to master branch"
task :deploy do
  puts "\n## Deleting content of master branch"
  status = system("git checkout master")
  status = system("rm Gemfile.lock")
  status = system("git rm -r *") 
  puts status ? "Success" : "Failed"
  puts "\n## Forcing the _site subdirectory to be project root"
  status = system("mv  _site/* .")
  status = system("rm -r  _site/")
  puts status ? "Success" : "Failed"
  puts "\n## Staging modified files"
  status = system("git add -A")
  puts status ? "Success" : "Failed"
  puts "\n## Committing master at #{Time.now.utc}"
  message = "Build site at #{Time.now.utc}"
  status = system("git commit -m \"#{message}\"")
  puts status ? "Success" : "Failed"
  puts "\n## Pushing commits to remote"
  status = system("git push origin master")
  puts status ? "Success" : "Failed"
end


desc "running rake default settings"
task :default => ["clean","commit","build", "deploy"] do
  puts "\n## All done!"
end
