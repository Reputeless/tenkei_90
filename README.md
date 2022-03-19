# 競プロ典型 90 問 練習 (C++17)

<b>[「競プロ典型 90 問」](https://atcoder.jp/contests/typical90)</b>を標準的な C++17 コードで解いていく、個人用勉強プロジェクトです。  

C++17 標準ライブラリの機能を優先して使い、競技プログラミング固有のハックやスタイル（`<bits/stdc++.h>`, 大きな配列、マクロ、`using namespace std` 等）の使用を避けているため、一般的な C++ ソフトウェア開発で再利用できる、モダン C++ の標準を意識したコードになっています。  

バグや改善案の報告は、このリポジトリの Issue をご利用ください。

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
|[020](https://atcoder.jp/contests/typical90/tasks/typical90_t)|[Log Inequality](./020.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/020.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/020.cpp)|整数で処理して誤差をなくそう|
|[032](https://atcoder.jp/contests/typical90/tasks/typical90_af)|[AtCoder Ekiden](./032.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/032.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/032.cpp)|小さい制約は順列全探索|
|[038](https://atcoder.jp/contests/typical90/tasks/typical90_al)|[Large LCM](./038.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/038.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/038.cpp)|オーバーフローに注意|
|[044](https://atcoder.jp/contests/typical90/tasks/typical90_ar)|[Shift and Swapping](./044.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/044.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/044.cpp)|見かけ上の変化をメモ|
|[046](https://atcoder.jp/contests/typical90/tasks/typical90_at)|[I Love 46](./046.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/046.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/046.cpp)|同じ意味のものをまとめて考える|
|[048](https://atcoder.jp/contests/typical90/tasks/typical90_av)|[I will not drop out](./048.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/048.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/048.cpp)|上界と下界を見積もる|
|[050](https://atcoder.jp/contests/typical90/tasks/typical90_ax)|[Stair Jump](./050.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/050.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/050.cpp)|漸化式を立てて DP をしよう|
|[052](https://atcoder.jp/contests/typical90/tasks/typical90_az)|[Dice Product](./052.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/052.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/052.cpp)|因数分解をしよう|
|[064](https://atcoder.jp/contests/typical90/tasks/typical90_bl)|[Uplift](./064.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/064.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/064.cpp)|階差を考えよう|
|[069](https://atcoder.jp/contests/typical90/tasks/typical90_bq)|[Colorful Blocks 2](./069.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/069.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/069.cpp)|a^b mod m は繰り返し二乗法|
|[075](https://atcoder.jp/contests/typical90/tasks/typical90_bw)|[Magic For Balls](./075.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/075.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/075.cpp)|O(√N) での素因数分解|
|[076](https://atcoder.jp/contests/typical90/tasks/typical90_bx)|[Cake Cut](./076.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/076.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/076.cpp)|円環を列にして二倍にする|
|[079](https://atcoder.jp/contests/typical90/tasks/typical90_ca)|[Two by Two](./079.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/079.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/079.cpp)|操作順序によらない|
|[082](https://atcoder.jp/contests/typical90/tasks/typical90_cd)|[Counting Numbers](./082.md)|★3|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/082.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/082a.cpp)|部分問題に分解する/数列の和の公式|
|[084](https://atcoder.jp/contests/typical90/tasks/typical90_cf)|[There are two types of characters](./084.md)|★3|(1) [👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/084-01.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/084-01.cpp)<br>(2) [👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/084-02.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/084-02.cpp)|(解法 1) ランレングス圧縮<br>(解法 2) 累積的に計算しよう|

### ★4

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|
|[001](https://atcoder.jp/contests/typical90/tasks/typical90_a)|[Yokan Party](./001.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/001.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/001.cpp)|答えで二分探索|
|[003](https://atcoder.jp/contests/typical90/tasks/typical90_c)|[Longest Circular Road](./003.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/003.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/003.cpp)|木の直径は最短距離計算を 2 回やる|
|[008](https://atcoder.jp/contests/typical90/tasks/typical90_h)|[AtCounter](./008.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/008.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/008.cpp)|状態 DP による高速化|
|[012](https://atcoder.jp/contests/typical90/tasks/typical90_l)|[Red Painting](./012.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/012.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/012.cpp)|連結判定は Union-Find|
|[026](https://atcoder.jp/contests/typical90/tasks/typical90_z)|[Independent Set on a Tree](./026.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/026.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/026.cpp)|二部グラフの性質を使おう|
|[028](https://atcoder.jp/contests/typical90/tasks/typical90_ab)|[Cluttered Paper](./028.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/028.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/028.cpp)|領域加算は二次元いもす法|
|[034](https://atcoder.jp/contests/typical90/tasks/typical90_ah)|[There are few types of elements](./034.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/034.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/034.cpp)|単調性を利用した尺取り法|
|[042](https://atcoder.jp/contests/typical90/tasks/typical90_ap)|[Multiple of 9](./042.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/042.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/042.cpp)|9 の倍数の性質|
|[043](https://atcoder.jp/contests/typical90/tasks/typical90_aq)|[Maze Challenge with Lack of Sleep](./043.md)|★4|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/043.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/043.cpp)|拡張 BFS・ダイクストラ|
|058| | | | |
|063| | | | |
|070| | | | |
|072| | | | |
|085| | | | |


### ★5

|問題|タイトル (解答コードへのリンク)|難易度|公式解説|キーワード (公式解説から引用)|
|:--:|--|:--:|:--:|--|
|006| | | | |
|013| | | | |
|021| | | | |
|029| | | | |
|030| | | | |
|036| | | | |
|[037](https://atcoder.jp/contests/typical90/tasks/typical90_ak)|[Don't Leave the Spice](./037.md)|★5|[👨‍🏫](https://raw.githubusercontent.com/E869120/kyopro_educational_90/main/editorial/037.jpg) / [📝](https://github.com/E869120/kyopro_educational_90/blob/main/sol/037.cpp)|DP をセグメント木で高速化|
|039| | | | |
|051| | | | |
|056| | | | |
|060| | | | |
|066| | | | |
|068| | | | |
|073| | | | |
|081| | | | |
|086| | | | |
|087| | | | |


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
