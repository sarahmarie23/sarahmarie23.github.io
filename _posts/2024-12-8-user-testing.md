---
layout: posts
title: User Testing - My takeaway
tag: web-development
---

### Iterative testing. Getting the customer involved early and often. 
These key ideas are not only frequently mentioned but thoroughly explained in books about agile programming. In fact, the first principle of the Agile manifesto states:

**"Our highest priority is to satisfy the customer
through early and continuous delivery
of valuable software."**

After reading about these ideas, it finally clicked for me: it's not just important, but *essential* to get your customer involved from the very beginning.

## A Bit of Background

I’ve been assisting with another grad student’s project, writing the user manual for a website they’ve been building. This project aims to modernize a doctor’s website. The doctor currently has an outdated site built using WordPress to organize content. The website features resources for:

* Families of patients with various conditions,
* Community members, and
* Other clinicians.

The doctor needed a modern way to organize these resources. Some resources overlap between audiences, and many of the links were broken.

## The Website Created

The new and improved website is vibrant, with a modern layout. It organizes resources into three broad categories. Since the resources are stored in a database, they can be tagged for multiple user types. Resources can also be batch uploaded, with automatic verification that the links work. It’s a significant improvement!

## The Doctor's First Words

When we met with the doctor for the first time and revealed the website, he was very thankful for all our hard work. He seemed genuinely appreciative and honored that my classmate chose this project as their Master’s capstone project. But he did have some feedback.

While the photos on the website were high-quality and well-executed, they weren’t the style he envisioned. He also felt the fonts didn’t align with his preferences. Additionally, he had concerns about accessibility features.

The new website included a range of text size options, which was great, but we missed some simple yet essential elements, like a magnifying glass icon to indicate the search bar. Instead of an icon, the website simply displayed the word “search.”

## Takeaways

<div style="text-align: center;">
    <img src="/assets/images/icons.jpg" alt="Icons" width="400">
</div>

### 1: The less the user has to read, the better

Redundant headings and text should be eliminated. If an idea can be expressed with an icon, it should be implemented. This makes the site more intuitive and accessible to users of all languages.

<div style="text-align: center;">
    <img src="/assets/images/accessibility.jpg" alt="Accessibility" width="400">
</div>

### 2: Accessiblity is essential

The doctor recommended [Recite Me](https://reciteme.com/us/), an accessibility toolbar, as a standard for websites. He emphasized that many patients would benefit from such features, making them a crucial addition.

<div style="text-align: center;">
    <img src="/assets/images/website.jpg" alt="Website" width="400">
</div>

### 3: It's easier to change the design early on

While you shouldn’t get too caught up in colors, fonts, and pictures early in the process, design is still important. Wireframes come first, but showing key design elements like homepage photos early on can provide valuable feedback.

Since I wasn’t involved in the website’s design phase, I imagine the creators could have saved time by discussing design choices—such as the front-page images—with the doctor early. That way, he could’ve provided the images he wanted from the start. Now, someone will need to update the photos, fonts, and potentially the color scheme to ensure everything works together seamlessly.

<div style="text-align: center;">
    <img src="/assets/images/grandma.jpg" alt="Grandma" width="400">
</div>

### 4: Know your user 

I was responsible for writing the user manual. I aimed to make it simple and easy to follow, using Google Docs for its intuitive interface.

After reviewing other user manuals, I noticed they use short, direct instructions like “Click the Edit button,” with each step clearly numbered.

The doctor appreciated the many pictures and red lines I included to indicate buttons and points of interest. I even added a glossary at the end with links to definitions. Still, I missed some terms—like “front end” and “back end”—which are clear to a developer but not to a general user.

His advice? Write as if you’re writing for your grandma.

## Conclusion

This experience gave me a taste of what it’s like to work with an actual user of our software. It underscored how critical it is to understand their needs, preferences, and how they interact with the product.

It’s made me even more eager to start interviewing potential users for my app!