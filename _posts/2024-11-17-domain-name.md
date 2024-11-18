---
layout: posts
title: So You Bought A Domain. Now What?
tag: web-development
---

*It all started with a need.* I attend weekly tech meetups and often share event details on Discord with my group. But as the list grew, keeping things organized became a challenge. I realized that others—like friends outside the group—could benefit from these lists too. That’s when I decided to build a website. The moment my ideal domain name was available, I knew it was a sign to start. This blog will document how I got from *just a domain name* to a functioning website.

## 📝 Here's What We'll Cover 

1. Buying a Domain
2. Hosting using GitHub Pages
3. Adding Your Project
4. Linking Your Domain to GitHub Pages

## 💲 Buying a Domain - Let's Get Started 

I have another domain on Squarespace and it was easy to set up, so I decided to go with them again. There are plenty of places to host your domain and content, and you don't need to use the same website for both. 

![squarespace website domain search bar](/assets/images/domain-name/domain-search.png)
*You're not limited to .com; try something new like .pizza!*

Note that the prices here are *ANNUAL* not monthly. Making a website can be affordable!

![squarespace list of your domains](/assets/images/domain-name/domain-list.png)
*Here you can see my new website that's about to be made and the one you're currently on.*

Now that you have a name, how do you get content on it?


## 👩‍💻 Hosting on GitHub Pages: Your Free Website Hosting Solution

If you’re like me and want to keep things simple and affordable, GitHub Pages is a fantastic option. It’s free and perfect for hosting a straightforward website like this one.

### ✅ Step 1: Create a New Repository on GitHub

![New repository page GitHub](/assets/images/domain-name/new-repo.png)

1. Log in to your GitHub account (or create one if you don’t have it yet).

2. Click the “+” button in the top-right corner and select “New repository.”

3. Give your repository a name—ideally, something relevant like my-awesome-site.

4. Make sure to:
    * Check “Public” so GitHub Pages can host it.
    * Check “Add a README file” to make editing easier later.

✨ *Pro tip: The repository name will be part of your GitHub Pages URL, so keep it concise!*

### ✅ Step 2: Enable GitHub Pages
![GitHub settings](/assets/images/domain-name/settings.png)

1. Navigate to your repository’s Settings tab.

2. Scroll down to the Pages section.
3. Under Source, select the branch you want to use (typically main) and click Save.

4. GitHub will generate a URL for your site (e.g., https://yourusername.github.io/repo-name/).

*Your site will be live in seconds—magic!*

### ✅ Step 3: Add Your Website Files

Now that GitHub Pages is enabled, it’s time to add some content to your website. Don’t worry—no coding experience or fancy tools are needed for this part!

1. Go to Your Repository on GitHub

    Navigate to the repository you just created.

    ![Repo add new file](/assets/images/domain-name/new-file.png)
    *Click 'Add File' near the top right*

2. Add a New File

    * Click the “Add file” button and select “Create new file.”
    * Name the file index.html (this will be your website’s homepage).

3. Write Your Website Code

    In the text editor, paste this simple starter code:

    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>Welcome to My Site</title>
    </head>
    <body>
        <h1>Hello, world!</h1>
        <p>This is the beginning of my new website!</p>
    </body>
    </html>
    ```

    ![Edit a new file screen](/assets/images/domain-name/index.png)
    *This is just to get started, we will change it soon.*

4. Commit Your Changes

    Scroll down to the bottom of the page. Under Commit new file, write a brief message like Add homepage and click the “Commit new file” button.

    ![Commit screen](/assets/images/domain-name/commit.png)
    *Add a description if you like, but it's not necessary*

### ✅ Step 4. Check Your Live Website

Wait a few seconds, then visit the URL GitHub Pages provided earlier (e.g., https://yourusername.github.io/repo-name/). You should see your new website live!

![hello world site](/assets/images/domain-name/hello-world.png)

## 🔗 Linking Your Domain to GitHub Pages

Now that your website is live on GitHub Pages, let’s connect it to your custom domain. Instead of a long GitHub URL, your visitors will type something sleek like yourcooldomain.com to see your site.

### ✅ Step 1: Log Into Your Domain Registrar’s Account

* This is the website where you purchased your domain (e.g., Squarespace, Namecheap, GoDaddy, etc.).

* Navigate to the DNS settings or Domain management section for your domain.

### ✅ Step 2: Add or Update DNS Records

* Delete any default DNS records, then add the following custom DNS settings to point to GitHub Pages.

![DNS records](/assets/images/domain-name/dns-settings.png)
*Add in these five records. These are necessary to tell your domain registrar that your website content is being hosted on GitHub.*

### ✅ Step 3: Save your changes

* Save the DNS settings. Depending on your registrar, changes may take a few minutes to 48 hours to propagate.

### ✅ Step 4: Find Your GitHub Pages Info

* Go to your GitHub repository.
* Navigate to Settings > Pages, and under the “Custom domain” section, type your domain name (e.g., yourcooldomain.com) and save it.

**You might need to wait! Don't worry if you initially get this error:**

![Improperly configured error](/assets/images/domain-name/improperly-configured.png)

**Or this error!**

![Improperly configured error](/assets/images/domain-name/improperly-configured-error.png)

Try again later today. 

![DNS successful](/assets/images/domain-name/dns-successful.png)
*I came back 6 hours later and now the DNS check was successful!*

When everything is loaded and ready, you should also check the 'Enforce HTTPS' box for extra encryption protection. After waiting 6 hours, I was still unable to check the box. I will try again tomorrow.

✨ *Pro Tip: If your domain isn’t working after 48 hours, double-check:*

* The DNS records match GitHub’s recommendations.
* You typed the custom domain correctly in GitHub Pages settings.

That's it! If everything is set up correctly, you’ll see your GitHub Pages site live under your custom domain! Now it's time to start coding and add some content. 😊