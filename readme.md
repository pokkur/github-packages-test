
## 手順メモ


1. private:true設定でgit設定
2. package.jsonへ　`publishConfig` フィールドを追加
3. privateではダメだった
    ```
    npm ERR! Remove the 'private' field from the package.json to publish it.
    ```