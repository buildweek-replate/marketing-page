

# marketing-page

## Product Pitch

Many businesses have leftover food at the end of the day. Replate is an easy to use app that lets them effortlessly have those extras picked up by a Replate volunteer and donated to one of our worthy partner organizations. Choose a convenient time and a volunteer will show up and take your extras to a predetermined place of need.

---

### Dependencies

I used Node, yarn, Less, and less-watch-compiler.


### Steps
(for PC)
* Download Node, Git Bash, Yarn, LESS, and less-watch-compiler

    * Node is the compiler used to convert language into code.
    * [Install Node](https://nodejs.org/en/)
    * Git Bash is used as our terminal.
    * [Install Git Bash](https://git-scm.com/download/win)
    * In Git Bash, run `node -v` to verify that node is installed.
    * [Install Yarn](https://yarnpkg.com/en/docs/install#windows-stable)
    * In Git Bash, run `yarn --version` to verify that yarn is working.
    * In Git Bash, run `yarn global add less` to install LESS.
    * In Git Bash, run `yarn global add less-watch-compiler` to install less-watch-compiler.

* Set up the project

    * Fork and clone this project (A git cheat sheet can be found [here](https://www.git-tower.com/blog/git-cheat-sheet))
    * cd into the project in Git Bash (A command line cheat sheet can be found [here](https://www.git-tower.com/blog/command-line-cheat-sheet/))
    * Once you are in the root of your project, run `less-watch-compiler less css index.less`
    * You can start and stop the less-watch-compiler with `CTRL + C`

* Navigating

    * The compiled index.css file can be found in the **css** folder.
    * The images used can be found in the **img** folder.
    * The LESS files can be found in the **less** folder.
        * **about.less** houses the About Us page styles.
        * **footer.less** houses the Footer styles.
        * **global.less** houses a few global styles.
        * **header.less** houses the header styles.
        * **index.less** imports all of the other less files to be compiled.
        * **landing.less** houses the Landing page styles.
        * **mixins.less** houses a couple parametric mixins used throughout the Landing and About Us pages.
        * **reset.less** has the Meyer reset.
        * **variables.less** has color and style variables, as well as the @mobile and @tablet escaped variables.
    * Mobile and Tablet styling is nested within the LESS files.
    * The Landing page content is found in **index.html**.
    * The About Us page content is found in **about.html**.
