Learning Git/Github from Daniel Shiffman
================
an-jing
2020-12-12

## Introduction

My favourite & only version control system has been - for a long time -
[RCS](, "Revision Control System") - created, I believe, as far back as
1982. And although it is said to be relatively simple to use, for me it
was best explained - to the modest level I wanted to use it - by Carla
Schroder in her book: “Linux Cookbook”. It was fine for me as a lone
user not needing to collaborate with anyone in a way that might have led
me to CVS or Subversion, etc. Perhaps I still don’t neeed to change but
I have now come to love things like the RStudio IDE and the Atom editor
and these products encourage linking into Git/Github. I have been a
little apprehensive to make the move. But I stumbled across some Daniel
Shiffman Git/Github video tutorials for beginners. I had already been
learning Proce55ing and p5,js from him & I can say for sure this guy is
the greatest teacher of *anything* I have ever seen! So what have I got
to lose?!

## BTW How am I Writing This?

Well I may do something else later, but for quite a while now my
favourite way for writing *anything* is to use RMarkdown in the RStudio
IDE. (I can compile into HTML or PDF, I can include inline
*L**a**T**e**x*, and I can include r code ‘chunks’. But now, since this
is all about learning to use Github, I am compiling my RMarkdown (.Rmd)
file into Github Markdown instead of straight into HTML. So my YAML
header (with two alternative forms of output commented out) looks
approximately like this:

    ---
    title: "Learning Git/Github from Daniel Shiffman"
    author: "an-jing"
    date: "r Sys.Date()"
    # output: html_document
    # output: md_document
    output: github_document
    ---

## Shiffman - Tutorial 1

See [Reference 2](https://youtu.be/BCQHnlnPusY) - this is for real
beginners - just what I like!

## How to put a file (eg a text file) into a Repo:

1 First create the Repo: - click **new repo**  
- **name the repo**  
- give repo a **description**  
- make repo **public**  
- **tick box** to initialise the repo with a **readme** file - click
‘**create the repo**’

2 Then add the file:  
- click **new file** to add  
- **name** the new file  
- click **commit new file** (to master branch)

3 Then edit the file to make a change:  
- click the **edit button** (disguised as a pen)
- make required changes
- optionally add an informative comment under "Commit changes"
- check selected to "commit directly to the main branch (unless otherwise required) 
- click on **commit changes**

## Some Terminology

-   **Git** - the version control software (useable both online &
    offline)
-   **Github** the website that provides the Git services online  
-   **Repository (‘Repo’)** a collection of files - as with a project  
-   **commit** - like doing a *save*
    -   **commit hash**

## References

1.  [Carla Schroder - Linux CookBook, O’Reilly,
    2005](https://epdf.pub/linux-cookbook5b7e45d21264a146fceeaf2347ef331081099.html)  
2.  [1.1: Introduction - Git and GitHub for
    Poets](https://youtu.be/BCQHnlnPusY)
