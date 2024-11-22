<img align="left" width="150" height="100" src="https://github.com/user-attachments/assets/15e3d8bb-acb0-4014-8505-b250fbc23c71" />

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>


 # Making the Most of GitHub - Github basics, Markdown formatting & general tips

_Created by Kirsty (November 2024) - For some background on why I chose this tutorial topic see the main [README](README.md) document of this repository._

Do you want to make exciting and interactive Markdown files? Do you want to easily change folder names, and move files about in Github but don’t know how to? Well then, this is the tutorial for you! When people are first introduced to Github they can find it confusing and hard to follow (as I did initially) but through some simple hacks and codes you will soon be a Github pro! 


This tutorial follows on from the [Intro to Github for version control](https://ourcodingclub.github.io/tutorials/git/) Coding Club tutorial where you can learn how to connect up your R studio with Github, and how version control works (go there now if you’re completely new to Github). For those who have completed that tutorial or are already familiar with Github, carry on reading! 
 

## Tutorial Aims:

1. **Github**
- Recap - what is Github?
- Moving files about in github
- Changing File and Folder Names & Deleting Them
- Reverting Commits
- Merge Conflicts - what do they mean?
  
2. **What is a Markdown?**

3. **Formatting a Markdown**
  
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

4. **Bonus Section** - General tips for a professional Markdown

## 1a. Recap - what is Github?

One of the first things I struggled with when I first started using Github was not fully understanding what Github is. So to start lets answer the question **What is Github?**

To fully understand Github you first need to understand what Git is. First released in 2005, Git is one of the most popular version control tools used by developers. It is installed locally onto your personal computer and allows you to track the changes you make to files, giving you a record of what has been changed, meaning you can revert to old versions of files where necessary. It is also highly useful when collaborating with others, as it means that multiple people can make changes which can then be merged together on the one file. 

<img align="centre" width="632" alt="image" src="https://github.com/user-attachments/assets/514e5702-fd33-414d-beae-2c358ef7d80c">

- <mark>Files for particular projects are saved in **repositories** </mark> (or repos as they are often referred to), which are essentially storage spaces for all of the files relating to your project. 
- <mark>Another word that you'll come across when using Github is **branches**. </mark> Your repositories contain the master branch which is the main code of the repository. From this master branch you can create other branches where you can experiment with the code without having to change the main code. If you are happy with changes you have made in your branch you can then commit them to the master branch. This means that you can safely experiment with code without interfering with the main code 

This leads us to Github which essentially acts as the cloud for Git. Github is a cloud-based system that holds all of your Git repositories and is specifically designed to make managing your repositories easier. For instance Github has **pull requests**. This is when you request to merge changes from one branch to another branch, collaborators can then discuss and examine the changes before commiting the changes to another branch. There is also an **issues tab** in Github repositories where you can flag issues you are having with your collaborators and you can then discuss ways of resolving them.

<img width="641" alt="Screenshot 2024-11-22 150049" src="https://github.com/user-attachments/assets/faa81953-9701-462a-85aa-ca03bfb237d6">

A final note about Github is that its repositories are largely open to the public, making collaborating and discussing with the wider programming community easier.

 #### Essentially Git is the software and Github is the programme that hosts and manages the software. 

<mark>Still confused? Visit these websites that go into more detail:</mark>
- [Git vs Github: Key differences](https://www.simplilearn.com/tutorials/git-tutorial/git-vs-github)
- [What is Github?](https://blog.hubspot.com/website/what-is-github-used-for#what-github)
- [Collaborating made easier on Github](https://www.gitkraken.com/blog/collaborate-on-github#:~:text=Using%20Branches%20Effectively,or%20implementing%20a%20particular%20feature.)

## 1b. Moving Files About in Github

 

## 1c. Changing File Names & Deleting Files

There are a number of ways that you can change file names and delete files. You can makes changes in R studio (if you have connected your Github repository and your R studio), you can make changes in your Github repository, or you can use the Github web editor. 

Changing names

- In Github
- In R
- Using the Github web editor 

Deleting files

- In R
- Using the Github web editor 

## 1d. Reverting Commits

You have to be very cafeful when reverting commits as you need to make sure that people haven't already pulled the commit your trying to revert. In the majority of cases it is best to just manually edit the file to get rid of the changes you just commited. You can do this by going onto your commits, and then you can select the commit that you made the changes on (in this example lets say you want to change 'Adding to section 1D'). 

<img width="925" alt="Screenshot 2024-11-22 152608" src="https://github.com/user-attachments/assets/e93fc2dd-660b-4148-935f-d751284d2498">

<img width="933" alt="Screenshot 2024-11-22 153013" src="https://github.com/user-attachments/assets/0829410c-8d82-417f-ae3e-95649687f466">

Once you're on the commit, the red boxes show what you deleted and the green boxes show what you added. This allows you to see what you need to change back in your document. 

<img width="793" alt="image" src="https://github.com/user-attachments/assets/48fb15ce-0564-4648-89ce-0dd68ae26c98">




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

## 4. Bonus Section - General tips for a professional Markdown

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
