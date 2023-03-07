# "You are literally here:" Where your DH project lives, and why it matters
Mattie Burkert (she/her, they), University of Oregon, mburkert@uoregon.edu

## Outline
- "You are literally here" 
- Where your DH project lives
- Why it matters
# "You are literally here" 
In ["Academic Land Acknowledgment for Settler Scholars"](https://asecsgradcaucus.wordpress.com/2020/02/25/academic-land-acknowledgment-for-settler-scholars-a-guest-post-by-dr-eugenia-zuroski/), Eugenia Zurowski calls on settler scholars to go beyond the scripted territorial acknowledgments that often function as mere disavowals of settler guilt. Zurowski urges: 
> “You are literally here....your acknowledgment of Indigenous land names a literal, not a metaphorical, relationship. You are literally and materially beholden to this place and its communities.” 

This post was a starting point for [my graduate seminar in winter 2022](https://mattieburkert.files.wordpress.com/2022/07/eng645_burkert_22496_syl.docx), as I and my students worked together to write the acknowledgments for [our digital edition of eighteenth-century novel *The Female American*](https://anthologydev.lib.virginia.edu/work/Winkfield/winkfield-female-american). We recognized that we were situated on Kalapuya Ilihi, the lands of the Kalapuya people. But where was our webpage, literally? 


## Where your DH project lives
If I say "server," you might think of something like this: 
![a long row of server stacks recedes into the distance](https://live.staticflickr.com/3519/3462607995_150a6b2624_b.jpg)
["Server room"](https://www.canva.com/link?target=https%3A%2F%2Fopenverse.org%2Fimage%2F70aeec43-476c-4a72-ad86-0b35aa6f39be%3Fq%3Dserver&design=DAFcSv4hDQs&accessRole=owner&linkSource=document) by torkildr is licensed under [CC BY-SA 2.0](https://www.canva.com/link?target=https%3A%2F%2Fcreativecommons.org%2Flicenses%2Fby-sa%2F2.0%2F%3Fref%3Dopenverse&design=DAFcSv4hDQs&accessRole=owner&linkSource=document).
---
But a server is just a physical computer that hosts the files for a website and makes them available to users over the Internet. 

![halfway open laptop with handwritten sign taped to it, reading "This is a server! (yes, really) DO NOT CLOSE LID!!"](https://pbs.twimg.com/media/Fiw1bTMagAAFQ2m?format=png&name=small) Tweeted by [nixcraft](https://twitter.com/nixcraft/status/1597710750789029888?ref_src=twsrc%5Etfw), November 29, 2022

---
Web hosting is probably the #1 obstacle to the sustainability of DH projects – in both senses of the word.[^1] Web hosting is also a major pain point for newcomers to DH, especially in the US context.

When thinking about publishing a DH project to a website, you might wonder: 
- Where should I host my website? 
- Should I use an institutional or individual solution?
- How much will it cost?
- Who will have server access?
- Who will perform maintenance and monitoring?
- What will happen if I change institutions, lose funding, retire, etc.?

## Common web hosting models and example projects
### Static content 
**Best for Files**: Institutional webspace
- You may have access to host files through an individual institutional webspace; to do so, you'll need to set up FTP using a client like FileZilla. - I use [my institutional webspace](https://pages.uoregon.edu/mburkert/) store high-resolution images of archival materials so I and my students can work with them together:

![simple file directory under the heading "Index of /~mburkert"](https://github.com/mattieburkert/asecs23/blob/main/webspace.JPG?raw=true)  


**Best for offprints and datasets**: Institutional or disciplinary repositories

- Minds@UW: https://minds.wisconsin.edu/handle/1793/71768 
- Digital Commons: https://digitalcommons.usu.edu/all_datasets/77/
- Humanities Commons: https://hcommons.org/ 
- Zenodo:  https://doi.org/10.5281/zenodo.7328444

*Tip: many (if not most) publishing contracts allow you to repository a copy of your article or chapter in order to un-paywall it.*

## Digital Exhibits and Collections

### Omeka 
- Omeka.org is an open-source web publishing platform designed for digital collections and exhibits
- Your institution may have a locally managed instance where you can host your site   
- If not, you can pay for the hosted option at Omeka.net
- You can also host it yourself using a service like ReclaimHosting.com; again, some colleges and universities have institutional Reclaim subscriptions for individual faculty and staff to launch sites outside of the yourcollege-dot-edu subdomain


Here's an example of an institutionally-hosted Omeka site my students created: exhibits.usu.edu/exhibits/show/hauntedbyhistory

![banner reading "Haunted by History: The Deep Eighteenth Century" surrounded by thumbnails of archival images](https://github.com/mattieburkert/asecs23/blob/main/haunted-banner.jpg?raw=true) 

### CollectionBuilder
A lightweight, sustainable, and free-to-host alternative to Omeka is [CollectionBuilder](https://collectionbuilder.github.io/), a static site generator.  

Last spring, I worked with Digital Scholarship Librarian Kate Thornhill to develop a CollectionBuilder site, [Environmental Justice Research Repository](https://learn-static.github.io/eng-470/), which houses digitized primary sources curated and catalogued by students in my digital humanities capstone course. We worked in collaboration with a local environmental nonprofit called Beyond Toxics to identify primary sources related to the history of environmental racism in the Eugene-Springfield, Oregon area, which they are now using in their campaigns. The site deploys from my free GitHub Pages account, but Beyond Toxics has also registered the domain oregonenvironmentaljustice.org to redirect there.

![full-length screenshot of the homepage of https://learn-static.github.io/eng-470/ ](https://github.com/mattieburkert/asecs23/blob/main/learn-static.github.io_eng-470_.png?raw=true)

## Blogs and Websites 
### WordPress
- WordPress is a Content Management System (akin to Drupal, another popular CMS). 
- Like Omeka, it is open source, and your institution may have a locally managed instance that allows you to leverage existing hosting resources.
- Here's a site my students developed on our institutional multi-site, drawing on materials hosted in our GitHub-hosted repository: blogs.uoregon.edu/english470s22
- Again, as with Omeka, you can create a WordPress.org site and host it through a third party (like Reclaim Hosting) or pay for hosting through the commercial site, WordPress.com. That's how I host my personal site: mattieburkert.com 

### Website Builders
Other website builders like Weebly, Wix, Squarespace, and Canva offer site building and hosting in one, with a focus on design and ease of use, but they are less flexible and more geared towards small businesses and entrepreneurs than academics. 

## Custom Applications 
A common architecture for serving an open-source website is a LAMP stack:
- Linux - operating system
- Apache[^2] - HTTP web server software 
- MySQL (or MariaDB, MongoDB, etc.) - database server software
- PHP (or Perl or Python) - scripting language

An example of a site built this way is The London Stage Database: londonstagedatabase.uoregon.edu. 

![screenshot of London Stage Database landing page, a keyword search bar superimposed on a collage of archival images](https://github.com/mattieburkert/asecs23/blob/main/londonstagedatabase.uoregon.edu_.png?raw=true)

LSDB deploys from [GitHub](https://github.com/orgs/LondonStageDB/) to a UO-owned virtual server running a LAMP stack. It had to be migrated from Utah State University to UO when I changed jobs in 2020. (Story time!)

## Why it matters
Returning to the [digital edition of The Female American](https://anthologydev.lib.virginia.edu/work/Winkfield/winkfield-female-american) ...

My students and I created the TEI-XML files for our edition and sent them to [Literature in Context](anthologydev.lib.virginia.edu), an open-access anthology project started by John O'Brien and Tonya Howe. As far as we could determine, the site was hosted on servers at the University of Virginia (assuming that it sits on a physical server stack at UVA rather than on the virtual machines that are increasingly central to university computing infrastructures, the precise geographic distribution of which is often closely guarded by vendors like Amazon and Google).

Inspired by work like “Antidote” (Marguerite Hemmings, LaJuné McMillan, Salome Asega, and Amber Starks, https://antidote.space), we wanted to draw attention to both the materiality and the disavowal of materiality surrounding digital experiences of identity and place. 

---

Here's what we ended up writing together:
> As editors, we occupy different positions with respect to the ongoing processes of colonialism and settler colonialism in which The Female American participates. Dr. Zoe Todd (Métis nation) writes that non-Indigenous folks tend to appreciate Indigenous scholarship but “balk at addressing specific Indigenous societies whose homeland they occupy.” While land acknowledgements will not rectify the historical or contemporary violence affecting Indigenous communities, this statement attempts to acknowledge some of the specific Indigenous societies and homelands with which we and this edition are entangled.
> 
> We, the editors, identify individually as both uninvited settlers on Indigenous land and as Black and Indigenous kin–that is, people related to or in relation with Indigenous communities. As Indigenous and Black kin, we acknowledge our feelings of conflict in publishing a text that reproduces harmful representations of Indigeneity, minimizes the presence of Indigenous people, and potentially furthers a reading of colonialism that undermines the violence of its reality against Black and Indigenous bodies. As settlers, we recognize that ideas of Indigeneity represented in The Female American reproduce stereotypes, inaccuracies, and literary violence. We acknowledge that the land we currently occupy is the homeland of the Kalapuya people, and that we are individually indebted to myriad other Indigenous lands and peoples. We recognize that we produced this edition using resources and knowledges available to us through our affiliation with the University of Oregon, an institution complicit in the ongoing settler-colonial project. We acknowledge our responsibility to support equity movements like Water for Warm Springs until this land is returned to its rightful inhabitants.
> 
> The Female American begins with the history of the seventeenth-century English arrival in Tsenacomoco, the homeland of the Powhatan Chiefdom. This settlement, which was called Jamestown, is today a cultural heritage site in the greater Williamsburg, Virginia area. Many Indigenous peoples hold ancestral and present-day relationships to this land, including the Cheroenhaka (Nottoway), Chickahominy, Eastern Chickahominy, Mattaponi, Monacan, Nansemond, Nottoway, Pamunkey, Patawomeck, Upper Mattaponi, and Rappahannock. Indeed, this edition is hosted at the University of Virginia, using servers sited on and powered by plants operated on Monacan lands. At the time of this writing, the Monacan Indian Nation is fighting to save their historical capital Rassawek from further incursion from the state of Virginia, which plans to build a water pumping station over it. Readers can learn more about the effort to Save Rassawek and to join in the effort to stop it at the Monacan Nation website.
> 
> We recognize the technological infrastructure that has allowed us to create this digital edition, including the extraction of rare earth minerals and human labor to produce electronic devices and the use of fossil fuels to power those devices. We encourage readers to account for the material conditions of their access to this edition as a site of entanglement with and indebtedness to Indigenous communities whose stewardship of the land stretches back to times immemorial and persists to this day.



[^1]: For more on DH sustainability, check out [The Socio-Technical Sustainability Roadmap](http://sustainingdh.net) & [The Endings Project](https://endings.uvic.ca). For a somewhat recent dust-up on the subject, see Johanna Drucker, [“Sustainability and Complexity"](https://doi.org/10.1093/llc/fqab025) and [Andromeda Yelton's legendary clapback](https://web.archive.org/web/20211122202905/https:/threadreaderapp.com/thread/1458445616409939971.html). For my own thoughts, see my articles in [*Digital Humanities Quarterly*](https://web.archive.org/web/20211122202905/https:/threadreaderapp.com/thread/1458445616409939971.html) and [*SECC*](https://muse.jhu.edu/article/883244) on the origins of the London Stage Database. 
[^2]: Members of the Natives in Tech group have recently called on the Apache Software Foundation to change its name: https://blog.nativesintech.org/apache-appropriation/