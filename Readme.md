# Gitty

I got tired of writing multiple lines of code every time I wanted to commit and push my changes to Git. So, I created Gitty - a simple shell script that automates the process. It works on Linux and macOS.

The commit message is passed as an argument when running the script.

## Setup

To set up Gitty, clone the repo and navigate to the directory where you cloned it ,then you need to move the script to a directory that's in your system's PATH and make it executable. You can do this by running the following commands:

```shellscript
sudo mv gitty.sh /usr/local/bin/gitty
```

```shellscript
sudo chmod +x /usr/local/bin/gitty
```

### Sample usage 

```shellscript
gitty "your-commit-message"
```

And thats it , it will add , commit and push the code to remote repo 
