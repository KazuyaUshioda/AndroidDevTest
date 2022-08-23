# AndroidDevTest
## GitにSSH接続する方法
1. `ssh-keygen -t ed25519`で公開鍵と秘密鍵のペアを作成
   - このとき、色々聞かれるけど全部エンターを押す
2. `cat ~/.ssh/id_ed25519.pub`で表示される公開鍵をコピー(全部まるっとコピーしてね)
3. コピーした鍵を[GitHub](https://github.com/settings/ssh/new)に置いておく