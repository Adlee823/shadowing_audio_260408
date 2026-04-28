# Shadowing MP3 + TTS fallback 穩定版

上傳到 GitHub Pages 的檔案結構：

```
index.html
lesson.json
audio/
  001.mp3
  002.mp3
  003.mp3
```

重點：
- 優先播放 `audio/xxx.mp3`
- MP3 找不到或手機/LINE 阻擋時，自動改用日文 TTS
- 解鎖音訊不再用 MP3 路徑判斷，所以不會因為音檔未上傳就顯示假解鎖失敗
- `lesson.json` 可自行增加句子
