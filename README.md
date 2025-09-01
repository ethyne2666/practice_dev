Git Practice – Fork, Clone, Upstream & Sync

This repository was created to practice essential Git & GitHub workflows with my friend.
We explored how developers collaborate using forks, remotes, and synchronization techniques.

🔑 Topics Practiced

Forking a repository

Create a copy of someone else’s repo under your GitHub account.

Cloning a repository

Bring the forked repo to your local machine using:

git clone <forked-repo-url>


Adding upstream remote

Connect the local clone back to the original repository:

git remote add upstream <original-repo-url>


Fetching & syncing changes

Get updates from upstream:

git fetch upstream
git checkout main
git merge upstream/main


Or a shorter way:

git pull upstream main


Pushing changes

After making edits locally:

git push origin main

🤝 Collaboration Flow

Fork the repository.

Clone the fork locally.

Set the upstream remote to stay updated.

Sync changes regularly from upstream.

Push your contributions to your fork.

Open a Pull Request (PR) to contribute back.

🛠 Example Commands We Used
# Clone forked repo
git clone https://github.com/your-username/git-practice.git

# Navigate into the repo
cd git-practice

# Add upstream
git remote add upstream https://github.com/original-owner/git-practice.git

# Verify remotes
git remote -v

# Sync latest changes
git pull upstream main

# Push to your fork
git push origin main

📚 What We Learned

How forks enable independent experimentation.

Why upstream is important to stay in sync with the original repo.

The difference between origin (our fork) and upstream (the original).

Team workflow: fetch → merge → push → pull request.

✨ This repo is purely for learning Git & GitHub collaboration basics.
