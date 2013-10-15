# vim: syntax=ruby
load 'tasks/this.rb'

This.name     = "stickler"
This.author   = "Jeremy Hinegardner"
This.email    = "jeremy@copiousfreetime.org"
This.homepage = "http://github.com/copiousfreetime/#{ This.name }"


This.ruby_gemspec do |spec|
  spec.add_runtime_dependency( 'sinatra'    , '~> 1.4'  )
  spec.add_runtime_dependency( 'addressable', '~> 2.3'  )
  spec.add_runtime_dependency( 'excon'      , '~> 0.27.3'  )
  spec.add_runtime_dependency( 'trollop'    , '~> 2.0' )
  spec.add_runtime_dependency( 'logging'    , '~> 1.8.1'  )

  # The Development Dependencies
  spec.add_development_dependency( 'rake'        , '~> 10.1'  )
  spec.add_development_dependency( 'rack-test'   , '~> 0.6.2' )
  spec.add_development_dependency( 'builder'     , '~> 3.2'   )
  spec.add_development_dependency( 'minitest'    , '~> 5.0'   )
  spec.add_development_dependency( 'rdoc'        , '~> 4.0'   )
  spec.add_development_dependency( 'ronn'        , '~> 0.7.3' )

end

load 'tasks/default.rake'
load 'tasks/man.rake'
