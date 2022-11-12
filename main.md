# Lab Report 4
## Part 1
To change the name of the `start` parameter and its uses to `base`, I first opened the file on vim. After opening the file on vim, I pressed `<esc>` to make sure I was in normal mode. I then typed the following command: `:%s/start/base/g`. 
What this command did is that it changed all instances of the paramter `start` to the paramter `base`. The `%` lets vim know the range of the change. The first word between the slashes is the word we are going to find. The second word in the slashes is the replacement word.
The `/g` lets vim know to replace all instances and not just the first.
## Part 2
