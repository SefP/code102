# Tuesday

* 6:00pm - Git: Branching
  * Did you push your code last night?
  * Create a new branch:
    * `git checkout -b tuesday`
  * Add a new file: notes/tuesday.md
    * Create the file in Atom, or from the command line with `touch notes/tuesday.md`
    * Add to your repo *before* you add any content:
      * `git add notes/tuesday.md`
      * `git commit -m "Add notes file for Tuesday"`
  * What happens if you check out master (`git checkout master`)? Is the new file there?
  * At the end of night we'll merge the new feature branch back into master
  * Make sure you check out the new branch (`git checkout feature/tuesday`) before continuing
* 6:15pm - Command Line: [Quick Intro to vi](/resources/vi_cheat_sheet.md)
* 6:30pm - Command Line: [Bash Aliases](/resources/bash_aliases.md)
* 7:00pm - Prework (you should be at least 40% complete by the end of class)
* 8:15pm - Git: Merging Branches
  * Commit your changes:
    * `git add -p`
    * `git commit -m "Add Tuesday notes"`
  * Merge the feature branch into master:
    * `git checkout master`
    * `git merge tuesday`
  * Push your changes:
    * `git push origin master` (now you understand what `master` means... tomorrow you'll understand `origin`)
* 8:40pm - Recap, Q&A

[Back to main README](/README.md) | [Wednesday](/schedule/wednesday.md)
