# doit-cli
**A foundation for building your own suite of command line tools.**

This is inspired by [Slack magic-cli](https://medium.com/@SlackEng/4a1bb5fe905b).

magic-cli exists to make it easy to create a set of tools that work together.  It's not a tool you use as-is; it's here to offer a starting point for your own custom command line tools.

Learn more about the origins of magic-cli in [The Joy of Internal Tools](https://medium.com/@SlackEng/4a1bb5fe905b), a post on the Slack Engineering blog.

## Installation
This repository includes a Makefile that will install `doit-cli` and all of its subcommands into `/usr/local/bin`:

````bash
$ make install
````

You can also use it to uninstall `doit-cli`:

````bash
$ make uninstall
````

## Updates

An example script for updating the tools is also included; it makes installing the latest tools into a single step process:

```bash
$ doit-cli update
Updated tools to 01ec2ef (2016-03-30 16:20:30 -0700)
```

## Reunning directly

Some scripts can be run directly, without cloning the repo:

1. Useful ubuntu: `wget https://raw.githubusercontent.com/rafaelbernard/doit/master/doit-useful-ubuntu -O - | sudo bash`

## Links

https://github.com/slackhq/magic-cli
https://slack.engineering/the-joy-of-internal-tools-4a1bb5fe905b#.fi5lnlxnk
