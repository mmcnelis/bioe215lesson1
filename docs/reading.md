Project Workflows - setwd() can cause problems because it will not make file paths work for anyone but the original author and even then in a couple years not for them either, making the project not portable. To recreate or expand plot, the next user has to manually edit where the project will fall in their own directory. - When you call rm(list=ls()), it deletes user-created objects from the global workspace.
- Loaded packages still persist invisibly
- Session>Restart R or the Mac shortcut that is Command+Shift+F10

Bryan(2018)
Imagine you’re working with a few collaborators on an analysis. Come up with two examples of Issues you might open. How would using Issues differ from communicating over email?
- 
What are three ways GitHub features can promote open science practices?