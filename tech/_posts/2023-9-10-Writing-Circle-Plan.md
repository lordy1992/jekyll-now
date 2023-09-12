---
layout: post
title: When worlds collide
---

I've decided to take on an idea influenced by one of my other great loves - [writing](/writing/).
There are many websites out there for writers to find community, to critique and get feedback, to look for advice, but I
haven't found anything that checks all the boxes I'm looking for.

I'd love to find a website with a richer feature set for providing feedback (a la inline comments, and 'track changes'),
along with a forum that is publicly viewable - so many writing forums these days are walled gardens, but I like to try before I buy (or, before I make a free account).

Since I haven't been able to find something suitable, I decided I'd build it myself.

#### MVP
I can imagine a suite of features one day (contests, agent/publisher query tools, articles, etc...), but for now I'll focus on the [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product),
and for that, here is the simplified set of features I'm aiming for:

* I can create an account, signing up with an email and password
* I can sign in to my account
* I can view a forum with a variety of categories, and can view posts within the categories, even when I am not logged in
* When logged in, I can create new posts in the forum
* Posts are versioned and maintain a history
* I can post my writing to a critique tool, publishing it to other users of the website
* I can view writing posts, by type and/or genre, and I can leave feedback by:
  * Direct edits in the document (that the submitter can accept or decline)
  * Comments annotating the document
  * Overall comments below the post
  * If enabled, public comments/discussion on the post

#### Milestones
These are the milestones I'm looking at for the MVP:

Milestone 1: Website is up and running (locally), with a basic landing page, forum + categories visible

Milestone 2: Account creation + login

Milestone 3: Forums - ability to post

Milestone 4: Ability to create new posts of work, versioned, can create a new version or load an old one

Milestone 5: Critique feature

Now to get started. I've set up a [Trello](https://trello.com/) board (progress!), and the first task is to come up with
a basic design and decide on the tech stack.