## Installation

The Flox Direnv intigation can be installed in the following ways.

By using Direnv's `source_url`:

```sh
source_url 'https://raw.githubusercontent.com/flox/flox-direnv/1.0.0/direnv.rc' 'sha256-kVnfzXozKxk7+MgZ2U9qU7Ob+s4PBFqPTGVZmQerJow='
```

By copying the `direnv.rc` file into the `~/.config/direnv/lib/` directory

```console
$ curl -o "~/.config/direnv/lib/flox-direnv.rc" 'https://raw.githubusercontent.com/flox/flox-direnv/1.0.0/direnv.rc'
```

## Usage

Add the following to your project's `.envrc` file.

```console
$ echo 'use flox' >> .envrc
```

If you'd like to use a remote environment instead of the local one, populate your `.envrc` as follows.

```console
$ echo 'use flox --remote=<owner>/<name>' >> .envrc
```

And to trust the remote envrionment explicitly.

```console
$ echo 'use flox --trust --remote=<owner>/<name>' >> .envrc
```

## Hello from the Flox team!

...
