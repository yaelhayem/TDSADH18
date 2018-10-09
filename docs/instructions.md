**For the Markdown/HTML Practicum, the class will use GitHub to collaborate in creating a web site composed primarily of transcribed historical archives.**

Practicum Outcomes:

1. Students will create an HTML page, a CSS document, and Markdown documents.

2. Specific techniques to apply:

   For example, if the document being transcribed is a newspaper article, the idea is to get as close to the original as possible by using headline text/font, indenting of paragraphs, lists with numbers, including photos, etc. 
   Footnotes may be required, as will other formatting options.

3. What item type(s) are acceptable/required?

   Newspaper articles?  Descriptions of physical items?  Letters/correspondence?  usw...

Reference
---

[GitHub Flavored Markdown (GFM)](https://github.github.com/gfm/)

[HTML Tutorial](https://www.w3schools.com/html/html_intro.asp)

[CSS discussion (scroll down to External CSS)](https://www.w3schools.com/html/html_css.asp)


   ---
   
Practicum Preparation Steps
---

1. Create an account on [GitHub.com](https://github.com/)

   Use your school username and email address.
   
2. Find the **TDSADH18 repository** owned by sgolanka [or use this direct link](https://github.com/sgolanka/TDSADH18)

   A [repository](https://help.github.com/articles/github-glossary/#repository) is a collection of files and folders saved on GitHub. It contains all of the resources used in a project.
   
3. **Fork** the repository by clicking the Fork icon in the upper right, and then click on your account name in the resulting pop-up window.

   To [fork](https://help.github.com/articles/github-glossary/#fork) a repository is to make a copy of it in you own account. The copy "remembers" where it came from, so you can merge your fork back to the original repository. This is one of the fundamental ways GitHub can be used for collaboration (it also keeps track of each change).
   
4. To see the repository on-line, you will need to go to the **Settings** tab, then scroll down.  In the **Github Pages** section, you need to choose a **source**.  Choose **Master Branch**.  Now you can return to this section, and you will see a live link to your web site.

   **Note:** to see new pages you have added (including your Markdown document), you will need to add a link.  You will eventually add a link to your own HTML page, and that page will be linked--by the teachers--to the master HTML page.  To see your Markdown online before you add a link, you can open the site, delete whatever comes after **TDSADH18/**, and replace it with: **../docs/name_of_your_document**.
   
You now have a repository that you can edit!
---

We'll be transcribing documents using [Markdown](https://help.github.com/articles/github-glossary/#markdown), as well as creating a web page using [HTML](https://en.wikipedia.org/wiki/HTML) and [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets).

   ---

Practicum Requirements and Techniques
---

**Creating a document using Markdown (you must transcribe 1 newpaper article):**

1. Navigate to the docs folder (in your repository, click on docs).

2. Create a new file in this folder (click **Create New**); give it a name describing your transcription, and add **.md** at the of the file name. This indicates that the file will be created using Markdown.

3. Edit the document.  Each time you make a set of edits, you will [commit](https://help.github.com/articles/github-glossary/#commit) the changes by entering a note about what you did (added link, fixed spelling error, etc.) and clicking **Commit** at the bottom of the page. Use the [GitHub Flavored Markdown](https://github.github.com/gfm/) reference for help.

   You can use this document as a guide for using Markdown--this is of course, a Markdown document. These lines are indented; using 3 blank spaces at the begining of the first line will cause the indent.  
   
   For "regular" text, there is nothing to do, but type.  Surround text that you want **bold** with two asterisks.
   
   Make a line into a "headline" by putting 3 dashes under it (don't indent the dashes)--the "Practicum Requirements and Techniques" line above is an example of this.
   
   Draw a horizontal line by using 3 dashes--but this time, indent the 3 dashes with 3 spaces AND make sure there is a blank line a above the three dashes.
   
   Make a numbered list by using a number--and leaving a blank line after each numbered item.
   
   Your repository has a "theme" selected, which affects the way your Markdown document appears.  You can experiment with different themes by going to the settings tab in your repository--scroll down until you see the theme section.
   
4. When you are satisfied that you have finished your edits, create a [Pull Request](https://help.github.com/articles/github-glossary/#pull-request).  this will notify the owner of the original repository that you are ready for your changes and additions to be merged into the master project.  Click **Pull Request** at the top of your repository, then **New Pull Request** then **Create Pull Request**.

**Creating a new [HTML](https://help.github.com/articles/github-glossary/#markdown) Page**

1. Navigate to the **HTML** folder in your repository, and click on it to enter the folder.

2. Create a new file in this folder (click Create New); give it a name (your username is fine), and add **.html** at the end of the file name. This indicates the file will be created using HTML.

3. You also need ot add a **css** file.  CSS stands for [Cascading Style Sheets](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) and it is how you can set the look of your HTML page. CSS can be used to set the font (or fonts)--type and size--used in your HTML page, to set the background color, to determine how headlines look, to make links look a certain way--virtually everything on your web page.
   Navigate to the **css** folder, click on it, create a new file, and add **.css** at the end of the file to indicate this file is a Cascading Style Sheet.

4. Use the index.html page as a guide for your html page.  Note that HTML uses "tags" that are enclosed in brackets like this: < >. Tags typically come in pairs--an **open** tag and a **close** tag.  For instance, if I wanted to make bold words in HTML, I would type \<b>bolded words\</b>, and it would appear as: **bolded words**.
   
   Note how you "connect" your css file to your html file (using \<link ref = "/css/yourcssfile.css" rel="stylesheet" type="text/css"\>).

5. Your HTML page must include links to your markdown files. (Again, use the index.html file for reference--it links to this file).

6. When you are satisfied with your changes, make a Pull Request to have your pages merged into the master project.



