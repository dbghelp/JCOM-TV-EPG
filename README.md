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
  
| tvg-id                       | Channel Name                           |
|------------------------------|----------------------------------------|
| jcom_2_1024_32736 | NHK東京　総合 |
| jcom_2_1032_32737 | NHK東京　教育 |
| jcom_2_1040_32738 | 日本テレビ |
| jcom_2_1048_32739 | TBS |
| jcom_2_1056_32740 | フジテレビ |
| jcom_2_1064_32741 | テレビ朝日 |
| jcom_2_1072_32742 | テレ東 |
| jcom_2_4112_32690 | HBC |
| jcom_2_4120_32691 | 札幌テレビ |
| jcom_2_4128_32692 | 北海道テレビ |
| jcom_2_4136_32693 | 北海道文化放送 |
| jcom_2_4144_32694 | テレビ北海道 |
| jcom_2_10240_32592 | NHK札幌　総合 |
| jcom_2_10248_32593 | NHK札幌　教育 |
| jcom_2_23608_32391 | TOKYO　MX |
| jcom_2_24632_32375 | テレビ神奈川 |
| jcom_2_25600_32352 | NHK前橋　総合 |
| jcom_2_25656_32359 | 群馬テレビ |
| jcom_2_26624_32336 | NHK水戸　総合 |
| jcom_2_27704_32327 | チバテレビ |
| jcom_2_29752_32295 | テレ玉1 |
| jcom_3_101_4 | ＮＨＫ　ＢＳ |
| jcom_3_101_11 | ＮＨＫ　ＢＳＰ４Ｋ |
| jcom_3_103_4 | - |
| jcom_3_141_4 | ＢＳ日テレ |
| jcom_3_141_11 | BS日テレ 4K |
| jcom_3_151_4 | ＢＳ朝日１ |
| jcom_3_151_11 | BS朝日 4K |
| jcom_3_161_4 | ＢＳ－ＴＢＳ |
| jcom_3_161_11 | BS-TBS 4K |
| jcom_3_171_4 | BSテレ東 |
| jcom_3_171_11 | BSテレ東 4K |
| jcom_3_181_4 | ＢＳフジ・181 |
| jcom_3_181_11 | BSフジ 4K |
| jcom_3_191_4 | ＷＯＷＯＷプライム |
| jcom_3_192_4 | ＷＯＷＯＷライブ |
| jcom_3_193_4 | ＷＯＷＯＷシネマ |
| jcom_3_211_4 | BS11 イレブン |
| jcom_120_033_65406 | ご案内チャンネル |
| jcom_120_034_65406 | オンデマンドチャンネル290 |
| jcom_120_037_65406 | J:COMプレミアチャンネル |
| jcom_120_038_65406 | NHKワールド JAPAN |
| jcom_120_039_65406 | オンデマンドチャンネル440 |
| jcom_120_102_65406 | 日テレNEWS24 HD |
| jcom_120_103_65406 | J:COM BS |
| jcom_120_104_65406 | ＴＶ５ＭＯＮＤＥ |
| jcom_120_105_65406 | ダンスチャンネル by エンタメ～テレ |
| jcom_120_106_65406 | スポーツライブ＋ |
| jcom_120_107_65406 | レジャーチャンネル |
| jcom_120_110_4 | ＢＳ１０ |
| jcom_120_121_65534 | ディスカバリーチャンネル |
| jcom_120_122_65534 | ムービープラス |
| jcom_120_123_65534 | 女性チャンネル♪LaLa TV |
| jcom_120_125_65534 | 日本映画専門チャンネル　HD |
| jcom_120_126_65406 | アジアドラマチックTV（アジドラ） |
| jcom_120_127_65406 | 衛星劇場HD |
| jcom_120_128_65406 | FIGHTING TV サムライ |
| jcom_120_129_65406 | ショップチャンネル プラス |
| jcom_120_130_65406 | ディズニージュニア |
| jcom_120_131_65534 | Dlife（ディーライフ） |
| jcom_120_132_65534 | J SPORTS 4 HD |
| jcom_120_133_65534 | ザ・シネマ HD |
| jcom_120_134_65534 | ヒストリーチャンネル 日本・世界の歴史＆エンタメ |
| jcom_120_135_65534 | チャンネル銀河　歴史ドラマ・サスペンス・日本のうた |
| jcom_120_136_65406 | テレ朝チャンネル１ |
| jcom_120_137_65406 | フジテレビＮＥＸＴ　ライブ・プレミアム |
| jcom_120_138_65406 | フジテレビＯＮＥ　スポーツ・バラエティ |
| jcom_120_139_65406 | フジテレビＴＷＯ　ドラマ・アニメ |
| jcom_120_140_65406 | ショップチャンネル |
| jcom_120_141_65406 | ホームドラマチャンネルＨＤ 韓流・時代劇・国内ドラマ |
| jcom_120_142_65406 | ナショナル ジオグラフィック |
| jcom_120_143_65406 | 旅チャンネル　ＨＤ |
| jcom_120_144_65406 | TBSチャンネル1 最新ドラマ・音楽・映画 |
| jcom_120_145_65406 | 釣りビジョンHD |
| jcom_120_146_65406 | GAORA SPORTS HD |
| jcom_120_147_65406 | スカイA |
| jcom_120_148_65406 | アクションチャンネル |
| jcom_120_149_65406 | アニマックスＨＤ |
| jcom_120_150_65406 | MTV HD |
| jcom_120_151_65406 | 映画･チャンネルNECO-HD |
| jcom_120_152_65406 | ＴＢＳ ＮＥＷＳ |
| jcom_120_153_65406 | ミステリーチャンネル |
| jcom_120_154_65406 | タカラヅカ・スカイ・ステージ |
| jcom_120_155_65406 | WOWOWプラス 映画・ドラマ・スポーツ・音楽 |
| jcom_120_156_65406 | 音楽・ライブ！　スペースシャワーTV HD |
| jcom_120_157_65406 | ファミリー劇場HD |
| jcom_120_158_65406 | J SPORTS 3 HD |
| jcom_120_159_65406 | 時代劇専門チャンネル HD |
| jcom_120_160_65406 | MONDOTV HD |
| jcom_120_161_65406 | ミュージック・エア |
| jcom_120_163_65406 | キッズステーション HD |
| jcom_120_164_65406 | グリーンチャンネルHD |
| jcom_120_165_65406 | グリーンチャンネル2HD |
| jcom_120_166_65406 | 日テレジータス HD |
| jcom_120_167_65406 | ゴルフネットワーク |
| jcom_120_168_65406 | J SPORTS 1 HD |
| jcom_120_169_65406 | J SPORTS 2 HD |
| jcom_120_170_65406 | 寄席チャンネル |
| jcom_120_171_65406 | カートゥーン ネットワークHD 海外アニメ国内アニメ |
| jcom_120_172_65406 | QVC |
| jcom_120_173_65406 | 東映チャンネルHD |
| jcom_120_174_65406 | KNTV |
| jcom_120_175_65406 | 歌謡ポップスチャンネル |
| jcom_120_176_65406 | TBSチャンネル2 名作ドラマ・スポーツ・アニメ |
| jcom_120_179_65406 | BSよしもと |
| jcom_120_180_65406 | CNNｊ |
| jcom_120_181_65406 | Mnet HD |
| jcom_120_182_65406 | アニメシアターX（AT-X） |
| jcom_120_183_65406 | ディズニー・チャンネル |
| jcom_120_184_65406 | KBS WORLD HD |
| jcom_120_185_65406 | 日経CNBC |
| jcom_120_186_65406 | アニマルプラネット |
| jcom_120_187_65406 | エンタメ～テレＨＤ☆ |
| jcom_120_188_65406 | テレ朝チャンネル２ |
| jcom_120_190_65406 | 日テレプラス ドラマ・アニメ・音楽ライブ |
| jcom_120_191_65406 | パチンコ★パチスロTV！ |
| jcom_120_192_65406 | ジュエリー☆GSTV |
| jcom_120_195_65406 | V☆パラダイス |
| jcom_120_196_65406 | 囲碁・将棋チャンネル |
| jcom_120_198_65406 | SPEEDチャンネル |
| jcom_120_200_4 | ＢＳ１０プレミアム |
| jcom_120_203_65406 | BS12トゥエルビ |
| jcom_120_227_65534 | 中国テレビ★大富チャンネル |
| jcom_120_249_65406 | CNN U.S. |
| jcom_120_257_65534 | BBCニュース |
| jcom_120_290_65534 | プレイボーイ チャンネル |
| jcom_120_291_65534 | レッドチェリー |
| jcom_120_293_65534 | ミッドナイト・ブルー |
| jcom_120_295_65406 | パラダイステレビ |
| jcom_120_401_65534 | satonoka 4K |
| jcom_120_416_65527 | ショップチャンネル ４Ｋ |
| jcom_120_417_65527 | 4Ｋ QVC |
| jcom_120_419_65527 | 日本映画＋時代劇 4K |
| jcom_200_00022_0 | J:COMチャンネル |
| jcom_200_00023_0 | J:COMチャンネル |
| jcom_200_00025_0 | J:COMチャンネル |
| jcom_200_00027_0 | J:COMチャンネル |
| jcom_200_00032_0 | J:COMチャンネル |
| jcom_200_00033_0 | J:COMチャンネル |
| jcom_200_00035_0 | J:COMチャンネル |
| jcom_200_00036_0 | J:COMチャンネル |
| jcom_200_00037_0 | J:COMチャンネル |
| jcom_200_00038_0 | J:COMチャンネル |
| jcom_200_00039_0 | J:COMチャンネル |
| jcom_200_00040_0 | J:COMチャンネル |
| jcom_200_00041_0 | J:COMチャンネル |
| jcom_200_00052_0 | J:テレ |
| jcom_200_00053_0 | J:テレ |
