# Palindrome detector

`tac_palindrome` is a simple Ruby gem created to detect palindromes

## Installation

To install `tac_palindrome`, add this line to your application's `Gemfile`:

```
gem 'tac_palindrome'
```

Then install as follows:

```
$ bundle install
```

Or install it directly using `gem`:

```
$ gem install tac_palindrome
```

## Usage

`tac_palindrome` adds a `palindrome?` method to the `String` class, and can be used as follows:

```
$ irb
>> require 'tac_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba.".palindrome?
=> true
>> phrase = "Madam, I'm Adam."
>> phrase.palindrome?
=> true
```

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).