### GIT Код хийх заавар!!!
1. Create new repository in github.com /чиний project-ийн нэр folder нэр адилхан байх ёстой/
`Private байх` , `Add README.md товчийн битгий дар`
2. Terminal дээрээ Config git хийх:
```
git config --global user.name <Your Name>
git config --global user.email <your.email@example.com>
```
3. Өөрийн github-руу хийх folder дотор:
```
git init 
git add .
git commit -m "<type>: (subject)"
```
### example commit:
  `fix: encoderiin timer`
  ###### type => chore, docs, feat, fix, refacter, style, values.
### Өөрийн project-ийг  github-ийн repository-той холбох:
```
git branch -M main
git remote add origin https://github.com/yourusername/your-repository.git
git push -u origin main
```
### Cloning an Existing Repository
```
git clone https://github.com/username/repository.git
```
### Before you push your commit(s), please:
```
git pull origin main
```
### Now you can push your code:
```
git push
```
### Private project-ийг clone хийх, push хийх үед Username, password нэхдэг.Иймд SSH-ээр хандвал олон удаа password, username хийх шаардлагагүй болно. 
#### SSH холбох заавар.
```
ls -al ~/.ssh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```
#### Гарч ирэх үр дүнг copy хийж ав.
```
cat ~/.ssh/id_rsa.pub
```
#### Github-ийн Settings-рүү орооод SSH and GPS keys.
`New ssh keys` ногоон товчин дээр дараад copy-дож авсан кодоо хуулж тавь.
