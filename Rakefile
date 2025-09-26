INSTALL_DIR = ENV['PROJECT_DIR']

task :srcinstall do
  puts 'installing phply scripts'
  ['unparse.py', 'php2python.py', 'php2json.py', 'php2jinja.py'].each do |f|
    sh "chmod +x tools/#{f} && install -c tools/#{f} #{INSTALL_DIR}"
  end
end
