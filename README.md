# Generative-AI-Tools

### この項目は書きかけです

#### Index
* テキスト生成AI
    * [ChatGPT](#ChatGPT)
    * [Claude2](#Claude)
    * [Gooble Bard](#Bard)
* 画像生成AI
    * [DALL･E3](#DALLE)
* 音楽生成AI
    * [Basic Pitch](#BasicPitch)（音声→MIDI変換）
    * [CREEVO](#CREEVO)（歌詞→音楽生成AI）
    * [MusicGen](#MusicGen)（テキスト→音楽生成AI）
    * [NeuralNote](#NeuralNote)（音声→MIDI変換）
    * 補助ツール
        * [Audacity](https://apps.microsoft.com/detail/audacity/XP8K0J757HHRDW?hl=ja-jp&gl=JP)（DAW）
        * [signal](https://signal.vercel.app/)（MIDIシーケンサー）
* 音声生成AI
    * [音読さん](#ondoku)
* 動画生成AI
    * [Runway Gen-2](#Runway)

***
<a id="ChatGPT"></a>

## [ChatGPT](https://chat.openai.com/)（テキスト生成AI）


<a id="Bard"></a>

## [Gooble Bard](https://bard.google.com/chat)（テキスト生成AI）


<a id="Claude"></a>

## [Claude2 クロード](https://claude.ai/chats)（テキスト生成AI）


<a id="ondoku"></a>

## [**音読さん**](https://ondoku3.com/ja/)（音声生成AI）

> 音読さんについて  
    ・テキストから音声を生成（.mp3）  
    ・無料で5000文字/月まで読み上げ可能  
    ・多言語、各種音声対応


<a id="CREEVO"></a>

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


<a id="MusicGen"></a>

### [**Meta MusicGen**](https://huggingface.co/spaces/facebook/MusicGen)（テキスト→音楽生成AI）

> MusicGen（ミュージックジェン）について  
    ・Meta社が開発（2023年6月発表）  
    ・テキストのプロンプトをもとに作曲  
    ・既存のメロディ（.mp3）+プロンプトでも生成可能  

参考：[YouTube](https://www.youtube.com/results?search_query=Meta+MusicGen)（紹介動画）  
※正直まだまだびみょーなツール（2023年11月4日現在）  


<a id="NeuralNote"></a>

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
    1. TRANSCRIPTION（カッコの値は初期値）
        * NOTE SENSIBILITY：音認識の閾値（0.70）
        * SPLIT SENSIBILITY：分割度合い（0.50）
        * MIN NOTE DURATION：ノート最短長（125ms）
    1. SCALE QUANTIZE
        * RANGE：ローパス･ハイパスフィルタ
1. [DRAG THE MIDI FILE FROM HERE] 箇所（判り難い）をデスクトップ等にドラッグして出力（.mid）  

参考：[GIGAZINE](https://gigazine.net/news/20230515-neuralnote/)（2023年5月15日記事）  
参考：[**signal**](https://signal.vercel.app/)（オンラインMIDIシーケンサー）  


<a id="BasicPitch"></a>

## [Basic Pitch](https://basicpitch.spotify.com/)（音声→MIDI変換）

> Basic Pitch（ベーシックピッチ）について  
    ・ウェブベースで音声ファイル→MIDIに変換  
    ・.wav .mp3 等に対応

1. [Basic Pitch](https://basicpitch.spotify.com/) にアクセス
1. [Drop your audio file here or click to select one] に 〇〇.wav をロード
1. MIDIに変換されたら [SHOW MIDI ADJUSTMENTS] を選択
1. 各種設定（カッコの値は初期値）
    1. Note Segmentation：分割度合い（0.50）
    1. Model Confidence Threshold：音認識の閾値（0.30）
    1. Minimum Pitch：ローパスフィルタ（0）
    1. Maximun Pitch：ハイパスフィルタ（3000）
    1. Minimum Note Length：ノート最短長（11）
    1. MIDI File Tempo：テンポ（120）

参考：[YouTube](https://www.youtube.com/watch?v=rFq_2CwFMwo)（Pasic Pitchの使用方法）  
参考：[**signal**](https://signal.vercel.app/)（オンラインMIDIシーケンサー）  


<a id="Runway"></a>

### [**Runway Gen-2**](https://app.runwayml.com/video-tools/teams/takashi246ra/dashboard)（動画生成AI）

> Runway（ランウェイ）について
    ・Runway社が開発するブラウザベースの動画生成AI
    ・テキスト→動画、画像→動画、画像+テキスト→動画
    ・生成時間に制限あり

参考：[YouTube](https://www.youtube.com/watch?v=ncwGMlccMkU)（使い方完全解説）  
※将来に期待  



<a id="DALLE"></a>

### [**DALL･E3**](https://app.runwayml.com/video-tools/teams/takashi246ra/dashboard)（動画生成AI）

> DALL･E3（ダリ3）について
    ・OpenAI社が開発する画像生成AI  
    ・[GPT-4]-[DALL･E3]-[プロンプト] で生成  

参考：[YouTube](https://www.youtube.com/watch?v=vqnPuTltFN8)（完全ガイド）  