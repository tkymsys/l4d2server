# 概要
todo

# 利用方法
```
// サーバーの導入
sh install.sh

// サーバーの起動
sh start.sh

// サーバーの停止
sh start.sh

// 環境の破棄
// ただしvolume配下のファイルは削除されないため、それらも不要であれば手動にて削除してください。
sh clean.sh
```

# コマンドメモ
```
docker-compose down --rmi all --volumes
docker system prune -f
winpty docker exec -it l4d2server_setup bash
winpty docker exec -it l4d2server_boot bash
```

# 参考
- https://xrnss.hatenablog.com/entry/2018/06/28/070115
- https://developer.valvesoftware.com/wiki/SteamCMD
