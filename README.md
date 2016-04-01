# weave-osx-ctl

A utility script for exposing Weave Net to the Mac, using Docker for Mac.

## Usage:

    weave-osx-ctl [ setup | reset | status | --help ]

## Options:

    --accept     Avoid interactive prompts - assumes a 'yes' answer to each question
    --debug      Sets the -x bit in bash to print output as the script executes
    --verbose    Prints more information as the script executes

## Summary:

    Configures routes to IP addresses of containers created using
    Docker for Mac (based on xhyve).

    The script times out after 60 seconds if no input is received.