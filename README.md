# bikeshare-research-fund

**シェアサイクル研究基金（Share Cycle Research Fund）** の公式サイトのリポジトリです。

シェアサイクルに関する研究に取り組む学生（高校生・高専生・大学生・大学院生）の学会参加費・渡航費を、個人として応援する小さな基金です。

A small personal fund supporting students in Japan who research bikeshare / bike sharing, covering conference fees and travel expenses.

## サイト

- 公開URL：https://kg-b0mbe.github.io/bikeshare-research-fund/
- 応募フォーム：[Googleフォーム](https://docs.google.com/forms/d/e/1FAIpQLSf2jOJY9yilhlvbJSAlVH2h4HnBgTDwcKtL0n9CMt3cU_EALQ/viewform)

## 基金の概要

| 項目 | 内容 |
|---|---|
| 支援額 | 1件 5万円 または 10万円（研究内容などを踏まえて決定） |
| 使途 | 学会・研究会の参加費、発表のための渡航費・交通費・宿泊費など |
| 対象 | シェアサイクルに関する研究に取り組む学生（高校生〜大学院生）。分野不問 |
| 形式 | 運営者個人からの贈与（返済不要） |
| 応募 | 公募のほか、運営者からのお声がけ・他薦も歓迎 |

## リポジトリ構成

```
index.html   … サイト本体（単一ファイル、依存なし）
README.md    … このファイル
```

HTML・CSSは `index.html` に全部入りです。ビルド不要で、そのままGitHub Pagesで公開できます。

## 論文カードの追加方法

サイトの「シェアサイクル研究を読む」セクションは、`<article class="paper-card">` ブロックのコピーで増やせます。

```html
<article class="paper-card">
  <div class="tags"><span class="tag">テーマ</span><span class="tag">国・都市</span></div>
  <h3>論文タイトル</h3>
  <p class="meta">著者／掲載誌（年）</p>
  <div class="stats"><span class="stat">掲載誌の位置づけなど</span></div>
  <p class="memo">ひとことメモ（この論文のどこが面白いか）</p>
  <a class="read" href="論文のURL" target="_blank" rel="noopener">論文を読む →</a>
</article>
```

## 運営

- 本基金は運営者が個人として行う活動であり、特定の企業・団体とは無関係です。
- お問い合わせ・論文の推薦は応募フォームからお願いします。

## License

- サイトの文章・「ひとことメモ」等のコンテンツ：© Keiji Yamada. All rights reserved.
- 紹介している各論文の著作権は、それぞれの著者・出版社に帰属します。
