# How we built Artifacts with Claude

URL: https://www.youtube.com/watch?v=vUdNaAAc4FY
数値: 25
時間: 3m

Transcript: "(00:13) Okay, can you see this? - Yes. Yes. - All right. Wait, of course you can see it, I can see it. It just kept replaying over and over again in my head. I haven't really done this demo yet, so we'll see how it goes. I wrote this instruction set. Can you start the first draft for me? H-h-h-holy shit. So back in March, I wanted to see how good the newest model was at generating websites. (00:49) And I had been copying and pasting the websites that it was generating into an editor. And then I was saving the file and I was opening the file in the web browser. And I was just noticing that this whole round-trip process was just taking a lot of time. And what I wanted it to do was I just wanted it to like render in the screen immediately. (01:12) I put together this really janky side-by-side interface. So I started to give a presentation about this interface and I think that was sort of when I think a lot of us realized, oh wow, like there's something here. When you see it immediately on the screen, there's something that sort of clicks. The core mechanics of this, it's the power of the model that's doing the work. (01:35) Yes. I don't know, it's just amazing to see. When I started building the prototype, there was a degree of just investigating to see how much of this is possible just by using some prompt engineering and instructions for Claude. Claude was very willing to play along and I had gotten like a proof of concept working in much less time than I anticipated and it just got my mind racing. (02:00) Eventually at 2:00 AM I felt like I had a pretty solid prototype. I posted it to Slack. The rest is history. I got a ton of help from a couple folks that stepped in who were equally excited by it. Yeah, it was a fun week. You know, after that message from Dario, it was maybe a week and a half before we got it into internal dogfooding so the entire rest of the company could start using it. (02:27) I think what Artifacts really shows is how really small tweaks to the way we interact with these systems can really make a big difference to how fun, engaging, creative they are to use. There's a lot of question marks about how people and AI are gonna interact in the future, and I think there's a real opportunity to create positive visions for that and ways that are more collaborative and ways that are more generative and creative where people are in the process, where they're iterating with these systems, where these systems help them do more (02:57) of what they would want to do but couldn't do otherwise without the help of a system. And I think that's part of what feels inspiring to me about Artifacts.”

## 要点（タイムスタンプ付き）

- **(00:13〜00:49)**
    
    デモ準備の開始。話者が「instruction set」を書き、最初のドラフトを依頼。最初は Web サイト生成モデルの試行をしており、生成されたものをエディタに貼ってブラウザで表示、検証するというプロセスを繰り返していた。[YouTube](https://www.youtube.com/watch?v=vUdNaAAc4FY&utm_source=chatgpt.com)
    
- **(00:49〜01:12)**
    
    この「貼って保存してブラウザで開く」という“ラウンドトリップ”（コード → 編集 → ブラウザ表示）の工程が非常に時間を食っていた。もっとインタラクティブに、即座に画面上でレンダリングされることを望んでいた。[YouTube](https://www.youtube.com/watch?v=vUdNaAAc4FY&utm_source=chatgpt.com)
    
- **(01:12〜01:35)**
    
    プロトタイプとして、サイドバイサイドの UI（生成 → 即時表示）が手早く組まれる。「画面にすぐ見える／編集できる」ことで感覚が変わる。モデルが指示に従い、コードを生成する能力に驚きがあったという。[YouTube](https://www.youtube.com/watch?v=vUdNaAAc4FY&utm_source=chatgpt.com)
    
- **(01:35〜02:00)**
    
    プロンプト設計（prompt engineering）を介してどこまで可能かを検証。思ったより短い時間でプルーフ・オブ・コンセプトが動き、これがアイデアを飛躍させるきっかけとなった。[YouTube](https://www.youtube.com/watch?v=vUdNaAAc4FY&utm_source=chatgpt.com)
    
- **(02:00〜02:27)**
    
    深夜まで作業を重ね、プロトタイプが「かなり良い」段階に。Slack に投稿すると社内で反響あり。1週間ほどで社内 dogfooding（社内テスト）に入り、会社全体で使い始められるようになった。[YouTube](https://www.youtube.com/watch?v=vUdNaAAc4FY&utm_source=chatgpt.com)
    
- **(02:27〜02:57)**
    
    Artifacts によって、人と AI のインタラクションの小さな工夫が、「創造性・反復性・没入感・コラボレーション感」に大きな変化をもたらすという洞察。AI が人の「本来やりたいけどできなかったこと」を手助けする存在になりうる。