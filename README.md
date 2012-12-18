# Timecard

Timecard is a Python script that calculates the durations of tasks that you have tracked using Quicktask (my lightweight Vim task management plugin).

Although it is around 160 lines of insane recursive text parsing, it's not very feature-rich. Please help me make it better!

Timecard runs on the command line and requires Python and the `argparse` and `dateutil` libraries. You can usually pick those up by running something like:

```
$ pip install argparse
$ pip install python-dateutil
```

If you don't have these libraries and you attempt to run Timecard, it will nag you.

# Usage

Obviously your first stop is `timecard --help`. There are a few options.

# License

This software is made available to you graciously and without expectation of recompense by Aaron Bieber. It has no license, nor warranty, nor expressed suitability for any purpose, etc., etc.
