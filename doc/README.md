# Overview

The EMC2 website is built using [Jekyll](https://jekyllrb.com/) a static site generator.
Most dynamic content, such as the workshop programs is described using simple Markdown
documents. A small amount of content is also contained in HTML.

The site has been designed to minimize the amount of HTML or styling work required when
adding new content.

## Directory Structure
* _editions - Contains the collection of instances of the workshop (e.g. HPCA-19)
* _includes - Contains common page content to be included in most pages (e.g. nav bar)
* _layouts - Contains templates and logic to construct various pages of the website.
* _organizers - Contains the collection of workshop organizer biographies.
* _programs - Contains the collection of workshop programs/schedules.
* assets - Contains various site assets like images etc.
* doc - Contains documentation for this site.

## Collections

Dynamic content for the site is defined in [collections](https://jekyllrb.com/docs/collections/).
Collections allow for related content to be defined and manipulated using queries and filters.
For example, a collection of program items can be filtered based on the date or workshop edition.

# Editions

The editions collection contains the instances (e.g. 2nd edition at HPCA 2019) of the workshop.
Each instance is defined in an HTML file that should be named with the following convention:

`NUMBER-CONFERENCE-YY.html`

`NUMBER` is 1, 2, 3 etc.
`CONFERENCE` is the common abbreviation of the co-located conference e.g. asplos
`YY` is the two digit year that the workshop is held e.g. 18 

## Edition Data

Most of what is contained in he edition page is configuration data related to the workshop.
The table below describes the configuration fields:

| Field | Description | Example |
|-------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| permalink | Defines the URL path for the workshop page. Should be set to `/CONFERENCE-YY` | /hpca-19 |
| edition | Unique identifier for the workshop. Should be set to `CONFERENCE-YY` | hpca-19 |
| colocated_short | A short name of the co-located conference. | HPCA 2019 |
| colocated_long | A long form name of the co-located conference. | 23rd ACM International Conference on Architectural Support for Programming Languages and Operating Systems |
| colocated_url | A URL to the co-located conference website. | http://hpca2019.seas.gwu.edu/ |
| event_date | Date of the workshop. Must be formatted as `YYYY-MM-DD` | 2019-02-17 |
| event_location | The city where the workshop is to be held. | Washington D.C. |
| event_room | The room at the conference venue where the workshop is to be held. | Doogwood Room |
| event_session | Specifies if the workshop is a full or half-day session. Must be one of `full` or `morning` or `afternoon` | full |
| is_upcoming | Set to true to indicate this edition should be listed as an upcoming workshop. |  |
| is_accepting_submission | Set to true to indicate this edition is accepting paper submissions. |  |

## Edition Assets

The only asset required for an edition item is the header background. This image should be a relatively
large JPEG and should ideally reflect the location that the workshop will be held.

The images must be located and named to match the edition collection item entry.

`assets/images/editions/NUMBER-CONFERENCE-YY.jpg`

# Programs

The programs collection contains the individual keynotes, talk and paper sessions of a workshop.
Each instance is defined in an markdown file, the name of the file is not important but should
be something sensible.

There are several types of program items each with unique configuration formats. The following
types are defined:

| Type | Description |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------|
| keynote | A keynote talk from a single speaker. A keynote consists of and abstract, biographies and avatar. |
| invited_talk | An invited talk. An invited consists of and abstract, biographies and avatar. |
| paper_session | A session where one or more papers are presented. A paper session consists of on or more paper titles with corresponding authors. |
| welcome | A welcoming note. |
| close | A closing note. |
| break | A program break for coffee, lunch etc. |

## Common Program Data

Most of what is contained in he edition page is configuration data related to the workshop.
The table below describes the common configuration fields for all program item types:

| Field | Description | Example |
|------------|---------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| edition | Specifies the workshop edition to attach this program item to. Must be set to `CONFERENCE-YY` | hpca-19 |
| type | Specifies the kind of item this represents. Must be one of `keynote`, `invited_talk`, `paper_session`, `welcome`, `close`, `break` or `lunch` | invited_talk |
| time_start | Specifies when this program item is scheduled to start. Must be formatted exactly as `YYYY-MM-DD hh:mm:ss` | 2018-03-25 14:30:00 |
| time_end | Specifies when this program item is scheduled to end. Must be formatted exactly as `YYYY-MM-DD hh:mm:ss` |  |

## Keynote and Invited Talk Program Data

| Field | Description | Example |
|---------------------|----------------------------------------------------------|--------------------------------------------------------------------------|
| title | The title of the talk. | 'Goldfarb Conjecture: A Mysterious Idea' |
| speaker | Details about the speaker. |  |
| speaker.name | The full name of the speaker. | Michael Goldfarb |
| speaker.affiliation | The company or university affiliation of the speaker. | NVIDIA |
| speaker.avatar | The file name to use for the avatar image. | goldfarb.jpg |
| speaker.url | The URL to the speakers website. | http://www.goldfarb.io |
| presentation | The file name to use for the uploaded talk presentation. | goldfarb-talk.pdf |

All talks should also contain an abstract and speaker biography. This can be added to the
collection item files contents after the configuration data is specified.
