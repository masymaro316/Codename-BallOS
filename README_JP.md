# Codename-BallOS
Codename BallOS プロジェクトについて 日本語版
最終更新日:西暦2025年9月15日午後
※あらかじめコードからご覧ください。
こんにちは。初めての方は初めまして。私はマシュマロです。
この度、二千二十五年八月二十九日(2025年8月29日)に、Codename BallOS プロジェクトの創設を宣言する事になりました。
初めてのOSプロジェクト創設の為、いろいろ未確定な部分がある事はご理解してくださると幸いです。
また、ライセンスは「Codename BallOS License」(独自ライセンス)を利用する予定です。
ライセンス情報は、別の.mdファイルに掲載しますので、ご確認ください。
その他、搭載する予定の機能、アプリケーションなどとその詳細は以下の通りです。
# 計画、決定事項
・カーネル
　カーネルは、モノシリック、マイクロ、ハイブリットの三つのカーネルの版を用意する。
・開発期間など、開発段階
　・開発段階
　　以下の段階となる。
　　・正式リリース前
　　　⋆α:最初の段階。基本的な機能やカーネルを成熟させる。
　　　⋆β:主要な機能の追加。(Surfin Net Browser、インターネット接続、EFI対応、GUI追加など)
　　　⋆Final Development Release/FDR:残りのほぼすべての機能を実装する。
　　　⋆Release Candidate/RC:カーネル決定、正式名称決定、最終調整など。
　　・正式リリース後
　　　⋆β:1.1以降のバージョンで実装する予定の段階。ほぼすべての部分を実装する。
　　　⋆Release Candidate/RC:こちらも1.1以降で実装する予定。複数のタイプを用意し、それを選別した後、次のRC2以降となる。
　　　⋆正式版:完成した安定板。
　　・開発スケジュール(予定)
　　　⋆コミュニティ創設宣言:2025年8月29日
　　　⋆V0.1α開発開始:2026年3月18日
　　　⋆V0.1αリリース:2026年4月30日
　　　⋆β(v0.1β)リリース:2029年12月28日～2030年2月16日
  　　⋆Final Development Release/FDR(v0.1 Final Development Release)リリース:2033年7月10日
　　　⋆Release Candidate/RC(v0.1 Release Candidate)リリース:2035年6月29日
　　　⋆正式リリース:2036年5月31日
　・コードネーム(正式リリース後)
　　基本的に韓国、台湾、日本の三国の都市から決定する。マイナーバージョンはつけることが多いと思われるが、無い可能性もある。
　  また、開発者向けの内部コードネームとしてスイーツの名前が付いたコードネーム(主にアイスクリームの名前)も決定する。ただ、マイナーバージョンは内部コードネームは制定しない可能性がある。
　　・決定したコードネーム
　　　⋆1.0:"Ulsan"(内部コードネーム:Cookkie & Cleam)
　　　⋆1.1:"Sejong"
　　　⋆2.0:"Tainan"
　　　⋆3.0:"Ube"
・ディレクトリ、ファイルの表記形式について
　このようになる。
  0:/user/desktop/Test
・標準のインストールドライブのファイル
　⋆OSsys
　　⋆DE
　　 ⋆Setting
　　 ⋆Driver
      ⋆Sys
      ⋆Add
　　 ⋆Temp
　　 ⋆SysThema
　　 ⋆feature
　　　⋆raw
　　　⋆Add
    　　⋆pack
　　⋆ext
　　⋆User
　　 ⋆Username 
　　 　⋆Thema
　　　 ⋆Desktop
　　　 ⋆Setting
　　　 ⋆Temp
　　　 ⋆personalfiles
　・対応言語(現時点)
　　以下の通り。方言も対応する予定。
　　⋆主要言語
　　　韓国語、英語(英国)、日本語
　　⋆準主要言語
　　　米英語、フランス語、ロシア語、中国語、スペイン語
　　⋆準々主要言語
　　　ドイツ語、イタリア語、ポルトガル語、チェコ語、スロバキア語、ハンガリー語、トルコ語、ポーランド語
　　⋆対応言語
　　　ラテン語、アラビア語、ギリシャ語、ポルトガル語(ブラジル)、ベーシック英語、エスペラント、トキポナ
　・システム要件
　・エディションなど 
　　⋆Long Support Release/LSR:最低で12年のサポートを提供する長期サポートバージョン。
　　⋆compound Licence integrate Edition(複合ライセンス統合版):すべてのライセンスパックを含んだエディション。
　　⋆Linux Edition、またはGNU/Linux Edition:Linuxベースだが、基本的には別プロジェクトとして創設予定のferenomの使用を推奨。
　　⋆Codename BallOS Mobile:モバイル版。IPhoneや多くのAndroid端末に対応する予定。こちらもLinux版を用意するが、創設予定のferenom Mobileの使用を推奨。
# コマンドについて
　・fdilist
　 ファイル、ディレクトリを一覧表示する。
　　⋆ -di
　　　オプション。ディレクトリのみ表示。
　　⋆-f
　　　ファイルのみ表示。
　　⋆-t
　・fdimove
　　ファイル、ディレクトリを移動する。
　・fdiedit
　　ファイル、ディレクトリを編集する。
　　　⋆-n
　　　　名前を変更する。
　　　⋆-e
　　　　パスワードを付与する。
　　　⋆-c
　　　 ファイルを隠蔽状態にする。(GUI使用時限定)
　・fdidel
　　ファイル、ディレクトリを削除する。
　・diCreate
 　 ファイル、ディレクトリを作成する。
   ⋆
# 機能などについて
　・キーボード
　　⋆Codename BallOS IME
　　　多くの言語の変換をサポートする予定。
　　⋆MozcなどGoogle IMEのオープンソース版※
　　　機能パックで対応予定。
　・対応ファイルシステム
　対応ファイルシステムについては、以下の通りとなります。
　　⋆CBOFS/Codename BallOS File System(独自ファイルシステム。後述に詳細を掲載する暗号化機能など搭載。)
　　⋆FAT(VFATオプション可能、FAT12、FAT16、FAT32オプション可能。、38年問題への対応あり。)
　　⋆exFAT(疑似対応?、38年問題への対応あり。)
　　⋆NTFS(OSで新規にフォーマットは不可。読み書きは可能。)
　　⋆HFS(新規でのフォーマットは不可にする可能性あり。)
　　⋆HFS＋(同上)
　　⋆APFS(同上)
　　⋆ext※(非推奨。38年問題への対応あり?)
　　⋆ext2※(38年問題への対応あり。)
　　⋆ext3※(同上)
　　⋆ext4※
　　⋆Xiafs※(非推奨。)
　　⋆XFS※
　　⋆Btrfs※
　　⋆ZFS※
　・対応ブートローダー
　　⋆Codename BallOS Loader
　　⋆GRUB※
　・対応予定デスクトップ環境
　　⋆Codename BallOS Desktop Enviroment
　　⋆Codename BallOS Mobile Desktop Enviroment
　　⋆Codename BallOS Custom Desktop Enviroment
　　　他のOSに類似したUIを利用したり、作成したりできる。
　　⋆CDE※
　　⋆GNOME※
　　  ⋆GNOME 1.4※
　　  ⋆GNOME 2.26※
　　  ⋆GNOME 3.38※
　　⋆Ubuntu Desktop※
　　⋆KDE1~6※
　　⋆Cinnamon※
　　⋆Budgie※
　　⋆LXDE※
　　⋆LXQt※
　　⋆MATE※
　　⋆Unity※
　　⋆Xfce※
　　⋆Pantheon※
　　⋆GNUstep※
　　⋆UKUI※
　  ⋆Trinity※
　※複合ライセンス統合版、または機能パックとしての搭載。
# アプリケーションについて
　・Apatch OpenOffice?
　　Apatchとの会談などを通じて決定する予定。
　・Surfin Net系アプリケーション
　　⋆Surfin Net Browser
　　⋆Surfin Net Mail
　　⋆Surfin Net Messenger
　・Codename BallOS File Manager
　・Codename BallOS Archiver
　　多くの圧縮形式を圧縮、解凍可能にする予定。
　・Codename BallOS Notepad
　・Codename BallOS Calculator
　・Codename BallOS Calender
　　リマインダー機能搭載予定。
　・Codename BallOS Application Manager
　　配信されたアプリケーションのダウンロード、インストール、アンインストールの支援と、インストールされたアプリケーションの一覧を確認したり、アンインストールしたアプリケーションを記録するなどができる。
　・Codename BallOS image Writer
　　USBに、DD書き込みや直接書き込みなどを行える。もちろんCD、DVDなども可能。また、イメージのチェックサムの確認と比較も可能で、チェックサムが一致しているか確認したいイメージファイルと、md5、SHA-128、SHA-256、SHA-512のいずれかのサムが記載されたファイルを選択して比較する。
　・Codename BallOS アンチウィルス
　・Codename BallOS Virtual Machine
　　image Writerのようなチェックサム比較機能搭載。また、エミュレータモードとして別のアーキテクチャのエミュレートも可能。
  ・Codename BallOS Studio
　　多くのプログラム言語のコンパイルなどを行ったり、作曲や作画などの制作を行うことができる。対応言語は後で掲載。
　・Codename BallOS BroadCast
　　専用に制作された無料の番組を視聴、配信できる。BSのような特別チャンネルも用意可能。
