# Our encampment website project

This site emerged out of a sleepless night of tutorial-watching. It is in plain HTML with minimal CSS, which proves to create maintenance issues related to code redundancy. Time shortages and the amateur nature of the project however prevent the author from learning a more intelligent way of implementation.

## File structure

Self-explanatory.

- 📁 css
- 📁 pages
- 📁 img
- index
- en_index

## Naming convention

Page files are named with their language and purpose.

```
lang_subpage
```

## Subpages

- nav
  - Navigation page (Language change redirects to nav for ease of maintenance)
- journal (index)
  - Daily journal
- events
  - Upcoming and previous events
- links
  - Useful links
- media
  - Us in the media
- publish
  - Our articles (Often full versions)
- gallery
  - Photos, posters, art related to our encampment
- demands
  - Our demands.
- public
  - Public information that we received from the University or traced ourselves.

## Maintenance reminder

When updating universal parts of the page (the head, navbar, the footer, etc.), remember to update it in every subpage. A useful convention here could be to start with nav.html of either language.
