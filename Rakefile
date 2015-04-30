desc "Install resume-cli"
task :install_deps do
  sh 'npm install -g resume-cli'
end

desc "Build resume"
task :build do
  sh "echo index | resume export --theme=elegant --format=html --force"
end
