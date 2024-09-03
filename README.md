# EaglerCraft Server

## setupguide

イーグルクラフトサーバーの作り方

まず、右上の「Fork」ボタンを押し、もう一度右下の「Fork」ボタンを押してこの作品をフォークします。  
そうしたら、`<> Code` のボタンを押し、`Codespaces` の `+` ボタンを押します。  
そしてしばらく待つと `[プレビュー] readme.md` と表示されます。これが表示されたら、下に表示されているターミナルに以下のコマンドを入力します。

1. 1つ目のコマンド:
    ```bash
    cd server && sudo java -jar server.jar
    ```
    このコマンドを実行すると文字が表示されるので、それが止まるまで待ちます。次に、左にあるソース管理というボタン（虫眼鏡マークの1つ下）を押し、`eula.txt` という名前のファイルをクリックします。  
    右側に表示される内容の中に `eula=false` という文字があるので、`false` の部分を `true` に書き換えます。  
    その後、左上にある水色の「コミット」ボタンを押し、緑のチェックボタンを押します。

2. 2つ目のコマンド:
    ```bash
    sudo java -jar server.jar
    ```
    このコマンドを実行します。

3. 3つ目のコマンド:
    ```bash
    cd bungee && sudo java -jar bungee.jar
    ```

    次に、ポート設定に移ります。ポートというボタンを下の方から探し、押します。  
    青い「ポートの追加」ボタンを押し、`8081` と入力します。さらにもう一度「ポートの追加」ボタンを押し、`25565` と入力します。  
    ポート `8081` の部分を押し、地球マークを押すことで開くことができます。

これで準備が完了し、サーバーに入ることができます。
