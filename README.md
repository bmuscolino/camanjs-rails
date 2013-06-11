camanjs-rails
=============

[http://camanjs.com/|CamanJS] as a Rails >=3.1 asset pipline gem.

## Installation

Add this line to your application's Gemfile:

    gem 'camanjs-rails', git: 'git@github.com:ksz2k/camanjs-rails.git'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install camanjs-rails

## Usage

Add the following directive to your Javascript manifest file (application.js):

    //= require camanjs/caman.full

If you want to include an jQuery adapter file, also add the following:

    //= require camanjs/adapters/jquery

If you want to include a plugin file, also add the following:

    //= require camanjs/plugins/<plugin>

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## See also

* https://github.com/Dinuz/camanjs-rails
