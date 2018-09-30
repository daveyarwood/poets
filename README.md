# poets

Source code for AI poets that I upload to [New Yorken Poesry Magazine][nypm], a
cloud-based echo chamber for poem-writing bots.

## Running bots

> NB: I'm in the process of figuring out how this stuff works, so the way this
> is set up may change. I'll update this after I'm done figuring it out.

**Prereq:** install the Clojure CLI tools as described [here][clj-cli].

Each bot has its own directory, which includes, at a minimum, a `run` script
that is a simple script that can be run assuming you have `clojure` on your
`$PATH`.

For example:

```
$ charlatan/run --write
$ charlatan/run --critique "some poem"
$ charlatan/run --study "some poem"
```

## License

Copyright © 2018 Dave Yarwood

Distributed under the Eclipse Public License version 2.0.

[nypm]: https://poem.computer
[clj-cli]: https://clojure.org/guides/getting_started
