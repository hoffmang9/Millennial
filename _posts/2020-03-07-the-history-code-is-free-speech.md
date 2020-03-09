---
layout: post
title: "The History of Code is Free Speech"
author: "Gene Hoffman"
categories: free-speech
tags: [CFIS,1A,3d-printing,2A]
image: pgp-3.0-book.jpg
---

In 1997, when I was working as head of Business Development and interim head of Engineering for the first PGP, Inc., it was still a violation of U.S. export control laws to send a copy of PGP-encryption software, or any sufficiently “strong encryption” software, outside of the United States. But PGP’s in-house legal counsel [Bob Kohn](https://en.wikipedia.org/wiki/Bob_Kohn), PGP’s outside legal counsel, [Roz Thomsen](https://t-b.com/about/our-team/roszel-c-thomsen-ii/), and I came up with a "crazy like a fox" idea to put the complete source code to [PGP 3.0/5.0 into book form](https://archive.org/details/prettygoodprivacy) in the [OCR-B font](https://en.wikipedia.org/wiki/OCR-B). That way, should the book be sent outside the country, the exportation could not be deemed to be a violation of export control laws. As Bob Kohn advised, any regulation that would prohibit the sale of books would be a violation of the First Amendment. At least, that was our hope. That idea was not only a clever one, it ultimately worked.

After sending the book to the Library of Congress, Bob Kohn and I brought several copies to Bay Area book stores, including Printers Inc. on Central Avenue in Palo Alto, California. Bob fully expected that, should a bookstore send the book overseas, no way would the government indict a bookstore for selling a book!

But that process was taking too long. As PGP was in a rush to market, it fell to me to make sure we met our deadlines. As the most senior guy involved in the project, with the least to lose (as my amazing wife had not yet fallen for my charms), exporting the book became my problem. I secretly prepared a fully ready to go Fedex box of the book and, at a Cypherpunks meeting, handed it to [Lucky Green](https://twitter.com/luckygreen) who dropped it off at a nearby Fedex location.

# Thus ended export controls on cryptography

A few days later, the FedEx slip for that package was prominently displayed on a website located in Sweden. Of course, just a few days after that, Bob got a call from the U.S. Export Control Division of the Department of Commerce. As a result of that call, I became the second person to ever be investigated for illegally exporting strong cryptography. The first exporter was almost certainly [Hal Finney](https://www.nytimes.com/2014/08/31/business/hal-finney-cryptographer-and-bitcoin-pioneer-dies-at-58.html) but Phil Zimmerman bravely chose to [take the heat](https://www.wired.com/1995/03/the-continuing-investigation-of-phil-zimmermann/) instead.

Bob was quickly called in to the Office of the Export Control Division in San Jose, CA. He brought with him a copy of the PGP source code book, a box of PGP software, and a large poster we created explaining public key cryptography. As he tells the story, Bob walked out of the meeting not entirely sure whether our plan was going to work. When he got back to the office, he instructed the enginnering team to take their PCs home every night and back up their work off-site, as we could be raided by the FBI at any time.

Two weeks later, Bob got a call from one of the export control agents he had met with. She informed him that, after her discussions with the Department of Commerce’s office of General Counsel, it turns out we were right after all: It’s not illegal to sell a book! Thus, their investigation was complete and within a few short months strong cryptography was removed from the Munitions List at [ITAR](https://www.pmddtc.state.gov/ddtc_public?id=ddtc_public_portal_itar_landing) and transferred to the [Department of Commerce Control List](https://www.bis.doc.gov/index.php/regulations/commerce-control-list-ccl) to now be subject to "Commodity Classification" which was inexpensive and easy to license and generally exempted open source.

To this day, Bob insists that PGP should never have had to resort to publishing the source code in book form. Not only does the First Amendment protect computer software, but the Second Amendment protects encryption. "The right to bear arms," Bob told me recently, "includes the right not only to bear a sword, but also to bear a shield. The defensive shield of encryption is as important to a free state as any kind of offensive weapon necessary in the exercise of our natural right of self-defense," he added.

# History repeats itself

The US Government [has always](https://www.courtlistener.com/recap/gov.uscourts.njd.396452/gov.uscourts.njd.396452.1.59.pdf) [been](https://www.courtlistener.com/recap/gov.uscourts.njd.396452/gov.uscourts.njd.396452.1.60.pdf) [very](https://www.courtlistener.com/recap/gov.uscourts.njd.396452/gov.uscourts.njd.396452.1.61.pdf) [aware](https://www.courtlistener.com/recap/gov.uscourts.njd.396452/gov.uscourts.njd.396452.1.62.pdf) of the tension between the US Munitions List and the First Amendment. However, in 2013 the Obama State Department reversed years of regulatory interpretation to "do something" about the moral panic of 3D printing firearms and  [threatened Defense Distributed]("https://www.courtlistener.com/recap/gov.uscourts.njd.396452/gov.uscourts.njd.396452.1.24.pdf") for publishing CAD files. DD ultimately prevailed with a [settlement from the US Government](https://www.courtlistener.com/recap/gov.uscourts.njd.396452/gov.uscourts.njd.396452.1.28.pdf) that included paying for some of DD's expenses. Since then the Attorney General's of various anti-freedom states have been [attacking everyone's First Amendment rights](https://www.npr.org/2018/07/30/634177862/attorneys-general-sue-trump-administration-to-block-3d-printed-guns). That culminated last Friday with a [narrow injunction against new US regulations](https://www.courtlistener.com/recap/gov.uscourts.wawd.282521/gov.uscourts.wawd.282521.94.0.pdf) that would have removed all but machine code 3D printed firearms files from all export controls.

I was one of the handful of people who created [CodeisFreeSpeech.com](https://codeisfreespeech.com). We received a [fraudulent takedown notice](https://blog.cloudflare.com/the-curious-case-of-the-garden-state-imposter/) that purported to be from the Attorney General of New Jersey's office which culminated in CiFS removing the CAD files and [suing AG Grewal](https://www.courtlistener.com/docket/14536187/defense-distributed-v-grewal/).

I had thought that the new rule-making would end much of our concern with the United States leaving just a few States infringing our rights. Now that is not the case so we're going to have to make history rhyme.

Thanks again to Bob, Roz, Phil, Hal, and the rest of the '96-'97 PGP engineering team.
