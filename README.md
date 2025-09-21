# my_ruff_settings
目的: 自分好みのruffのルールを育てていく


- 仮想環境
  - ubuntu
    - 作成: `python -m venv .venv`
    - 起動: `source .venv/bin/activate`
- パッケージをインストールする際はrequirements.txtに書いて、そこを参照してインストール
- インストールしたら、requirements.lock.txtにバージョンも含めて書き出す

【例】
```
1. requirements.txtの末尾に、追加したいライブラリ名を追記
2. pip install -r requirements.txt
3. pip freeze > requirements.lock.text
```