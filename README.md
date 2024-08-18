# Learn OS in 3days

## そもそもOSとは？

OS（オペレーティングシステム）は、ハードウェアを制御し、OS以外のソフトウェアに対して基本的な機能を提供するソフトウェアである。代表的なものとして、Linux、Windows、macOSなどがある。ソフトウェアを使う以上は逃れることのできないほどOSというのはとても身近な存在だが、何をもってOSとするかという厳密な定義は存在しない。そもそもOSがなくてもソフトウェアを動かすことはできる。しかし、当たり前だがソフトウェアはハードウェアの上で動作するため、その場合はハードウェアを直接制御するための実装が必要になる。またそのソフトウェアだけではなく、その他のソフトウェアも動作するとなると、複数のソフトウェア間でハードウェアという共通のリソースを共有するための仕組みが必要になる。これらの機能をソフトウェアを作るたびに実装するとなると非常に手間がかかる。そこで、それらの機能をまとめて提供するのがOSである。しかし、どの機能を提供するかはOSによって異なるため、何をもってOSと呼ぶのかという厳密な定義は存在しないわけだが、現代のOSであれば基本的な機能は大体共通しているため、それらを学ぶことでOSについての理解を深めることができる。

## OSの役割

OSの役割には大きく２つあり、ハードウェアリソースの管理と、ソフトウェアの実行の制御を行う。現代のコンピュータには、CPU、メモリ、ストレージ、その他の入出力装置などがあり、それらのハードウェアリソースを管理するために、メモリ管理、ファイル管理、入出力制御を行う。また、ソフトウェアの実行を制御するために、プロセス管理も行う。

- メモリ管理
- ファイル管理
- 入出力制御
- プロセス管理
