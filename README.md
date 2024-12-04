# JCOM-TV-EPG
XML EPG for JCOM TV channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for JCOM TV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/JCOM-TV-EPG/refs/heads/main/jcom.xml

## Features

- XML formatted EPG for JCOM TV channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/JCOM-TV-EPG/refs/heads/main/jcom.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/JCOM-TV-EPG/refs/heads/main/jcom.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id              | Channel Name                      |
|---------------------|-----------------------------------|
| abema-anime         | ABEMA アニメチャンネル            |
| abema-anime-2       | ABEMA アニメチャンネル2           |
| special-plus-7      | アニメSPECIALチャンネル           |
| anime-special-2     | アニメSPECIAL2チャンネル          |
| isekai-anime        | 異世界・ファンタジーアニメチャンネル |
| isekai-anime-2      | 異世界・ファンタジーアニメ2チャンネル|
| lovecomedy-anime    | ラブコメアニメチャンネル          |
| dailylife-anime     | 日常・青春アニメチャンネル         |
| late-night-anime    | 深夜アニメチャンネル              |
| anime-live          | アニメLIVEチャンネル              |
| precure             | プリキュアチャンネル              |
| atashinchi          | あたしンちチャンネル              |
| family-anime-1      | ファミリーアニメ                 |
| family-anime-2      | ファミリーアニメ２               |
| 80s-anime-1         | なつかしアニメ80's                |
| 90s-anime-1         | なつかしアニメ90's                |
| 00s-anime-1         | なつかしアニメ00's                |
| abema-special       | ABEMA SPECIALチャンネル           |
| special-plus        | ABEMA SPECIAL 2チャンネル         |
| abema-news          | ABEMA NEWSチャンネル              |
| news-plus           | ABEMA NEWS会見チャンネル          |
| asia-drama          | 韓国・中国ドラマチャンネル         |
| asia-love-comedy    | 韓国ラブコメディ                 |
| asia-loveromance    | 韓国ラブロマンス                 |
| asia-historical     | 韓国時代劇                       |
| asia-drama-2        | 韓国・中国ドラマチャンネル2       |
| k-world             | K WORLDチャンネル                |
| drama               | ドラマ映画チャンネル              |
| drama-2             | ドラマ映画チャンネル2             |
| mahjong             | 麻雀チャンネル                   |
| shogi               | 将棋チャンネル                   |
| world-sports        | SPORTSチャンネル                 |
| world-sports-1      | SPORTS LIVE1 チャンネル          |
| fighting-sports     | 格闘チャンネル                   |
| hiphop              | HIPHOPチャンネル                 |
| commercial          | CMチャンネル                     |
| boatrace            | BOATRACEチャンネル               |
| keirin-auto         | 競輪・オートレースチャンネル       |

