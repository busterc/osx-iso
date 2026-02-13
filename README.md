# OSX-ISO

> Create a bootable ISO of OS X / macOS, from the installation app file.

## Prerequisites

The appropriate installation app file(s) must be located in `/Applications` i.e.

```
/Applications/Install macOS Tahoe.app
/Applications/Install macOS Sequoia.app
/Applications/Install macOS Sonoma.app
/Applications/Install macOS Ventura.app
/Applications/Install macOS Monterey.app
/Applications/Install macOS Big Sur.app
/Applications/Install macOS Catalina.app
/Applications/Install macOS Mojave.app
/Applications/Install macOS High Sierra.app
/Applications/Install macOS Sierra.app
/Applications/Install OS X El Capitan.app
/Applications/Install OS X Yosemite.app
/Applications/Install OS X Mavericks.app
```

- See: [How to download macOS](https://support.apple.com/en-us/102662)

## Install with [Homebrew](https://brew.sh)

```sh
$ brew tap busterc/tap
$ brew install osx-iso
```

## Usage

```sh
$ osxiso

 1) macOS Tahoe
 2) macOS Sequoia
 3) macOS Sonoma
 4) macOS Ventura
 5) macOS Monterey
 6) macOS Big Sur
 7) macOS Catalina
 8) macOS Mojave
 9) macOS High Sierra
10) macOS Sierra
11) OS X El Capitan
12) OS X Yosemite
13) OS X Mavericks
14) Quit

Select OS or Quit:
```

## License

ISC License (ISC)

Copyright &copy; 2015-2026, Buster Collings

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
