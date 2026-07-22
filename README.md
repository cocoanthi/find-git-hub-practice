# FindGitHub Practice

GitHub機能の実践・学習を目的とした、Ionic FrameworkとAngularで構築されたモバイルフォーカスのWebアプリケーション。

## 📱 概要

このプロジェクトは、**Ionic Angular**で構築されたモバイルWebアプリケーションです。GitHub統合とモバイルWeb開発の実践学習を目的としており、最新のWebテクノロジーとレスポンシブデザインを組み合わせています。

## 🛠️ 技術スタック

- **フレームワーク**: [Angular](https://angular.io/) v20.0.0
- **モバイルフレームワーク**: [Ionic](https://ionicframework.com/) v8.0.0
- **言語**: TypeScript (63.6%)
- **スタイリング**: SCSS (14.5%)、HTML (15.8%)
- **スクリプト**: JavaScript (6.1%)
- **モバイル統合**: [Capacitor](https://capacitorjs.com/) v7.4.2

### 主な依存パッケージ
- Angular コアモジュール（animations、forms、router、platform-browser）
- Ionic Angularコンポーネント
- RxJS リアクティブプログラミング用
- Capacitor ネイティブモバイル機能用（app、haptics、keyboard、status bar）

## 📦 プロジェクト構成

```
find-git-hub-practice/
├── src/                          # ソースコード
├── resources/                    # アプリリソース（アイコン、スプラッシュ画面）
├── angular.json                  # Angular CLI設定
├── ionic.config.json            # Ionic設定ファイル
├── capacitor.config.ts          # Capacitor設定
├── tsconfig.json                # TypeScript設定
├── karma.conf.js                # テストランナー設定
├── package.json                 # 依存パッケージとスクリプト
└── .eslintrc.json              # ESLintルール
```

## 🚀 はじめ方

### 必要な環境
- Node.js と npm
- Ionic CLI（オプション）: `npm install -g @ionic/cli`
- Angular CLI: `npm install -g @angular/cli`

### インストール

```bash
# リポジトリをクローン
git clone https://github.com/cocoanthi/find-git-hub-practice.git
cd find-git-hub-practice

# 依存パッケージをインストール
npm install
```

### 利用可能なスクリプト

```bash
# 開発サーバーを起動
npm start
# または
ng serve

# 本番ビルド
npm run build

# ウォッチモード（変更時に自動再構築）
npm run watch

# テスト実行
npm test

# リント実行
npm run lint
```

## 🧪 テスト

このプロジェクトはユニットテストに Karma と Jasmine を使用しています：

```bash
npm test
```

テスト設定は `karma.conf.js` と `tsconfig.spec.json` で管理されています。

## ✨ コード品質

- **リント**: ESLint with Angular固有のルール
- **コードスタイル**: EditorConfig対応（`.editorconfig`）
- **ブラウザサポート**: `.browserslistrc` で定義

## 📱 モバイルサポート

このプロジェクトはCapacitorを使用してネイティブモバイル機能を統合しており、以下が可能です：
- アプリライフサイクル管理
- ハプティックフィードバック
- キーボード制御
- ステータスバーカスタマイズ

## 📝 設定ファイル

- **`angular.json`**: Angular CLIのビルドと実行オプション
- **`ionic.config.json`**: Ionicフレームワークの設定
- **`capacitor.config.ts`**: Capacitorプラグイン設定
- **`tsconfig.json`**: TypeScriptコンパイラオプション
- **`.eslintrc.json`**: ESLint設定
- **`.browserslistrc`**: ブラウザ互換性ターゲット

## 🤝 貢献

このプロジェクトへの貢献を歓迎します：
1. リポジトリをフォーク
2. フィーチャーブランチを作成
3. 変更をコミット
4. プルリクエストを提出

## 📄 ライセンス

このプロジェクトはIonic Frameworkスターターテンプレートをベースにしています。

## 🔗 参考リンク

- [Ionic ドキュメント](https://ionicframework.com/docs)
- [Angular ドキュメント](https://angular.io/docs)
- [Capacitor ドキュメント](https://capacitorjs.com/docs)
- [GitHub ドキュメント](https://docs.github.com)

---

**最終更新**: 2025年8月
