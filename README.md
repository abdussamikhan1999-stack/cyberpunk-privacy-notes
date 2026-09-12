# Cyberpunk / Privacy / Security Notes

Notes distilled from a `/cyb/erpunk` general thread (4chan `/g/`-style), covering
cyberpunk culture/media, privacy tooling, anonymity networks, and security
learning resources.

See [LINKS.md](LINKS.md) for the full raw link list, organized by section, and
[ALT-CYBERPUNK-FAQ-SUMMARY.md](ALT-CYBERPUNK-FAQ-SUMMARY.md) for a full
summary of the alt.cyberpunk FAQ (a ~15,900-word community document spanning
1993-present).

> "With software there are only two possibilities: either the users control
> the program or the program controls the users." — Richard Stallman
> (the thread's header quote — sets the theme: software freedom and
> user-controlled computing as the throughline connecting cyberpunk fiction
> to real privacy/security practice.)

## Cyberpunk (the culture, not just the aesthetic)

- **What it actually is**: "cybernetics" + "punk" — a "low life, high tech"
  genre where technology is visceral and intimate, not distant. Dystopian
  near-futures, megacorporations vs. hackers/marginalized people, rapid tech
  change, body modification, post-industrial cities. The recurring idea:
  "the street finds its own uses for things" — communities repurpose tech in
  ways its makers never intended.
- **Getting into it** (per the thread's own guide): start by reading a lot.
  Foundational fiction — Gibson's *Burning Chrome* and the Sprawl trilogy,
  Sterling, *The Shockwave Rider*, *Altered Carbon*; manga (*Gunnm*, *Ghost in
  the Shell*); anime/film (*Blade Runner*, *Akira*, *Serial Experiments Lain*,
  *Texhnolyze*). Then technical nonfiction (networking, RF, optics,
  biotech/CRISPR) and social theory about how institutions actually function.
- **The cyberdeck**: originally Gibson's fictional portable hacking rig; today
  real-world "cyberdecks" are DIY/retro-styled portable computers (often built
  around old keyboards, e.g. Commodore-64-style cases) built more for
  aesthetic/tinkering satisfaction than practical advantage over a laptop.
  Minimum bar: power, an OS, connectivity, a keyboard, video out, portability.

## Networks (anonymity/overlay networks)

- **Tor** — onion-routing network for anonymous browsing; the most mature and
  widely supported of the three.
- **I2P** — a garlic-routing overlay network geared more toward anonymous
  peer-to-peer and internal ("eepsite") services than general web browsing.
- **Freenet** (now Hyphanet) — distributed, censorship-resistant data store
  for publishing/retrieving content anonymously.

## Privacy — what to actually do about it

- **Privacy Guides' tool list** is the best single starting point: covers
  browsers (Tor Browser/Firefox/Brave), VPNs (Proton/IVPN/Mullvad), email
  (Proton Mail/Tuta), encrypted cloud storage, DNS, password managers,
  security keys, de-Googled Android ROMs, router firmware, and Tor/I2P for
  advanced users. Prioritizes open-source, audited, non-walled-garden options.
- **Privacy-friendly frontends** exist for most major platforms so you don't
  have to hit the tracking-heavy original site directly: Invidious/Piped
  (YouTube), Nitter (Twitter, often offline), Teddit/Libreddit (Reddit),
  Searx/Whoogle (Google Search), Wikiless (Wikipedia). The `libredirect`
  browser extension auto-redirects to whichever of these is currently alive.
- **Have I Been Pwned** — check if your email/phone shows up in a known
  breach.
- **Data broker / people-search removal** — there's a real, unglamorous chore
  here: sites like Whitepages, Spokeo, BeenVerified, TruePeopleSearch, and
  data aggregators like Acxiom/LexisNexis sell your info by default, and each
  has its own opt-out flow. Worth doing once and periodically re-checking,
  since brokers routinely re-list people.
- **RMS on Facebook** — Stallman's standing case against Facebook specifically
  (as opposed to social media in general): surveillance/tracking scope, real-
  name policy enabling both government tracking *and* fake-account abuse,
  documented political censorship, engagement-driven psychological harm,
  election/disinformation risk, and anti-competitive "buy, copy, or kill"
  behavior toward competitors. Useful as a concrete, itemized version of "why
  does this matter" rather than a vague privacy platitude.
- **Libreboot** — free/open BIOS replacement firmware, for the "own your boot
  process" end of the privacy spectrum (much more involved than swapping an
  app).

## Security — learning and defense

- **EFF's Surveillance Self-Defense** is the best on-ramp for a non-specialist:
  basics of how surveillance actually works, step-by-step tool setup guides,
  and scenario-based plans (protester, journalist, LGBTQ youth, healthcare
  worker, etc.) rather than one-size-fits-all advice.
- **The two igwiki "cybersecurity" guides** are Linux-hardening focused and
  noticeably dated in places (their own text admits it) — full-disk
  encryption (LUKS), keylogger/rootkit defense, firewall/sysctl hardening,
  Firefox hardening (NoScript/uBlock/fingerprint resistance), and a caveat
  worth remembering: "Tor isn't yet able to cash in the promises it makes" —
  i.e., don't treat anonymity tools as magic.
- **The "basics and armory" + "Learning/News/CTFs" igwiki pages** are the
  actually-useful ones if you want to go from "interested in security" to
  "practicing it": baseline competencies (networking, TCP/IP, OWASP-style web
  attacks, Linux CLI, malware kill chains), practice targets (DVWA, WebGoat,
  Metasploitable), and real CTF/wargame platforms — **OverTheWire,
  PentesterLab, HackThisSite, VulnHub, Root-Me** — plus news/CVE sources
  (Threatpost, Packet Storm, Exploit-DB, CVE Details) and learning platforms
  (Cybrary, Metasploit Unleashed, SANS reading room). If you want a starting
  point from this whole thread, **it's this: pick one CTF platform (OverTheWire
  is the classic first one) and just start.**
- **IntelTechniques (Michael Bazzell)** — structured OSINT training/
  certification (OSIP) and books; the standard reference for "how to actually
  find information about a person/target," used both offensively (research)
  and defensively (finding out what's findable about *you*).
- **"Shit just got real" pastebin** — a 2017-era link aggregation on corporate
  surveillance networks, state-sponsored hacking, and encryption-backdoor
  policy fights. Framed as raw evidence/reporting, not a how-to — most
  useful as background on *why* the privacy tooling above exists, not as an
  active resource (it's ~9 years old at this point).

## Inaccessible from here

The FAQ link (`archive.is/mkDpa`) couldn't be auto-fetched from this
environment — `archive.is` blocks this tool's fetcher — but its full text was
pasted in manually and summarized; see
[ALT-CYBERPUNK-FAQ-SUMMARY.md](ALT-CYBERPUNK-FAQ-SUMMARY.md). The "huge list
of cyberpunk media" archive.is link is still unfetched — same block, no
manual copy yet. The `mega.nz`/`mediafire` archive links (Cyberlife,
Bibliothek, /sec/ PDFs, other library) are compressed binary archives that
can't be previewed via a text fetch either way — listed as-is in LINKS.md for
later.
