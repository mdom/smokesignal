# smokesignal

Chat like xkcd1810

# Description

(xkcd 1810)[https://xkcd.com/1810/] made a reference to someone chatting
using apache requestlogs. And that's exactly what smokesignal is doing.

    $ smokesignal send "foobar" "http://foo.example.org/topic" "http://bar.example.org/topic"
    $ smokesignal read "/topic" /var/log/apache.log

# License

Copyright 2017 Mario Domgoergen <mario@domgoergen.com>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see http://www.gnu.org/licenses/.
