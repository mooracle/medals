THIS IS A README EXAMPLE

The project is to build a medal store.

This is for the example of learning Git functions.

Right now just add this to the cloned directory of medals.

Now we will test for branches in remote. For the first test we will deliberately creates:
1. master in the PC then push it into remote
2. we make the Mac also do an edit then commit locally
3. After that we will fetch the remote (origin/master) to the Mac and see its log
4. then we will push the Mac local Master head to the remote

We will see what will happen there
Note:
1. In PC commit we will edit the README.md file
2. In the Mac we will edit the CONTRIBUTING.md
3. We only focus first on non conflicting files and just want to see how the two master pushed

The master branch failed to push into remote since remote detect conflicting branch names
The master from the PC was far ahead thus I decided to use the simplest solution using pull in the Mac
The result is the master branch in Mac were being merged with the origin/master first
Then since there are not conflicting files the merged was successful.
Then I can safely push the latest master branch into remote from the Mac

This time we will make it interesting after the PC has push commit
The PC push the latest README.md commit in a new branch called masterv2
This time I will push another commit under the master branches
Then I will make the PC to fetch the latest update
and then try to merge them using pull method.

Now I am at the antREAD branch and want to push this bragnch to remote
Then test the fetch in the Mac and see if it can be pulled
What will happen if it was fetch and what will happen if this is being pulled.

I am now at the new_readme branch which is checked out without me having to make
Next I will commit this changes and see what will be like in the other side
