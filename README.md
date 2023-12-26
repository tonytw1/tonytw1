Next available for work February 2024


## Personal projects

Non dressage code which solves problems I'm interested in.

Attempting to show competence and a vague understanding of how computers work.


### Squirrel Detector

[Squirrel Detector](https://github.com/tonytw1/squirrel-detector) demonstrates a willingness to tackle a new
technology (machine learning) and use pragmatic tools (python, MQTT) to realise something end to end.


### Wellynews 

[Wellynews](https://github.com/tonytw1/wellynews) aggregates community news from my home town.

Shows sensible evolution of a long-running project into separate services which can then 
develop into standalone applications in their own right.

Demonstrates a commitment to openness and Internet standards by supporting RSS views of all content.


### OpenStreetMap Jigsaw

[OpenStreetMap Jigsaw](https://github.com/tonytw1/osm-jigsaw) is a fairly unhinged exploration of the geometry of the OpenStreetMap dataset.
Transforms the ~ 5 billion elements of an OSM extract into sorted graph of shapes which it exposes as a JSON API.
This graph to used infer readable place names solely from the arrangement of nested shapes.
Trade-offs and optimizations to make this run to completion on an obtainable computer.

## Language specific competence

### Go

[MQTT Scraper](https://github.com/tonytw1/mqtt-scraper) demonstrates a goroutine and the use of locks 
(which seem popular in the Go world) to control concurrent access to a shared resource. 
This application is routing metrics; probably a good example of the systems programming glue which Golang excels at.

Packaged as a container image to defer conversations about where it actually runs.
Google Cloud Build for infrequent builds.


### Kotlin

[NominatimAC](https://github.com/tonytw1/nominatim-ac) is an example of a Spring Boot / Kotlin application 
which has been migrated inflight from Java. The proper documentation of optional values was an important improvement over Java.

This application has ~ 100 million records in its dataset demonstrating knowledge of working with large (won't fit in memory) data streams.

[Whakaoko](https://github.com/tonytw1/whakaoko) is another Kotlin / Spring Boot application with more moving parts and persistence.
Long-lived run time which has todo real work against flaky third party URLs.

I used Kotlin for [Advent of Code 2023](https://github.com/tonytw1/advent2023) and it seemed to produce lower line counts than Java.
The syntaxes for filtering, mapping and sorting were alot more memorable than their Java equivalents.


### Java

Java is still an important language which is predominant in whiteboard interview settings.

General Java competence is demonstrated in these [Advent of Code 2022](https://github.com/tonytw1/advent2022/tree/main/src) submissions.

[This intuition](https://github.com/tonytw1/advent2022/blob/b2a345ae7c4fa36a59602d9e3a871d3ee14a4546/src/Day15.java#L45) on line 45 of [Day 15](https://adventofcode.com/2022/day/15) part 2 was considered fairly novel by my peers.

Includes some token [stream usage](https://github.com/tonytw1/advent2022/blob/b2a345ae7c4fa36a59602d9e3a871d3ee14a4546/src/Day15.java#L87). 

### Scala

[Cards](https://github.com/tonytw1/cards) is an example of how I'd use Scala and Play Framework for a standalone service.

Scala Futures and WS Client are a good fit for the long-running async HTTP fetches this application makes.

I do not feel that Scala 3 is applicable until it's officially supported by Play Framework.


## Commercial code

Unsquashed real world code. Dealing with uncertainty and been a good neighbour in a shared code base.

- [Google Showcase implementation at the Guardian](https://github.com/guardian/frontend/pull/24038).
- [Guardian Grid Elasticsearch migration](https://github.com/guardian/grid/pull/2373/commits).

- [Addressing an undocumented feature which was driving inbound support requests](https://github.com/guardian/open-platform-site/pull/88/commits/4c7db919b6b806c62fdec17fb0e6bf89235676a1)


## Other


### Android

Been able to customise your device using the skills from your day job was a big draw.
Been able to read and contribute to front end code bases is still a useful collaboration skill.

I developed 2 Android apps with large user bases; [Guardian Lite](https://github.com/tonytw1/guardian-lite) and [London Bus Times Preview](https://github.com/eelpie/countdown-android).
The latter received a highly commended award in [Transport for London's 2013 accessible app competition](https://www.tfl.gov.uk/info-for/media/press-releases/2013/december/tfl-announce-winners-of-accessible-app-competition).
