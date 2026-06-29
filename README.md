# basic-html

fork repo: https://github.com/handson-academy/basic-html to your account 
explain developer tools
main
explain domain / url / http(s) / request and response headers/ 
copy to postman
make a curl
curl into file 1.html

echo "
something one
something two
something three
" > 2.txt

grep something *
grep three *
grep something * | wc -l

sudo su
vi 3.txt
aaa
bbb
ccc
ddd

add text 
delete lines
save

chmod 007 3.txt
cat 3.txt

exit

cat 3.txt
sudo cat 3.txt


git clone [your repo]
cd basic-html/

sudo yum install python
python --version
python -m http.server 5555
nohup python -m http.server 5555 &
tail -f nohup.out

ps -ef | grep python
pgrep python
kill -9 [pid]
pkill python

test the http://[public ip]:5555/index.html 

go to git -> settings -> developer settings-> personal access tokens -> tokens (classic)
generate new token (classic
no expiration all privileges

git branch test-branch
git checkout test-branch
git status
vi index.html 
vi index2.html
git add index2.html
git commit -a -m "2 indexes"
git push

create a pull request
show that handson academy can merge

create a new branch in ui test-branch
create new files
git pull
ll
git checkout test-branch2
ll

cd ..
find . -name "index*.html" 
find . -name "index*.html" | xargs grep Hello
grep -r Hello *

mkdir newdir
echo "
{\"service\": {\"id\": 3, \"name\" : \"service3\"}}
" > newdir/1.json

sudo yum install jq
cat  newdir/1.json | jq -r '.service.name'

echo "
version: v1
services:
  service1: myservice
" >  newdir/2.yml

sudo wget -qO /usr/local/bin/yq https://github.com/mikefarah/yq/releases/latest/download/yq_linux_amd64
sudo chmod a+x /usr/local/bin/yq
cat  newdir/2.yml | yq -r '.services.service1'

sed -i 's/myservice/nivservice/g' newdir/2.yml 
cat  newdir/2.yml | yq -r '.services.service1'

ll
rm -rf newdir/

pwd
cd ~/basic-html/
 
ssh-keygen
cat ~/.ssh/id_rsa.pub 
go to github -> settings -> ssh and gpg add the key

make a private repository
try to clone with https
now with ssh

df -h
find . -type f -exec du -ah {} + | sort -rh | head -n 10
