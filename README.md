A command line wrapper around the GNU Privacy Guard (GPG) library to make it sane.

Requires Ruby 1.9 and [GnuPG](http://www.gnupg.org/). I recommend `brew install gnupg`.

## Installation

```console
$ git clone https://github.com/h3h/pgp-ruby.git

$ ln -s pgp-ruby/pgp ~/bin/pgp

$ which pgp
/Users/foo/bin/pgp
```

## Usage

Friendly human commands to wrap `gpg (1)`’s ugly ones.

```console
$ pgp list

$ pgp sign 12345EFA

$ pgp encrypt my_file for foo@example.com

$ pgp pull

$ pgp push 12345EFA

$ pgp export 12345EFA

```

## Author

Brad Fults (bfults@gmail.com)

## License

Licensed under the MIT License. See LICENSE.
