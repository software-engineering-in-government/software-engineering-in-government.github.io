# Software engineering in government community blog
![Github actions status badge](https://github.com/software-engineering-in-government/software-engineering-in-government.github.io/workflows/Fetch%20blog%20posts/badge.svg)

A blog aggregator for stuff relevant to the software engineering community of practice 👾

## How to add content
To add content, add a new section to [planet.ini](./planet.ini), and raise a pull request.

## What can be included
Only add feeds if:

- **all** content published to the feed is relevant to the software engineering community of practice<sup>*</sup>
- the content is published on a blog run by a member of the community or their organisation
- the content is targeted at a technical audience<sup>*</sup>

If a blog doesn't meet those criteria, see if there's a category feed that is more suitable.

<sup>*</sup>This is not the case for many of the blog.gov.uk blogs. If in doubt, consider who decides what gets published and when. If people outside of the community of practice control that, then don't add it.

## Running locally
To build the site locally:
1. install [pluto](https://feedreader.github.io/)
2. install the [digest2 theme](https://github.com/software-engineering-in-government/planet-digest)
3. run `make`

## Licence
All code is licenced under the [MIT licence](https://opensource.org/licenses/MIT).

All content is owned by the original publisher, e.g. anything from blog.gov.uk is Crown copyright and licenced under the [Open Government Licence](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). See individual blogs for more details.
