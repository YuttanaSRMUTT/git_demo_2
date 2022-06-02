# gitdemo

```
$ echo "# git_demo" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin https://github.com/YuttanaSRMUTT/git_demo_2.git
$ git push -u origin main
```
```
$ git add .
$ git status
$ git commit -m "2nd" OR git commit -a -m "2nd"
$ git push 
```

```
$ git commit -a -m "3rd"
$ git push 
```



# git configuration

## Show the configuration
```
git config --global --list
git config --list
```

## Set git username and email globally
```
git config --global --list
git config --global user.name "YuttanaS"
git config --global user.email "yuttana.s.rmutt@gmail.com"
```

## Git Ignored
* สร้าง Files .gitignore
* เพิ่มนามสกุล File ที่เราจะไม่สนใจ Upload
* *.log คือชื่อ Files
* bin/ คือชื่อ Folder
* add files .gitignore เข้าไปใน directory
* ```$ git add . ```
* ```$ git commit -a -m "4th" ```



