# ttl

Command line program to display DNS Time To Live (TTL) numbers in
easily-readable formats.

## Usage

    $ ttl [-s] [-t type] -h domain

* -s: Show TTL in seconds (rather the default HH:MM:SS format)
* -t: Give a DNS record type to query for the domain
* -h: Display this help message

## Requirements

You'll need a copy of `dig` installed on your system.

## Author

This was thrown together in ten minutes by Dave Cross (dave@davecross.co.uk).
He'd love to know if you found it useful.

## Code

The code is on Github at https://github.com/davorg/ttl. Patches are very
welcome.

## Copyright

Copyright (c) Magnum Solutions Ltd. All rights reserved. This program is
free software; you can redistribute it and/or modify it under the same
terms as Perl itself.
