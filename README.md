# 窦墨个人主页 v4 - 完整播放器版

## 本地运行
方案A: VS Code → 右键 index.html → Open with Live Server (推荐)
方案B: 终端 → python3 -m http.server 8080 → 浏览器 localhost:8080

## 播放器功能
- ▶ 播放/暂停
- ⏮ ⏭ 上一首/下一首
- 🔘 进度条（可拖拽）
- 🔊 音量调节
- 🎵 音频频谱可视化
- 📜 3D 歌词滚动 + 逐字卡拉OK高亮

## 添加新歌
用记事本打开 index.html，找到 PLAYLIST，照着已有格式加：
{
  title: "歌名", 
  artist: "歌手",
  src: "音频链接",
  lrc: "[00:00.00]歌词内容\n[00:05.00]..."
}
加完保存刷新即可。
