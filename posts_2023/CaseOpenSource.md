# The Case for Open Source and Open Data

It all started with me trying to do some scripting work one morning in February. Scripting has become an important part of my podcasting efforts. And with 57 episodes published at the time of writing, there's been a lot of scripting. 
For over two years, I have been using a scripting app and it's been an overall good and very smooth experience. It runs on desktops and mobile devices. The text editor is simple and well designed and uses markdown formatting. 

All well and good. 

Until the aforementioned morning, that is. On that day, the licence server of the app, which manages subscription and users, decided to throw a wobbly. It no longer recognised and accepted my subscription, which at that stage was still valid for another 6 months. All of a sudden I was locked out. And instead of working on my content I spent the entire morning trying to restore access to it. 

When the licence server gracefully accepted my credentials again, I thought I'd do the right thing and start saving and exporting my scripts elsewhere. Helpfully, there are share, save and export functions in the app. 
Alas, the content is saved using a proprietary, binary format instead of the markdown text format it has been written in. And exporting gets you PDFs, which isn't exactly an editor's dream either. 

In short, the purveyor of the application had me in a vice by restricting both access (I have to be a paid subscriber) and use (the data format is proprietary or a difficult to edit version) of my content. Which raises an interesting question about who controls and owns the digital content we create (see [3]).

Take books, for example. Purchasing a printed copy means you own the book. Its keep and use is under your control. With digital books on the other hand, you purchase the rights to read the content, but you do not own it. I know this reads like hair splitting. And in practical terms, you may choose not to worry about it. 
Unless this happens: in 2019, Microsoft closed its Books section (see [2] in the ref section). All purchased books were no longer accessible and e-libraries vanished into thin air. In cases like this, control over your data and content clearly do matter. 

Which brings me back to the little wobble I had with the scripting app. The subscription fee I pay not only buys me the rights to use the software. It also stores, shares and organises the data I produce with it. This type of service has created an opportunity for some vendors to lock you into their "ecosystem" by taking effective control over your data and intellectual property. 

As more and more companies move into subscription based services, it is more and more important that we retain (and regain) control over our digital work and content. It befalls to us to ensure we select vendors that follow [FAIR](https://www.go-fair.org) principles: findable, accessible, interoperable and reproducible. We can do this by choosing products based on open source software and open data standards. 

There was a great talk (see [1]) I went to at [FOSDEM 2023](https://www.fosdem.org/2023) given by an investigative journalist who uses open source software for creating tools tackling disinformation [1]. Journalists in the field don't have the luxury to use software with tight access controls and limitations. They can hardly afford to go through the experience I went through. They need access to their content. Wherever. Whenever.  

Of course, this comes at a price. Software engineers and companies want to make a living, too. But running a business and using open source software and data standards are no contradiction. In fact, many successful companies are using them in their products and services. 

In terms of my scripting app, it didn't take me too long to set up an alternative workflow. The app had three main parts, which I replaced with the following:

- **Edit:** I use Visual Studio Code. But frankly any text editor would do, command-line (emacs) or GUI based. 
- **Organise:** based on the file system, i.e. build a folder structure around your content. 
- **Share and Store:** I use GitHub and Dropbox. Of course, there are many other cloud services around.

This is, of course, no longer a seemless end to end solution. And it looks like a lot of additional work. But it isn't. The extra effort turns out to be marginal. And it gives me back what I lost, briefly, before: access and control over my data. 


## References
[1] [FOSDEM 2023 Tackling disinformation using opensource software](https://www.fosdem.org/2023/schedule/event/openresearch_tackling_disinformation/)
[2] [Microsoft Books closing] (https://support.microsoft.com/en-us/account-billing/books-in-microsoft-store-faq-ff0b7b84-7052-4088-9262-d7e4ee22419c)
[3] (https://theconversation.com/do-we-really-own-our-digital-possessions-115003) Article on ownership rights of digital objects, 2019


