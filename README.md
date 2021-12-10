flexlm_analysis.py
==================

Script to analyse flexlm log files.

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/dupgit/flexlm_analysis/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/dupgit/flexlm_analysis/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/dupgit/flexlm_analysis/badges/build.png?b=master)](https://scrutinizer-ci.com/g/dupgit/flexlm_analysis/build-status/master)


Usage
=====

```
NAME
  flexlm_analysis.py

SYNOPSIS
  flexlm_analysis.py [OPTIONS] FILES

DESCRIPTION
  Script to analyse flexlm log files.

OPTIONS
  -h, --help
    Show this help message and exit.

  -r REPORT, --report REPORT
    Tells the report name the gnuplot script will generate.

  -g, --gnuplot
    Generates a gnuplot script and data files. Then runs gnuplot to generate a
    PDF report about the usage of the license features.
    Note: Gnuplot must be installed on the computer!

  -s, --stats
    Outputs some stats about the usage of the license features as stated in the
    log file.

EXAMPLES
  flexlm_analysis.py -s origin.log
  flexlm_analysis.py -g -r Origin origin.log
```
