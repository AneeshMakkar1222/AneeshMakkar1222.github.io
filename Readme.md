# Hosting the resume in Markdown on GitHub

## *Purpose*
---
Learning the practical steps of hosting and formatting a resume using Markdown, Markdown editor, Github Pages, and Jekyll. Another purpose relate these practical steps described above to the general principles of current Technical
Writing, as explained in Andrew Etter's book Modern Technical Writing
## *Prerequisites*
---
The first requirement is the knowledge of markdown language which is needed to write a resume in markdown format. Then there is also a need for an editor which supports the markdown format. For more information on Markdown, I have attached a link to a Markdown tutorial under the **More Resources** section.

## *Instructions*
---

### 1. **Uploading Documents on Distributed Version Control System**
> The version-control system which will be used in this 
> assignment is Github. There are some reasons why 
> version controlled systems are preferred by a lot of
> people. Firstly, distributed version control systems(DVCS)
> have better performance. Secondly, DVCS can be used for
> offline work and is considered superior for concurrent 
> work on the same file. Lastly, the most prominent reason 
> for technical writers to use DVCS is that developers 
> prefer them.
> 
> #### *Instructions for uploading resume on Github*
> 1. If you do not have a GitHub account, then first sign up
> for your GitHub account. If you already have a GitHub 
> account, then you can skip to step 2.
> 2. Login into your GitHub account. To upload the resume in 
> GitHub there is a need for a repository. The following 
> steps will assist you with creating the repository:-
> >* Click on your account icon. After clicking on it a menu 
> will pop up.
> >* Click on your repository in the menu.
> >* After then click the new button. 
> >* Enter [username].github.io as the repository name 
> and click create repository button.

> 3. If you are creating your first file in the repository,
>  then there will be an upload file link in the quick setup 
> column. Click that button and then upload your resume. 
> Don't forget  to press the commit changes button.
> 4. If there already exists a file in the repository,
>  then follow the given steps:-
> >* click add file button and then a pop-up menu will 
> appear.
> >* click the upload button and choose the resume from your
>  files. After uploading the file click the commit changes 
> button.
> 
> According to Etter's perspective, it is recommended to 
> store the documentation along with the product source 
> code. Moreover, store your documentation in a file named 
> README.md at the root of the summary.  

  

### 2. **Host a Static Website**
#### *Advantages of Static Websites*
>  According to Etter, static websites are advantageous as:-
> >* They can be hosted anywhere.
> >* They have no server-side application dependencies, no 
> databases, and nothing to install, so migrating the entire 
> site is as easy.
> >* They need a few hardware resources.

#### *How to host a static Website*
> 1. Firstly, we need to install ruby for the
> purpose of  hosting the website. For installing 
> ruby follow the given procedure:-
> >* Open the link for installing ruby which is 
> mentioned in the **More Resources** section.
> >* Then click on the *RubyInstaller* link given in
> the **Ways of Installing Ruby** section.
> >* Click on the red *download* button which is at
> the top of the webpage.
> >* Download any version of rubyInstaller with the
> devkit.
> >* Open the downloaded application and choose the
> option to install all the packages of ruby 
> (Option 3).   
> 2. Secondly, we also need to install Jekyll. For 
> installing  Jekyll follow the listed steps:-
> >* Open Command prompt
> >* type `gem install bundler jekyll` 
> >* type `jekyll -v` to check whether it got installed or not.
> If it got installed then the output will show the version 
> of the Jekyll that got installed otherwise the output will
> be an error. 
> 3. After downloading Jekyll we need to clone the repository
> of the GitHub. For cloning the GitHub repository follow the 
> listed step:-
> >* Open the command prompt and type `git clone https://github.com/[username]/[username].github.io` where username 
> is the GitHub's account username and [username].github.io is the 
> name of the repository that is being cloned.
> 4. After creating the clone open the clone directory by 
> using the command `cd [username].github.io`.
> 5. Initialize the website by using the command `jekyll new 
> [website name]` and then switch to the new website 
> directory  by using the command `cd [website name]`.
> 6. Install the webrick bundle by using `bundle add webrick` command first and then using `bundle install` command.
> 7. To open the website that you just created type `bundle 
> exec jekyll serve` command. After that go to browser and 
> search `http://localhost:4000`
> 8. Lastly, push the required files using Git desktop or by 
> typing three listed commands in sequence: -
> >* `git add --all`
> >* `git commit -m "Initial commit"`
> >* `git push -u origin main`
> >* After that just open the link `https://[your-github-name].github.io` in the web browser where you will find the website.
>
> Below is an example of my static website 
> containing my resume.
> ![Resume](resumeFinal.gif)


### *More Resources*
>* Resource for Markdown tutorial: This [Markdown Tutorial](https://www.markdowntutorial.com/) link is the best to 
> learn the basic syntax of the Markdown format.
>* Resource for using jekyll to host static websites: I 
> learned how to make static host websites from this [Jekyll Tutorial](http://jekyllrb.com/) link. It is a helpful link as 
> in my perspective, it has the information on the easiest 
> way of hosting a static website.
>* Link to the book written by Etter(Modern Technical 
> Writing) : I got to know a lot about the advantages of markdown 
> format and the version control system from this [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) book.
>* Link for installing ruby: [Install Ruby](https://www.ruby-lang.org/en/downloads/)
## *Authors and Acknowledgments*
---
Aneesh Makkar

I will like to thank my team members. (Tristan Dyck, Asifur Rahman, Katrina Dotzlaw) 
## *FAQs*
---
> 1. Why is Markdown better than a word processor? 
  Ans. There is no need for the editors to worry about 
>editing. the look and feel of websites can be modified 
>without affecting the content by 
> using Markdown.
>
> 2. Why is my resume not showing up ?
>
>    Ans. After making changes to resume it takes around
> 3 - 5 minutes  to see those changes. GitHub takes a 
> little time to make those changes.
> Also make ensure that GitHub Pages site is coming 
> from the correct branch of GitHub.
> This option is available in GitHub settings.
