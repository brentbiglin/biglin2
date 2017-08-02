+++
date = "2017-07-10T12:00:00+06:00"
title = "A Design and Content Agency Concept Site"
categories = ["Design", "Development"]
tags = ["Hugo", "HTML CSS", "Netlify", "GitHub", "Adobe Illustrator"]
+++
## Website Design

![Screenshot of design and content agency concept site](/img/qwertycat2.png "Design and Content Agency Homepage")
["QwertyCat"](https://qwertycat.io)

I created a [design and content agency concept site](https://qwertycat.io) using a static site generator based on Google's Go language, named [Hugo](https://gohugo.io/). The reason to use a static site generator is so that the content strategist can create simple Markdown files with front matter that automatically titles, dates, categorizes, and tags each individual post. Once the content files are uploaded to the appropriate folder, the site rebuilds itself with the new post included within the structure of the site.

![Screenshot of Netlify Deployment](/img/qwertycat1.png "Netlify Deployment")

The beauty of this system is that it's automatic, yet fully customizable. Even the deployment of the site is made easy; the Hugo file system is hosted as a [GitHub](https://github.com/) repository, which is then built, deployed, and hosted by [Netlify](https://www.netlify.com/). Each GitHub push triggers a new deployment of the site.
