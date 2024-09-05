# S3IAMBatchGenerator
Easy to use batch/shell file generator to manage IAM users and groups.

This tool is prepared to automate the operation related to IAM such as manage users and groups.
The automation is performed by using AWS CLI commands and there are prerequisites for the execution of the commands provided by this tool.

## Prerequisites:
Please install the AWS Command Line Interface (CLI)
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html

<b>IMPORTANT:</b> YOU NEED TO INSTALL AWS CLI FIRST TO USE THIS TOOL.
To install the AWS CLI version 2, see Install or update to the latest version of the AWS CLI.

## AWS CLI Configuration and Credential File
To execute the commands you must configure AWS CLI with your Access Key and Secret Key.
The configuration file and the credential file can be created with the AWS CLI installed by executing the aws configure command:</p>
`aws configure`

Please refer this AWS document for details.
https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html

## Command References
<b>Details:</b></p>
For all available commands, please refer to the official AWS documentation that can be found bellow:
https://awscli.amazonaws.com/v2/documentation/api/latest/reference/iam/index.html

<b>NOTE FOR WASABI CLOUD STORAGE USE</b></p>
The command HAS to be executed with the ENDPOINT option specified. 
Please always add the endpoint  "--endpoint-url https://iam.ap-northeast-1.wasabisys.com" (please change based on your target region if necessary).

## How To Use
Please refer to the following document that explain step by step how to use the tool provided here.
https://github.com/luizcarloskazuyukifukaya/S3IAMBatchGenerator/blob/main/HowToUse.pdf

# 日本語による補足
このツールは、ユーザーやグループの管理など、IAMに関する操作を自動化するために用意されています。 
自動化は AWS CLI コマンドを使用して実行され、このツールによって提供されるコマンドの実行には前提条件があります。 

## 前提条件： 
AWSコマンドラインインターフェース(CLI)をインストールしてください。
https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/cli-chap-welcome.html

<b>重要:</b></p> 
このツールを使用するには、まず AWS CLI をインストールする必要があります。 
AWS CLI バージョン 2 をインストールするには、「AWS CLI の最新バージョンにインストールまたは更新する」を参照してください。 

## AWS CLI 設定ファイルと認証情報ファイルの設定
AWS CLIコマンドを実行するには、アクセスキーとシークレットキーを指定した設定ファイルと認証情報ファイルを作成する必要があります。 
設定ファイルと認証情報ファイルは、'aws configure' コマンドを実行することで作成可能でして、そのためにはAWS CLI をインストールする必要があります。上述の前提条件をご確認下さい。</p>
`aws configure`

詳細については、このAWSドキュメントを参照してください。
https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/cli-configure-files.html

## コマンド リファレンス 
詳細：</p> 
使用可能なすべてのコマンドについては、以下のAWSの公式ドキュメントを参照してください。 
https://awscli.amazonaws.com/v2/documentation/api/latest/reference/iam/index.html

## 使い方
ツールの具体的な使い方に関しては、以下のドキュメントを参照下さい。
https://github.com/luizcarloskazuyukifukaya/S3IAMBatchGenerator/blob/main/HowToUse.pdf


<b>WASABI CLOUD STORAGEの使用に関する注意事項</b></p> 
コマンドは、ENDPOINT オプションを指定して実行する必要があります。
エンドポイントは必ず「<b>'--endpoint-url https://iam.ap-northeast-1.wasabisys.com'</b>」を追加してください(必要に応じて対象地域に応じて変更してください)。