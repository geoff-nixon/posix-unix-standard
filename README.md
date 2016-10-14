# **The Single UNIX™ Specification, Version 4**
##  The POSIX™ Standard, IEEE Std 1003.1™-2008, 2016 Edition - ISO/IEC 9945
### _Includes: IEEE 1003.1-2008, IEEE 1003.1M-2008/Cor 1-2013, IEEE 1003.1-2008/Cor 2-2016_

----

_POSIX_ (i.e., the 'base specification' for the **Single UNIX™ Specification**) is a trademark of Bell Labs.
 or AT&T, or X/Open, or the Open Group. Or somebody. Is an open standard — or so they tell me.

##### **And it's now received its first revision bump in 14 years!**
_(Get ready folks! Its gonna be brand new ball game! I'm told the Open Group has really taken semantic versioning to heart.)_ 

I know your you're dying to get a hold of the new standard yourself,
and since its the developed **by** "the _Open_ Group", no problem, right?

Well, in fact, I found it a little difficult to get ahold of this _open standard_ myself. If you've tried a hand at it you probably wound up on here on the [IEEE website](http://ieeexplore.ieee.org/document/7582338/), where they will gladly let you download a PDF for the low, low price of $814.00 USD, or just $1,018 for a print copy. That's only a bit more than a three hundred dollar price hike from the last version! Other side of the pond? Maybe [here](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=50516) where you can purchase it for CHD 238,00 (Swiss francs). 

Or if your just a cheapskate like me, perhaps you've been trying to get your browser to work with the Open Group's slick [troff-to-html version](http://pubs.opengroup.org/onlinepubs/9699919799) — be sure you version of Netscape Navigator has frames support!


So, it took me an absurd amount of time to figure this out, so I thought I'd share — and lucky enough, it its _still_ the case that:
  
**You can indeed get a legal, free full copy of the standard, without being extorted by an international standards body.**

To access the standard, you have to **join** the Austin Group, the working group responsible for drafting the specification.
It's not exactly advertised, but you can actually do this online: 
  1. Create an account at the Open Group website, [here](https://www2.opengroup.org/ogsys/common/createIndividual.html).  
  2. Log in at this [page](https://collaboration.opengroup.org/operational/portal.php). From the menu on the left, click 'Manage My Activities'.
  3. At the bottom of the page, under Public Projects, you'll see _The Austin Group_. Click to 'join the activity'.
  4. Go to http://www.opengroup.org/austin/login.html and accept their conditions.
  5. At last, a link. It's password protected. Use the login you've just created.

While technically a "draft", I've confirmed this is the full, final standard.

_If you're password is rejected, you either:_
  1. [Need to wait a bit (perhaps an hour or so)](https://github.com/geoff-codes/posix-standard/issues/3) for your login/password be enabled.
  2. [Need to try a different browser. On Windows, some have suggested using Internet Explorer rather than Chrome.](https://github.com/geoff-codes/posix-standard/issues/2) 
  3. If you still cannot access the PDF, you haven't completed all the steps above successfully. Go back and make you're actually 'joined the group', etc.

The actual direct link to the Base Standard of the SUSv4, IEEE Std 1003.1, 2016 Edition (with Technical Corrigendum 2) is here:  
https://www.opengroup.org/austin/restricted/issue7-tc2/C165.pdf

Lots of good stuff in those 3,956 pages of riveting operating system minutia. Keep it by the bedsize table for some light reading. Here's an except:

> The pax utility is no longer allowed to create separate identical symbolic links when extracting linked symbolic links from an archive, because the standard now requires implementations to support (hard) linking of symbolic links.

Wrap your head around that one?
