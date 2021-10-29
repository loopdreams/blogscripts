# blogscripts
Collection of personal scripts for automating blog workflow. These scripts only work with my current, personalised setup.

Scripts:

- blog_blop: By drew/uoou/friendo. The main script for compiling the website. Generates html from a markdown folder.
- blog_gemindex: By Fixato. Generates a Gemlog index page from a folder of .gmi files.
- blog_gemindexmake: just runs the above script, deletes previous index.gmi so it isn't included in the new output
- blog_gemtoot: By drew/uoou/friendo. Writes a 'toot' to a file and uploads it. 
- blog_crosspost: Takes a .gmi file as an argument and converts it to a .md file that will work with blop. (in other words, coverts the gemini files to html via blop) 
- blog_push: just rsync commands for pushing the files to server
- blog_publish: calls all the other scripts when I want to publish/push a blog.

Additional:

- blog_gemquotes: inserts random quote on gemini homepage
- gemfeed.py: script by Solderpunk to generate a gemini atom feed
