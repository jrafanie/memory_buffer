# MemoryBuffer

Ruby module to create memory buffers on Linux and Mac platforms.

[![Gem Version](https://badge.fury.io/rb/memory_buffer.svg)](http://badge.fury.io/rb/memory_buffer)
[![Build Status](https://travis-ci.org/ManageIQ/memory_buffer.svg)](https://travis-ci.org/ManageIQ/memory_buffer)
[![Code Climate](http://img.shields.io/codeclimate/github/ManageIQ/memory_buffer.svg)](https://codeclimate.com/github/ManageIQ/memory_buffer)
[![Dependency Status](https://gemnasium.com/ManageIQ/memory_buffer.svg)](https://gemnasium.com/ManageIQ/memory_buffer)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'memory_buffer'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install memory_buffer

## Usage

MemoryBuffer supports `.create_aligned_string` to create a Ruby string from a buffer obtained via [memalign](http://linux.die.net/man/3/memalign).

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake rspec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ManageIQ/memory_buffer.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

