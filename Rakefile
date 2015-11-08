desc "Pull and update"
task :update do
  sh 'git pull origin master'
  sh 'npm install -g resume-cli'
end

desc "Build resume"
task :build do
  sh "echo index | resume export --theme=elegant --format=html --force"
end
