Title: RECAP Extension 0.6 Beta Released
Date: 2010-01-21 16:41
Author: recapthelaw
Category: Announcements
Slug: recap-extension-0-6-beta-released
Status: published

The Mozilla Foundation
[released](http://arstechnica.com/open-source/news/2010/01/hands-on-firefox-36.ars)
version 3.6 of Firefox today, and we're proud to release the
corresponding version of the RECAP extension, beta version 0.6. In
addition to Firefox 3.6 compatibility, we've also thrown in a new
feature
[suggested](http://recapthelaw.uservoice.com/forums/26501-general/filter/completed)
by our users: the option to save documents using filenames that we
describe as "lawyer style" in contrast to the "Internet Archive style"
we've traditionally used. For example, rather than saving a document as
"gov.uscourts.cand.204881.46.0.pdf," you can now configure the extension
to store a document as "N.D.Cal.\_3-08-cv-03251\_46\_0.pdf." Those who
prefer the traditional filenames are free to continue using those as
well.

We've also improved our docket-parsing code, allowing us to extract more
metadata from court dockets. New fields we're now scraping include
"Assigned to", "Referred to " , "Cause", "Nature of Suit", "Jury
Demand", "Jurisdiction", and "Demand." We also scrape information about
parties, including names, contact information, and attorneys. You can
see a good example
[here](http://ia341316.us.archive.org/1/items/gov.uscourts.txnd.188733/gov.uscourts.txnd.188733.docket.html)
(to choose a case at random).

If you're an existing Firefox user, Firefox periodically checks for
updates to extensions and should automatically fetch the new version of
the RECAP extension. Or you can force it to check immediately by
clicking Tools-&gt;Extensions-&gt;Find Updates (or, depending on your
Firefox version, Tools-&gt;Add-Ons-&gt;Find Updates). As always, please
[let us know](mailto:info@free.law) if you find any bugs.