# pwd
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ pwd
/d/workspace/gitTest
</code></pre>

# ls
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ ls
README.md  add_file_test.txt  add_folder_first/  readme/
</code></pre>

# alias ll='ls-al'
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ alias ll='ls -al'

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ ll
total 9
drwxr-xr-x 1 LuckyHwajoon 197121    0 Dec 26 17:19 ./
drwxr-xr-x 1 LuckyHwajoon 197121    0 Dec 26 16:13 ../
drwxr-xr-x 1 LuckyHwajoon 197121    0 Dec 26 17:24 .git/
-rw-r--r-- 1 LuckyHwajoon 197121 1599 Dec 26 16:11 README.md
-rw-r--r-- 1 LuckyHwajoon 197121   23 Dec 26 16:03 add_file_test.txt
drwxr-xr-x 1 LuckyHwajoon 197121    0 Dec 26 16:08 add_folder_first/
drwxr-xr-x 1 LuckyHwajoon 197121    0 Dec 26 17:28 readme/
</code></pre>

# Git Config (환경설정)
## git config --list
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager-core
pull.rebase=false
credential.https://dev.azure.com.usehttppath=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=hwajoon
user.email=hwajunlee@daum.net
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/hwajoon/gitTest.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
</code></pre>
 
## git config user.name
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git config user.name
hwajoon
</code></pre>

## git config --global user.name <github-name>
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git config --global user.name hwajoon

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git config user.name
hwajoon
</code></pre>

## git config user.email
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git config user.email
hwajunlee@daum.net
</code></pre>

## git config --global user.email <email>
<pre><code>
</code></pre>
    
## git config --list | grep "user.name"
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git config --list | grep "user.name"
user.name=hwajoon
</code></pre>    

## cat ~/.gitconfig
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ cat ~/.gitconfig
[filter "lfs"]
        clean = git-lfs clean -- %f
        smudge = git-lfs smudge -- %f
        process = git-lfs filter-process
        required = true
[user]
        name = hwajoon
        email = hwajunlee@daum.net
</code></pre>

