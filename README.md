# Answers
This is my repository of ziglins answers, this is a good place if your lost
or do not know how to complete a specific ziglins challenge

this is also a repo for me to keep track of how mutch ziglins answers i have done to learn the language in full,
this should not take me that long as i already have built up knowlege or low level / systems level programming, with rust, c, and haskell 

if you have any specific question you think i could have done better you might aswell make a pull request and i will look over it and see if it works well with their examples.


# Ziglings

Welcome to Ziglings! This project contains a series of tiny
broken programs (and one nasty surprise).  By fixing them, you'll
learn how to read and write [Zig](https://ziglang.org/) code.

![Ziglings](images/ziglings.jpg "Ziglings")

Those broken programs need your help! (You'll also save the
planet from evil aliens and help some friendly elephants stick
together, which is very sweet of you.)

This project was directly inspired by the brilliant and fun
[rustlings](https://github.com/rust-lang/rustlings)
project for the [Rust](https://www.rust-lang.org/) language.
Indirect inspiration comes from [Ruby Koans](http://rubykoans.com/)
and the Little LISPer/Little Schemer series of books.

## Intended Audience

This will probably be difficult if you've _never_ programmed
before.  But no specific programming experience is required. And
in particular, you are _not_ expected to have any prior
experience with "systems programming" or a "systems" level
language such as C.

Each exercise is self-contained and self-explained. However,
you're encouraged to also check out these Zig language resources
for more detail:

* https://ziglang.org/learn/
* https://ziglearn.org/
* https://ziglang.org/documentation/master/
* [Zig in Depth! (video series)](https://www.youtube.com/watch?v=MMtvGA1YhW4&list=PLtB7CL7EG7pCw7Xy1SQC53Gl8pI7aDg9t&pp=iAQB)

Also, the [Zig community](https://github.com/ziglang/zig/wiki/Community)
is incredibly friendly and helpful!

## Getting Started

Install a [development build](https://ziglang.org/download/) of
the Zig compiler.  (See the "master" section of the downloads
page.)

Verify the installation and build number of `zig` like so:

```
$ zig version
0.13.0-dev.xxxx+xxxxxxxxx
```

Clone this repository with Git:

```
$ git clone https://ziglings.org
$ cd ziglings.org
```

Then run `zig build` and follow the instructions to begin!

```
$ zig build
```

Note: The output of Ziglings is the unaltered output from the Zig
compiler. Part of the purpose of Ziglings is to acclimate you to
reading these.

## A Note About Versions

**Hint:** To check out Ziglings for a stable release of Zig, you can use
the appropriate tag. 

The Zig language is under very active development. In order to be
current, Ziglings tracks **development** builds of the Zig
compiler rather than versioned **release** builds. The last
stable release was `0.12.0`, but Ziglings needs a dev build with
pre-release version "0.13.0" and a build number at least as high
as that shown in the example version check above.

It is likely that you'll download a build which is _greater_ than
the minimum.

Once you have a build of the Zig compiler that works with
Ziglings, they'll continue to work together. But keep in mind
that if you update one, you may need to also update the other.

