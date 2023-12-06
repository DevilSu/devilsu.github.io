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

Can make changes in submodule, just cd into the submodule and do the normal git add commit push in there.
    - do it in themes/dvs_qubt_mod

!!!!!!!!!!!!!!! IMPORTANT !!!!!!!!!!!!!!!
Have to git push in submodule first, otherwise the main git repo cant find the modified shit in submodule
and will fail to compile on github repo...

Other useful links:
https://gohugo.io/quick-reference/emojis/


to change theme:
- change config.yaml
- change config/_default/module.yaml

justify align text:
- in theme, change assets/css/compiled/main.css
    - look for body{}
        - add the line: text-align: justify;



Create custom shortcodes: https://gohugo.io/templates/shortcode-templates/

if add\delete tabs, like about, Home, ...
- modify config/_default/menus.yaml

change profile photo:
- in config/_default/params.yaml