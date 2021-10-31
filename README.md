# playcanvas_project_template

## playcanvas-syncのインストール
https://github.com/playcanvas/playcanvas-sync  

    git clone git@github.com:playcanvas/playcanvas-sync.git
    cd playcanvas-sync
    npm install
    npm install -g

## APIキーを設定
.pcconfigをホームディレクトリに作成  

    {
      "PLAYCANVAS_API_KEY": "作成したAPIキー",
      "PLAYCANVAS_USE_CWD_AS_TARGET": 1
    }

## 作業ディレクトリにpcconfig.jsonを作成
    {
      "PLAYCANVAS_BRANCH_ID": "ブランチID 12345678-1234-1234-1234-123456789012",
      "PLAYCANVAS_PROJECT_ID": プロジェクトID,
      "PLAYCANVAS_TARGET_DIR": "./src",
      "PLAYCANVAS_BAD_FILE_REG": "^\\.|~$",
      "PLAYCANVAS_BAD_FOLDER_REG": "\\."
    }
