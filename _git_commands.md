# add yourself as an author
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

# Initialize a git repository
git init

# Add a file to staging area
git add <file>

# Add all files to staging area
git add .

# check project status
git status

# commit changes
git commit -m "My message"

# undo changes made to a file
git restore <file>

# undo changes made to all files
git restore .

# show commit history
git log

# show commit history in a nice format
git log --oneline --graph --decorate --all