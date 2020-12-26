# gitTest
This is created to test git first. 

1> GitBash 설치
     https://gitforwindows.org/  (for window) 
2> Github 로그인
     https://github.com
3>  New Repository 생성
     1) new repository
     2) Create a new repository
         - select public
         - rename branch name : main -> master
4> git 소스를 로컬로 가져오기 (Root Folder 연결)
     : Web 상의 Git과 연결될 Local Folder
     1) 로컬에 폴더 생성
     2) 생성된 폴더에서 gitbash 실행  ( git bash here )
     3) git init
     4) git remote add origin (remote address) ex) https://github.com/hwajoon/gitTest.git
     5) git pull origin master

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
