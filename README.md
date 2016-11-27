# NyMegaLotto

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ny_mega_lotto'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ny_mega_lotto

## Usage

Test app. generates random lotto numbers

```ruby
winning_numbers = NyMegaLotto::Drawing.new.draw

puts winning_numbers
```



## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
