## コンテナランタイムKata Conteiner

Dockerはコンテナランタイム  
Linuxコンテナは数コマンドで作れる  


Dockerはこのコマンドを抽象化している
他のコンテナランタイムについて

OCI について
CRI について

chroot 新たにrootとするディレクトリ rootディレクトリ変更後に実行するコマンド

Kata Conteinerとは
* 軽量の仮想マシン(KVMベース)
* コンテナと同等の速度を実現
* 分離レベルが高い
* OCI、CRI サポート
* コンテナの速度とVMの分離を両立

* Agent
* Runtime
* Proxy
* Shim
* Kernel
* QEMU

VM BootしながらコンテナイメージとVolumeを並行作成してhotplug
