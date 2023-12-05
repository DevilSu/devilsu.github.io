Hugo
link: https://medium.com/@magstherdev/github-pages-hugo-86ae6bcbadd
- sudo apt install hugo
- hugo new site FOLDER_NAME -f yml
- cd FOLDER_NAME
- Add theme:
    git submodule add https://github.com/chrede88/qubt.git themes/qubt
- Modify!
- Run site:
    - hugo server --bind=0.0.0.0
- Deploy site:
    - create a repo with name: devisu.github.io (without any files in it)
    - clone it to local 
    - copy and paste all files in
    - Compile the F**k website!
        - command line: hugo
        - This will create a folder called public, just leave it there
    - git add .
    - git commit -m "First commit"
    - git branch -M main
    - git push origin main
    - Do the settings thing: https://gohugo.io/hosting-and-deployment/hosting-on-github/

Other useful links:
https://gohugo.io/quick-reference/emojis/