# History and status

## Who ran it

TicketCombat.com never named its author. It was a one-person, ad-supported
hobby site run by someone who also posted as **"ticketcombat"** on Ontario
forums such as RedFlagDeals and ontariohighwaytrafficact.com, answering
questions and pointing people to the site. The site's own feedback page says
it launched in mid-2008, and that the author stopped collecting comments in
early 2009 because there were too many to keep up with.

The only contact address on the site was `comments@ticketcombat.com`.

## Timeline

All dates come from the domain registry (RDAP) and the
[Wayback Machine capture index](https://web.archive.org/web/*/ticketcombat.com/*).
"First seen" means the first archive capture, which is usually a little after
the page was actually written.

| Date | Event |
|---|---|
| 2008-01-09 | `ticketcombat.com` registered |
| 2008-11-21 | First archive capture of the homepage. Most Step 1–5 pages first seen in Dec 2008 |
| 2008-10 → 2009-02 | Forum users praise the site; these posts are quoted on its feedback page |
| 2009-02 | Stop-sign section first seen |
| 2009-02 → 2010-01 | Seat-belt section first seen |
| 2010-03 → 2010-04 | Parking-ticket section (20 pages) first seen |
| 2009-09 → 2011-04 | Advanced Step 4 pages first seen (how-to-file guides, Section 109 notices, Toronto prosecutor contacts) |
| 2011-03-16 | Terms and Conditions last updated |
| by 2011-05 | Author withdraws the "bilingual signs" defence, one of the site's signature arguments. The page is replaced with a notice saying the Ontario Court of Appeal rejected *R. v. Myers* in 2011 (see [Step 5](guide/step-5-trial.md)) |
| 2010-07 → 2015-03 | Downloadable Word templates first seen (sample disclosure request, affidavit, Form 4F, waiver letter, 11(b) explainer) |
| 2017–2019 | Busiest period in the archive: 1,538 / 2,547 / 2,008 captures per year |
| 2020–2021 | Captures drop to 314 and then 7 per year |
| 2024-07-13 | Archive captures HostGator's **account-suspended page** (`/cgi-sys/suspendedpage.cgi`) |
| 2024-07-23 | Site back up; normal pages captured again |
| 2025 | Site served over HTTPS; footer reads "©2025 TicketCombat.com" |
| 2025-11-03 | **Last good capture** (`/step4/step4.php`) |
| 2025-12-10 | Domain record last changed (most likely an auto-renewal); paid through **2027-01-09** |
| 2026-10-24 | Every URL returns HostGator's "Error. Page cannot be displayed. Please contact your service provider for more details." |

Archive capture counts mostly measure how often crawlers and people saved
pages, not visitor traffic. Still, the drop after 2019 suggests the site was
getting less attention.

## Why it's down

This is inferred from public records only. Nobody has confirmed it.

**The domain is fine.** It is still registered with Namecheap, was renewed
recently, and doesn't expire until January 2027. Its name servers still point
to HostGator (`ns649/ns650.hostgator.com`), and DNS still resolves to a
HostGator shared server (`198.57.247.132`, `gator3168.hostgator.com`).

**The hosting account is gone.** That server still answers for the domain, but
with HostGator's generic error page instead of the site. HTTPS fails too: the
server presents HostGator's own `*.hostgator.com` certificate instead of the
site's certificate, which it was using in 2025. Both are what you see when a
domain still points at a shared server but the hosting account behind it has
been suspended, cancelled, or moved.

**It has happened before.** In July 2024 the account was briefly suspended and
came back about ten days later. A short suspension followed by recovery is
typical of a billing lapse.

The most likely story is that the HostGator plan lapsed or was cancelled at
the end of 2025, while the domain kept renewing on its own at a different
registrar. The site may come back if the owner notices. If the domain is
allowed to expire in January 2027, it may be bought by someone else.

## Is a full copy available?

There is no downloadable bundle (nothing on archive.org, and archive.today has
only a 2014 homepage snapshot). The Wayback Machine has good copies of
essentially the whole site: about 130 HTML pages, the downloadable Word
templates, and a PDF court decision. Every page is linked from the
[page index](page-index.md).

This repository does **not** mirror the site's text or offer it as a download.
The site's terms forbid republishing or modifying its content without written
permission, so these notes summarize and link instead. See
[Why there's no download](no-download.md).
