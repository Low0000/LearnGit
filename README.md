1. git --version
2. git config --global user.name "Low0000"
3. git config --global user.email "1211101699@student.mmu.edu.my"
4. git init / git clone URL
5. git status 檢查狀態是否提交
6. git add README.md / git add .
7. git commit -m "DETAILS EDITED" 標注更改了什麽内容的日志
8. git log / git log --oneline
EXAMPLE:
505d750 (HEAD -> main, origin/main) Create a readme file
5a5f689 Roll back git ignore to only .jpg format
a54c3a4 Add a png ignore
dbad37c Add a jpg file
61aec1b Ignore all .jpg file
6ddc5c4 Roll back Spec to 1st edition
a9f67bc 2nd point
1de03c7 Original Point

9. git diff 1de03c7 -- price.md 檢查不一樣的地方
10. git checkout 1de03c7 -- price.md 返回想要恢復的點 ---> git commit -m "（記錄修改内容）"  
11. git remote add origin https://github.com/Low0000/LearnGit.git --> git branch -M main --> git push -u origin main (創建鏈接去github)


Collaborator Instruction
1. 
