---
layout: default
---

## Week 1: Introduction to Command Line Environments

We started by setting up our command line environments and familiarizing ourselves with basic commands and 
navigation. The initial videos and readings laid the groundwork for effective command line usage.

### Reflection
I learned how to effectively interact with the command line and grasped the importance of using basic 
commands to navigate and manage files.

- Navigating directories (`cd`, `ls`)  
- Basic file operations (`touch`, `cp`, `mv`, `rm`)  
- Viewing file contents (`cat`, `less`, `head`, `tail`)

## Week 2: Navigating a UNIX System

This week focused on understanding the UNIX file system, processes, and remote server access. We explored how 
to manipulate directories and files efficiently.

### Reflection
I gained a solid understanding of the UNIX file system structure and learned how to access and manage files 
on remote servers.

```bash
cd /path/to/directory
```
This command changes the current directory to the specified path.

## Week 3: Basic Corpus Processing

We covered essential text processing commands, regular expressions, and the grep command. These tools are 
vital for handling and searching text effectively.

### Reflection
I learned how to perform basic text processing, which is crucial for any data analysis task.

```bash
grep 'pattern' file.txt
```
This command searches for the specified pattern within the file, returning matching lines.

## Week 4: Advanced Corpus Processing

This week introduced the sed command and the concept of text processing pipelines, allowing for more complex 
data manipulation.

### Reflection
Understanding sed opened up new possibilities for streamlining text processing tasks.
```bash
sed 's/old/new/g' file.txt
```
This command replaces all occurrences of "old" with "new" in the specified file.

## Week 5: Scripting and Configuration Files

We explored scripting basics, environment variables, and configuration files. Scripting is essential for 
automating tasks in the command line.

### Reflection
I learned how to create scripts that can automate repetitive tasks, greatly improving my efficiency.
```bash
#!/bin/bash
echo "Hello, World!"
```
This script prints "Hello, World!" to the terminal when executed.

## Week 6: Installing and Running Programs
This week was about managing software installations and using Makefiles. Understanding these concepts is 
crucial for managing dependencies in projects.

### Reflection
I became comfortable with installing software and using Makefiles to automate project builds.
```bash
%.freq: %.no_md.txt
    bin/freqlist.sh $< $@
```
This Makefile rule defines a target for generating frequency lists from text files, highlighting the 
importance of automation in project management.

## Week 7: Version Control

We learned about version control systems, particularly Git and GitHub, which are vital for collaborative 
projects and tracking changes.

### Reflection
I understood the significance of version control in managing code and collaborating with others effectively.

```bash
git commit -m "Initial commit"
```
This command saves changes to the local repository with a message describing the commit.

## Final Project
In the final week, we explored Jekyll for static site generation and GitHub Pages for hosting projects 
online. This enables easy sharing of project documentation.

### Reflection
I realized the power of Jekyll and GitHub Pages for creating and publishing project documentation in an 
organized manner.
```bash
bundle exec jekyll serve
```
This command is used to start a local server for a Jekyll site.
