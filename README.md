Digital Availability
===

Introduction
---

This repo is partly a thought experiment and partly an opening of a discussion: how can
software engineers advertise their availability to people who could offer them work? The
current answers to this (job boards and recruiters) are not particularly satisfying. The
problems include:

* Recruiters, somewhat by design, act as gatekeepers between skilled developers
and their technical counterparts in an organisation
* Recruiters are sales-people first, and unfortunately sometimes bring to the table
the unpleasant characteristics one expects of sales-people (with some honourable
exceptions, of course)
* Recruiters only have a cursory knowledge of technology, so it can be hard to
have a detailed conversation about industry experience

There are additional problems in the contract market, where recruiters are paid
a percentage of day rate:

* If a recruiter can put forward two contractors for the same role, they are financially
incentivised to prefer the one at the lower rate, since that will give them a better
commission
* Recruiters will sometimes ask a contractor to work for a lower rate, possibly
with the implication that the client will look on the discount favourably, even though
it is unlikely that the client will even hear about it.

These problems can be somewhat alleviated by encouraging open-book practises in
recruitment (which I hope to explore in another project).

Advertising availability
---

What I'd like to see is an open digital format in which an engineer can publish their
current and forthcoming availability for full or part-time work. They would self-publish
this (e.g. on a personal web-site or GitHub pages) and any interested parties could
subscribe. This would be available firstly to employers and clients, and to any others,
such as recruiters, who can offer value in the supply chain.

The URL of the information would be submitted to an index and parsed for storage and
publishing. The data within could be shown on a web-site very easily:

* As a list of contractors arranged by skills or availability order
* As a calendar of forthcoming availability
* As a map of contractor locations

Research
---

I am not aware that anyone has tackled the problem of availability yet. However, I
am conscious that if I were to propose an open format for this, it could easily segue
into an open standard for CVs/resumes, and there are a number of efforts in this
realm already. While I think it is true that the current standards are rather
simplistic, there may be value in concentrating on availability on its own, and
discovering whether software professionals would use it at all.

Format
---

Although XML has gone out of fashion these days, I like it primarily because adding
comments is very easy, which is useful in annotating sections. Indeed, this is why
I am not so much in favour of JSON, even though the industry has generally gone down
that road.

YAML and TOML are possibilities, and they both support indentation, although the
indentation can be hard to visually parse.

To-do
---

* Add notes about how I'd like this to change the value proposition from recruiters
* Add links to research on CV formats and some commentary
* Do a research piece on availability specifically
* Make changes to the current "Digital CV" to separate the CV and availability themes
