# Clean Up The Kitchen!

![Dirty Fridge](https://2.bp.blogspot.com/-plaqoWwxUnA/UoVrgyNPUHI/AAAAAAAAAeY/jhALyfFVTpU/s1600/dirty-fridge-clipart-i1.jpg)

Your kitchen is a disaster. We're not blaming anyone, but when we opened up the fridge today, we almost passed out. Please, please clean up your mess.

## Instructions

You'll be practicing your command line skills by organizing the files in your refrigerator.

+ On your virtual machine, use `cd ~` to go to your root directory.

+ Copy this line in to the terminal to get all the directories and files onto your virtual machine: `git clone https://github.com/woodstockcs/kitchen.git`.

+ Type `ls` to make sure you see `kitchen`.

+ cd into that directory. Use `cd` and `ls` to have a look around your kitchen. It should look something like this:

![tree of directories](https://s3.amazonaws.com/upperline/curriculum-assets/command-line/current-tree.png)

+ Using `ls`, `pwd`, `cd`, `mv`, and `rm`, get the food files in their correct directories. Here's how we'd move the watermelon from the meat directory into the fruits directory (first you'll need to `cd` into the meat directory):

```
mv watermelon.jpg ../produce/fruit
```
This will move the watermelon up one level (..) which will place it in the general fridge directory, and then it is moved into "produce" and then "fruit"

+ Use `rm` to remove any roaches you find!

+ Use `touch` to add at least three new foods - label them as .txt files. For example (in the fruit directory) type:

```
touch peaches.txt
```

+ Add anything new you learned to the `cheatsheet.txt` file in your root directory.

## How to Submit
1. Take screenshots of the `ls` listings for each of the six directories in this assignment: freezer, dairy, meat, drinks, fruit, vegetables.
1. Copy those screenshots into the assignment document on google classroom.
1. Answer the remaining questions in that document.

**Definition of done = You've followed all the instructions above and pressed 'Turn in' for this assignment's document in google classroom.**
