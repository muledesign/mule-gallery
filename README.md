# Mule Gallery

Hello, intrepid steward, custodian, or curator of Mule Gallery. I welcome you. If you are here, the task of updating the Internet Web Site has fallen to you. This trial, once terrible to behold, has been streamlined as of late, and I, the README, humbly present myself as your guide. Read on, my stalwart charge!

## Updating show information
At any given time, the Mule Gallery site has information on the **current** show, and the **upcoming** show. Information for each show is pulled from a file in the `_shows/` directory. Click that folder, click the file you want to update, and click the ✏️ button to edit the show information. Most fields take a simple and mostly self-explanatory bit of text enclosed in quotes. The show description can be rather longer and is written in [Markdown](https://daringfireball.net/projects/markdown/).

## Uploading images
Go to the `images/` folder and click **"Upload files"**. _It's that easy!_

## Adding upcoming events
Add a `.md` file in the `_events/` directory. They should look like this:

```
---
title: ""
link: ""
datetime: ""
order: 1
---
```

The events are ordered on the site in the order they were made. Events without a link will show up juuust fine, but all the other fields are mandatory. When an event is over, you can just delete the event file to take it off the site.

## Anything else
Ask somebody? I dunno.
