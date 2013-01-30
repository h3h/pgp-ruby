A command line wrapper around the GNU Privacy Guard (GPG) library to make it sane.

Requires Ruby 1.9 and [GnuPG](http://www.gnupg.org/). I recommend `brew install gnupg`.

## Usage

Friendly human commands to wrap `gpg (1)`’s ugly ones.

```console
$ pgp sign 12345EFA

$ pgp push 12345EFA

$ pgp export 12345EFA

$ pgp pull

$ pgp list
```

## Author

Brad Fults (bfults@gmail.com)

## License

Licensed under the MIT License. See LICENSE.
