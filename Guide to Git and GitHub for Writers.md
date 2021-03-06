# Guide to Git and GitHub for Writers



## Introduction

Earlier this year, my simmering rage at conventional word processors finally boiled to the surface, driving me to take the drastic action I'd been putting off for years: Learn to write and publish content using Git and GitHub (*insert gasp here*.) 

Okay, maybe that's being a *bit* dramatic (hey, I'm a writer - I'm using creative license here). It wasn't exactly rage. More like an underlying frustration I couldn't quite put my finger on. After all, what was different about this project versus the hundreds I've worked on before, that made working with Word (or Google Docs, my old go-to) untenable? 

Actually, a few things:

- I was working remotely on a long-term project for a startup software development client with high technical expertise located on the other side of the world. 
- We needed a central, open-source, reliable platform that everyone knew how to access and use.
- We had several collaborators, each with valuable insights and perspectives to offer on the content I created. 
- With so many small pieces of content, we needed an easy way to track progress, revisions and dialogue on each one. 

Enter GitHub. After a couple of months plugging away on Google Docs (a tool I'd sworn by previously and still use for collaborating with less technically savvy clients on short-term projects), we all began to discover its limitations when it came to formalizing an efficient content production and approval process. My client (Custom Programming Solutions) generously offered to teach me how to use Git and GitHub so we could collaborate more productively long-term. *Bonus: I get to share what I learned with you!* 

 This is a guide for writers, by a writer/content marketer who's been where you are: frustrated with the constraints and headaches current writing software and workflows foist on us, and wondering if there's anything better - an open source, distraction-free, secure platform that supports hassle-free collaboration between you and your clients. 

I'll cover the following: 

[TOC]

### What are Git and GitHub?

### Git

Git is a general purpose distributed revision control system. Essentially, it's version control software (VCS) designed to let you manage your workflow and keep track of versions of documents. 

 VCS systems calculate differences, or deltas, between documents. Comparing differences between versions means some exciting options appear at your fingertips, including:

- Reports on differences between versions

- Easily merging changes to documents (which can be confusing with Word or other word processors) 

- Referencing change sets directly (so you and your collaborators each understand exactly which changes are being discussed)

- Creating patches (*explanation here*)



  For Git to be able to calculate differences between files, the files must be stored in a document that the software can "read" so it can detect what's changed. A plain text file (e.g.: a Markdown document) is perfect for this. Any changes to the document will be seen in the lines of the file that are responsible for it. Contrast this to other file types like Word .doc files, where a change to one line is hard to locate in the file, or images, where changing the file won't lead to a nice textual summary of what's changed. 



### Who needs this guide?

------





### Why should writers use GitHub?

---

 Though Git is a repository hosting service much-loved by developers for its robust version control, issues management and change tracking capabilities. It turns out, writers are on a continual quest for a tool that offers these features and allows them to work on a truly collaborative basis with their clients.

#### The problem with word processors and web-based writing tools 

*Explanation*

Multiple formats, repurposed content, collaborators, need to be cross-compatible with different devices 

Use this workflow and your content will be ready for the web faster

### Benefits of distributed vs. centralized systems

Git is a decentralized version control system. Here's why that's important: 

- **Each repository is essentially a backup.**
  My client (who's used Git for several years) says he has yet to lose a large amount of data on any project using Git. Even if one machine goes down, you can still access your data from other machines. The decentralized system is a nice backup feature in disguise. If you didn't have this, you'd need to consider backups and disaster recovery strategies. Not having to be so worried about this means you reduce the mental burden on you and your team, and reduce the risk of a devastating loss of data and hours. 

- **You'll have a stable platform to collaborate with clients and partners.**

  Because the system is decentralized, it's designed to handle multiple people can work on the same document at the same time. While some centralized systems (such as Joomla, *other examples*)





### What you need to get started

---

You'll need to install and set up a few tools that will help you do your work faster and more efficiently. Set up your workflow now and save hours on repeatable tasks. 

### Install a Markdown editor

You'll want to work in Markdown for this exercise (read this to find out why). Markdown is a simple markup language that's ideal for writers that lets us control the display of the document. We can create lists, add images, format words in bold or italic, include quotes or raw HTML or do other things using a few keys and non-alphabetic characters such as #, *, or _. 

Brush up on Markdown with a tutorial, and keep a cheat sheet on hand. https://www.markdowntutorial.com/

https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet

#### Typora

[Typora]: https://typora.io/	"Typora"

gives you a distraction-free space to write, complete with a live preview feature that helps you focus on your content. I love how it helps me see an outline of my document at a glance, import and export different file types and keep track of the size of my documents in terms of words, reading minutes and even lines and characters. 

Bonus: The Auto pair feature, which auto-completes pairs of brackets and quotes similar to a code editor, is a huge time saver.

You can use Typora on Windows, Linux and OS X.

Other great text editors include:

[iA Writer]: https://ia.net/writer	"iA Writer "
[Ulysses]: https://ulysses.app/	"Ulysses"
[Visual]: https://code.visualstudio.com/	"Visual Studio Code"



### Set up Version Control on GitHub

------

No matter what type of project we're working on, as writers we need to do a few things with every piece of work - type text, save it, and make it accessible for anyone we're collaborating with to contribute and edit our work. 

Here's how to set up GitHub to work for you:

1. Download Git to your computer. Find the Windows installer here https://git-scm.com/download/win and the OS X installer here https://git-scm.com/download/mac. Linux users - you can probably find what you need.
2. Visit https://github.com/.
3. Create your account.
4. Download the GitHub desktop client. https://desktop.github.com/

That's it! With Git, you can track your own and others' revisions far easier and cleaner than you could in Google Docs, Word or other tools. Plus, you can all simultaneously edit the document by "pushing" your changes.



### So, now you have:

- A working knowledge of Markdown
- A Markdown-focused text editor (Typora highly recommended)
- A way to upload your content to the web without using confusing word processors or proprietary programs 
- A central storage place for your content. Your team will be able to edit, publish and re-use it painlessly across devices and platforms.



### Getting ready to work

------

Now that you've got your workspace set up (think of it as having put one of those IKEA desks together), it's time to create a place for your files and make them accessible to your team via GitHub (kind of like setting up a filing cabinet with folders inside). Here's how to do that. 

#### 1. Create a folder and file

1.  Just like on Google Drive, you should keep all related work in one folder so anyone who needs it can find it. I'll share my folder structure for this repository dedicated to the Guide to Git and GitHub. I've got one folder for the main document and supporting files, and one for images. 
2. Open Typora.
3. Hit **File -> New**.
4. Name your Typora file whatever you want and save it in your work folder (a file name that describes what's in the document is best). 

You should have a basic file structure that looks like this:



To see that outline feature in Typora I talked about before, go to your Typora document and create some headlines and sub-headlines. Then click View -> Outline to see a structural overview of your content. 



#### 2. Build your GitHub repository

Git might seem intimidating when you first dig into it (I was lucky enough to have Janis personally tutor me in all things Git/GitHub). If you don't have a tutor, this process can still be easily broken down into steps:

1. Open GitHub Desktop.
2. Hit **File -> Add Local Repository**.
3. Select your work folder you created in Step 1.
4. You may have to click **create a repository here**.
5. Hit **Create Repository** or **Add Repository** as requested by GitHub.
6. GitHub takes care of everything. You might see hidden files like this in your folder. That's fine, leave 'em there:
7. You'll see your repository in the left pane:



#### 3. Push your repository to github.com 

Right now, your GitHub repository is stored on your computer (what we nerds call "stored locally"), but that won't do - the whole point is to have your stuff secure and backed up in a non-proprietary "cloud", accessible and editable by your team. Here's how to make that happen:

1. Go to GitHub Desktop and hit the **Publish Repository** button in the row along on the top. Here's what it looks like in Windows:
2. Check **Keep this code private** if you'd like to (you'll need to have a paid account and be an organization owner or have admin permissions for your repository. Learn more about making a public repository private. https://help.github.com/articles/making-a-public-repository-private/).
3. That's it for settings, unless you're an organization owner. 
4. Hit **Publish Repository**. 
5. You'll need to log in to GitHub if you're not already. 
6. GitHub Desktop will push your files to the cloud and create a repository on the web-based app. https://github.com/

Now comes the fun part! You get to log in to github.com and see your repository all ready to go:



#### Some extra stuff to do

##### 1. Invite collaborators to your repository

As we've said above, the real power of Git and GitHub lies in its ability to allow groups and remote teams to collaborate easily when it's time to edit and revise your work. 



##### 2. Create a branch

When you create your repository, you start with one master definitive branch. A branch is a copy or "snapshot" of the master as it was at a specific point in time. Anyone working on the repository can create a branch to experiment or make edits before committing them to master. 

This is kind of like when you have different versions of the same file, except with the power of Git and GitHub, it's easy to eventually merge them all together and see changes, instead of ending up with different versions of the same file floating around your team and confusing everyone.

**How to create a branch**

1. In GitHub Desktop, go to the **Branch** menu (second from right).
2. Click **Branch -> New Branch**.
3. Give your branch a name. 
4. Click the blue **Create branch** button or hit the Enter key.

Learn more about branches in the GitHub Guide https://guides.github.com/activities/hello-world/#branch



##### 3. Write a good README file

A README is just like an About or FAQ page for your project.

From makeareadme.com https://www.makeareadme.com/#what-is-it: 
*"A README file is a text file that introduces and explains a project. It contains information that is commonly required to understand what the project is about."*

If you want others to use or contribute to your project, creating a README file before you show your project to the public and placing it in the top level directory is a good idea - it will help bring new people up to speed. 



### So, now you have:

- Someplace to store your stuff, both on your computer and on github.com. 
- Your first project and README files. 

Now it's time to get to work!



### Write

------

 Now that you've got your workspace set up and a way to get your stuff online, it's time to do your thing. So create content - write that blog post, article, e-book or whatever. Here are some tips to keep in mind:

#### 1. Give your document structure

No matter what you're writing, you'll need some basic elements of structure in your document, such as:

##### Headings 

We don't read content word for word any more. We scan. This means your readers will be scanning your document looking for headings to catch their attention and clue them in that the text following is important and relevant to them. Plus, good search engine optimization (SEO) requires headings. 

To make a heading in your Markdown-focused editor, use this syntax:

`# Heading 1`

`## Heading 2`

`### Heading 3`

...and so on, all the way to `###### Heading 6`

If you transfer your content to HTML, each heading becomes proper markup for heading levels, and will look like this: 

`<h1>Heading 1</h1>`

`<h2>Heading 2</h2>`

`<h3>Heading 3</h3>`

...and so on, all the way to `<h6>Heading 6</h6>`

In Microsoft Word, these become proper headings and in PowerPoint, they become slide headings, along with an outline. 

You might also prefer using keyboard shortcuts to create headings. In Typora, use CTRL+1 to create a level one heading, CTRL+2 for a second level heading and so on on Windows. On a Mac, use CMD+1 for a level one heading.



##### Bullet points and lists

Lists are another thing that make your content easily scannable. If you've ever tried to type out a list in HTML in WordPress or another CMS, you feel my pain - the formatting often gets all messed up. Compare that to lists in Markdown, which are as easy as typing: 

`* List item 1`

`* List item 2`

`* List item 3`

This automagically becomes: 

* List item 1
* List item 2
* List item 3


For numbered lists:

`1. List item 1`

`2. List item 2`

`3. List item 3`


You'll notice that each time you hit the Enter key in a list,  another bullet point will appear. Hit the Enter key again to go back to typing in regular paragraphs.

In Rich Text Format (RTF) or Microsoft Word, you'll see proper headings. Export to HTML and, like the syntax above, this becomes proper HTML format: 

<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ul>



##### Links

Including relevant, high-quality links to content on your own and other sites is a must when writing for the web. Here's how to do that:

`[Put link text here](https://www.github.com)`

Becomes: 

[Put link text here](https://www.github.com) 



##### Images

Here's where it gets interesting. Because Markdown is text-only, you won't embed images in your file. Instead, we use code to point to the image:

`![caption for image](image/folder/imageabc.png)`



To insert the code, go to **Format -> Image** in Typora or use the shortcut CTRL+SHIFT+I

When I do so, I end up with a photo embedded in my Markdown document:

![Hand using laptop trackpad](C:\Users\Allison\Downloads\hand-using-laptop-trackpad.jpg)



Click on the photo and you'll see the file path. This will transfer when you export to Word (.doc), PDF or Google Docs. In your GitHub document, you'll see what looks like a link.

However, if you're converting to WordPress or another CMS, you'll have to insert the images again. Inserting the images now is still worth your time, though, because then you'll know where they belong within your content, and you'll have them stored on your computer, so inserting them into your post in WordPress shouldn't take long.



### So, now you have:

- Your content structured in a Markdown file, ready for exporting to Word, PDF, HTML or other formats.
- Images placed where they belong within your content. 
- Images stored on your computer for uploading into WordPress or your favourite CMS.  



#### See your outline

Typora's Outline viewer gives you a nifty way to see exactly how your headlines are structured and where you are in your document at any given time - useful for large projects and for when you need to see all your headings and sub-headings at a glance.



### Commit your work

As writers, we're used to saving our work to a folder or the cloud. With GitHub, your saved changes are called commits. Each time you commit a change, you're able to attach a description explaining why you made that change (for example, if you describe the section you've written in both the title and description for your commit, you'll have an at-a-glance-history of the progress of your work from the day you started until now.)

Committing pushes your work to GitHub and lets you take advantage of version management. Get into the habit of making your commits at natural break points - when you complete a main section, after adding links and support files, after making edits, when you pack it in for the day, etc. Here's how to do that: 

1. Open GitHub Desktop.

2. Choose your project.

3. Once you've made a few commits, you'll see: 

   * which files have changed
   * which text has been added
   * which text has been deleted 

   4) In the bottom left corner, you'll see a summary section. Type a short title and description here to let everyone know what you've updated.

   5) Hit **Commit to master**.

   6) You're done! Your file will now have its title and description attached, and you'll be able to see it on github.com...after you do one last thing. 



   ### Push your changes to GitHub

   Right now, your file is saved to your computer and you've made a commit, but that won't help you if:

   * You want your editor, boss or other team member to take a look at your stuff, but dread the exchange of 40 billion emails as everyone suggests changes

   * You leave your computer sitting on a bus when you get off at your stop 
   * Your hard drive suddenly goes kaput, your document was on your computer and you haven't backed up to the cloud or to an external hard drive 



   To prevent hours of work being tossed away in a catastrophe, you'll want to push your changes to github.com. Here's how to do that:



   1. Open GitHub Desktop. 
   2. Click **Push Origin**. 
   3. That's it! All your changes have been pushed to GitHub - the most reliable, secure backup you'll probably ever have.



   You'll be able to see a history of your commits by clicking Code, then History at the top right corner of your GitHub document.





   ### Another cool thing about GitHub

   Content creation is a messy, non-linear process; I might have an idea that's somewhat related to the content I'm currently writing, but maybe it would be better as its own blog post, video script outline, podcast synopsis, tweet, or whatever.

   Instead of leaving those words to languish in a notes app or a half-written email you never send to your partners, you could push your document to GitHub, then delete the section, make a commit and push again, so: 

   a) you can see your idea without having to find and open another document

   b) others can review your words and offer their thoughts 

   c) you can recover deleted files (If you've ever feverishly pounded out an idea on your keyboard, sworn you've saved it in one of your umpteen "trusted" places only to never find it again, and cursed the writing gods forever after, this is huge for you.)










Steps
 Use a collaborative writing project as an example - get blocked on this - message Janis on slack. want live on site as quickly as possible. ask Janis for example usage of git 

1. Create a repository 
2. Create a branch
3. Commit changes
4. The diff viewer
5. Collaborate (open a pull request)
6. Merge Pull Request (Review and publish phase)



### Limitations of Git and GitHub for writers and teams

---





### Wrap up

---



Do you use Git and GitHub in your content workflow? Do you love it or hate it? What was the learning process like for you, and do you have any tips, tricks, or advice you think should be included in this guide? Tell me in the comments! 



### Extra resources

------

The GitHub Guide - github.com https://guides.github.com/activities/hello-world/

