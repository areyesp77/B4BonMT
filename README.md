# B4BonMT
Basic bash scripts applied to Machine Translation

## Requirements 

In order to follow the tutorial, you will require a personal computer. Depending on your operative system, you will require **one** of the following: 

  * **Windows machine**. You have to download both [KiTTy](http://www.9bis.net/kitty/#!index.md) and [kscp](http://www.9bis.net/kitty/files/kscp.exe); both area available in this project as a single zip file
  * **Mac**. Nothing; you are ready to go
  * **Linux**. Nothing; you are ready to go

## Resources

We will use a small subset of the English-Italian part of the [Europarl parallel corpus](https://www.statmt.org/europarl/), which are available in this project as en.zip and it.zip. 

## Why is bash relevant?

  * Quick and easy text and data processing
  * The right way to interact with real computing software
  * One gate to Python and deep learning
  
## Hands on Bash 

### Find yourself at home

You will first learn how to setup a remote connection to the machine.

Afterwards, you will understand what is the meaning of "living" in a multi-user setting. You will learn how to list the files and directories, as well as how to move around.

Commands: `ssh`, `ls`, `pwd`, `cd`, `mkdir` 

### How to display and edit a file

Files can be simply displayed (without performing any modification) or actually opened for edition purposes. You will learn to do both. 

Commands: `cat`, `more`, `less`, `most`, `wc`, `nano`, `head`, `shuf`

### Grabbing information in a file from the command line
 
Until now, the kinds of operation you have performed are quite basic and not too different from what you can do with standard tools. Now we start to do interesting stuff. In this section you will learn how to sort, filter, modify, and combine the information in a file

Commands: `sort`, `grep`, `sed`, `column`

### Storing the results
 
All the operations carried out show their result in the terminal, but do not alter the contents nor are stored anywhere. Now we learn how to store them.

Commands: `>`, `%%>>%%`

### Understanding the structure of the commands 

We have played with quite a few commands already. Let us understand how commands are usually structured. 

#### Piping to combine commands  

Let's start making things interesting: all these commands can be executed one after the other at no extra cost. These are the so-called **one-liners**.

Commands: `awk`, `|`


### How to find some help 

Commands: `man`

### Exercises 

**EXERCISE 1**. Let us "measure" a file: bytes, megabytes, lines, words, etc.

**EXERCISE 2**. Shuffle a parallel corpus in order to have sentences from different speeches. 

**EXERCISE 3**. Find the most frequent tokens in the two parts of a parallel corpus and analyse them.

**EXERCISE 4**. Get all words which are cognates wrt Italian from a tsv dictionary. Afterwards, count the number of tokens which belong to each family. 

## Location and time 

The first (and so far only) edition of the tutorial was held in Room 4 of DIT's PhD Lab on Wednesday 6 November from 9.15 to 10.45. 
