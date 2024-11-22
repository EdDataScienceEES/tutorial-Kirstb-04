<img align="left" width="150" height="100" src="https://github.com/user-attachments/assets/15e3d8bb-acb0-4014-8505-b250fbc23c71" />

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>


 # Making the Most of GitHub - Github hacks, markdown formatting & general tips

*Created by Kirsty (November 2024)*

For some background on why I chose this tutorial topic see the main [README.md](tutorial-Kirstb-04
/README.md) document for this repository.

Do you want to make exciting and interactive Markdown files? Do you want to easily change folder names, and move files about in Github but don’t know how to? Well then, this is the tutorial for you! When people are first introduced to Github they can find it confusing and hard to follow (as I did initially) but through some simple hacks and codes you will soon be a Github pro! 


This tutorial follows on from the [Intro to Github for version control](https://ourcodingclub.github.io/tutorials/git/) Coding Club tutorial where you can learn how to connect up your R studio with Github, and how version control works (go there now if you’re completely new to Github). For those who have completed that tutorial or are already familiar with Github, carry on reading! 
 

## Tutorial Aims:

1. **Github**
- Recap - what is Github?
- [Moving files about in github](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1a-moving-files-about-in-github)
- [Changing File Names & Deleting Files](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1b-changing-file-names-&-deleting-files)
- [Undoing Commits](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1c-undoing-commits)
- [Merge Conflicts - what do they mean? ](https://github.com/EdDataScienceEES/tutorial-Kirstb-04/blob/master/index.md#1d-merge-conflicts---what-do-they-mean)

2. **What is a Markdown?**

3. **Formatting a Markdown**
  
*Images and Text*

- Adding images
- Changing image size and alignment
- Text (bold, italic, headings, fonts, colours, highlighting)
- Changing text size and alignment
- Adding quotes
- Inserting code & automatic copying
  
*Adding Links*

- Linking within Github
- Linking outwith Github
  
*General Formatting*

- Sectioning your markdown
- How to add spacing into your markdown

<p>&nbsp;</p>

4. **Bonus Section** - General tips for a professional markdown

## 1a. Recap - what is Github?

One of the first things I struggled with when I first started using Github was not fully understanding what Github is. So to start lets answer the question **'What is Github?'**. Founded in 2008, Github is an online software development programme, used by programmers to store, track, and collaborate on software projects. 

<mark>Still confused? Visit these websites that go into more detail on what Github is and what it's used for:</mark>
- https://blog.hubspot.com/website/what-is-github-used-for#what-github

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

## 1d. Undoing Commits

## 1e. Merge Conflicts - what do they mean?

## 2. What is a Markdown?

A markdown is a document which uses the Markdown markup coding language (confusing names I know!) 
[R markdown](https://ourcodingclub.github.io/tutorials/rmarkdown/)


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
**Your italic text here**
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

To add code 


## 3b. Adding Links

## 3c. General Formatting

```diff
<details>
<summary> Your section title </summary>

Your section contents

</details>
```

You may have noticed that no matter how many times you hit 'Enter' in your markdown code as soon as you click 'Preview' 

## 4. Bonus Section - General tips for a professional markdown

The style and layout of your markdown will vary depending on your specific project, but these are some general tips that are good to keep in mind, read on to find out!

When trying to make a document look good it can be easy to under or over do-it. Plain black and white text is proffessional right? Adding lots of colours and pictures will make it more interesing! No and no. It's tricky but you need to find a balance. A plain document can be boring and tedious to read, whilst a document that uses an array of colours and pictures without adding to the readers understanding can be overwhelming and unproffessional. 

For example look at these three markdown examples on creating a BBC news story:
1. [Too simple](Example_markdowns/BBC_too_simple.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/bcf290ce-08bc-49c3-b9bd-5e06e628146d">


The paragraphs of text in this example makes it seem more like an essay than a README document, and it therefore doesn't engage or entice the viewer to read on. 
  
2. [Too messy](Example_markdowns/BBC_overwhelming.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/0480b644-01a8-4529-a29a-b276b4a0aa85">



On the other hand this example looks more like a school project than a proffessional document to be taken seriously. It has no set formatting e.g. different picture sizes and alignments, a range of text colours, and overuse of underlining and making words bold, and so it looks messy and unproffessional. 

3. [Just right](Example_markdowns/BBC_good.md)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/0c0a8227-6f44-4276-9cf9-6a18830551d9">




This is a good mix of these two. It has a set format throughout, and only uses images and colours where necessary. It engages the viewer but also provides only the necessary information, resulting in a concise and professional README document.
