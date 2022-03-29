## Rails 3 rspec failure in Rubymine

The command

    rspec ./spec/models/simple_spec.rb

will pass from the command line if you have an rvm environment with jruby-9.0.5.0@rails3.2.22.2

However, when run from within Rubymine by right clicking the simple_spec test and run or debug,
it fails with

    jruby: no Ruby script found in input (LoadError)
