# zenn-content

Zenn 公開用リポジトリ。`articles/` にmarkdownを置き、ZennのGitHub連携で自動公開する。

## 使い方
- 記事プレビュー: `npm install` → `npm run preview`（<http://localhost:8000>）
- 新規記事: `npm run new:article`
- 公開: 記事の frontmatter を `published: true` にして `git push`

執筆・匿名化チェックは BuildLog パイプライン（`../SOURCE.md` / `../../../pipeline/`）に従う。
