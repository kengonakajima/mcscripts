# mcscripts
Minecraft admin scripts



## snapshot

新しい Amazon Linux 2017.03 でのバックアップ復帰テスト

- tar ixf minecraft_game_snapshot_2017-05-17_09h26.tar.bz2   # => minecraft dir
- useradd minecraft
- mv minecraft /usr/local/games
- cd /usr/local/games
- chown -R minecraft minecraft
- chgrp -R minecraft minecraft
- /usr/local/games/minecraft start

## インスタンス起動時の自動起動(init.d)
TODO

