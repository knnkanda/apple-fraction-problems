# Apple Fraction Problems


https://apple-fraction-problems.vercel.app/

# Apple Fraction Problems / りんごのぶんすう

## 日本語

### 概要

「りんごのぶんすう」は、分数をりんごの切り分けとして目で見ながら学ぶための、小さな算数学習アプリです。

算数が苦手になるきっかけは、抽象的な記号だけが先に出てきて、「何を表しているのか」がつかめない瞬間に起こりやすいと考えています。このアプリでは、分数をいきなり計算式として扱うのではなく、りんごを分ける・見る・足す・足りない部分を考える、という順番で理解できるようにしています。

目標は、算数嫌いになるおちこぼれポイントを少しずつ越えていける、楽しい算数体験を作ることです。

### 学習ステージ

#### 1. みてえらぶ

色がついているりんごのピースを見て、分数を選びます。

ここでは、`1/2`、`1/3`、`1/4` などを「記号」ではなく「りんごの何個分か」として認識することを目指します。

#### 2. たしざん

同じ大きさに切られたりんごの中で、赤い部分とオレンジの部分を合わせます。

たとえば `1/3 + 2/3 = 1` のように、分母が同じ分数を足すときは、同じりんごの中で色のついたピースを合わせればよい、という感覚を育てます。

#### 3. 1をつくる

すでに色がついている分数を見て、あとどれだけ足せばりんご1個になるかを考えます。

これは、足りない分子を考える練習です。たとえば `1/4 + ? = 1` のような問題を、記号だけでなく「まだ色がついていないピース」として理解します。

### 今後の発展

このアプリは、分数の入口として作っています。今後は次のような学習へ発展させることを想定しています。

- `2 1/3` のような帯分数の理解
- 分数どうしの足し算
- 分数と整数の関係
- 分数のかけ算
- りんご以外の教材表現

### 開発方針

このアプリは、ローカルでMVPを作り、ベータ版として公開し、実際に子どもや学習者に触ってもらいながら改善していく方針です。

特にスマートフォンで使いやすいことを重視しています。正解後に次の問題へ進むボタンが見切れないようにし、余計な説明よりも、見たまま理解できる画面を優先します。

### 公開URL

https://apple-fraction-problems.vercel.app/

---

## English

### Overview

Apple Fraction Problems is a small math learning app that helps children understand fractions by looking at sliced apples.

Many children begin to dislike math when abstract symbols appear before they understand what those symbols mean. This app tries to avoid that gap. Instead of starting with formulas, it begins with visual recognition: dividing an apple, seeing colored pieces, adding pieces, and thinking about the missing part needed to make one whole apple.

The goal is to create a fun math experience that helps learners overcome the points where they might otherwise start to feel left behind.

### Learning Stages

#### 1. Look and Choose

Learners look at the colored pieces of an apple and choose the matching fraction.

This stage helps children recognize fractions such as `1/2`, `1/3`, and `1/4` as parts of a whole apple, not just as written symbols.

#### 2. Addition

Learners add red and orange pieces inside the same sliced apple.

For example, `1/3 + 2/3 = 1` becomes easier to understand when both parts are shown inside one apple. The app is designed to reduce unnecessary mental effort and let learners see that fractions with the same denominator can be combined by counting the colored pieces.

#### 3. Make One

Learners look at a partial fraction and choose how much more is needed to make one whole apple.

This stage builds the idea of the missing numerator. For example, `1/4 + ? = 1` can be understood visually as the uncolored pieces that still need to be filled.

### Future Direction

This app is intended as an entry point to fractions. Future versions may expand into:

- Mixed numbers such as `2 1/3`
- Fraction addition
- The relationship between fractions and whole numbers
- Fraction multiplication
- Other visual learning materials beyond apples

### Development Approach

The app follows an MVP-first approach: build a simple local version, publish a beta, let real learners try it, and improve the experience based on concrete feedback.

Mobile usability is a priority. The main action, such as moving to the next question, should remain visible on smartphone browsers. The interface should avoid unnecessary text when a visual reward or visual explanation already communicates the idea clearly.

### Live Demo

https://apple-fraction-problems.vercel.app/


A single-file Japanese web app for learning apple fractions visually.

## Local preview

Open `index.html` in a browser.

## Deploying to Vercel

This is a static HTML app. Import this GitHub repository into Vercel and deploy with the default settings.
