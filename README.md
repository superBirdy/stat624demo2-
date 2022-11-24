# stat624demo2
demonstrating how to create a pull request

add description of the code\
add instructions for how to use\
add anything that will facilitate and promote use of your repo


git clone https://github.com/superBirdy/stat624demo2-.git \
cd stat624demo2-\
echo "x=5" >>test.py\
git add .\
git status\
git commit -m "add test.py"\
git push origin main


cd stat624demo2-\
#swith to a new branch 'dev'\
git checkout -b dev\
#create another python\
echo 'print("Hello World!")' >> hello_world.py\
git add .\
git status\
git commit -m "hello_world.py"\
git push --set-upstream origin dev
