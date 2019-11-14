# Djangoを使ったwebアプリケーションチュートリアル
* [Djangoドキュメント](https://docs.djangoproject.com/ja/2.2/)
* [gitを使った際、学校のプロキシを設定する方法](https://github.com/nkc-bakusi/jango-tutorial/wiki/Git%E3%81%AE%E4%BD%BF%E3%81%84%E6%96%B9)

## Djangoを使ったアプリのビルドの仕方
1. Pythonをダウンロード
2. Pythonのパスが通っていることを確認 コマンドプロンプトで `python --version` で3.?って出ればok
3. コマンドプロンプトでgithubからDLしてきたプロジェクトファイルの場所に移動 `cd C:\Users\user\Desktop\jango-tutorial\` ← desktopに置いたなら
4. pipを使ってDjangoをダウンロード `pip install django` 学校なら後ろに `--proxy proxy.denpa.ac.jp:8080` をつける
5. `python manage.py runserver`を打って
    ```
    Performing system checks...

    System check identified no issues (0 silenced).

    You have unapplied migrations; your app may not work properly until they are applied.
    Run 'python manage.py migrate' to apply them.

    11月 12, 2019 - 15:50:53
    Django version 2.2, using settings 'mysite.settings'
    Starting development server at http://127.0.0.1:8000/
    Quit the server with CONTROL-C.
    ```
こんな感じの文章が出てきたら成功