# guidance_google_search_example
Sample of combining guidance and google custom search api.

## Overview
guidanceからgoogle search apiを呼び出すプログラムのサンプル


## Environment
- Windows 10 Home
- pyenv
  - Python3.10.9

## Usage

### 環境変数の設定
.envファイルを作成

```bash
OPENAI_API_KEY="" # OpenAI API KEYを指定
GOOGLE_CUSTOM_SEARCH_API_KEY="" # Google Custom Search API KEYを指定
CUSTOM_SEARCH_ENGINE_ID="" # Google Custom Search EngineのIDを指定
```

### 環境構築
```bash
pyenv local 3.10.9
python -m venv venv
venv/Script/activate
(venv)pip install -r requirements.txt
```

### 実行
```bash
(venv)jupyter lab
```



## Author
[T-Sumida]()