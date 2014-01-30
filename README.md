# btsync-api
jsonの表示に[jq](http://stedolan.github.io/jq/)を利用しています。

## 使い方
引数にオフィシャルのメソッド名をくわせる。
>btsync-api get_os <br />
btsync-api get_version <br />
btsync-api get_folders SECRET <br />
btsync-api get_secrets SECRET <br />
btsync-api add_folders PATH SECRET

オフィシャルには存在しないメソッド
>btsync-api gen_secrets

## mac
mac用のinitスクリプトなどなど
