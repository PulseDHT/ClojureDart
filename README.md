<img src="logo1024.png" width="100%">

# What is ClojureDart?

ClojureDart is a port of the Clojure language to Dart.

Its primary goal is to leverage Dart and Flutter to extend Clojure's reach to
mobile and desktop apps.

# Foreword

We promised to publicly release ClojureDart before Easter 2022, so here it is!

This doesn't represent a specific technical milestone, it's still a work-in-progress but we believe it's good enough for use by the bravest Clojurists.

# Who is behind it?

Tensegritics, an itty-bitty Clojure consultancy by [Baptiste Dupuch](https://github.com/dupuchba)[🐦](https://twitter.com/BaptisteDupuch) and [Christophe Grand](https://github.com/cgrand)[🐦](https://twitter.com/cgrand).

# Status

Here be Dragons!

ClojureDart is a work-in-progress. Some features may be outright missing or
partially implemented or even bugged. In any case get in touch with us or open
an issue.

- no REPL yet
- multi-method (WIP)
- sorted-collection (WIP)

Some differences have been documented, see [Differences with Clojure](doc/differences.md).

# Quick starts

- [Plain Dart](doc/quick-start.md) (recommended first step)
- [With Flutter](doc/flutter-quick-start.md)

# `cljd.flutter.alpha`

`cljd.flutter.alpha` is an utility namespace to remove Flutter boilerplate and integrate it a bit more with Clojure.

[Learn more about it!](doc/flutter-helpers.md)

# Going further with Flutter

In the [samples directory](samples/) you'll find some ports of [Flutter recipes](https://docs.flutter.dev/cookbook**.

## How to run a sample project

Clone the ClojureDart repo.

```shell
git clone https://github.com/Tensegritics/ClojureDart.git
```

Go to the sample you want to try, let's say `fab`:

```shell
cd ClojureDart/samples/fab
```

Init the project:
```shell
clj -M -m cljd.build init sample.fab
```

Start a simulator or connect a device.

Then launch the watcher:
```shell
clj -M -m cljd.build flutter
```

Enjoy! 🧃

# Thanks!

To all individuals who blindly believed in our endeavor and sponsored our work.

To NuBank who approached us very early for sponsorship.

To Roam Research who bet their mobile apps development (now in the App Store and Play Store) on ClojureDart and allowed us to make steady progress since Summer 2021.

If you want to sponsor our work, you can sponsor either of us, we'll balance sponsorship. If you are a company you can also contact us directly.
