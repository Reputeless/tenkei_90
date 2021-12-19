# C++17 で解く「競プロ典型 90 問」

**「競プロ典型 90 問」**を標準的な C++17 コードで解いていく個人用勉強プロジェクトです。  

C++17 標準ライブラリの機能を優先して使い、競技プログラミング固有のハックやスタイル（`<bits/stdc++.h>`, 大きな配列、マクロ、`using namespace std` 等）の使用を避けているため、一般的な C++ ソフトウェア開発で再利用できる、モダン C++ の標準を意識したコードになっています。  

バグや改善案のレポートは、このリポジトリの Issue をご利用ください。

### ★2

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|
|[004](https://atcoder.jp/contests/typical90/tasks/typical90_d)|[Cross Sum](./004.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/004.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/004.cpp)|扱いやすい形にして前計算しよう|
|[010](https://atcoder.jp/contests/typical90/tasks/typical90_j)|[Score Sum Queries](./010.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/010.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/010.cpp)|区間の総和は累積和|
|[022](https://atcoder.jp/contests/typical90/tasks/typical90_v)|[Cubic Cake](./022.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/022.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/022.cpp)|最大公約数はユークリッドの互除法|
|[024](https://atcoder.jp/contests/typical90/tasks/typical90_x)|[Select +／- One](./024.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/024.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/024.cpp)|パリティを考える|
|[027](https://atcoder.jp/contests/typical90/tasks/typical90_aa)|[Sign Up Requests](./027.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/027.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/027.cpp)|map を使いこなそう|
|[033](https://atcoder.jp/contests/typical90/tasks/typical90_ag)|[Not Too Bright](./033.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/033.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/033.cpp)|コーナーケースに気を付けよう|
|[055](https://atcoder.jp/contests/typical90/tasks/typical90_bc)|[Select 5](./055.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/055.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/055.cpp)|「定数倍」を見積もる|
|[061](https://atcoder.jp/contests/typical90/tasks/typical90_bi)|[Deck](./061.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/061.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/061-02.cpp)|deque を知っていますか？|
|[067](https://atcoder.jp/contests/typical90/tasks/typical90_bo)|[Base 8 to 9](./067.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/067.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/067.cpp)|N 進法展開を理解しよう|
|[078](https://atcoder.jp/contests/typical90/tasks/typical90_bz)|[Easy Graph Problem](./078.md)|★2|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/078.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/078.cpp)|グラフの基本を知ろう|

### ★3

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|
|[002](https://atcoder.jp/contests/typical90/tasks/typical90_b)|[Encyclopedia of Parentheses](./002.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/002.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/002.cpp)|小さい制約は全探索を考えよう|
|[007](https://atcoder.jp/contests/typical90/tasks/typical90_g)|[CP Classes](./007.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/007.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/007.cpp)|要素の検索はソートして二分探索|
|[014](https://atcoder.jp/contests/typical90/tasks/typical90_n)|[We Used to Sing a Song Together](./014.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/014.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/014.cpp)|ソートして貪欲法|
|[016](https://atcoder.jp/contests/typical90/tasks/typical90_p)|[Minimum Coins](./016.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/016.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/016.cpp)|工夫した全探索|
|[018](https://atcoder.jp/contests/typical90/tasks/typical90_r)|[Statue of Chokudai](./018.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/018.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/018.cpp)|三角関数を使いこなそう|
|020| | | | |
|032| | | | |
|038| | | | |
|044| | | | |
|046| | | | |
|048| | | | |
|050| | | | |
|052| | | | |
|064| | | | |
|069| | | | |
|075| | | | |
|076| | | | |
|079| | | | |
|082| | | | |
|084| | | | |

### ★4

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|

### ★5

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|

### ★6

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|

### ★7

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|


### 参考リンク
- [競プロ典型 90 問 - AtCoder コンテストページ](https://atcoder.jp/contests/typical90)
- [競プロ典型 90 問 - GitHub 公式リポジトリ](https://github.com/E869120/kyopro_educational_90)
- [競プロ典型 90 問 - テストケース](https://www.dropbox.com/sh/nx3tnilzqz7df8a/AAC-L790bxKBVkmB6pdMUgk4a/typical90?dl=0&subfolder_nav_tracking=1)
- [AtCoder での実力アップを目指そう！ ～競プロ典型 90 問～ - Qiita](https://qiita.com/e869120/items/1b2a5f0f07fd927e44e9)
- [「競プロ典型90問」非公式難易度表・ソースコード共有 - Google スプレッドシート](https://docs.google.com/spreadsheets/d/1GG4Higis4n4GJBViVltjcbuNfyr31PzUY_ZY1zh2GuI/edit#gid=0)
- [AC (AtCoder) Library Document](https://atcoder.github.io/ac-library/document_ja/index.html)
