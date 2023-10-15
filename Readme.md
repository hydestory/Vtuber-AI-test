# Vtuber(AI) Test

## 工作流程步驟：
![螢幕擷取畫面 2023-10-15 142749](https://github.com/hydestory/Vtuber-AI-test/assets/35997995/8dbf4cb4-3d14-4559-b90e-e70d1e905c35)

1. **語音輸入/YouTube 聊天室擷取**
   - 捕捉語音輸入或YouTube聊天室的訊息。

2. **使用 Whisper 進行語音轉文字（STT）**
   - 使用 Whisper 將捕捉到的音訊轉換為文字，使用語音轉文字（STT）技術。

3. **使用 Google 翻譯轉換為中文**
   - 使用 Google 翻譯將由 Whisper 獲得的文字轉換為中文。

4. **ChatGPT 回應**
   - 使用 ChatGPT 基於翻譯後的文字生成中文回應。

5. **使用 Google 翻譯轉換為日文**
   - 使用 Google 翻譯將 ChatGPT 生成的回應再轉回日文。

6. **使用 Voicevox 進行文字轉語音（TTS）**
   - 使用 Voicevox 將日文文字轉換為語音。

7. **輸出**
   - 提供最終的 TTS 輸出作為回應，2d模型會隨著輸出的文字而張嘴，達到模仿說話的效果。
