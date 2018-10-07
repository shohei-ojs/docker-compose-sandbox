# Python 2.7 イメージを使って、イメージ構築を始める
FROM python:2.7
# 現在のディレクトリ . を、イメージ内のパス /code に加える
ADD . /code
# 作業用ディレクトリを /code に指定する
WORKDIR /code
# Python の依存関係（のあるパッケージを）インストールする
RUN pip install -r requirements.txt
# コンテナが実行するデフォルトのコマンドを python app.py にする
CMD python app.py