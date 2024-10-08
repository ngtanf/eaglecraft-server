# イーグルクラフトサーバーの作り方


1. まず、右上の「Fork」ボタンを押し、もう一度右下の「Fork」ボタンを押してこの作品をフォークします。  
  そうしたら、`Code` のボタンを押し、`Codespaces` の `+` ボタンを押します。  
  そしてしばらく待つと `[プレビュー] readme.md` と表示されます。これが表示されたら、下に表示されているターミナルに以下のコマンドを入力しエンターキーで実行します。

    ```bash
    cd server && sudo java -jar server.jar
    ```

3. このコマンドが打てたら、文字が出てくるのでそれが止まるまで待ち、
  左にあるソース管理というボタン(虫眼鏡マークの1つ下)を押し、`eula.txt` をクリックします。
  そうすると、右の方に ~省略~ `eula=false` という文字が出てくるので `false` の部分を `true` に書き換えます。
  そうしたら、左上にある水色の　コミット　という緑のチェックボタンを押します。
  そして以下のコマンドを入力し実行します。

    ```bash
    sudo java -jar server.jar
    ```

5. そうしたら、ターミナルの左の方にある　`+`　ボタンを押しそこで、以下のコードを入力します。
 
    ```bash
    cd bungee && sudo java -jar bungee.jar
    ```
    

4. 次に、ポート設定です。
    ターミナル の隣りにある、ポートというボタンを押します。  
    青い「ポートの転送」ボタンを押し、`8081` と入力します。さらにもう一度「ポートの追加」ボタンを押し、`25565` と入力します。  
    ポート `8081` の部分を押し、右側にある地球マークを押すことで開くことができます。

これで基本的な準備は完了しました。マルチプレイ を押して、最初から入っているサーバーのアドレスを共有すれば、みんなが入ることができます。
