# source history

## Reset
- git reset --[hard | sort | mixed]
* (주의) hard는 모든것을 되돌림 !
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git log --graph --oneline
* cbad585 (HEAD -> master, origin/master) commit3
* 39e2107 commit2
* 4e0fbe2 commit1
* ca7199a add source history command
* 25bc1d5 Update branch_command.md
* 328e9f2 Update first_git_usage.md
* 79c895b Update first_git_usage.md
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

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git reset 39e2107   // ------------------------> commit3를 삭제하고  39e2107인 commit2로 이동
Unstaged changes after reset:
M       add_file_test.txt

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git log --graph --oneline
* 39e2107 (HEAD -> master) commit2
* 4e0fbe2 commit1
* ca7199a add source history command
* 25bc1d5 Update branch_command.md
* 328e9f2 Update first_git_usage.md
* 79c895b Update first_git_usage.md
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

## Revert
- git revert 
* history만 변경, 소스 그대로
<pre><code>
</code></pre>
