# Generative-AI-Tools

* テキスト生成AI
    * [ChatGPT](https://chat.openai.com/)
    * [Gooble Bard](https://bard.google.com/chat)
    * [Claude2](https://claude.ai/chats)（クロード2）


### [**CREEVO**](https://creevo-music.com/)

> CREEVO（クリーボ）について  
    ・歌詞をもとに作曲する音楽生成AI  
    ・京都大学の研究チームによる開発  
    ・同様のツールに東京大学の [Orpheus](https://www.orpheus-music.org/)（オルフェウス）がある

1. テキスト生成AIを使って作詞（12小節まで）
1. Googleアカウントでログイン
1. [デザイン作曲] を選択
1. 歌詞を入力
1. [コード進行] を設定
    * 楽曲の全体的な特徴
    * 調
1. [メロディのスタイル] を設定
    * メロディの雰囲気
    * テンポBPM
    * メロディ楽曲
    * メロディ生成の設定
        * 音域
        * 遊び度
        * 和音の当てはまり度
    * 伴奏のスタイル（伴奏なしも選択可）
        * 伴奏パターン1,2
        * 伴奏楽器
        * ドラムパターン
1. [音声合成版] または [インストゥルメンタル版] を保存（.mp3）


### [**NeuralNote**](https://github.com/DamRsn/NeuralNote)（Audio→MIDI変換）

1. [ここ](https://github.com/DamRsn/NeuralNote/releases)から NeuralNote_Standalone_Windows.zip をダウンロード
1. 展開後 NeuralNote.exe を起動
1. [LOAD OR DROP AN AUDIO FILE] から 〇〇.wav をロード
1. 各種設定  
    1. TRANSCRIPTION
        * NOTE SENSIBILITY ≒ ノート長（初期値0.70）
        * SPLIT SENSIBILITY ≒ 分割度合い（初期値0.50）
        * MIN NOTE DURATION ≒ ノイズ除去（初期値125ms）
    1. SCALE QUANTIZE
        * RANGE ≒ ローパス･ハイパスフィルタ
1. [**DRAG THE MIDI FILE FROM HERE**] 箇所（判り難い）をデスクトップ等にドラッグして出力（**.mid**）  
参考：[GIGAZINE](https://gigazine.net/news/20230515-neuralnote/)（2023年5月15日記事）  


### [**Meta MusicGen**](https://huggingface.co/spaces/facebook/MusicGen)