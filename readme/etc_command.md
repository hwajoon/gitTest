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
$ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-regex]
    --get-all             get all values: key [value-regex]
    --get-regexp          get values for regexp: name-regex [value-regex]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value_regex]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-regex]
    --unset-all           remove all matches: name [value-regex]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <>         value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry
</code></pre>
 
  > * git config user.name
  > * git config --global user.name <github-name>
  > * git config user.email
  > * git config --global user.email <email>
  > * git config 한눈에 보기
  > * cat ~/.gitconfig
