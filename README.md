---
title: ITNAS TEST1002
emoji: 💻
colorFrom: yellow
colorTo: green
sdk: gradio
sdk_version: 4.44.1
app_file: app.py
pinned: false
---

※セキュリティ面から組織用のプライベートモードでスペースを稼働させています。

下記より組織に参加し、デモページにアクセスいただけます！

## 1.下記リンクへアクセス

v1 デモページ(Hugging faceのログインもしくはアカウント作成をリンク先で求められます)

[](https://huggingface.co/organizations/SANTIAI/share/RNKhmvsbNFYOgHWiXeFtpHleYmPRtfklCZ)

## 2.ITNAS TEST1002というスペースをクリック

 ログイン後、オーガナイゼーションに加わると下記のようなページが表示されるかと思います。

すでに参加している３アカウントは僕のサブ垢です。

完成次第いつでもこのリポジトリの所有権は譲渡可能です。

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/11790adb-e888-466b-93bd-39461663951d/dac19c1b-e49c-48f0-95dc-29bdde523d1d/image.png)

スペースにアクセスすると、このようなUIが開くかと思います。

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/11790adb-e888-466b-93bd-39461663951d/045b93b3-af13-4eb6-8b2e-1c1640a45e41/image.png)

セットアップに必要な手順は３つです。

**OpenAIのAPI入力、Neo4jのパスワード入力(下記参照)、使用モデルの選択**

現在僕のneo4j インスタンスが稼働しています。

下記パスワードのご入力とOpenAIのAPI取得をお願いいたします。

```jsx
_jhAjvotP0ru3z26Ad2nYHW93ZEGYZqZGeIHmBFeu9YHXTzEvOzz09g4pqyCmRQecOy0_XzUBXnbgEZ8Zy_tiY
```

モデルはプルダウンよりご選択いただけます。※graph_documents (1).pklが最新

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/11790adb-e888-466b-93bd-39461663951d/3931341a-b8ed-48d8-8edb-51135e8bfdc5/image.png)

上記3点を行った後、Setupをクリックします。右のStatusに成功と表示されれば完了です。

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/11790adb-e888-466b-93bd-39461663951d/55227e69-d536-4dc2-8de7-a3220c6c0e52/image.png)

今はテスト用に少量のデータのみベクトル化したpklファイルをアップしておりますので

質問も動作確認用としてテンプレを並べております。

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/11790adb-e888-466b-93bd-39461663951d/f3ed368c-5816-4812-b92d-be4ac60a554d/image.png)

会話のリフレッシュボタンの下に**ログを保存する**ボタンがあり

そちらクリックいただくとこのようにテキストファイルで保存することができます。

このQ&Aも今後データセットに回せればと思っています。
