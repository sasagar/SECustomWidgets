# LOCALTIME

Show the local time as a widget.  
ローカルタイムを表示させるウィジェットです。

## How to use

As a [global README file](../../../), put each contents of the files to the every tabs.  
LOCALE file should be ignored. That is just for development.

親階層の [README](../../../) の通り、各ファイルの内容を、各タブにコピーして下さい。
LOCALE ファイルは無視して下さい。開発用のファイルです。

## Points

- When the widget size changed, the widget text area does not expand all the time. Save and reload the editor will be fix this.
- If you want to set the background transparent, set the background color `rgba(0,0,0,0)` .
- For this version, the locale is only available for `en-US` and `ja-JP`.
- Text to show the timezone can be blank. The text on this field would be added and shown at the end of the time.

- ウィジェットのサイズを変更したときに、テキストの表示エリアのサイズが変わらないことがありますが、保存してから再読込すると直ります。
- 背景を完全に透過したいときには `rgba(0,0,0,0)` を Background color に設定して下さい。
- 現在サポートされているロケールは `en-US` と `ja-JP` のみです。
- Text to show the timezone は不要なら空欄にできます。このフィールドの内容は時間の表示の最後に付く文字になります。

## Format

Format should be written with following format texts.

Format 欄は以下のフォーマットに従って記載できます。

- `%YYYY%`: 4 digits year / 4 桁年（ex. 2016）
- `%YY%`: 2 digits year / 2 桁年（ex. 16）
- `%MMMM%`: Full month name / 月の長い表記、日本語では数字のみ、英語では March など（ex. March / (for ja-JP) 3）
- `%MMM%`: Short month name / 月の短い表記、日本語では数字のみ、英語では Mar.など（ex. Mar / (for ja-JP) 3）
- `%MM%`: 2 digits month / 2 桁月（ex. 03）
- `%M%`: Month (short number) / 月（ex. 3）
- `%DD%`: 2 digits date / 2 桁日（ex. 02）
- `%D%`: Date (short number) / 日（ex. 2）
- `%HH%`: 2 digits Hour at 24 Hours / 2 桁で表した 24 時間表記の時（ex. 06 / 15）
- `%H%`: Hour at 24 Hours (short number) / 24 時間表記の時（ex. 6 / 15）
- `%h%`: 2 digits Hour at 12 Hours / 2 桁で表した 12 時間表記の時（ex. 03 / 09）
- `%h%`: Hour at 12 Hours (short number) / 12 時間表記の時（ex. 3 / 9）
- `%A%`: AM/PM / 午前/午後表記（ex. PM / (for ja-JP) 午後）
- `%mm%`: 2 digits Minutes / 2 桁分（ex. 08 / 24）
- `%m%`: Minutes (short number) / 分（ex. 8 / 24）
- `%ss%`: 2 digits Seconds / 2 桁秒（ex. 09）
- `%s%`: Seconds (short number) / 秒（ex. 9）
- `%W%`: Long weekday name / 曜日の長い表記（ex. Wednesday / 水曜日）
- `%w%`: Short weekday name / 曜日の短い表記（ex. Wed / 水）
