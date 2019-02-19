Scalp-all! is a fork of nanopony's fork of the GoogleCode-based. Our aim is to automate the process of scalping apache, iis, webtob, other servers web logs.

# Scalp-all!

Original Scalp! is a log analyzer for the Apache web server that aims to look for security problems developed by Romain Gaucher. The main idea is to look through huge log files and extract the possible attacks that have been sent through HTTP/GET (By default, Apache does not log the HTTP/POST variable).

default_filters.xml is a part of PHP IDS project;

Scalp-all! that I arbitrarily modified is a log analyzer for various web server logs. I'll add more web server log format and regex argument for line catching.   

## How it works, Usage, Help, Features

Please see the site(https://github.com/nanopony/apache-scalp). 

## added-Usage 

-F, --format : the log file format 'apache' by default, available list is apache, webtob, iis, ...
(ex) ./scalp-0.4.revision.py -l log.txt -f ./default_filter.xml -F iis -o ./scalp-output --txt 

