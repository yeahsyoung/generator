# generator

echo "# generator" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:yeahsyoung/generator.git
git push -u origin master

git push -u origin master -f 

git remote add origin git@github.com:yeahsyoung/generator.git
git push -u origin master