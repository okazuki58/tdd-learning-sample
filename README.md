# 🧪 TDD Learning Sample

## 📚 概要

このリポジトリはTDD（テスト駆動開発）とGitHub Actionsを実践的に学習するためのものです。

各課題にはすでにテストが用意されています。  
あなたは、そのテストが通るようにコードを実装してください。

---

## 🚩 学習の流れ

1. リポジトリをクローンして環境をセットアップする
2. GitHubの[Issue](https://github.com/okazuki58/tdd-learning-sample/issues)を確認し、課題内容を理解する
3. テストが通るように`src/`の中にコードを実装する
4. コードを書いたらコミットしてGitHubにPushする
5. GitHub Actionsで自動テストが実行され、結果が表示される
6. テストが成功したら課題完了、次の課題へ進む

---

## 🛠️ セットアップ方法

以下を順番に実行してください。

```bash
git clone <あなたのリポジトリURL>
cd tdd-learning-sample
npm install
```

### テストの実行

```bash
npm test
```

---

## 🚨 テスト失敗時の対処方法

テストが通らない場合は、エラーの内容をよく読み、問題箇所を修正して再度テストを実行してください。

---

## 🧑‍💻 使用している技術

- JavaScript (Node.js)
- Jest（テストフレームワーク）
- GitHub Actions（CI/CD）

