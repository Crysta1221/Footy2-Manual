# Footy2-Manual
## Footy2とは
なべじん さんによって作成されたHSP、C/C++向けのテキストエディットコントロールです。これにより、HSP スクリプトエディタのようなテキストエディットコントロールを配置することができ、プログラミング用のエディタとして利用できる拡張機能です。元は、有料でしたが、Footy2になってからは無料で提供されています。(クレジット参照)
現在、なべじんさんのホームページは閉鎖されており、Footy2のdll,拡張機能パッケージ、マニュアルなどが入手できなくなっています。(ただ、Open HSPのリポジトリに残っています。また、このプロジェクト内にもコントロールが使えるようにするためのこれら一式が同梱されています。
## このプロジェクトについて
このプロジェクトは、Hot Soup Processor(https://hsp.tv )で利用可能な拡張機能、Footy2 Edit Controlに関するドキュメント、サンプルコードなどGitHubにまとめたプロジェクトです。このプロジェクトは新しくFooty2を学習する方、新しい関数・命令を学習する方向けに作成しました。このプロジェクトのサンプル、リファレンスは、Open HSP リポジトリ内にあるFooty2のマニュアル、footy2を拡張機能にしたfooty.asを参照して作られたものであり、作者様公式のものではありませんのでご注意ください。
## 使用方法
主に二つの方法があります。お好きな方をお選びください。ただ、②の方法が確実なので特に理由がない場合、こちらをお勧めします。
- ① GitHubのリポジトリページからダウンロードする
   - Footy2-Manualの `< > Code` に移動し、Codeというボタンがあるので押します。一番下に、`Download ZIP` という項目がありますのでクリックします。これで、実行に必要なサンプルソースとパッケージを使用することが出来ました。
   - この方法では、不具合で古いパッケージを必要とする場合に、使用することができます。ただし、全ての依存関係はダウンロードされないため、実行時に失敗する場合があります。
- ② Git for Windows を利用し、コマンドプロンプト経由でダウンロードする
   - まず、Git for Windowsをダウンロードしてインストールします。インストールは特に設定をいじる必要はありませんが、インストール方法を検索するとスムーズにインストールできます。その後、Windowsのコマンドプロンプトを実行します。(`Win`+`R`キーで、「ファイル名を指定して実行」より`cmd.exe`と入力するか、Windowsのスタートボタンから、「コマンドプロンプト」と検索して実行します。)
次に、コマンドプロントの画面で `git`と入力し、英語の文字列( Git fot Windows ver. ・・・)が表示されるか確認してください。入力しても、`git`は実行可能なファイルではありませんなどのエラーが出た場合、インストールされていないか、関連づけが正常に行われていない場合があるので再インストールしてください。
実行に成功した場合、コマンドプロンプトに C:¥User¥<ユーザー名>¥ドキュメント > となっていると思うので、ディレクトリをダウンロードフォルダに移動します。
`cd C:¥Users¥<パソコンのユーザー名>¥Downloads`と入力して、ブラウザがダウンロードしたファイルを格納するフォルダに移動します。(わかりやすいため)
(例:ユーザー名が、Windowsなら、`cd C:¥Users¥Windows¥Downloads`と入力して、ダウンロードフォルダに移動します)
その後、`git clone https://github.com/kojigit13/Footy2-Manual`と入力し、Enterで実行します。自動的にこのプロジェクトに含まれるすべてのファイルがダウンロードされます。
   - この方法は全てのファイルをダウンロードするため、失敗する可能性が低くなります
## ビルド方法
- 前提: 
   - Windows 7 SP1以降がインストールされているPC
   - Hot Soup Processor 3(以降HSP3)がインストールされていること
   - (オプション) Win10 SDKあるいは、Visual C++ 2013以降 (Windows 10がインストールされているPCでは不要です。Win7に、
   `api-win-crt-runtime 1-1-0.dll`がインストールされていない場合、必要になる場合があります。Windows 10には該当するDLLがすでにインストールされているため、オプションは不要になります)
 
 HSP3は、HSPの公式ページ(https://hsp.tv )にてインストーラが配布されていますのでインストールしてください。オプションになっている Windows 10 SDK、Visual C++は、Microsoft公式ページで再頒布パッケージとして配布されており、無料でダウンロードできます。また、Visual Studio 2017以降をお持ちの方(Communityライセンスは無料)は、オプションのパッケージとしてVisual Studio Installer経由でインストールすることができます。
## ライセンス
- 当プロジェクト
   - このプロジェクトは、誰でも自由に関わることができます。また、同梱のソースファイルは、誰でも自由に改変し、再配布することができます。ただ、このソースをそのまま再配布する場合は、ソース上部のコメントを削除しないようお願いします。同梱のFooty 2モジュールに関しては、作者様のライセンスに則り、使用することができます。
- Footy 2
   - 
