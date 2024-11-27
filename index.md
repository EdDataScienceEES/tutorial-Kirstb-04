<img align="left" width="150" height="100" src="https://github.com/user-attachments/assets/15e3d8bb-acb0-4014-8505-b250fbc23c71" />

<img align="left" width = "100" src="https://github.com/user-attachments/assets/20eb3c53-d63a-4dd8-8e51-1b1bce654f1d" />


<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

 # An overview of GitHub - GitHub basics, Markdown formatting & general tips

_Created by Kirsty (November 2024) - For some background on why I chose this tutorial topic see the main [README](README.md) document of this repository._

<mark>For this tutorial in website form see [this link](https://eddatascienceees.github.io/tutorial-Kirstb-04/).</mark>

Do you want to make exciting and interactive Markdown files? Do you want to easily change folder names, and move files about in GitHub but don’t know how to? Well then, this is the tutorial for you! When people are first introduced to GitHub they can find it confusing and hard to follow (as I did initially) but through some simple hacks and codes you will soon be a GitHub pro! 


The overall aim of this tutorial is to give the reader a comprehensive overview of how to use GitHub, and to cover the main topics that people struggle with when first using GitHub. It acts as a part two to the [Intro to GitHub for version control](https://ourcodingclub.github.io/tutorials/git/) Coding Club tutorial. There you can learn a bit about what GitHub is, how version control works,  how to connect up your R studio with GitHub, and how to make your own repository in GitHub (go there now if you’re completely new to GitHub). For those who have completed that tutorial or are already familiar with GitHub, carry on reading! 


## Tutorial Aims & Steps:

1. **GitHub** - Section one aims to cover some of the GitHub basics that a lot of people struggle with
- [Recap - What is GitHub?](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1a-recap---what-is-github)
- [Folders & Files](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1b-folders--files---creating-them-moving-them-changing-their-names-and-deleting-them) - [Creating them](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#creating-folders--files), [moving them](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#moving-folders--files), [changing their names and deleting them](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#renaming-and-deleting-folders-and-files)
- [Reverting Commits](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1c-reverting-commits)
- [Merge Conflicts:](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1e-merge-conflicts-what-they-mean--how-to-resolve-them) What they mean & how to resolve them
  
2. [**What is a Markdown?**](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#2-what-is-a-markdown) - Section two aims to cover what a Markdown document is

3. [**Formatting a Markdown**](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#3-formatting-a-markdown)- Section three aims to cover some useful markup language
  
*Images*

- [Adding images, changing size & alignment](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#3a-images)

*Text*
- [Headings](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#headings), [bold](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#bold-text), [italic](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#italic-text), [highlighting](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#highlighted-text), [colours](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#coloured-text)
- [Changing text alignment](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#changing-text-alignment)
- [Adding quotes](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#adding-quotes)
- [Adding code & automatic copying](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#adding-code--automatic-copying)
- [Creating Tables](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#creating-tables)
  
*Adding Links*

- [Linking within GitHub](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#linking-within-github)
- [Linking outwith GitHub](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#linking-outwith-github)
  
*General Formatting*

- [Adding collapsable sections to your Markdown](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#adding-sections-to-your-markdown)
- [Adding spacing to your Markdown](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#adding-spacing-to-your-markdown)

<p>&nbsp;</p>

4. **Bonus Section** - This section will offer some general tips for the topics covered in this tutorial
- [Tips for a professional Markdown](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#tips-for-a-professional-markdown)
- [Tips for getting help with GitHub](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#tips-for-getting-help-with-github)

5. [**Useful Links**](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#useful-links)

6. [**Contact Details**](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#contact-details)

<p>&nbsp;</p>

## 1a. Recap - what is GitHub?

One of the things I struggled with when I first started using GitHub was not fully understanding what GitHub is. So to start lets answer the question **What is GitHub?**

To fully understand GitHub you first need to understand what Git is. First released in 2005, Git is one of the most popular version control tools used by developers. It is installed locally onto your personal computer and allows you to track the changes you make to files, giving you a record of what has been changed, meaning you can revert to old versions of files where necessary. It is also highly useful when collaborating with others, as it means that multiple people can make changes to the one project. 

<img align="centre" width="632" alt="image" src="https://github.com/user-attachments/assets/514e5702-fd33-414d-beae-2c358ef7d80c">


**Words you'll come across in GitHub:**
- <mark>Files for particular projects are saved in **repositories** </mark> (or repos as they are often referred to), which are essentially storage spaces for all of the files relating to your project. 
- <mark>Another word that you'll come across when using GitHub is **branches**. </mark> Your repositories contain the master branch which is the main code of the repository. From this master branch you can create other branches where you can experiment with the code without having to change the main code. If you are happy with changes you have made in your branch you can then commit them to the master branch. This means that you can safely experiment with code without interfering with the main code.

This leads us onto GitHub itself which essentially acts as the cloud for Git. It is a cloud-based system that holds all of your Git repositories and is specifically designed to make managing your repositories easier. For instance, GitHub has **Pull requests**. This is when you request to merge changes from one branch to another branch, collaborators can then discuss and examine the changes before committing the changes to another branch. There is also an **Issues tab** in GitHub repositories where you can flag issues you are having with your collaborators and you can then discuss ways of resolving them.

<img width="641" alt="Screenshot 2024-11-22 150049" src="https://github.com/user-attachments/assets/faa81953-9701-462a-85aa-ca03bfb237d6">

A final note about GitHub is that its repositories are largely open to the public, making collaborating and discussing with the wider programming community easier.

 #### Essentially Git is the software, and GitHub is the programme that hosts and manages the software. 

<mark>Still confused? Visit these websites that go into more detail:</mark>
- [Git vs GitHub: Key differences](https://www.simplilearn.com/tutorials/git-tutorial/git-vs-github)
- [What is GitHub?](https://blog.hubspot.com/website/what-is-github-used-for#what-github)
- [Collaborating made easier on GitHub](https://www.gitkraken.com/blog/collaborate-on-github#:~:text=Using%20Branches%20Effectively,or%20implementing%20a%20particular%20feature.)

<p>&nbsp;</p>

## 1b. Folders & Files - Creating them, moving them, changing their names, and deleting them

As a very organised person I like to have folders within folders, and I am constantly deleting and moving files about in my repositories. However, when I first started using GitHub I could not get my head around how to do this. So, for the hyper organised like me, follow these simple steps to get a beautifully organised repo!

<p>&nbsp;</p>

### Creating Folders & Files
To create a file in GitHub simply go to the homepage of your repository, click **Add file**, and then **Create new file**.

<img width="691" alt="Screenshot 2024-11-23 152318" src="https://github.com/user-attachments/assets/ddac8102-b3f0-4395-8e37-4997ba0b3986">

<p>&nbsp;</p>

If you want to put your file in a folder, in the **Name your file...** box just type the name of the folder you want (this can be a pre-existing folder or you can create a new one) then type a forward slash (**/**). You will then get another **Name your file...** box where you can type in the name of your new file. Finally, commit your changes. 

<img width="938" alt="Screenshot 2024-11-23 152842" src="https://github.com/user-attachments/assets/84c3948b-473a-4056-8c74-563cfbc85066">

<p>&nbsp;</p>

To have a folder within a folder simply type a forward slash (**/**) after your previous folder name in the **Name your file...** box, then type another forward slash (**/**) and type in your new file name. 

<img width="937" alt="Screenshot 2024-11-23 153739" src="https://github.com/user-attachments/assets/e8e790cf-a336-4a5a-b9d3-283db643cbf3">

<p>&nbsp;</p>

### Moving Folders & Files

The easiest way to move folders and files in GitHub is to use the GitHub **web editor**. To access this go to the homepage of your repository and press the full stop/period key (**.**). This should open a page that looks something like this:

<img width="958" alt="image" src="https://github.com/user-attachments/assets/d1b72e49-c16b-4299-bc73-158b2dd96729">

<p>&nbsp;</p>

Whether you want to move a single file or a whole folder the process is the same. Simply **left click** on the folder or file you want to move and **drag** it to whatever folder you want to add it to. You will then get a message pop up asking if you are sure, click **Move**.

<img width="650" alt="image" src="https://github.com/user-attachments/assets/6b80685f-d198-4ab2-9b9e-47b9c24ca68e">

<p>&nbsp;</p>

Once you have done this you will need to commit your changes. Go to the **Source Control** tab on the left-hand side of the web editor, add a meaningful  commit message and then click **Commit & Push**.

<img width="400" alt="Screenshot 2024-11-23 155905" src="https://github.com/user-attachments/assets/dfb5acd2-00e1-4165-9b81-12261dddb18e">

<p>&nbsp;</p>

To return to your repository click the three horizontal lines in the top left of the screen and select **Go to Repository**.

<img width = "400" alt="Screenshot 2024-11-23 160154" src="https://github.com/user-attachments/assets/0a8f74a9-6ea1-4d68-99cc-442cf6fda83e">

<p>&nbsp;</p>

### Renaming and Deleting Folders and Files

There are a number of ways that you can change folder and file names as well as deleting them. You can make changes in R studio (if you have connected your GitHub repository and your R studio), you can make changes in your GitHub repository directly, or you can use the GitHub web editor. Although all valid choices I will again be showing you how to do this in the web editor. It's a very useful tool and it's therefore good to get to grips with it. 

Open the GitHub web editor (on the homepage of your repository press the full stop/period key (**.**). Once on the web editor simply right click on whatever folder or file you want to rename or delete and select whichever option is appropriate.

<img width = "400" alt="Screenshot 2024-11-23 160820" src="https://github.com/user-attachments/assets/ab92481a-3d13-422a-8ea4-f946a4193a7c">

<p>&nbsp;</p>

Then simply follow the on-screen instructions. Before returning to your repository remember to **Commit & Push** on the **Source Control** tab and write a meaningful commit message. **Forgotten how to do these steps?** <mark>See the [Moving Folders & Files](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#moving-folders--files) section above </mark>.

<p>&nbsp;</p>

## 1c. Reverting Commits

Ever mistakenly made a commit that you desperately want to take back? Don't worry we've all done it. Simply use the GitHub web editor to revert your commit. 

First you need to copy the id code of the commit that you're wanting to convert. Go into your commit history:

<img width="676" alt="Screenshot 2024-11-22 155851" src="https://github.com/user-attachments/assets/db009ca0-02ac-44f0-9565-044385bcb833">

<p>&nbsp;</p>

Then copy the id code:

<img width="930" alt="Screenshot 2024-11-22 155511" src="https://github.com/user-attachments/assets/31ce3b36-5905-4f11-bc9b-098bbef000fc">

<p>&nbsp;</p>

You then need to open the GitHub **web editor**. To do this go to your repository home page and press the full stop/period key (**.**), you should get a page that looks something like this: (Make sure to click on the second toggle in the top right corner of the page, to get this page set-up!)

<img width="677" alt="image" src="https://github.com/user-attachments/assets/62bd3597-930b-4069-a9b9-2898de6d807e">


<p>&nbsp;</p>

You then need to select **Continue working in GitHub Codespaces** so that you can work in an environment where you can run code. Once you've done this you should be taken to a separate page called **Codespace**. Here is where you revert your commit.

<p>&nbsp;</p>

At the bottom of the **Codespace** page you will have a terminal where you can type in code. After the dollar sign (**$**) type **git revert**, then paste your commit id, and press enter.

<p>&nbsp;</p>
<img width="692" alt="Screenshot 2024-11-22 160919" src="https://github.com/user-attachments/assets/73ecf72c-0047-43f1-b41b-a7e0084f95d8">

<p>&nbsp;</p>

**Important Note!** <mark> If it was a merge commit, like the below example, then you will need a slightly different code. After the dollar sign (**$**) type **git revert -m 1**, then paste your commit id, and press enter </mark>

<img width="700" alt="image" src="https://github.com/user-attachments/assets/23adc034-247d-4564-a66c-77130682c2a1">

<p>&nbsp;</p>

Once you have run the code you need to go onto the **Source Control** tab where you can commit your revert.

<img width="949" alt="Screenshot 2024-11-22 161724" src="https://github.com/user-attachments/assets/0f784f74-081e-4d3e-9016-9cc8fd5a25c6">

<p>&nbsp;</p>

Finally, sync the changes, cross the page, and return to your repository.

<img width="370" alt="Screenshot 2024-11-22 161942" src="https://github.com/user-attachments/assets/13e57c9b-6ad9-4653-91b6-3f7735061cb6">

<p>&nbsp;</p>
Once back to your repository check that your revert was successful. You should have a new commit that looks like this.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/27d900f3-1aff-4141-98bb-8eadad9da3f0">

<p>&nbsp;</p>

**You have to be very careful when reverting commits as you need to make sure that people haven't already pulled the commit you're trying to revert, especially if you are reverting a commit you made to the master branch, as this can cause major issues. But as long as you're sensible with it and let collaborators know all should be fine!**

<p>&nbsp;</p>

## 1e. Merge Conflicts: What they mean & how to resolve them?

Merge conflicts occur when you are collaborating with others on the same project and multiple people are trying to merge branches that have competing commits. Essentially you have each made different edits to the same script and GitHub doesn't understand how to combine them and so instead comes up with an error, a **merge conflict**. The merge conflict will appear when you create a pull request to merge two branches e.g. here, I am trying to merge the alpha branch with the main branch but it isn't working due to a merge conflict.

<p>&nbsp;</p>

<img width="787" alt="Screenshot 2024-11-24 131941" src="https://github.com/user-attachments/assets/1a64d344-597d-46e7-90e3-1650fee789f1">


<p>&nbsp;</p>

The easiest way to resolve merge conflicts is use the GitHub **web editor**. The below message will appear once you have submitted the pull request. 

<img width="683" alt="Screenshot 2024-11-24 131300" src="https://github.com/user-attachments/assets/022b685f-ddbc-4d05-a574-851f048b5e74">

<p>&nbsp;</p>

Click on the web editor link and there you can view the competing codes (which are helpfully highlighted), and you can manually go through it to ascertain where the problem lies and which code to keep, or how to combine them (the resolution is very dependent on the specific situation).

<p>&nbsp;</p>

![Screenshot 2024-11-24 131425](https://github.com/user-attachments/assets/454c26b8-d33c-4f6e-8140-20d32b1d354d)

<p>&nbsp;</p>

Once you have resolved the code, select **Mark as resolved** in the top right corner, then **Commit merge**. You will then be taken back to your repository where you can **Merge pull request** and **Confirm merge**.

<p>&nbsp;</p>

## 2. What is a Markdown?

A Markdown is a plain-text document that uses a markup language, as well as some HTML tags, to add formatting elements, such as headings and images. You can create a Markdown in a number of programs including R studio (for a tutorial on this see the Coding Club's tutorial [Getting Started with R Markdown](https://ourcodingclub.github.io/tutorials/rmarkdown/)). However, I will be going over how to create a Markdown in GitHub. To do this simply add a new file into your repository, name it whatever you like but remember to end your name with .md _e.g. Coding Tutorial.md_, this will create a markdown file. 

Once created you can explore your Markdown. When editing your document there are two tabs at the top, **Edit** and **Preview**. The **Edit** tab is where you write your text and markup language, and the **Preview** tab is where you can check how your code will look before you commit it. Once you have committed any changes you can then see a **Preview** of your document, the **Code** used to create it, and a **Blame** tab where you can see who made changes to the document and when. 

Although the prospect of learning another coding language may be daunting, don't worry! The markup language is actually very simple and straight forward, I'll go through some of the most common codes below.

<p>&nbsp;</p>

## 3. Formatting a Markdown

## 3a. Images

### Adding Images, Changing Size & Alignment
Adding images into your Markdown document is surprisingly easy. Simply copy your desired image and paste it in!
You can then change your image size and alignment using the below code:

```plaintext
<img align="left" width="150" src="the link for your image" />
```

To get the link for your image, paste your image into the Markdown and copy the link from the brackets e.g. 

<img width="550" src="https://github.com/user-attachments/assets/d3f3c701-7174-4e90-8f24-a7e0ff1d8c8f">

- You can change the alignment by replacing **"left"** with **"center"** or **"right"**
- You can change the overall size of the image simply by changing the width number
- You can also manually change height (add height= " " after width), however I prefer to only use width as using both can sometimes stretch or squish the dimensions of your image



<p>&nbsp;</p>

## 3b. Text 

### Headings

To add headings into your document simply add a hashtag (**#**) and a **space** before your desired heading. The more hashtags you add before your heading the smaller your heading will become; they will become like subheadings to your bigger headings.  

<p>&nbsp;</p>

### Bold Text

The code for bold text is:

```plaintext
**Your bold text here**
```

<mark>To automatically make text bold, highlight the desired text and press **ctrl** + **b** together.</mark>

<p>&nbsp;</p>

### Italic Text 

The code for italic text is:
```plaintext
_Your italic text here_
```

<mark>To automatically make text italic, highlight the desired text and press **ctrl** + **i** together.</mark>

<p>&nbsp;</p>

### Highlighted Text

To highlight text simply use the below code:

```plaintext
<mark> Your highlighted text </mark>
```

<p>&nbsp;</p>

### Coloured Text 

Creating coloured text in a GitHub Markdown is not fully reliable as it uses a specific type of HTML tag that GitHub doesn't support. I would therefore recommend only using coloured text for personal as opposed to professional Markdowns as the code can be temperamental, but nevertheless it can be fun to play around with!

To generate different coloured text, use the below code:

```plaintext
$\color{blue}{\text{Your\ text\ here}}$
```

Add a backslash and a space after each word to create spaces between the words. To change the colour simply type the colour you want into the curly brackets where **blue** currently is _e.g. purple, green, yellow_.

**Important Note!** 

- **<mark>By changing the colour of the text the font of the text also changes.</mark>** There isn't a way around this and so bear this in mind before changing the colour of your text.
  
<p>&nbsp;</p>

### Changing Text Alignment

If you want to change your text alignment, simply use the below code:

```plaintext
<p align="center">
Your content
</p>
```

This becomes;

<p align="center">
Your content
</p>

If you want your text aligned to the right, then simply remove **"center"** from the above code and replace it with **"right"**.

<p>&nbsp;</p>

### Adding quotes

To add a quote into your Markdown simply put a **>** before your quote:

```plaintext

> Your quote here

```

This becomes;

> Your quote here

<p>&nbsp;</p>

### Adding Code & Automatic Copying

To **add code** you simply add backticks (**`**) around the code:

```plaintext
`Your code here, e.g. library(dplyr)`
```

This becomes;

`Your code here, e.g. library(dplyr)`

<p>&nbsp;</p>

To **add automatic copying** around text, as I have been using throughout this tutorial, simply use the below code:

```plaintext

```plaintext
The text you want copied here
```


**Important Note!** <mark>You need to add another three backticks below the text you want copied for the code to work.</mark> Due to a formatting glitch I couldn't add this into the above code! e.g. 

<img width="290" alt="image" src="https://github.com/user-attachments/assets/38576cd1-56f0-41de-8ad0-c8c01bbd5c9c">


This allows others to quickly and easily copy whatever is in the box. It's a very useful code, especially if you are making a coding tutorial!

<p>&nbsp;</p>

### Creating Tables
Want to add a table into your markdown? No bother, just follow the below steps!

To create tables, you'll need to use pipes `|` (used to create columns), and hyphens `-` (used to create headers). To start, create a blank line above where your table will be, this ensures that the markdown understands that you're making a table.

Use the below code as the structure for making tables, make sure to have at least three hyphens below your headers, and don't worry about your columns lining up perfectly in the code, they will once you commit your changes!
```plaintext
|Header 1|Header 2|
| ----   | ----   |
| Cell content| Cell content |
```

This becomes;

|Header 1|Header 2|
| ----   | ----   |
| Cell content| Cell content |

<p>&nbsp;</p>

## 3c. Adding Links

### Linking Within GitHub
To link within GitHub, you can either **link to something in your Markdown document** or you can **link to another folder/file in your general repository**. To link to something that's in your Markdown document you simply use the following code:

```plaintext
[the title of your link](the link address)
```

To get the link address hover over the link symbol next to the heading, right click and select **Copy Link Address**, then copy this into the above code.

<img height= "400" alt="Screenshot 2024-11-23 174945" src="https://github.com/user-attachments/assets/5d4a8000-749e-423d-b7a7-300000845088">


**Important Notes!** 
- **<mark>You can only create a link to a heading**, so much sure to add a hashtag (**#**) before the place you want to link to </mark>
- **<mark>If you are previewing your Markdown and copy the link address from the preview, then the link will take you to the preview**. To change this so that you are taken to the final Markdown document either commit your changes and copy the link address from the fully updated Markdown or change the **/edit/** section of your link address to **/blob/**, e.g.</mark>

<img width="600" alt="Screenshot 2024-11-23 175601" src="https://github.com/user-attachments/assets/539cadab-f60d-4b06-b132-be7f84b95cd0">

<p>&nbsp;</p>

To link to elsewhere in your repository, it will be a similar code:

```plaintext
[the title of your link](the file path)
```

If you want to link to a file that is in the same place as your Markdown, then the file path is simply the name of the file _e.g. README.md_ for example. However if the file or folder is not in the same place as your Markdown then you need to type **../** before you type the file path. This command essentially says take me to the main directory and then find the file from there. So let's say you wanted to link to a file called **Outputs** that was in **Folder1**, then your file path would be **<mark>(../Folder1/Outputs)</mark>**.

<p>&nbsp;</p>

### Linking Outwith GitHub

Thankfully linking outwith GitHub is a lot simpler! Just copy and paste the link for the website into the following code and that's it:

```plaintext
[the title of your link](link address)
```

<p>&nbsp;</p>

## 3d. General Formatting

### Adding Sections to Your Markdown

To add **collapsable sections** into your Markdown simply use the below code:
```plaintext
<details>
<summary> Your section title </summary>

Your section contents

</details>
```

This will become:

<details>
<summary> Your section title </summary>

Your section contents

</details>

You can add as many collapsable sections into your Markdown as you like, it can be very useful if you have a long document!

<p>&nbsp;</p>

### Adding Spacing to Your Markdown

You may have noticed that no matter how many times you hit **Enter** in your Markdown code as soon as you click **Preview** the space you created disappeared and your blocks of text come one after the other. A useful code to sort this is:

```plaintext
<p>&nbsp;</p>
```

This creates a line of space. Simply copy and paste this as many times as you like to create more and more lines of space.

<p>&nbsp;</p>

## 4. Bonus Section 

### Tips for a professional Markdown

The style and layout of your Markdown will vary depending on your specific project, but in this section, I will go over some general tips that are good to keep in mind!

When trying to make a document look good it can be easy to under or over do-it. Plain black and white text is professional right? Adding lots of colours and pictures will make it more interesting! No and no. It's tricky but you need to find a balance. A plain document can be boring and tedious to read, whilst a document that uses an array of colours and pictures without adding to the readers understanding can be overwhelming and unprofessional. 

For example, look at these three Markdown examples on creating a BBC news story:
1. [Too simple](Example_markdowns/BBC_too_simple.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/bcf290ce-08bc-49c3-b9bd-5e06e628146d">


The paragraphs of text in this example makes it seem more like an essay than a Markdown document, and it therefore doesn't engage or entice the viewer to read on. 
  
2. [Too messy](Example_markdowns/BBC_overwhelming.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/0480b644-01a8-4529-a29a-b276b4a0aa85">



On the other hand, this example looks more like a school project than a professional document to be taken seriously. It has no set formatting e.g. different picture sizes and alignments, a range of text colours, and overuse of underlining and making words bold, and so it looks messy and unprofessional. 

3. [Just right](Example_markdowns/BBC_good.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/0c0a8227-6f44-4276-9cf9-6a18830551d9">




This is a good mix of the two above examples. It has a set format throughout, and only uses images and colours where necessary. It engages the viewer but also provides only the necessary information, resulting in a concise and professional Markdown document.

<p>&nbsp;</p>


### Tips for Getting Help with GitHub
A final tip I have for you is to use Google, I cannot emphasise this enough!! All of the things I've talked through in this tutorial I learned through websites, chat forums, and videos. I guarantee that any question you have, whether it be on markup language, on GitHub, or even on general coding someone else has had the same question! You would be surprised by how useful Google is even for the most obscure questions.

<p>&nbsp;</p>

<mark>**Anyway, that's it, you made it to the end of the tutorial!** Hopefully you understand more about GitHub and Markdowns than you did before!</mark>

<p>&nbsp;</p>

## Useful Links:
- For all of the Coding Club tutorials [click here](https://ourcodingclub.github.io/tutorials)
- For the sources of the media I used in this tutorial see the [Media Sources](Media_Sources.md) document in this repository

<p>&nbsp;</p>

## Contact Details:
- **Got questions about the contents of this tutorial?** Feel free to contact me at **S2359118@ed.ac.uk**
