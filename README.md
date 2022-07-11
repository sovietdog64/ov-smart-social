# Smart Social Overview

The goal of the Smart Social Project is to enable a Smart City to communicate with itself.

The populace should be able to Discover, Learn, and Participate in meetups, gatherings, and events, while remaining informed about news and important topics, with location and community awareness in the way information is made available. At the same time, the ability to respond to and share these items will help to complete the social engagement loop, whether between government agencies and the people of Las Vegas, or amongst themselves.

## Project Policies

Unless otherwise and specifically indicated with replacement files in this repository, this project will adhere to the default Code for Vegas Foundation policies for Code of Conduct and Contributing, found at

* [Code of Conduct - Code for Vegas Foundation](https://github.com/CodeForVegas/.github/blob/main/CODE_OF_CONDUCT.md)
* [Contributing to this Project - Code for Vegas Foundation](https://github.com/CodeForVegas/.github/blob/main/CONTRIBUTING.md)

## General Focus Areas

As a preliminary feature set, it makes sense to aim for broadly accepted and long-established tools and platforms that already work. Rather than re-inventing a wheel and asking for yet more user sign-ups, leveraging open protocols and tools, and methods and software people are all likely familiar with, will help to drive early adoption and continued ideation.

This is the *Familiar Surprise* approach.

Basically, if the Smart Social platform can leverage tools already in use, established, tried-and-true, we can add features and functionality to existing platforms and enhance expectations rather than subverting them.

### Smart Calendar

The challenge is discovery and Las Vegas is not an environment easy to navigate as we attempt to find out what is going on and where.

The proposed strategy here is a base introduction to the notion that a Smart City is not necessarily enabled by using Slack or Discord or Meetup or Eventbrite or... the list goes on. Beginning with standard calendars, iCalendar and iCalendar Streams, organizer-owned RSVPs, calendar sharing and status broadcast (in the event of reschedule, cancellation, etc).

By making use of standard map and location data structures and protocols, it is also a small matter to connect a date and time with a place, and to provide additional useful information such as parking and transit data, not to mention weather and other appropriate, useful information.

A useful resource for general calendar technologies is at [CalConnect](https://devguide.calconnect.org/) also included in References below.

### Smart News

There are many ways to consume news and current information. The challenge here is connecting any one event to a series of events unfolding in a story arc, connceting events in or near a particular location over time, and tracking directly and indirectly-related pieces of information to help maintain an informed populace.

Case in point, at the time of the preparation of this overview, water levels at Lake Mead are continuing to decline, and while daily and even hourly weather reports are commonplace, this vital resource is report on as though it were a comet or cicada hatching. Connecting news updates about water levels to other related news events is a simple, yet highly apprpriate example.

### Smart Contact

If a Smart City relies on Twitter and Nextdoor to inform its population of important updates, there is something missing. That is Smart Contacts.

Maintaining a locale-based anonymous communication channel is reasoably simple with modern technology and enables one-way broadcast based on location, and two-way conversation regarding service requests and other lower-priority discussion (this would not be intended to take the place of emergency services contacts such as 9-1-1 and similar).

### Smart TBD

This overview is subject to change, especially as we iterate on community adoption and feedback of this city-scale approach to communication.

## References

[Raymon Loewy - MAYA - Familiar Surprise](https://uxdesign.cc/most-advanced-yet-acceptable-theory-meets-digital-product-innovation-f14897147dd5)

    “To sell something surprising, make it familiar; to sell something familiar, make it surprising.”

    — Raymond Loewy

### Calendars and Events

[vCalendar RFC](https://datatracker.ietf.org/doc/html/rfc5545)

[CalConnect.org Dev Guide (visit the wiki)](https://devguide.calconnect.org/)

[Schema.org Event type](https://schema.org/Event)

[iCalendar.org](https://icalendar.org/)

### Contacts

[vCard RFC](https://datatracker.ietf.org/doc/html/rfc6350)

[CardDAV RFC](https://datatracker.ietf.org/doc/html/rfc6352)

[Schema.org Person type](https://schema.org/Person)

### News and Announcements

[RSS Specifications collection](http://www.rss-specifications.com/)

[ATOM RFC](https://datatracker.ietf.org/doc/html/rfc4287)

[Schema.org article about News Markup](https://schema.org/docs/news.html)

### Secure Email, Messaging, Chat

[Matrix.org Decentralized Communication](https://www.matrix.org/)

[Public Key Infrastructure (start at Wikipedia)](https://en.wikipedia.org/wiki/Public_key_infrastructure)
