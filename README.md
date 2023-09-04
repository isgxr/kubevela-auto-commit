# auto-commit

每次推送分支时，都会触发“自动提交”工作流程。

The workflow will use the `GitHub SHA` as a version to update the `PublishVersion` in app.yaml with message `[ci skip] deploy from <GitHub SHA>`
该工作流程将使用“GitHub SHA”作为版本，以使用消息“[ciskip]从 <GitHub SHA> 部署”来更新 app.yaml 中的“PublishVersion”

Note that the commit that update the PublishVersion won't trigger the workflow to run a second time.
