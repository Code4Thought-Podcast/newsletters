# The Case for Open Source and Open Data

It all started with me trying to do some scripting work one Wednesday morning in February. Scripting has become an important part of my podcasting efforts. And with over 50 episodes under the belt there's been a lot of scripting. 
For two years, I have been using an app for that and it's been an overall good experience. It runs on desktops and mobile devices. The text editor is simple and well designed, the text is based on markdown formatting. Alas, it isn't free. But hey, there is no such thing as a free lunch, right?  

All well and good. Until the aforementioned Wednesday morning, that is. On that day, the licence server of the app, which manages subscription and users, decided to throw a wobbly. It no longer recognised and accepted my subscription, which at that stage was still valid for another 6 months. And instead of working on my content I spent the entire morning trying to restore my subscription. I could no longer work with my content from two years, leave alone create new one. 

When the disturbance in the force passed and the licence server gracefully accepted my credentials again, I thought I'd do the right thing and start saving and exporting the content elsewhere. Helpfully, there are share, save and export functions in the app. 
Alas, the content is being saved in a proprietary and binary format rather than the markdown formatted text it is being written in. And exporting gets you PDFs, which isn't exactly an editor's dream either. 

Which means that not only is access to the content being restricted. Further use and sharing is equally limited. In short, I have little to no control over the content I create within the app. The purveyor of this app has you in a vice - or in modern speak you are caught in their "ecosystem". 

Don't get me wrong. I do think software engineers and creators of apps must be paid, and paid well. After all, I am one of them. But as we have moved from a software purchase to a software subscription based economic model, it is no longer only the use of software we pay for. We also pay for access to the content, intellectual material and data we produce with it as well. 

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