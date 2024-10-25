
# The Flinch link checker

https://github.com/joto/flinch

Flinch is a powerful and flexible web link checker that will make your life
as a web designer or web server admin easier. Flinch is implemented in Perl
and released under the GPL (GNU General Public License). It can be used to
check all the external links on your web pages periodically and produce HTML
reports of its findings. If a web resource at the end of a link has not been
reachable for a few days, Flinch can send you an email.

For installation instructions see the HTML documentation in the doc directory.

## Prerequisites

Flinch needs the Perl modules XML::Generator, XML::Parser::PerlSAX,
HTML::LinkExtor, LWP::UserAgent, URI, Digest::MD5, and HTTP::Status from
[CPAN](https://www.cpan.org/).

On Debian/Ubuntu systems you can install the following packages:

```
apt install libxml-generator-perl libxml-perl liburi-perl libdigest-md5-perl \
            libwww-perl libhttp-message-perl
```

## Documentation

The documentation is
[here](https://www.jochentopf.com/software/flinch/index.html).

## License

Copyright © 2001-2024 by Jochen Topf <jochen@topf.org>

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 2 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program; if not, write to the Free Software Foundation, Inc., 59 Temple
Place, Suite 330, Boston, MA 02111-1307, USA

## Author

Written by Jochen Topf <jochen@topf.org>

