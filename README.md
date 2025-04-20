# 生成・校閲アプリケーション

このアプリケーションは、OpenAI GPT-4o-mini APIを使用して、テキスト生成の機能を提供するStreamlitベースのウェブアプリケーションです。

## 機能

- **テキスト生成**: 指定したトピックに基づいて、メルマガ・SMS・SNS投稿などのテキストを生成
- **テキスト校閲**: 入力されたテキストの法的確認、文法、スペル、表現などを改善


## インストール方法

1. リポジトリをクローンする：
```
git clone https://github.com/yourusername/text-generation-app.git
cd text-generation-app
```

2. 依存パッケージをインストールする：
```
pip install -r requirements.txt
```

3. `.env`ファイルを作成し、OpenAI APIキーを設定する：
```
OPENAI_API_KEY=your_openai_api_key_here
```

## 使用方法

1. Streamlitアプリを起動する：
```
streamlit run app.py
```

2. ブラウザで`http://localhost:8501`を開く

3. サイドバーから使用したい機能を選択し、必要なパラメータを入力する

4. 「生成する」「校閲する」などのボタンをクリックして結果を得る

## 必要条件

- Python 3.8以上
- Streamlit 1.34.0
- OpenAI Python SDK 1.6.1
- python-dotenv 1.0.0
- 有効なOpenAI APIキー

## 注意事項

- このアプリケーションはOpenAI APIを使用するため、APIの使用料金が発生します
- 生成されたテキストは参考用途にのみご利用ください
- APIキーは`.env`ファイルに保存し、GitHubなどの公開リポジトリにアップロードしないでください

## 作者

近藤　智行
