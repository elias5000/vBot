vBot
===

Preface
-------

Do not use this piece of software as it is built years ago on top of a long since deprecated module.
This repository was only created to conserve this piece of labour for documentary reasons. ;-)

Required Perl modules
---------------------

*   CGI
*   Encode
*   Date::Parse
*   DBD::PgLite
*   DBD::SQLite
*   DBI
*   Net::IRC
*   Unicode::CheckUTF8
*   Time::HiRes
*   XML::LibXML::Valid
*   WWW::Mechanize
*   XML::Parser
*   XML::RSS
*   XML::Atom::Client

Running vBot
------------

To run vBot simply edit lib/config.pm_dist, rename it to
lib/config.pm and execute the run script.

It will restart vBot every time it terminates after 60 sec wait timeout.
If you do that in screen or through daemontools you can set it up as a daemon.