
begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

task :default => 'test:run'
task 'gem:release' => 'test:run'

Bones {
  name  'bones-yard'
  authors  'Tim Pease'
  email  'tim.pease@gmail.com'
  url  'http://github.com/TwP/bones-yard'
  ignore_file  '.gitignore'
}

