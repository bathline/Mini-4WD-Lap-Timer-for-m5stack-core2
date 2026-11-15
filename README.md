デバイス	用途
M5Stack Core 2	計測処理、LCD表示、ボタン操作
M5Stack用ToF-90°測距センサーユニット（Unit Mini ToF-90° / U196、VL53L0X搭載）	車体を開く

プロジェクト	使用環境
開発ツール	PlatformIO（VS Code拡張またはCLI）
要素	m5stack-core-esp32
フレームワーク	Arduino
ライブラリ	M5Unified、Pololu VL53L0X
ライブラリはplatformio.iniの設定に従ってPlatformIOが取得されます。

・
リポジトリを取得し、PlatformIOでプロジェクトを開きます。M5StackをUSBで接続して、プロジェクトのディレクトリで次回を実行してください。

git clone https://github.com/bathline/Mini-4WD-Lap-Timer-for-m5stack-core2.git
cd Mini4WDLapTimer

# ビルド
pio run

# M5Stackへ書き込み
pio run -t upload
VS CodeのPlatformIOからビルド/アップロードを実行することもできます。
