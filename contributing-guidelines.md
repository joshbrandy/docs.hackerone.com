# Style Guide

### Adding New Articles
You can add new articles to either the Hacker Book or the Program Book.

#### Hacker Book
When adding a new article, make sure you format the file such that the first several lines of the markdown file are:

`---`<br>
`title: "Title of the Article"`<br>
`path: "/hackers/title-of-the-article.html"`<br>
`id: "hackers/title-of-the-article"`<br>
`---`

#### Program Book
When adding a new article to the program book, make sure you format the file such that the first several lines of the markdown file are:

`---`<br>
`title: "Title of the Article"`<br>
`path: "/programs/title-of-the-article.html"`<br>
`id: "programs/title-of-the-article"`<br>
`---`

#### Changelog Entry For a New Month
You can also add a changelog entry for a new month that isn't listed on the changelog yet. To add a changelog entry for a new month, make sure you format the file such that the firs several lines of the markdown file are:

`---`<br>
`title: "Month Year"`<br>
`path: "/changelog/[year]/[month]"`<br>
`date: "year-month number"`<br>
`---`

Example:
<br>`---`<br>
`title: "November 2016"`<br>
`path: "/changelog/2016/November"`<br>
`date: "2016-11"`<br>
`---`

### Github Formatting
How do I... | Answer
----------- | -------
Add a link to a page within the docs site of the same book | `[Start H1 Response](start-h1-response.html)` or `[Start H1 Bounty](start-h1-bounty.html)`.
Add a link to a page within the docs site to an article in another book | `[Start H1 Bounty](/programs/start-h1-bounty.html)`
Add an image | `![image name](./images/signal-impact-2.png)`
Referencing the HackerOne blog link | Use `https://hackerone.com/blog` not www.hackerone.com/blog

### Active Voice
We use active voice at HackerOne as active voice is more personal and engaging vs. passive voice. In active voice, the subject does or acts upon the verb, while in passive voice, the subject is being acted upon. 

Active Voice (Yes, please use this!) | Passive Voice (Steer away from this)
------------------------------------ | -------------------------------------
Click the link to search | The link should be clicked when you're ready to search for an article.
The hacker reported the vulnerability. | The vulnerability was reported by the hacker.
The security team triaged the report. | The report was triaged by the security team.

### Contractions
In order to convey a personal and less formal voice, it's best to use contractions instead of the formal non-contractions.

Contraction - (Yes, please use this!) | Non-Contracted Phrases (Steer away from this)
------------------------------------- | -----------------------------------
can't | cannot
don't | do no
won't | will not
it's | it is
they're | they are
we've | we have
you're | you are

### Spelling
There are some words that can be used either way. In order to keep consistency, we need to agree on which ambiguous word we'll be using.