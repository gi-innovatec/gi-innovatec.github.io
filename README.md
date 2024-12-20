# website
Use this website as a template for your academic research group
This website is powered by Jekyll and uses some Bootstrap and Bootswatch. We tried to make it simple yet adaptable, so that it is easy for you to re-use it for your purpose.

Getting started
All pages are written in markdown for easy editing, and Jekyll uses Liquid for the data-driven pages. The publicaion list, news items, and group members are stored as .yml data sheets (plain text) in the _data folder, so that one can update the website easily. The pages are in the _pages folder. Updating and maintaining is easy using Github (not worldpress-easy, but there are other advantages (see e.g. this, or this). Jekyll takes all the markdown and data files, and creates beautiful html files in the _site folder.

If you never used Jekyll, read the wikipedia article article and check out their website. Same for Github, which will host your first website draft.

Create and open a github account, go to our repository, and click ‘fork’. This is now your copy of the website, and you can change and adapt it as you want. You don’t have to link to us or mention us (but of course we appreciate it). Then change the name of the repository to “your_username” and the name of the branch to “gh-pages”. Your website is now automatically published under your_username.github.io/your_username/. Except that it probably still looks like our website.

To modify the webpage, you can either do everything on on github.com (go to a file, click “edit”, then “commit”, “push”), or install Jekyll on your computer and play with your local copy that you sync with the branch on github.com. The former is much easier in the beginning, but a bit less convenient once you start rewriting everythint. To get it to work on your computer (and to learn a bit more about Jekyll), here and here are tutorials on how to use it and how set it up locally. Also, consider using the Github desktop app, I found it helpful.

Customization
Now let’s make this your website.

First, go to the news.ylm, publist.ylm, and team.ylm files in the _data folder and insert your own data into the data fields. Watch out: Jekyll is quite strict about extra or missing spaces etc. Adhere to the format. In the beginning, test each change: commit, push, and check the published website.

For publications, you can add a “1” in the highlight field, then it will be featured prominently. You can add important news items (red, “news1”), and less important news items (blue, “news2”).

For the news items, just keep adding them. The first 10 will be displayed on the ‘home’ page.

For the team.ylm file

Next, change the content of all files in the _pages folder. To change the title in the homepage, go to homelay.html in the _layout folder.

Lastly, change the footer and perhaps header appropriately (in _include).

You might also want to change the style or theme. I imported style files (in sass) from Bootstrap/Bootwatch, you can replace them with your own (in the _sass directory). For small changes, just work on the override stuff in the main.sass file in the CSS folder. Or change some variables in the _variables.sass file, like the background color etc.

As said, Jekyll takes all the markdown and data files, and creates beautiful html files in the _site folder.In the end, either upload these files to your server, or buy yourself a domain and check the instructions on github on how to host it there.
