# 1. GitBash 설치
     https://gitforwindows.org/  (for window) 
# 2. Github 로그인
     https://github.com
# 3. New Repository 생성
     1) new repository
     2) Create a new repository
         - select public
         - rename branch name : main -> master
# 4. git 소스를 로컬로 가져오기 (Root Folder 연결)
     : Web 상의 Git과 연결될 Local Folder
     1) 로컬에 폴더 생성
     2) 생성된 폴더에서 gitbash 실행  ( git bash here )
     3) git init
     4) git remote add origin (git remote address) ex) https://github.com/hwajoon/gitTest.git
     5) git pull origin master  // 지정해 놓은 Repository에서 소스를 끌어옵니다.
# 5. 현재 Git의 로그를 Check !
      1) git log  or    git log --graph --oneline
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
          
$ git log --graph --oneline
* 79c895b (HEAD -> master, origin/master) Update first_git_usage.md
* c530403 add branch guide file' q
* dc83038 (sub2) Update first_git_usage.md
* e2bed92 Update first_git_usage.md
* 361869a Update first_git_usage.md
* 1dd41af Update etc_command.md
* dcc88fd Update etc_command.md
* d46e5a2 modified markdown type
* 26853b8 add etc command
* b7c42e1 add guide files
* ce2cfe9 Update README.md
* 4fa999c Update README.md
* 0a1ec39 add folder & file
* b7a3f10 add txt file first
* 1e98126 Update README.md
* bf93883 Update README.md
* 00fb9c4 Update README.md
* fc73d07 Initial commit
</code></pre>

# 6. 현재 Git의 상태를 Check !
     1) git status
# 7. 변경된 파일들을 모두 Tracking  !
     1) git add .
# 8. 인식할 수 있는 commit을 달아줍니다.
     1) git commit -m "message"   or  git commit -am "message"
# 9. 실제로 Git에 PUSH
      1) git push origin +master   or   git push -u origin master   or git push origin master

# 10. Pull - Push command
      1) init
          - git init
      2) .gitignore 파일 작성     
      3) Pull
          - git pull origin master
      4) Push
          - git status
          - git add .  or  git add <file명>
          - git commit -m "message"
          - git push origin +master 
          
# 11. git remote rm origin
   1) git remote rm origin : 서버와 연결된 repo 끊기
          
# 12. ETC
<pre><code>
////////
..create a new repository on the command line
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/hwajoon/gitTest.git
git push -u origin master

///////////
.. push an existing repository from the command line
git remote add origin https://github.com/hwajoon/gitTest.git
git push -u origin master
</code></pre>
