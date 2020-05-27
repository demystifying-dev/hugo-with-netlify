# Using NetlifyCMS with Hugo SSG

Following [NetlifyCMS Docs](https://www.netlifycms.org/docs/hugo/)

## Creating a new site

Open a terminal and create a Hugo Site

```zsh
victorkane@Victors-MacBook-Air hugo % hugo new site hugo-with-netlify
Congratulations! Your new Hugo site is created in /Users/victorkane/Work/learn/hugo/hugo-with-netlify.

Just a few more steps and you're ready to go:

1. Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/ or
   create your own with the "hugo new theme <THEMENAME>" command.
2. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>/<FILENAME>.<FORMAT>".
3. Start the built-in live server via "hugo server".

Visit https://gohugo.io/ for quickstart guide and full documentation.
```

In another terminal we are going to start the Hugo local server and leave it running for the duration of the session

```zsh
% cd ~/Work/learn/hugo/hugo-with-netlify
% hugo server
Building sites … WARN 2020/05/27 11:06:42 found no layout file for "HTML" for kind "home": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/05/27 11:06:42 found no layout file for "HTML" for kind "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/05/27 11:06:42 found no layout file for "HTML" for kind "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.

                   | EN
-------------------+-----
  Pages            |  3
  Paginator pages  |  0
  Non-page files   |  0
  Static files     |  0
  Processed images |  0
  Aliases          |  0
  Sitemaps         |  1
  Cleaned          |  0

Built in 13 ms
Watching for changes in /Users/victorkane/Work/learn/hugo/hugo-with-netlify/{archetypes,content,data,layouts,static}
Watching for config changes in /Users/victorkane/Work/learn/hugo/hugo-with-netlify/config.toml
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

Point your browser at http://localhost:1313/. You won't see anything yet, as we have yet to add content.
