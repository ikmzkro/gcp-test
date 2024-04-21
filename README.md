`Error: google-github-actions/auth failed with: retry function failed after 4 attempts: failed to parse service account key JSON credentials: unexpected token  in JSON at position 0`の対応。

GCPコンソールから発行したJSONキーであればうまくいくが、適当に設定したGCPのKEYだと同じよぅなエラーが発生することが確認できた

https://zenn.dev/kou_kawa/articles/04-gcs-github-actions#%F0%9F%97%9D%EF%B8%8Fgcp%E3%81%B8%E3%81%AE%E8%AA%8D%E8%A8%BC%E6%83%85%E5%A0%B1%EF%BC%88json%E3%82%AD%E3%83%BC%EF%BC%89%E3%82%92github-secrets%E3%81%AB%E4%BF%9D%E5%AD%98