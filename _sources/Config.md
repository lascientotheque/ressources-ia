```

jb build . 

ghp-import -n -p -f _build/html

git checkout gh-pages
# Adding files ...
git commit -m "Update"
git push origin gh-pages
git checkout master


```