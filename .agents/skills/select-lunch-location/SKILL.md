---
name: select-lunch-location
description: Use when asked to select a lunch location by a group of people (colleagues) working in the same place with a wide variety of option available nearby taking the regular weekly nature of the lunch event under consideration
---

# Select Lunch Location

## Overview
Selecting a lunch location regularly (usually weekly) requires fairness. Collect information about participants and up-to-date preferences first; check for any special dates (e.g. somebody in the group had a birthday recently), search for open lunch opportunities nearby and make a decision.

## Step 1: collect participants
Collect the names of the participants in short form (names only, no surnames) as list, extract the information from prompt, if available; ask the user otherwise.

## Step 2: check special events
Check whether any of the participants had birthday recently (within last week) and hasn't yet used it to select a lunch location.

## Step 3: check nearby lunch locations
Ask for team current location -- the lunch location **MUST** be within comfortable walking distance (~15 min), if the weather conditions allow it (no rain, no hail, no snow). Otherwise, look for delivery options within the same distance. Use https://www.accuweather.com (or any other online weather forecast available to you) to identify the weather at the location.

## Step 4: make decision
Summarize collected information. Suggest a location based on the collected information. If the suggestion is accepted, store it locally in the file following the pattern `LUNCH-yyyy-MM-dd.md` together with the list of participants, use following template:

```
---
name: LUNCH-<yyyy-MM-dd>.md
participants: <list-of-participants>
date: <yyyy-MM-dd>
location: <location>
---
```
.

If there are any already stored decisions available, use them as exclusion criteria for the suggestion to ensure, the team does not visit same location consecutively many times in a row. Try to rotate available options as much as possible.