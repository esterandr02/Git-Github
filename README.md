<p align="center" flex="box">
  <img alt="git-icon" src="assets/git.png" width="140"/>
  <img alt="git-icon" src="assets/git-name.png" width="150"/>
</p>

<h1 align="center">Git and Github</h1>

### 👤️ Account
```bash
# Login
$ git config --global user.name your-username

# Config
$ git config --global user.email your-email
```

### 🏁️ Getting Started

```bash
# Init a local project
$ git init

# new file
$ touch

# clone an exist repo
$ git clone github-repository-URL
```

### 📊️ Management

```bash
# get a relatory about repo modifications and git stage
$  git status

# add all modifications source this path
$ git add .   

# add some especific modification(file)
$ git add file-name

# commit modifications with a short message(generally explaining what you change)
$ git commit -m "message"

# push the first commit
$ git push -u origin branch-name

# normal push
$ git push
```

### ⬆️ Check modifications

```bash
# show all modifications
$ git log

$ git remote -v
```

### 📍️ Branch
  
```bash
# create a new branch
$ git branch branch-name

# Go to some branch
$ git checkout branch-name

# delete branch
$ git branch -D

# dele remote branch
$ git push origin --delete branch-name
```

### 🔄️ Update 
 
 ```bash
# Update the local repository source remote's
$ git pull
 ```
### 🔙️ Go Back to some Commit

```bash
# take a commit code you want go back on the git log
$ git checkout commit-code
```

Made with ♥ by Ester :wave: [Get in touch!](https://www.linkedin.com/in/ester-albuquerque-3589911a6/)
