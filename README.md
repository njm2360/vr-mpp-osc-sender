## VRChat用連打ツール

### 機能

- OSCで`/input/useRight`をひたすらトグルする(0と1を交互書き込み)
- OSC送信先のポートを変更可能
- VRChat Quick LauncherのOSCに入力する値を自動生成

### 使い方

1. OSC送信ポートを決めます。この値は同一PC内で重複しないように選択してください
   - 1窓しか起動しない場合はデフォルトのままでOKです

1. VRChat Quick LauncherのOSCに`Quick Launcher OSC setting value`の文字列を張り付けて起動します
   - デフォルトのポート番号(9000番)のままの場合は何も入力しなくてOKです

1. 送信間隔を決めて`Send OSC`にチェックを入れている間、OSCで`/input/UseRIght`をトグルして送信し続けます

### 注意事項

- OSCの送信先はlocalhostのみです。他のPCには送れません。
- このツールを使用して生じたいかなる損害については責任を負いかねます。
