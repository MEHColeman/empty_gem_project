# Rails Project Template

This project is a simple template creating new gem project with some useful
defaults.

Clone this project into your desired directory and run `bin/setup`
~~~
~/projects>hub clone MEHColeman/empty_gem_project new_gem
~/projects>cd new_gem
~/projects/new_thing>bin/create
~~~

This will:
  * Configure some stuff
  * Run some code generators to set up a default testing framework
  * Tidy up the generated code
  * Replace this README with a new template for your new project.
  * Create a new, clean git repository with a single initial commit of your new
    files.

## Make tasks
There are some commands set up in a Makefile to run various code quality
checks.

Makefile contains:
make secure    # run bundle audit to check for known vulnerabilities
make quality   # run rubycritic and simplecov
make fast      # run fasterer
make all       # all of the above

## License

This code is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
