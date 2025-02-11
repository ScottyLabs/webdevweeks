---
layout: guide
title: Home
---

<br>

<img class="hero-logo" src="{{ site.baseurl }}/assets/img/logo.svg">
##### Web Dev Weekend

<span id="time"></span>

Web Dev Weekend is a series of lectures, workshops, and exercises that introduce
you to the fundamentals of web development.

If you want to make websites outside of the classroom, get a head start on later
electives, or attend hackathons, Web Dev Weekend will give you the foundational
knowledge you need to get started.


## How do I register?

1. __[Register]({{site.registration_link}})__
  - You certainly don't have to register to attend, but we like knowing how many
    people to expect and what people will be interested in learning.
    <a href="{{site.registration_link}}"><button>Register Here!</button></a>
1. __[Read "The Basics"][basics]__
  - This quick read will introduce you to some common concepts and explain what
    the workshops are about.
1. __[Pick some workshops!](#schedule)__
  - Workshops are largely independent of each other: you can attend as many or
    as few as you'd like.

After participating in these workshops, you might want to show your friends the
cool things that you built.

## Schedule

Click on any of the links to read more about what each section will cover!

You can go to as many or as few as you'd like. Most talks have no
pre-requisites, but the ones that do list them on their descriptions.

### Location
WDW will be held in Rashid Auditorium!

### Saturday, November 13th

| Session                                                      | Time                   |
|--------------------------------------------------------------|:----------------------:|
| Opening Ceremony                                             | 1:45 p.m. -- 2:00 p.m. |
| [Git & Github](git/)                                         | 2:00 p.m. -- 3:00 p.m. |
| [HTML & CSS](html+css/)                                      | 3:00 p.m. -- 4:00 p.m. |
| [JavaScript](javascript/)                                    | 4:00 p.m. -- 5:00 p.m. |

### Sunday, November 14th

| Session                                                      | Time                   |
|--------------------------------------------------------------|:----------------------:|
| [Beautiful Soup](beautifulsoup/)                             | 2:00 p.m. -- 3:00 p.m. |
| [Flask](flask/)                                              | 3:00 p.m. -- 4:00 p.m. |
| [Deployment](deployment/)                                    | 4:00 p.m. -- 5:00 p.m. |



## What will I learn?

We'll teach you enough to get started on your first web development project.
This could be something that you work on outside of class, at a hackathon, or
for a club.

Exactly what you learn will depend on what workshops you go to, and you can
learn what each workshop is about by reviewing [basics][basics].

It's not possible to teach you everything you need to know in two hours. Many
things that we consider "essential" (like mobile web development) have been left
out because of time. However, we aim to teach you foundational skills that you
can build on in the future.


## Who is running WDW?

Web Dev Weekend is run by [ScottyLabs](https://scottylabs.org). We also run
[TartanHacks](http://tartanhacks.com/) (CMU's largest software hackathon) and
other educational events like
[CrashCourse](https://scottylabs.org/crashcourse/).

## Previous Talks

We've run WDW many times before, sometimes with different workshops. Here are
previous workshops that aren't running this year, but whose resources resources
might be useful:

- [Synergize Your CSS: Using a Framework][css-frameworks]
- [UX Prototyping with Framer.js][framer]
- [Frontend JavaScript with AngularJS][angular]
- [Crafting Well-Designed Sites][design]
- [P5 - JavaScript Graphical Sketchbook][p5]

[basics]: basics/
[html+css]: html+css/
[design]: design/
[p5]: p5/
[react]: react/
[css-frameworks]: css/
[javascript]: javascript/
[tensorflow]: tensorflow/
[backend]: backend/
[deployment]: deployment/
[angular]: angular/
[framer]: prototyping/
[rest]: rest/
[postman]: postman/
[setup]: setup/
[appengine]: appengine/
[extensions]: chrome extension/
[git]: git/
[flask]: flask/
[express]: express/
[beautifulsoup]: beautifulsoup/
[react]: react/

<!-- schema.org information about the event, so it shows up in Google -->
<script type="application/ld+json">
{
  "@context": "http://schema.org/",
  "@type": "Event",
  "name": "Web Dev Weekend",
  "organizer": {
    "@type": "Organization",
    "name": "ScottyLabs",
    "sameAs": "https://scottylabs.org/"
  },
  "startDate": "2016-11-4T13:40",
  "endDate": "2016-11-5T20:00",
  "description": "A series of interactive workshops that teach the fundamentals of web development.",
  "location": {
      "@type": "Place",
      "name": "Wean Mac Cluster",
      "address": "WEH 5201"
  },
  "image": "{{ site.baseurl }}/assets/img/logo.svg"
  }
</script>
