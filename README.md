# eventtime

Responsive event timekeeper web app for smartphone and desktop browsers.

## Usage

1. Open the GitHub Pages URL for this repository (or open `index.html` locally).
2. Enter a target time.
3. The page shows live current time and the signed difference:
   - `+HH:MM:SS`: current time is ahead of target.
   - `-HH:MM:SS`: current time is behind target.

## GitHub Pages

The workflow at `.github/workflows/deploy-pages.yml` publishes the repository root as a static site on pushes to `main`.
Mobile-friendly event timekeeper web app for GitHub Pages.

## GitHub Pages

After pushing to `main`, GitHub Actions deploys the static site with `.github/workflows/deploy-pages.yml`.

Site URL:

- `https://kumapuni.github.io/eventtime/`

## Local preview

Open `index.html` in your browser, or run a static server:

```bash
cd <project-directory>
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
スマホでもパソコンでも使いやすい、イベント用タイムキーパーの静的Webアプリです。

## 機能

- 現在時刻をリアルタイム表示
- 入力した時刻との差分を表示
- 黒背景の見やすいレスポンシブUI
- 数字は DIN Next 優先のフォント設定
- GitHub Pages で公開可能

## 使い方

1. `index.html` を公開します。
2. ブラウザで開きます。
3. 時刻を入力して「開始」を押すと、現在時刻との差分が更新されます。

## GitHub Pages の設定

1. リポジトリの **Settings** を開く
2. **Pages** を選ぶ
3. **Build and deployment** で **Deploy from a branch** を選ぶ
4. Branch に `main` または公開したいブランチを選ぶ
5. Folder に `/ (root)` を選ぶ
6. 保存すると、数分後に公開 URL が表示されます

## 備考

- このアプリは静的ファイルのみで動作します。
- DIN Next が端末にない場合は、近い代替フォントへフォールバックします。
