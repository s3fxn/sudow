# sudow

sudow - sudo wrapper to avoid secure_path.

**This command bypass the security mechanism called secure_path.**

**You need to know the risk before use.**

## Installation

    $ gem install sudow

## Usage

```
$ sudow command args...


$ which gem
/usr/local/ruby2.5.1/bin/gem

$ sudo gem install ...
sudo: gem: command not found

$ sudow gem install ...
sudo /usr/local/ruby2.5.1/bin/gem install ...
Fetching: ...

*This command bypass the security mechanism called secure_path.*
*You need to know the risk before use.*
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/s3fxn/sudow.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
