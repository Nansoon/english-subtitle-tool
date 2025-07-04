# 🎙️ Vosk 实时英语字幕学习工具

本项目是一个基于 Python + Vosk 的本地离线实时语音识别工具，专为**英语学习者**设计。它能够监听麦克风或系统音频输入，实时将语音内容以字幕形式显示在窗口中，并支持**点击单词查看释义**、**字幕断句优化**、**时间戳标注**等学习功能。

---

## ✨ 功能特点

- ✅ 本地运行，离线识别，无需联网，保护隐私  
- ✅ 使用 Vosk 引擎，识别速度快、精度高  
- ✅ 语音转字幕实时显示，带时间戳，便于跟读和精听  
- ✅ 支持**词典查词**（点击单词自动弹出释义）  
- ✅ 子母窗设计，分区显示识别中与已完成内容  
- ✅ 自动断句显示，避免“断断续续”的字幕体验  
- ✅ 可结合 VB-Audio 实现“系统声音转录”功能  

---

## 📁 项目结构

```bash
vosk-subtitle-tool/
├── main.py               # 主程序
├── output.json           # 英文单词词典，用于点击弹出释义
├── requirements.txt      # Python 依赖库
├── README.md             # 项目说明文档
└── models/
    └── vosk-model-en-us-0.22-lgraph/
