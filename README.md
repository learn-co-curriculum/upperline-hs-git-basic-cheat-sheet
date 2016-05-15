## Git Cheat Sheet

<img src="https://s3.amazonaws.com/after-school-assets/cheating.gif" width="300" align="right" hspace="10">

Git got you freaked? It's normal. There are a lot of commands that have control over a lot of different actions. This is precisely why we never expect you to memorize anything. In fact, we're even providing you with a cheat sheet. It's not cheating when it's programming!

### To Copy An Existing Repository To Your Computer:
1. Go to the repository page on github.com
2. Click on the fork button on the top right of the screen.
3. Copy the SSH clone link on the right side of the new page.
4. Navigate to the development folder in your terminal and type `git clone [copied_text]`
5. cd into the folder you downloaded on your computer.


### To Push Work To GitHub:
So you've finished a lab or a project and want to push your work to GitHub?

1. Check the status of your project with `git status` 

2. When you're working on a project and want to commit your code:
  +  Use `git add` with the filename you want to to add to your 'holding station'
  + When you're ready to commit, `git commit -m "add a message about the changes you've made`
  + When you're ready to push to your repository on github.com: `git push origin [branch name]` (if it's the first time you do this, add the flag `-u` after `git push`)
  

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-git-basic-cheat-sheet' title='Git Cheat Sheet'>Git Cheat Sheet</a> on Learn.co and start learning to code for free.</p>
