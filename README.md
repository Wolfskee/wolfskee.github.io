# How to hosting your Resume through GitHub Pages

## INTENDED AUDIENCE
This instruction will help computer science students who has no background with Markdown file, Jekyll, and GitHub to host their Resume through GitHub Pages.

## PREREQUISITES
### Getting Started
In this section, you need to prepare the items that be listed below:
1. Get yourself a Markdown editor
  * [Atom](https://atom.io)
  * [VSCode](https://code.visualstudio.com/)
2. [Create GitHub Account](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
3. [Download Ruby](https://www.ruby-lang.org/en/downloads/)
4. [Download Jekyll](https://jekyllrb.com/docs/)

## Instructions
**Step 1**: Create a Repository in GitHub.  
Once you created your GitHub Account. Login in to your GitHub Account, you will see a "**New**" button on your top Left.
 ![A GIF showing the step 1](https://github.com/Wolfskee/EricS.github.io/blob/master/pic/createRepository.gif)  
 give a name for your repository:
 ![A GIF showing the give name of repository]()


Step 2: Clone the Repository
On your local machine, clone the repository you just created using VS Code's built-in Git functionality. Open VS Code, press F1 or Ctrl+Shift+P, and type "Git: Clone." Enter the URL of your repository when prompted.

Step 3: Add Your Resume
Copy and paste your resume into a new file in the repository. Save the file with the name "index.md".

Step 4: Choose a Jekyll Theme
Choose a Jekyll theme for your resume. A good place to start is the Jekyll Themes website. Once you've found a theme you like, copy the files for that theme into your repository. Make sure to include any dependencies or assets that the theme requires.

Step 5: Customize the Theme
Customize the theme to your liking. This may involve modifying the theme's configuration file, adding custom CSS, or changing the layout of the resume.

Step 6: Preview Your Resume
To preview your resume locally, open a terminal in VS Code and run the command "bundle exec jekyll serve". This will start a local Jekyll server, which you can view in your browser at http://localhost:4000.

Step 7: Push Changes to GitHub
Once you're happy with your resume, commit your changes and push them to GitHub using VS Code's Git functionality.

Step 8: Enable GitHub Pages
In the repository settings on GitHub, enable GitHub Pages and choose the "main" branch as the source. Your resume should now be live at http://your-username.github.io.

Relating to Etter's Book
In Andrew Etter's book Modern Technical Writing, he emphasizes the importance of using plain text formats like Markdown to create documentation. By hosting your resume on GitHub Pages using Jekyll, you are using a plain text format that can be easily version-controlled and collaboratively edited. Additionally, by choosing a Jekyll theme for your resume, you are using a reusable and customizable template, which follows Etter's principles of efficiency and consistency.

Demo

More Resources
Markdown tutorial
Andrew Etter's book Modern Technical Writing
Jekyll Themes
Authors and Acknowledgments
This README was created by the OpenAI GPT-3 language model with contributions from the OpenAI team.

FAQs
Why is Markdown better than a word processor?
Markdown is better than a word
