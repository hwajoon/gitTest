# branch

## git branch <branch-name> # branch 만들기
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git branch sub1

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git branch
* master
  sub1
</code></pre>

## git branch # branch 전체 보기
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git branch
* master
  sub1
  sub2
</code></pre>

## git checkout <branch-name> # branch 전환
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git checkout sub1
Switched to branch 'sub1'

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (sub1)
$ git branch
  master
* sub1
  sub2
</code></pre>

## git branch remote <branch-name>   /   git granch -d <branch-name>
<pre><code>
LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git branch
* master
  origin
  sub1
  sub2

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git branch -d origin
Deleted branch origin (was 328e9f2).

LuckyHwajoon@DESKTOP-LPIHDHS MINGW64 /d/workspace/gitTest (master)
$ git branch
* master
  sub1
  sub2
</code></pre>

## git clone <git-remote-address>
<pre><code>
</code></pre>
