---
title: Gleaner
layout: default
---

# Gleaner

**Gleaner** is a personal tool that turns videos into readable, bilingual (English and Chinese) articles.

It is a self-hosted, single-user application. It is not distributed to the public and is not affiliated with, endorsed by, or sponsored by YouTube or Google.

## What it does

- **Paste a link or pick from your subscriptions.** You choose which videos to process, either by pasting a video link or by selecting a new video from channels you subscribe to.
- **Transcribe.** The audio of the videos you choose is fetched for personal, offline processing and transcribed on your own server using open-source speech recognition.
- **Write it up.** The transcript is organized into an article with a title, a summary, chapters and paragraphs, with the original text and a translation shown side by side. You can export the result as Markdown, TXT or PDF.

## How it uses your Google account

If you choose to connect your Google account, Gleaner requests a single read-only permission:

`https://www.googleapis.com/auth/youtube.readonly`

It is used for one purpose only: to read the list of channels you are subscribed to, so that you can pick new videos from them. Gleaner never posts, edits, deletes or changes anything in your YouTube or Google account.

You can disconnect at any time in the app, or revoke access in your Google Account at <https://myaccount.google.com/permissions>.

Gleaner's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Links

- [Privacy Policy](privacy)

## Contact

Questions: xiang978771447@gmail.com

---

## 中文简介

**Gleaner(拾言)** 是一个个人使用的工具,把视频整理成可阅读的中英对照文章。

它是自托管、单用户的应用,不面向公众分发,也与 YouTube、Google 没有任何隶属、认可或赞助关系。

**功能:** 粘贴视频链接,或从你订阅的频道里选择新视频;对你选定的视频音频做本地语音转写;再整理成带标题、摘要、章节和段落的文章,原文与译文上下对照,可导出为 Markdown、TXT 或 PDF。

**对 Google 账号的使用:** 如果你选择连接 Google 账号,应用只申请一个只读权限(`youtube.readonly`),唯一用途是读取你订阅的频道列表,以便你挑选新视频。应用不会发布、修改或删除你账号里的任何内容。你可以随时在应用中断开连接,或在 <https://myaccount.google.com/permissions> 撤销授权。

[隐私政策 / Privacy Policy](privacy)
