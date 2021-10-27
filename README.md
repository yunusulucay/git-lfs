# git-lfs
Using git large file storage. If you use linux you can follow these steps.

1) install git-lfs (on terminal)
-> sudo apt-get update
-> sudo apt-get install git-lfs

2) Set up git-lfs for your user account by defining:
-> git lfs install (on terminal, enough one time run)

3) Go to the repository for ex. "/home/yunus/Documents/GitHub/repo_test" in this page on terminal run -> git lfs track "*.mp4" (This means allow all .mp4 files to upload)

4) git add .gitattributes (on terminal)

5) git commit .gitattributes (on terminal with same directory repo_test)

6) git push (on terminal)

Anymore you can send your large mp4 files(for this example) to your repo_test repo.
