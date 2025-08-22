# Live-face-swapping

🔥 开源直播/实时换脸项目

1. DeepFaceLive
	•	📌 GitHub: iperov/DeepFaceLive
	•	特点：实时换脸工具，可以通过显卡跑深度学习模型，在 Zoom/OBS 等直播中直接使用。
	•	用途：主要面向研究和娱乐（虚拟主播）。

2. SimSwap
	•	📌 GitHub: neuralchen/SimSwap
	•	特点：支持 任意人脸替换，并能嵌入到实时应用中。
	•	有些分支支持 Webcam 实时替换，可以结合 OBS 推流。

3. FaceSwap
	•	📌 GitHub: deepfakes/faceswap
	•	最早的换脸工具之一，功能丰富，主要是离线训练和处理，但可扩展到直播场景。

4. Avatarify
	•	📌 GitHub: alievk/avatarify-python
	•	特点：通过摄像头捕捉表情 → 驱动另一个头像视频。
	•	常用于虚拟主播，换脸更多是“驱动角色”，而不是完全伪造。

5. First Order Motion Model (FOMM)
	•	📌 GitHub: AliaksandrSiarohin/first-order-model
	•	核心算法：根据驱动视频动态生成目标视频，可做“任意人像驱动”。
	•	应用：直播虚拟人、表情迁移。

⸻

⚙️ 常见组合用法
	•	换脸引擎：DeepFaceLive / SimSwap
	•	直播软件：OBS Studio
	•	推流场景：抖音直播、Twitch、B站（合法用途下）
	•	显卡需求：建议 NVIDIA RTX 系列
