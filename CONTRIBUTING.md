# Contributing Guildelines for the DEBSOC Page 

* * *

There are many  sectors in which you can contribute to this project :
* Authoring a post (preferably the Blog should be in **Debate Context**)
* Reporting an issue and giving suggestions.
* Localizing it or contributing to the code.

---

## Points to remember:
### 1. Local Setup:
    
   For setting up locally Fork the repositry and clone it using the commands given below in the terminal.
    
 ```sh
    # create a local clone of the repository
    git clone https://github.com/YOUR-USERNAME/github.com/MvitDebsoc/DebsocBlog
    # switch to the created directory
    cd DebsocBlog
    # start local server
    bundle exec jekyll serve
 ```
  This will start the Jekyll Server at :
   
   If the server does not start, you might not have the necessary dependencies installed. Refer the next section.

### 2. Dependencies Required: 

   This website is built with **Jekyll**, which is a website generator it is designed for building static blogs.
   
   Please follow the steps below to setup the dependencies:</br>
    1. Install Jekyll locally via command line.</br>
    2. Clone a starting point to local machine, build the website and serve it locally.
    
   For above stated steps and more you need to get familiar with GIT and GITHUB to know more about it and installation refer : [GIT/GITHUB](https://blog.glugmvit.com/gitpart2/)
   
   To know about how to contribute to open source and setting up refer: [CONTRIBUTE](https://blog.glugmvit.com/contributing-to-glugblog/)
  * * *
  
 ## Adding Post :
  There are two ways you can add posts:
   * Using _Github Editor_
   * Using _Local Editor_
   
   The Second way is more preferable more begineers as there are less chances of making mistakes and all the changes one can check on Local server.
   1. **Using _Github Editor_**
       * You can easily write your blog by adding the contents uder the _posts category.Make sure you write the content in the markdown format and save the file in filename.md
       form. '.md' refers to Markdown one can easily learn [Markdown](https://www.markdowntutorial.com/), it helps the author to write thhe content with ease and make the blog look decent. 
       * Change the file in name to today's date and the title of the post. Jekyll needs the file to be named year-month-day-title.md format. Update the title at the top of the Markdown file.
   2. **Using _Local Editor_**
       * You can use any editor of your choice but the most common editor used is [VScode Editor](https://code.visualstudio.com/download).Then add yout post under the _post category and name the file in year-month-day-title.md format.
       * Commit your post's markdown fike and push to your GITHUB repository. The steps to commit and pushing the file is included in above shared links.
       
      **Adding Author Details:**
       - You can add the your details while adding your post. 
       - Go to _config.yml file and make changes as stated there and save the file.
   * * *
   ## Hosting on GitHub and Pull Request 
   You can use the following commands to push your changes.
      
 ```sh
       
       # Check the staus of files changed 
       git status
       # Adding the files to Commit
       git add <file name>
       # Commiting the chnages 
       git commit -m "message"
       # Pushing the changes to your github repo
       git push
       
```
    
  After the changes being pushed go to your Github Repository and make a Pull request.The maintainer will go through your changes and suggest if any more changes nededs to be done and merge your changes. 
  
  This how you can easily write a blog and contribute to Our Debsoc Website.
  
  Thank you!
   
 
    
