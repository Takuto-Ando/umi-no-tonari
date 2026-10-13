# 展示テスト — 生きもののつながり

架空データを使った、日本語のインタラクティブ展示テストページです。

**テストページ： https://takuto-ando.github.io/umi-no-tonari/**

- 架空のアザラシ4頭とUnknown、自作SVGイラストによる模擬映像。
- 個体クリック、プロフィール、映像と相関図の双方向選択、検索、再生・停止・シーク、登退場、表示切替。
- 名前・個体・関係・移動はすべて架空です。実AI推論・実カメラ映像ではありません。
- Unknownに名前や社会関係を付けず、近接や共起から「仲良し」などを断定しません。
- 手元の動画はブラウザ内で再生します。ファイルはアップロードされず、架空の名前を実動画へ重ねません。

このリポジトリにはGitHub Pages用のbuild済み静的テストファイルだけを配置しています。
研究データ、モデル、実動画、SQLite DB、Python backendは含みません。
React、TypeScript、Vite、Tailwind CSS、React Flowによる展示テストUIです。
GitHub Pagesでは同梱の架空データを使用し、APIは呼び出しません。

公開branchは`codex/20261013-pages`、配信元はbranchのrootです。
React Flowの画面内attributionは保持しています。
