# Codename-BallOS
Codename BallOS プロジェクトについて 日本語版
最終更新日:西暦2025年9月15日午後
※あらかじめコードからご覧ください。
こんにちは。初めての方は初めまして。私はマシュマロです。
この度、Codename BallOS プロジェクトの創設を宣言する事になりました。
初めてのOSプロジェクト創設の為、いろいろ不安定な部分がある事はご了承くださると幸いです。
また、ライセンスは「Codename BallOS License」(独自ライセンス)を利用する予定です。
ライセンス情報は、別の.mdファイルに掲載しますので、ご確認ください。
その他、搭載する予定の機能、アプリケーションなどとその詳細は以下の通りです。
# 計画
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
　　　 ⋆Tenp
　　　 ⋆personalfiles
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
　　
# 機能などについて
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
　　※複合ライセンス統合版、または機能パックとしての搭載。
# アプリケーションについて
　・Surfin Net系アプリケーション
　　
　　　
