<!--
 Copyright (C) 2022 Code for Vegas Foundation
 
 This file is part of ov-smart-social.
 
 ov-smart-social is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.
 
 ov-smart-social is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License
 along with ov-smart-social.  If not, see <http://www.gnu.org/licenses/>.
-->

# Smart Social Smart Contacts

## Highest Priority Considerations

## Specification Details

If a Smart City relies on Twitter and Nextdoor to inform its population of important updates, there is something missing. That is Smart Contacts.

Maintaining a locale-based anonymous communication channel is reasoably simple with modern technology and enables one-way broadcast based on location, and two-way conversation regarding service requests and other lower-priority discussion (this would not be intended to take the place of emergency services contacts such as 9-1-1 and similar).

## External Reference Materials

[vCard RFC](https://datatracker.ietf.org/doc/html/rfc6350)

[CardDAV RFC](https://datatracker.ietf.org/doc/html/rfc6352)

[Schema.org Person type](https://schema.org/Person)

## User Stories

Individual stories may be converted into Issues, or consolidated or exploded as needed for development and implementation.

**Terms**:

- **Consumer**: a user of Smart Contacts services in general, usually a person but possibly automation tools.
- **Operator**: a bus driver, and so on.
- **Controller**: a transit operations staff member, and so on.
- **Company**: a transit company, commission, or other agency overseeing transit services

### Typical Uses

- **Card**: As a Consumer, I need to know when my bus will arrive so that I can plan my arrival at the bus stop accordingly.
  - **Conversation**: Each Consumer of transit services has their own journey to make from their actual point of origin to the bus stop at which they will wait for the arrival of their bus.
  - **Confirmation**:
    - Consumer is able to determine estimated versus scheduled arrival time for any route at any stop, with statistical information presented in clear terms (% on time, etc)

---
