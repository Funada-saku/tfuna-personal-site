# Personal Site

Astroで作った静的な個人サイトです。プロフィール、リンク、制作物、メモ、更新履歴を1ページにまとめます。

## 使い方

```powershell
npm.cmd install
npm.cmd run dev
```

内容は `src/pages/index.astro` の配列を書き換えると更新できます。

## ビルド

```powershell
npm.cmd run build
```

生成物は `dist/` に出ます。Cloudflare PagesやGitHub Pagesに置けば、サーバー代なしで公開できます。

## 公開先の例

- Cloudflare Pages: Build command `npm run build`, Output directory `dist`
- GitHub Pages: GitHub Actionsで `npm run build` し、`dist` をPagesに公開
