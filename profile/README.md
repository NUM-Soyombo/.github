### GIT Код хийх заавар!!!
1. Create new repository in github.com /чиний project-ийн нэр folder нэр адилхан байх ёстой/
2. Config git:
```
git config --global user.name <Your Name>
git config --global user.email <your.email@example.com>
```
3. In your folder 
```
git init 
git add .
git commit -m "<type>: (subject)"
```
### example commit:
  fix: encoderiin timer.
  type => chore, docs, feat, fix, refacter, style, values.
### Connecting Your Local Repository to the Remote Repository
```
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

