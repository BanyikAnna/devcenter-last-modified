---
published_at:
last_modified_at:
title: ビルドのトリガー
redirect_from: "/jp/jp/builds/triggering-builds/triggering-builds/"
menu:
  builds-main:
    identifier: triggering-builds
    weight: 4

---
Bitriseのビルドトリガーには以下のいずれかを選択できます。

- [手動による開始](/jp/builds/triggering-builds/starting-builds-manually/)
- [スケジュールによる開始](/jp/builds/scheduling-builds/)
- トリガーイベントによる開始

BitriseにIncoming Webhooksを設定している場合、指定されたトリガーイベントまたはWorkflowによりビルドを自動的に開始することができます。
また、複数のトリガーを指定したり、トリガーの追加、削除を行うことができます。

デフォルトでは、アプリケーションを登録すると2つのトリガーを持っています。
1つ目は任意のブランチがリポジトリにプッシュされたとき、2つ目は新規のPull Requestが作成されたときです。
これらは自由に変更、削除することができます。

トリガーは`Workflow Editor`の`Triggers`セクションで管理できますが、`bitrise.yml`を直接編集して設定することも可能です。
DevCenterのこのセクションでは、WebサイトのUI上でトリガーを設定および管理する方法について説明します。

- [プッシュをトリガーにする](/jp/builds/triggering-builds/trigger-code-push)
- [Pull Requestをトリガーにする](/jp/builds/triggering-builds/trigger-pull-request)
- [Tagをトリガーにする](/jp/builds/triggering-builds/trigger-git-tags)
- [単一のトリガーで並列ビルドを開始する](/jp/builds/triggering-builds/trigger-multiple-workflows)
- [Gitホスティングサービスにビルド結果を通知する](/jp/builds/triggering-builds/status-reporting)