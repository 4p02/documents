A tool for creating brief summaries and short links for web content
- It takes a URL of a webpage or a YouTube video as an input and returns a brief summary and a shortened URL.
- It has both free and pro features

Features:
- Short Link Creation
- Summarization: uses NLP or LLMs to summarize the content of a given web-url
- Custom Summarization Levels (pro-feature)
- Social Media Integration through Google and FB authentication (pro-feature)
- API Access (pro-feature)
- User Dashboard (pro-feature) for registered users to track their activity, manage links, and customize settings.



backends:
- golang
- python
  - flask
  - django
  - jinja
- node/deno
  - express

db:
- maria/postgres
- postrest
- sqlite

frontends:
- web frontend
  - mockups on figma?
  - react
  - svelte
  - js/ts
  - bootstrap
  - tailwind
  - sass
- api
- webextension (js/ts)
  - web-ext



requirements:
- accounts
  - authentication: email/pw, oauth
  - issue/manage api keys
- dashboard
- summarize
  - transcribe videos with whisper, maybe include description (cpp/py)
  - scraper (py)
  - selenium (py)
  - webdriver (py)
- api
  - auth
  - create/manage short links
  - summarize url webpage



teams:
- backend:
  - mikey, meet, mike, john
  -
- frontend:
  - qiqi, jose, david, hamza




----
release planning:

Objective:
To develop software requirements (product and sprint backlogs). This document will detail the system which is stated in the project proposal.
- Be as detailed as possible
- You will be able to revise it slightly later.
Tasks:
- Think, discuss about the requirements (user-stories) and prepare
- Find a tool to manage the user-stories
- Invite the TA to your release planning meeting to finalize the requirements
Write your report and submit it by Friday 26rd Jan by 23:59.
Grading: completeness, thoroughness and correctness of the requirements/user-stories and as well as submission format (requirements, format, language, etc.)
Upload all of your reports to your GitHub page and Brightspace. Include a breakdown of each person’s contribution.
