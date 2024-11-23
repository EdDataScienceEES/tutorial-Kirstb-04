<img align="left" width="150" height="100" src="https://github.com/user-attachments/assets/15e3d8bb-acb0-4014-8505-b250fbc23c71" />

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>


 # An overview of Github - Github basics, Markdown formatting & general tips

_Created by Kirsty (November 2024) - For some background on why I chose this tutorial topic see the main [README](README.md) document of this repository._

Do you want to make exciting and interactive Markdown files? Do you want to easily change folder names, and move files about in Github but don’t know how to? Well then, this is the tutorial for you! When people are first introduced to Github they can find it confusing and hard to follow (as I did initially) but through some simple hacks and codes you will soon be a Github pro! 


The overall aim of this tutorial is to give the reader a comprehensive overview of how to use Github, and to cover the main topics that people struggle with when first using Github. It acts as a part two to the [Intro to Github for version control](https://ourcodingclub.github.io/tutorials/git/) Coding Club tutorial. There you can learn a bit about what Github is, how version control works,  how to connect up your R studio with Github, and how to make your own repository in Github (go there now if you’re completely new to Github). For those who have completed that tutorial or are already familiar with Github, carry on reading! 
 



## Tutorial Aims:

1. **Github** - Section one aims to cover some of the Github basics that a lot of people struggle with
- [Recap - what is Github?](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1a-recap---what-is-github)
- Moving files about in github
- Changing Names & Deleting - Files and Folders
- [Reverting Commits](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1d-reverting-commits)
- Merge Conflicts - what do they mean?
  
2. **What is a Markdown?** - Section two will cover what a markdown document is

3. **Formatting a Markdown** - Section three will go cover useful markdown language
  
*Images and Text*

- Adding images
- Changing image size and alignment
- Text (bold, italic, headings, fonts, colours, highlighting)
- Changing text size and alignment
- Adding quotes
- Adding code & automatic copying
  
*Adding Links*

- Linking within Github
- Linking outwith Github
  
*General Formatting*

- Sectioning your Markdown
- How to add spacing into your Markdown

<p>&nbsp;</p>

4. **Bonus Section** - This section will offer general tips for the topics covered in this tutorial
- [Tips for a professional Markdown](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#4-bonus-section---tips-for-a-professional-markdown)

## 1a. Recap - what is Github?

One of the first things I struggled with when I first started using Github was not fully understanding what Github is. So to start lets answer the question **What is Github?**

To fully understand Github you first need to understand what Git is. First released in 2005, Git is one of the most popular version control tools used by developers. It is installed locally onto your personal computer and allows you to track the changes you make to files, giving you a record of what has been changed, meaning you can revert to old versions of files where necessary. It is also highly useful when collaborating with others, as it means that multiple people can make changes to the one project. 

<img align="centre" width="632" alt="image" src="https://github.com/user-attachments/assets/514e5702-fd33-414d-beae-2c358ef7d80c">


**Words you'll come across in Github:**
- <mark>Files for particular projects are saved in **repositories** </mark> (or repos as they are often referred to), which are essentially storage spaces for all of the files relating to your project. 
- <mark>Another word that you'll come across when using Github is **branches**. </mark> Your repositories contain the master branch which is the main code of the repository. From this master branch you can create other branches where you can experiment with the code without having to change the main code. If you are happy with changes you have made in your branch you can then commit them to the master branch. This means that you can safely experiment with code without interfering with the main code.

This leads us onto Github itself which essentially acts as the cloud for Git. Github is a cloud-based system that holds all of your Git repositories and is specifically designed to make managing your repositories easier. For instance Github has **pull requests**. This is when you request to merge changes from one branch to another branch, collaborators can then discuss and examine the changes before commiting the changes to another branch. There is also an **issues tab** in Github repositories where you can flag issues you are having with your collaborators and you can then discuss ways of resolving them.

<img width="641" alt="Screenshot 2024-11-22 150049" src="https://github.com/user-attachments/assets/faa81953-9701-462a-85aa-ca03bfb237d6">

A final note about Github is that its repositories are largely open to the public, making collaborating and discussing with the wider programming community easier.

 #### Essentially Git is the software and Github is the programme that hosts and manages the software. 

<mark>Still confused? Visit these websites that go into more detail:</mark>
- [Git vs Github: Key differences](https://www.simplilearn.com/tutorials/git-tutorial/git-vs-github)
- [What is Github?](https://blog.hubspot.com/website/what-is-github-used-for#what-github)
- [Collaborating made easier on Github](https://www.gitkraken.com/blog/collaborate-on-github#:~:text=Using%20Branches%20Effectively,or%20implementing%20a%20particular%20feature.)

## 1b. Moving Files About in Github

 

## 1c. Changing Names & Deleting - Files and Folders

There are a number of ways that you can change file and folder names as well as deleting them. You can makes changes in R studio (if you have connected your Github repository and your R studio), you can make changes in your Github repository directly, or you can use the Github web editor. 

Although all valid choices I will be showing you how to do this in the web editor. It's a very useful tool and it's therefore good to get to grips with it. 

## 1d. Reverting Commits

Ever mistakenly made a commit that you desperately want to take back? Don't worry we've all done it. Simply use the Github web editor to revert your commit. 

First you need to copy the id code of the commit your wanting to convert.
- Go into your commit history

<img width="676" alt="Screenshot 2024-11-22 155851" src="https://github.com/user-attachments/assets/db009ca0-02ac-44f0-9565-044385bcb833">

<p>&nbsp;</p>

- Then copy the id code

<img width="930" alt="Screenshot 2024-11-22 155511" src="https://github.com/user-attachments/assets/31ce3b36-5905-4f11-bc9b-098bbef000fc">

<p>&nbsp;</p>

You then need to open the Github **web page editor**. To do this go to your repository home page and press the full stop/period key (**.**)
- You should get a page that looks something like this

<img width="955" alt="Screenshot 2024-11-22 160336" src="https://github.com/user-attachments/assets/1de26c52-b74a-40c9-82f4-e22e7cd0b989">

<p>&nbsp;</p>

- You then need to select **Continue working in Github Codespaces** so that you can work in an environment where you can run code. Once you've done this you should be taken to a sepearate page called **Codespace**. Here is where you revert your commit.
- At the bottom of the **Codespace** page you will have a terminal where you can type in code. After the dollar sign (**$**) type **git revert**, then paste your commit id, and press enter.

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

<img width="227" alt="Screenshot 2024-11-22 161942" src="https://github.com/user-attachments/assets/13e57c9b-6ad9-4653-91b6-3f7735061cb6">

<p>&nbsp;</p>
Once back to your repository check that your revert was successful. You should have a new commit that looks like this.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/27d900f3-1aff-4141-98bb-8eadad9da3f0">

<p>&nbsp;</p>

You have to be very cafeful when reverting commits as you need to make sure that people haven't already pulled the commit your trying to revert, especially if you are reverting a commit you made to the master branch, as this can cause major issues. But as long as you're sensible with it and let collaborators know all should be fine!


## 1e. Merge Conflicts - what do they mean?

## 2. What is a Markdown?

A Markdown is a document which uses the Markdown markup coding language (confusing names I know!) 
[R Markdown](https://ourcodingclub.github.io/tutorials/rmarkdown/)


## 3a. Images and Text

Adding images, changing image size and alignment

```diff
<img align="left" width="150" height="100" src="https://github.com/user-attachments/assets/15e3d8bb-acb0-4014-8505-b250fbc23c71" />
```


Text (bold, italic, headings, fonts, colours, highlighting)

- **ctrl** + **b** to automatically get the code for bold text

```diff
**Your bold text here**
```

- **ctrl** + **i** to automatically get the code for italic text

```diff
_Your italic text here_
```

Changing text size and alignment

Adding quotes

To add a quote simply put a **>** before your quote

```diff
> Your quote here
```

This becomes;

> Your quote here

Inserting code & automatic copying

To add code you simply add backticks (**`**) around the code

```diff
`Your code here`
```

This becomes;

`Your code here`


To add automatic copying around text, as I have been using throughout this tutorial simply use the below code;

```diff

```diff
The text you want copied here
```
```

```


## 3b. Adding Links

## 3c. General Formatting

```diff
<details>
<summary> Your section title </summary>

Your section contents

</details>
```

You may have noticed that no matter how many times you hit 'Enter' in your Markdown code as soon as you click 'Preview' 

## 4. Bonus Section - tips for a professional Markdown

The style and layout of your Markdown will vary depending on your specific project, but in this section I will go over some general tips that are good to keep in mind!

When trying to make a document look good it can be easy to under or over do-it. Plain black and white text is proffessional right? Adding lots of colours and pictures will make it more interesing! No and no. It's tricky but you need to find a balance. A plain document can be boring and tedious to read, whilst a document that uses an array of colours and pictures without adding to the readers understanding can be overwhelming and unproffessional. 

For example look at these three Markdown examples on creating a BBC news story:
1. [Too simple](Example_markdowns/BBC_too_simple.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/bcf290ce-08bc-49c3-b9bd-5e06e628146d">


The paragraphs of text in this example makes it seem more like an essay than a Markdown document, and it therefore doesn't engage or entice the viewer to read on. 
  
2. [Too messy](Example_markdowns/BBC_overwhelming.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/0480b644-01a8-4529-a29a-b276b4a0aa85">



On the other hand this example looks more like a school project than a proffessional document to be taken seriously. It has no set formatting e.g. different picture sizes and alignments, a range of text colours, and overuse of underlining and making words bold, and so it looks messy and unproffessional. 

3. [Just right](Example_markdowns/BBC_good.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/0c0a8227-6f44-4276-9cf9-6a18830551d9">




This is a good mix of the two above examples. It has a set format throughout, and only uses images and colours where necessary. It engages the viewer but also provides only the necessary information, resulting in a concise and professional Markdown document.
