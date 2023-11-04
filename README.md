# Generative-AI-Tools

### この項目は書きかけです

* テキスト生成AI
    * [ChatGPT](https://chat.openai.com/)
    * [Gooble Bard](https://bard.google.com/chat)
    * [Claude2](https://claude.ai/chats)（クロード2）


## [**音読さん**](https://ondoku3.com/ja/)（音声生成AI）

> 音読さんについて  
    ・テキストから音声を生成する（.mp3）  
    ・無料で5000文字/月まで読み上げ可能  
    ・多言語、各種音声対応

## [**CREEVO**](https://creevo-music.com/)（歌詞→音楽生成AI）

> CREEVO（クリーボ）について  
    ・歌詞をもとに作曲（.mp3）する音楽生成AI  
    ・京都大学の研究チームによる開発  
    ・同様のツールに東大 [Orpheus](https://www.orpheus-music.org/)（オルフェウス）がある

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
1. [音声合成版] or [インストゥルメンタル版] を保存（.mp3）  

参考：[**Audacity**](https://apps.microsoft.com/detail/audacity/XP8K0J757HHRDW?hl=ja-jp&gl=JP)（波形編集+MIDIシーケンサー）  


## [**NeuralNote**](https://github.com/DamRsn/NeuralNote)（音声→MIDI変換）

> NeuralNote（ニューラルノート）について  
    ・深層学習（ディープラーニング）を利用
    ・音声ファイル（3分迄）をMIDI（.mid）に変換  
    ・スタンドアロン版（Mac/Win対応）とVST3版がある
    ・.wav .aiff .flac .mp3 .ogg に対応

1. [ここ](https://github.com/DamRsn/NeuralNote/releases)から NeuralNote_Standalone_Windows.zip を選択
1. ダウンロード→展開後 NeuralNote.exe を起動
1. [LOAD OR DROP AN AUDIO FILE] から 〇〇.wav をロード
1. 各種設定  
    1. TRANSCRIPTION
        * NOTE SENSIBILITY ≒ ノート長（初期値0.70）
        * SPLIT SENSIBILITY ≒ 分割度合い（初期値0.50）
        * MIN NOTE DURATION ≒ ノイズ除去（初期値125ms）
    1. SCALE QUANTIZE
        * RANGE ≒ ローパス･ハイパスフィルタ
1. [DRAG THE MIDI FILE FROM HERE] 箇所（判り難い）をデスクトップ等にドラッグして出力（.mid）  

参考：[GIGAZINE](https://gigazine.net/news/20230515-neuralnote/)（2023年5月15日記事）  
参考：[**signal**](https://signal.vercel.app/)（オンラインMIDIシーケンサー）  


## [Basic Pitch](https://basicpitch.spotify.com/)（音声→MIDI変換）

> Basic Pitch（ベーシックピッチ）について  
    ・ウェブベースで音声ファイル→MIDIに変換
    ・

### [**Meta MusicGen**](https://huggingface.co/spaces/facebook/MusicGen)