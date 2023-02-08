# The Case for Open Source and Open Data

Some might argue that the case in favour of open source software and open data is clear and obvious and no longer needs to be made. 
In particular data and their handling by companies, which has drawn a lot of attention in recent years. From the case of Cambridge Analytica (3) to books and interviews how the data economy has been limiting our freedom (see for example ref 1 and 2 below).
The free software and open source software movements probably need no introduction to software engineers. A lot of us are writing free and open software, are engaged in maintaining it or are at least using some open source software projects and libraries in our engineering work.

But apart from the big picture, there is a very concrete and tangible impact when using proprietary software and data formats. And one that happened recently to me, which I want to share.

It started with me trying to do some scripting work one Wednesday morning in February. Scripting has become an important part of my podcasting efforts. And with over 50 episodes under the belt there's been a lot of scripting. 
Since I started podcasting, I have been using an app that manages scripts, notes and drafts very well. It runs on desktops and mobile devices, which means you can use it anywhere. The text editor is simple and well designed, the notes are in markdown language. 
It comes, as apps do these days, with an annual tax. Pardon me, I mean subscription. 

All well and good. 
Erm... not quite. Because on that aforementioned Wednesday morning, the licence server of the app, which manages subscription and users, decided to throw a wobbly. It no longer recognised and accepted my subscription, which at that stage was still valid for another 6 months. And instead of working on my content I spent the entire morning trying to restore my subscription and access, not to mention edit, my content, which now sadly sat behind an insurmountable paywall. 

It all came back together a few hours later. However, by then I thought I should try and salvage the content I created and back it up elsewhere. Helpfully, there is a share function in the app. And it saves your data locally or to cloud backup services such as Dropbox. 
Alas, the data it saves are in a proprietory binary format. Which is odd, given the content is simple text in markdown format (I suspect the file format could be hacked, though). Well, not giving up I tried to export it. Which then gives me the exported content in PDF. Not exactly an editor's dream either, I'd say.

In practice, this means all the content that I created, all the data I produced are actually not mine. I have given the family silver away, in exchange for a "seemless user experience" and an annual subscription fee. The company, through error or design, can close the door any time. And that is before we ask ourselves the question what they do with all the other user data. 

That this is not an isolated incident can be seen in other examples, where users and subscribers of e-Books find their previous purchase was removed. Or try to restore a purchase for an item that is no longer available (there was a recent report on that one, too). 

Don't get me wrong. I do think software engineers and creators of apps must be paid, and paid well. After all, I am one of them. But as we have moved from a software purchase to a software subscription based economic model, it is no longer only the use of software we pay for. We also pay for access to any content, intellectual material and data we produce with it as well. 

There was a great talk I went to at [FOSDEM 2023](https://www.fosdem.org/2023) given by an investigative journalist who uses open source software for creating tools tackling disinformation (4). Journalists in the field don't have the luxury to work with software that is tied to specific devices (they have to work with whatever they have access to) and that limits access to content. They cannot afford to go through the experience I went through this morning with my editing software. It needs to work. They need access to the content. Wherever. Whenever. Full stop. 

Subscription based apps, and you hardly find any other in app stores these days, have become cash cows for companies. Just think how much money per month you spend on music and video streaming services, apps, cloud storage, news, social network services, content sharing etc. All the while the content you get through the services has become ephemereal. Here today, gone tomorrow. 

But there is a different way and I think a way that serves us better. The way that open source/free software and open data give you back control. Maybe the experience won't be quite as smooth as with subscription end to end services. But in actual fact, often the additional effort is minimal and a question of getting used to working in a slightly different way. 

Take the scripting software as an example. It helps to split the "smooth" end-to-end experience into its essential components.  
- **editing** there is a plethora of free command line and GUI based text editors available
- **data format** store the data in a format that is a recognised and open standard and freely exchangeable. For text this is trivial, even if it is formatted as markdown. 
- **organising** use the file system. 
- **sharing** This part, there we will need another service. GitHub comes to mind, but I appreciate that not everybody is comfortable with it. Dropbox is very popular. And there is another open source based service called [Nextcloud](https://nextcloud.com), but I haven't tried it yet. 

Setting all this up and using it took me far less time than figuring out how to restore my paid subscription and regaining access to my content. Lesson learnt!

## References
(1) Shoshana Zuboff: The Age of Surveillance Capitalism, Profile Books Ltd, 2019, ISBN 978 1 78125 684 8, eISBN 978 1 78283 274 4
(2) [Financial Times 30 January 2023 paywall](https://www.ft.com/content/0cca6054-6fc9-4a94-b2e2-890c50d956d5), Interview with Shoshana Zuboff: 'Privacy has been extinguished. It is now a Zombie'  
(3) Wikipedia on [Cambridge Analytica scandal](https://en.wikipedia.org/wiki/Facebook–Cambridge_Analytica_data_scandal)
(4) [FOSDEM 2023 Tackling disinformation using opensource software](https://www.fosdem.org/2023/schedule/event/openresearch_tackling_disinformation/)