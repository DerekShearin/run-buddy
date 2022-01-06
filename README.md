# Run Buddy, Inc

## Purpose
A website that offers fitness training services. 

## Built With
* HTML
* CSS

## Website
https://lernantino.github.io/run-buddy/

## Contribution
Made with ❤️ by Derek Shearin

I created the branch "develop" then realized I didn't commit the second-style sheet and Privacy policy. After I gdid that, 
alfaf@MSI MINGW64 ~/Desktop/BOOTCAMP/projects/run-buddy (main)
$ git push origin main
To github.com:DerekShearin/run-buddy.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:DerekShearin/run-buddy.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 

alfaf@MSI MINGW64 ~/Desktop/BOOTCAMP/projects/run-buddy/assets/css (develop)
$ git checkout main
Switched to branch 'main'

alfaf@MSI MINGW64 ~/Desktop/BOOTCAMP/projects/run-buddy/assets/css (main)
$ git status
On branch main
nothing to commit, working tree clean

alfaf@MSI MINGW64 ~/Desktop/BOOTCAMP/projects/run-buddy/assets/css (main)
$ git pull origin main
remote: Enumerating objects: 14, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 11 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (11/11), 11.38 KiB | 315.00 KiB/s, done.
From github.com:DerekShearin/run-buddy
 * branch            main       -> FETCH_HEAD
   357008b..cf21f6d  main       -> origin/main
Auto-merging assets/css/secondary-styles.css
CONFLICT (add/add): Merge conflict in assets/css/secondary-styles.css
Auto-merging privacy-policy.html
CONFLICT (add/add): Merge conflict in privacy-policy.html
Automatic merge failed; fix conflicts and then commit the result.
