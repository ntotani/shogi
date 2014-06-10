1. このリポジトリをcloneする
2. git submodule update --init --recursive      # cocos2d-xを取得
3. frameworks/cocos2d-x/download-deps.py        # external以下を取得
4. frameworks/cocos2d-x/plugin/tools/publish.sh # pluginを書き出し
5. XcodeでPROJECT => leadblowを選択、インスペクタのNameを編集してプロジェクト名を変更
6. Androidのbuild.xmlとres/values/strings.xmlのleadblowをプロジェクト名に変更
