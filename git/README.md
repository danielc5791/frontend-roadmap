# Git

1. Download git for your platform

* [For Mac](https://git-scm.com/download/mac)
* [For Windows](https://gitforwindows.org/)
* [For Linux](https://git-scm.com/book/es/v1/Empezando-Instalando-Git#Instalando-en-Linux)

2. Clone the roadmap repository and push some changes:

  * In the console type:
  ```sh
  $ git clone https://github.com/push-dev/frontend-roadmap.git
  ```
  * Then checkout a new git branch with your name in it:
  ```sh
  $ git checkout -b feature/git-yourname
  ```
  * Create a new .html file under the git folder with your name and add it to your changes:
  ```sh
  $ git add git/yourname.html  
  ```
  * Check the status of your repository:
  ```sh
  $ git status  
  ```
  * Make sure your file is set to be added.
  * set a meaningful commit message:
  ```sh
  $ git commit -m "Includes yourname git changes"
  ```
  * Push your local changes:
  ```sh
  $ git push -u origin feature/git-yourname
  ```
3. Create a Pull request pointing to master and make sure other devs can review it.
  * go to [git repo](https://github.com/push-dev/frontend-roadmap)
  * Click on Compare & Pull request button
  * Put a meaningful title and description.
  * Add some reviewers. (Share your github username in the chat)
  * Wait for the approval of at least 1 reviewer and merge your branch into master.
  * Delete your old branch (for the sick of cleanness)


4. Double check everybody has access to your changes by asking them to do a git pull:
  ```sh
  $ git pull
  ```
