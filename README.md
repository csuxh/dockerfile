
dock build . -t csuxh/jackhttpd:v1.0
docker push csuxh/jackhttpd:v1.0

git init
git add .
git commit -m 'xxx'
git push origin master
git pull
