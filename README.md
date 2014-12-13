sudo apt-get install git
git config --global user.name "vsree2204"
git config --global user.email "sreedhar2204@gmail.com"
mkdir test
cd test/
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/vsree2204/test.git
git push -u origin master

