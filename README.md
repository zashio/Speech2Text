# Speech2Text
音声ファイルを指定すると、そのスクリプトを返す関数です。
ほぼ[Google-Cloud-Speech-APIのソース](https://github.com/GoogleCloudPlatform/python-docs-samples/tree/master/speech/cloud-client)を使用しています。
##使い方
'os.environ["GOOGLE_APPLICATION_CREDENTIALS"]="あなたの認証用jsonファイル"'
の部分さえ直してくれれば、あとは引数の部分に任意の音声ファイルを指定して、実行することができます。
