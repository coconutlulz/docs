
## 2018-August-15 (Wednesday) | ⭐️ ⚙️

Now it's the time to explain what is the purpose of Trinkets and why it exists.

Some of the things are not yet crystal clear in my mind, so it might take some time to put them in writing and I might come back to edit this text in the future.

I'm using a Github repository and not a normal blog post, both because I'm lazy and also because this is how I worked for years anyway. I kind of feel nervous when I post a public post, but writing to myself feels natural... Maybe I'll repost this text on Medium, or whatever, when I consider it finished.

## What is Trinkets

"Shiny Trinkets" or "Trinkets" is the name of a Github organization and is a place to create free & open applications and libraries.
I'm writing open source for 10 years now, but the Trinkets project has a unique history, that I'll write about later.

I have taken a lot from the open-source community, so this is my humble way of giving back.

Even if not the entire suite of applications is useful for someone, each application can be used separately and even more, parts of the apps can be hacked together to create new things, because the MIT license is very permissive.

So these are the goals of this organization:

## Constitution / Manifest / Philosophy

Our applications are created by humans and for humans. They are not created for machines. And not for IT companies, or for marketing companies.
The focus of the applications is not to make the creators of the apps empowered, or to make a huge profit. The focus is for the applications to be really useful and easy to use.

We believe that the tools should be totally out of our way and because of that, the software we build has special limitations and requirements.
The first thing is that a piece of software should enable good practices in the user, in such a way that if the software is eliminated, the user can still use the good practices in his daily life and all the data created and used by the software is still usable by the user.

User's data is solely his own and he must have absolute control over it.
By default, all data is stored on user's devices and can be easily seen by the user in its entirety.
The user might decide to store the data somewhere else (eg: cloud storage)
The user should know where that data is located and is free to change his own past data (eg: he might want to redact sensitive data).

The conclusion that comes from the previous ideas is that it's highly preferable to store the data in human readable text files, than in a binary database, even with the risk of an acceptable performance loss. A good compromise can be that the "the only source of truth" is the readable text file, but a specialized converter translates the text into a performant structure in a database, from time to time and the application uses the optimized database.

Our software must work offline just as normal as online, because we have no central servers that dictate the behaviour of our apps. But we understand that Cloud Services are important for specific usecases so the user should be able to use them without limitation.

All the libraries and dependencies we use are carefully selected to be the best quality. And we try to keep them to a minimum.

We like to call these concepts "Ethical software". Don't treat your customers like products. Just like ethical eating, that doesn't treat animals like products.

We understand that this kind of software cannot satisfy everybody, but that's OK. In the same way being straight is not for everybody. Or eating vegetarian food doesn't satisfy everybody's tastes. Choice and diversity are important.

There are other people and applications that respect the same principles and we applaud them.

This line is extracted from `jrnl` manifest:
> jrnl is a simple journal application for your command line. Journals are stored as human readable plain text files - you can put them into a Dropbox folder for instant syncing and you can be assured that your journal will still be readable in 2050, when all your fancy iPad journal applications will long be forgotten.

^ exactly that 👍

So, this ends my first public post about this. If you have any comments, ideas, please create an issue, or let's talk on [Reddit/r/ShinyTrinkets](https://www.reddit.com/r/ShinyTrinkets) (it's pretty lonely down there but hey, let's make it crowded!).

> (U) [^_^] (U)<br/>

PS: I've written parts of these ideas and the constitution 2 months ago somewhere in my text documents, but I forgot about it. And a few days ago, I wrote the constitution again and then, I discovered the text from 2 months ago... I was shocked to discover it's exactly the same!! I used different words, but I said exactly the same things...

~Signed: CroQ

--------------------------------------------------------------------------------

## 2018-July-30 (Monday) | 🤖 ☀️

This is my first ever public post regarding the Trinkets projects! Wheee ⭐️ 🎉 !!

I'll take the time to explain what This Github Org is about, why I created it.

## Eof()
