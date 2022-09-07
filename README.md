# chinaknox.github.io

git clone https://github.com/chinaknox/chinaknox.github.io

cd chinaknox.github.io/

echo "Hello World!" > index.html

git config --list
git config user.name
git config user.email

git config --global user.name 'username'
git config --global user.email 'user@email.com'

git config user.name 'username'
git config user.email 'user@email.com'

git add --all
git status
git commit -m "commit comment"
git push -u origin main


https://chinaknox.github.io


### SIGNATURE CHECKSUM ###
keytool -list -printcert -jarfile <app.apk> | grep -Po "(?<=SHA256:) .*" | xxd -r -p | openssl base64 | tr -d '=' | tr -- '+/=' '-_'