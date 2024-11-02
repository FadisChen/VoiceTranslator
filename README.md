# 語音翻譯器 (Voice Translator)

這是一個基於網頁的即時語音翻譯工具，支援語音輸入、文字輸入、圖片文字辨識（OCR）和語音輸出功能。

## 功能特點

### 1. 語音輸入與翻譯
- 支援中文語音輸入（🎤）
- 支援多國語言翻譯（日文、英文、西班牙文、泰文）
- 即時語音識別和翻譯

### 2. 文字輸入與翻譯
- 支援手動文字輸入（📝）
- 雙向翻譯功能
- 支援複製貼上

### 3. 圖片文字辨識 (OCR)
- 支援相機拍照辨識文字（📷）
- 自動翻譯辨識結果

### 4. 語音輸出
- 支援翻譯結果的語音播放
- 可在設定中開關 TTS 功能

### 5. 客製化設定
- 可調整字體大小（小、中、大、特大）
- 可選擇目標翻譯語言
- 深色模式支援
- 設定會自動保存

## 使用說明

### 基本操作
1. 上方輸入區：
   - 點擊 🎤 進行語音輸入
   - 點擊 📝 進行文字輸入
   
2. 下方輸入區：
   - 點擊 🎤 進行中文語音輸入
   - 點擊 📝 進行文字輸入

3. 相機功能：
   - 點擊右下角 📷 開啟相機
   - 拍照後自動辨識文字並翻譯

### 設定選項
點擊右下角 ⚙️ 可開啟設定面板：
- API 設定：輸入 Gemini API Key
- 翻譯設定：選擇目標語言
- 語音設定：開關 TTS 功能
- 字體設定：調整顯示字體大小

## 系統需求
- 支援現代瀏覽器（Chrome、Firefox、Safari、Edge）
- 需要網路連接
- 需要麥克風權限（語音輸入）
- 需要相機權限（OCR 功能）
- 需要 Gemini API Key

## 注意事項
1. 首次使用需要在設定中輸入 Gemini API Key
2. 語音識別需要穩定的網路連接
3. 相機功能需要 HTTPS 環境或本地主機
4. 建議使用 Chrome 瀏覽器以獲得最佳體驗

## 技術實現
- 使用 Web Speech API 實現語音識別
- 使用 Gemini API 進行文字翻譯
- 使用 Gemini Vision API 實現圖片文字辨識
- 使用 Web Speech Synthesis API 實現語音輸出
- 使用 localStorage 保存使用者設定

---

# Voice Translator

This is a web-based real-time voice translation tool that supports voice input, text input, image text recognition (OCR), and voice output.

## Features

### 1. Voice Input and Translation
- Supports Chinese voice input (🎤)
- Supports multilingual translation (Japanese, English, Spanish, Thai)
- Real-time voice recognition and translation

### 2. Text Input and Translation
- Supports manual text input (📝)
- Bidirectional translation functionality
- Supports copy and paste

### 3. Image Text Recognition (OCR)
- Supports camera photo text recognition (📷)
- Automatically translates recognized text

### 4. Voice Output
- Supports voice playback of translation results
- TTS function can be toggled in settings

### 5. Customizable Settings
- Adjustable font size (small, medium, large, extra-large)
- Selectable target translation language
- Dark mode support
- Settings are automatically saved

## Usage Instructions

### Basic Operations
1. Upper Input Area:
   - Click 🎤 for voice input
   - Click 📝 for text input
   
2. Lower Input Area:
   - Click 🎤 for Chinese voice input
   - Click 📝 for text input

3. Camera Function:
   - Click 📷 in the bottom right to open the camera
   - Automatically recognize and translate text after taking a photo

### Settings Options
Click ⚙️ in the bottom right to open the settings panel:
- API Settings: Enter Gemini API Key
- Translation Settings: Choose target language
- Voice Settings: Toggle TTS function
- Font Settings: Adjust display font size

## System Requirements
- Supports modern browsers (Chrome, Firefox, Safari, Edge)
- Requires internet connection
- Requires microphone permission (voice input)
- Requires camera permission (OCR function)
- Requires Gemini API Key

## Notes
1. First-time use requires entering the Gemini API Key in settings
2. Voice recognition requires a stable internet connection
3. Camera function requires HTTPS environment or localhost
4. Recommended to use Chrome browser for the best experience

## Technical Implementation
- Uses Web Speech API for voice recognition
- Uses Gemini API for text translation
- Uses Gemini Vision API for image text recognition
- Uses Web Speech Synthesis API for voice output
- Uses localStorage to save user settings

