---
title: Meeting the MyEd Team
description: Last Monday we met the people in charge of MyEd
published: 2013-04-13
author: Ben Jeffrey
---


Last Monday (2013-04-08) we met[^1] the team in charge of the University
of Edinburgh's [MyEd](http://myed.ed.ac.uk) portal, in order to talk
about our [proof-of-concept MyEd 2."oh"][myed 2.0] redesign, as well as
their plans to overhaul the actual MyEd!


We met Martin Morrey and Paul Johnson from the
[Service Management Section][] of IS, and Kate Glencross from
[Student Communications][], after Ewan Klein introduced Kate and myself over
email. It turns out that [Information Services][] are planning an overhaul of the
MyEd interface this year, and this team are now heading up MyEd's front-end
and strategic direction for the foreseeable future.

We talked a while about common complaints with MyEd:

* seperate 'tabs' and 'channels' make getting information/services a manual search[^tabs]
* the interface is not particularly optimized for mobile access
* some links to [Learn][] don't work on iPhones[^learn]
* existing mobile apps are pretty poor, and virtually unknown
* [EASE][] login doesn't allow browsers to save login details[^ease]
* little alternative access to important data outside of MyEd
* a plethora of isolated university systems, each with their own notifications:
    - Personal Tutor system
    - Learn
    - Office 365 email
    - the EUSA website
    - Library services (loans, charges due...)

The MyEd team was already aware of many of these issues, and they're
now considering solutions to them.


MyEd, only... *better*
----------------------

The consensus, leaving Monday's meeting, was that:

* MyEd's interface will be overhauled, and made more accessible for mobile devices
* the [U@Ed apps][] will likely be discontinued at some point, as
    they duplicate functionality in MyEd, and not particularly well
* Martin and Paul both agreed that opening up data is often a good idea
    for pragmatic reasons, and so we may see this reflected in MyEd's
    design in the future
* the MyEd team are keen to work with the INF-YT in future, in order
    to get as much student feedback as possible!


One particular idea that we pushed is that personal notification feeds (not
tied to MyEd) would be a great resource for power-users -- Martin and
Paul seemed interested, and indicated that it might be possible to
compile and publish the notifications as a separate service, with MyEd as
one subscriber to it. This would be a great first-step for having access
to your own data, and could bring technical benefits, too.


MyEd needs you!
---------------

The MyEd team are currently gathering information and feedback on MyEd in
its current iteration, and they're really interested in students'
opinions, and making the service more useful for all the audiences it
serves -- not only current university students, but lecturers, post-
graduates, and prospective students too.

If you have any issues or ideas for MyEd, they want to know,
so [give them your feedback][MyEd feedback]!




<!-- footnotes and links -->
[^1]: Since the meeting was at rather short notice, we actually tried to set
    up a Google + Hangout, with me at the actual location (on an unfamiliar
    laptop!). I couldn't actually get sound from anyone else,
    so they watched and typed messages, while I talked with the MyEd team
    in person.

[^tabs]: The fiddly navigation also dissuades exploration -- there are tabs
    that I've never visited, and I have little desire to spend longer in MyEd
    than is necessary.

[^learn]: Specifically, iPhones don't seem to follow login redirects properly
    for the course links in the Studies tab/Learn channel. I'd give you a link
    to the page, but MyEd doesn't seem to conform to the "U" in "[URL][]"...

[^ease]: This is because the "username" and "password" boxes on the EASE login
    page have     the `autofill="off"` attribute set, which disables your
    browser from saving any of your login details for you. It's not really
    a security     feature, as it simply means you have to type your login
    details every. single. time.

[Service Management Section]: http://www.ed.ac.uk/schools-departments/information-services/about/organisation/applications-division/apps-division-who/apps-division-units/apps-div-serv-mgt/staff-list-serv-mgt
[Student Communications]: http://www.ed.ac.uk/schools-departments/communications-marketing/student-communications
[MyEd feedback]: http://www.ed.ac.uk/schools-departments/information-services/services/computing/comms-and-collab/myed-portal/introduction-to-myed/myed-feedback
[myed 2.0]: https://github.com/INF-YT/don
[Information Services]: http://www.ed.ac.uk/schools-departments/information-services
[U@Ed apps]: http://www.ed.ac.uk/schools-departments/information-services/services/computing/comms-and-collab/mobilecampus
[Learn]: http://learn.ed.ac.uk/
[URL]: https://en.wikipedia.org/wiki/Uniform_Resource_Locator
[EASE]: https://www.ease.ed.ac.uk/
