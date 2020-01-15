## Application Exercise 02 - Star Wars

Visualizing Star Wars data!

### A recap on cloning the assignment repo

- Go to the `ae-03-starwars-your-name-goes-here` repo on GitHub that you created

- Click on the green **Clone or download** button, **Use HTTPS**, and click on the clipboard icon to copy the repo URL.

- Go to RStudio Cloud and **into the STA 199 course workspace**. Create a **New Project from Git Repo**. You will need to click on the down arrow next to the **New Project** button to see this option.

- Copy and paste the URL of your assignment repo into the dialog box.

- Click OK, and you should see the contents from your GitHub repo in the Files pane in RStudio. 

### Configure git

There is one more piece of housekeeping we need to take care of before we get started. Specifically,  we need to configure your git so that RStudio can communicate with GitHub. This requires two pieces of information: your email address and your name.

Type the following lines of code in the **Console** in RStudio filling in your name and email address.

`library(usethis)
use_git_config(user.name="your name", user.email="your email")`

For example, mine would be  

`
library(usethis)
use_git_config(user.name="Yue Jiang", user.email="yue.jiang@duke.edu")
`

**RStudio and GitHub can now commmunicate with each other and you are ready to do the exercise!**
