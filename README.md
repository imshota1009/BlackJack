# 🃏✨ ファンタジー・ブラックジャック (Fantasy Blackjack)

> **「勇者よ、カードで運命を切り開け！」**  
> ファンタジーの世界観で楽しむシンプルなブラックジャックゲーム  

👉 [ここから遊べます](https://imshota1009.github.io/BlackJack/)

---

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## 🎮 ゲーム概要
- ブラウザですぐ遊べるシンプルなカードゲーム  
- HTML / CSS / JavaScript のみで構築  
- 勇者（プレイヤー）となり、ディーラーに挑戦！  

---

## ✨ 特徴
- 🏰 **ファンタジーUI**：中世風のフォントや配色を採用  
- 👹 **オリジナル絵札**：J/Q/Kの代わりにゴブリン(G)・エルフ(E)・ドラゴン(D)  
- 🎵 **BGM & 背景**：没入感のある音楽と背景画像を設定可能  
- 📱 **レスポンシブ**：PC・スマホ両対応  
- 🎲 **直感操作**：「ヒット」か「スタンド」だけのシンプル設計  

---

## 🃏 ルール
- **目標**：カードの合計を「21」に近づける  
- **カードの点数**
  - A（エース） → 1点 or 11点  
  - 2〜10 → 数字通り  
  - G/E/D（ゴブリン, エルフ, ドラゴン） → 10点  
- **行動**
  - 🖐️ **ヒット (Hit)**：カードを1枚引く（21超え＝バストで負け）  
  - ✋ **スタンド (Stand)**：その手札で勝負  
- **ディーラーのルール**：合計が17以上になるまでカードを引き続ける  

👉 **21を超えずにより近い方が勝利！**

---

## 🛠️ セットアップ方法
1. 本リポジトリをクローン or ZIPダウンロード  
2. `fantasy_blackjack.html` をブラウザで開く  
3. 即プレイ可能！  

---

## 🎵 BGMと背景画像
同じフォルダに以下のファイルを置いてください：  

- `fantasy_music.mp3`（BGM）  
- `fantasy_background.jpg`（背景画像）  

※ 好きな音楽や画像を使いたい場合はファイル名を合わせるか、ソースコードを編集してください。  

---

## 🎨 カスタマイズ方法

### 🔊 BGM変更
```html
<audio id="bgm" src="fantasy_music.mp3" loop></audio>
