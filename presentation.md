title: Scala製プロダクトのJava戦略
class: animation-fade, middle
layout: true

<!-- This slide will serve as the base layout for all your slides -->

---

class: impact

# .my-title[Scala製<br>プロダクトの<br>Java戦略]
#### 2018-10-24 Wed. @yoshiyoshifujii

---

# 自己紹介

.col-6[

- Yoshitaka Fujii [@yoshiyoshifujii](https://twitter.com/yoshiyoshifujii)
- ChatWork株式会社 (2ヶ月)
- Scala関西 Summit スタッフ
- Scala歴 4年
- Contributed to Akka
- [chatwork/akka-guard](https://github.com/chatwork/akka-guard)
- 🍣 🍶

]

.col-6[

.right[<img src="https://pbs.twimg.com/profile_images/907421547551277056/_vQ3f2Fg_400x400.jpg">]

]

---

background-image: url(scala_ks.png)

---

class: impact

.center[<img src="qr.png">]

---

# Agenda

1. JDKの新しいリリース・モデル
2. ScalaのJava11対応状況
3. 選択肢

---

class: impact

# JDKの新しい<br>リリース・モデル

---

# JDKの新リリース・モデル

> オラクルは2017年9月、JDKの提供サイクルとライセンス方式に関して、新たなリリース・モデルを発表しました。
> これらはJDK 9より一部が適用され、2018年9月に公開予定のJDK 11で完全移行します。
> 新リリース・モデルはJDKの過去のリリース・モデルの課題を解決したものであり、ユーザーにより多くのメリットをもたらします。


https://www.oracle.com/technetwork/jp/articles/java/ja-topics/jdk-release-model-4487660-ja.html

---

# JDKの新リリース・モデル
## 年6回の定期リリース・サイクル

- 新機能が追加される6カ月に1回(毎年3月、9月）のフィーチャー・リリースに加え
- 脆弱性対策などを施したアップデート・リリースを1年に4回
  - 毎年1月、4月、7月、10月

---

# JDKの新リリース・モデル
## GPL v2.0ライセンスの適用

- オラクルがビルドしたOpenJDKのバイナリ
- オープンソース・ライセンス「GNU General Public License（GPL） v2.0」
- 公式バイナリとして配布
- 無償版の配布を容易にするため
- ただし、ユーザーが開発したアプリケーションについては、GNUのClasspath ExceptionによってGPL v2.0の適用から除外される

---

# JDKの新リリース・モデル
## Oracle JDKの有償機能の無償化

- これまで有償で提供していたOracle JDKの機能をOpenJDKで公開
- JDK 11より全てが利用可能予定

---

# JDKの新リリース・モデル
## 無償アップデートの終了時期と有償サポートの提供

- オラクルがビルドした公式OpenJDKバイナリは、新バージョンがリリースされたタイミングで旧バージョンの更新を終了
- 無償版を利用するユーザーは、新バージョンに移行することでJDKを引き続き無償で更新できる
- 特定バージョンでJDKの更新を継続したいユーザーには、JDK 11から3年ごとにLTS指定されるフィーチャー・リリースに対してOracle JDKバイナリを有償で提供

---

class: impact

# Scalaの<br>Java11対応状況

---

class: impact

# 選択肢

---

# The basics

## Getting started

Use [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to write your slides. Don't be afraid, it's really easy!

--

## Making points

Look how you can make *some* points:
--

- Create slides with your **favorite text editor**
--

- Focus on your **content**, not the tool
--

- You can finally be **productive**!

---

# There's more

## Syntax highlighting

You can also add `code` to your slides:
```html
<div class="impact">Some HTML code</div>
```

## CSS classes

You can use .alt[shortcut] syntax to apply .big[some style!]

...or just <span class="alt">HTML</span> if you prefer.

---

# And more...

## 12-column grid layout

Use to the included **grid layout** classes to split content easily:
.col-6[
  ### Left column

  - I'm on the left
  - It's neat!
]
.col-6[
  ### Right column

  - I'm on the right
  - I love it!
]

## Learn the tricks

See the [wiki](https://github.com/gnab/remark/wiki) to learn more of what you can do with .alt[Remark.js]
