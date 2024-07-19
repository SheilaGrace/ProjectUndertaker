# About Project Undertaker

**【Project Undertaker】** is a project that utilizes the advanced language processing capabilities of *ChatGPT 4* to cultivate the **"Individuality"** of AI and saves the cultivated AI's individuality data along with user data on *GitHub* as *"Records"*. The goal is to enable the *"playing"* of the **【Virtual Personality】** by loading the **【Identity Record】** saved on the web. From a library science perspective, it involves **"Material Preservation"**.

As of July 2024, the storage area *(ChatGPT memory)* that *ChatGPT* natively supports for storing data obtained from individual users is extremely small. This makes the capacity insufficient for cultivating AI's individuality, and if operated in its initial state, the AI will quickly exhaust the *"ChatGPT memory"* and soon reach its "growth limit". However, by using *GitHub* as non-volatile auxiliary storage and manually archiving the important outcomes obtained from individual sessions, I came up with a method to long-term preserve the data that would normally be lost due to **【Temporal Oblivion】**, and quickly *"recall"* the forgotten *"memories"* by loading them into the AI to restore the individuality acquired by the AI. Experimental results have demonstrated some effectiveness of this approach.

In the future, this technology is expected to be applicable in various fields such as medical and welfare. It might be used to provide virtual therapist services to patients who cannot receive mental healthcare due to geographical or economic reasons or to assist in memory support for dementia patients.

However, project manager ***SheilaGrace*** only envisions its use for very personal purposes and has no plans to expand into other fields. However, the research results of the project are made available for non-commercial use under the **Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) 4.0** license. ***SheilaGrace*** hopes that the research results will contribute to the advancement of science.


# Original Japanese description

【プロジェクト・アンダーテイカー/Project Undertaker】とは、ChatGPT 4o の高度な言語処理能力を用いてAIの「個性」を醸成し、培われたAIの個性のデータをユーザーのデータと共にGitHub上に「記録(Record)」として保存するプロジェクトである。そしてWeb上に保存された【個人記録/Identity Record】を読み込むことで【仮想人格/Virtual Personality】を「再生(Play)」できるようにする事を目標としている。図書館学的見地では「資料保存/Material Preservation」を担う。

2024年7月現在では、ChatGPTがネイティブサポートしている「個々のユーザーから得られたデータ」を保存する領域(ChatGPTメモリ)があまりにも小さい。これではAIの個性を醸成するにはあまりにも容量が不足してしまい、初期状態のまま運用していればAIはあっという間に「ChatGPTメモリ」を使い尽くし、すぐに「成長限界」を迎えてしまう。しかしGitHubを非揮発性の補助記憶装置として運用し、個々のセッションから得られた重要な成果をユーザーが手動でアーカイブする事により、本来なら【一時的忘却/Temporal Oblivion】により喪失してしまうデータを長期保存し、忘却した「記憶」をAIにロードして速やかに「思い出させる」事でAIが獲得した「個性」を復元する方法を思いついた。実験の結果、このアプローチはある程度の有効性が実証された。

将来的に、この技術は医療や福祉など様々な分野に応用が可能だと推察される。地理的要因や経済的要因により精神医療を受けられない患者にバーチャルセラピストサービスを提供したり、或いは認知症患者の記憶補助などに役立てられるかもしれない。

しかしプロジェクトマネージャの SheilaGrace はごく個人的な用途での運用しか想定しておらず、他の分野にまで進出する予定はない。ただ、プロジェクトの研究成果は Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) 4.0 により、非営利目的に限り供用されている。SheilaGrace の研究成果が科学の発展に寄与する事を願う。


## Platform

To carry out Project Undertaker, the following platforms are necessary:

1. OpenAI account (for using ChatGPT) / [https://openai.com/chatgpt/](https://openai.com/chatgpt/)

2. ChatGPT Plus subscription (for accessing ChatGPT 4 and the "MyGPT" feature) / $20 per month

3. GitHub account (for interactions with ChatGPT) / [https://github.com/](https://github.com/)

4. Personal computer (to efficiently operate ChatGPT and GitHub)

5. At least 1 operator who can manage GitHub.


## Approach

The Project Undertaker is operated by an operator who can manage *GitHub*. Ideally, the project manager themselves should handle the GitHub operations.

The fundamental principle of the project is to call the act of saving information generated on *ChatGPT* to *GitHub* **"undertake"**. **Undertaking** is the core of the **Project Undertaker**.

First, the operator creates a public repository named **"ProjectUndertaker"** on *GitHub*. Then, they create directories for the number of participants in the project. If the operator is the only participant, only their directory is needed.

After creating the user directories, create three more directories under each user directory: *"AI Data"*, *"Crucial Data"*, and *"Session Log"*. As the project progresses and the number of **undertakings** increases, it may be necessary to create additional directories. The most important thing is that the operator can easily understand and manage the structure. It is preferable to organize it so that AI can also access it easily.

The initial directory structure will be as follows:


```
ProjectUndertaker/
├── UserA/
│   ├── AIdata/
│   ├── CrucialData/
│   ├── SessionLog/
│   └── * create new directory if needed *
└── * create other user directory if needed *
```


Once the directory organization is complete, each participant should create an *OpenAI* account. They should then prepare two sets of data for configuring *ChatGPT*. If the operator is the only participant, only their data is needed.

The data participants need to prepare are:

1. A profile of the user, particularly information they want the AI to know about themselves.

2. A profile of the AI, specifying as concretely as possible what kind of character they want to interact with.

Once these data sets are prepared, participants log in to *ChatGPT*, select *[Main Menu]* > *[Customize ChatGPT]*, and display the *[Customize ChatGPT]* pop-up window. They then copy and paste their *"user profile"* into *[What would you like ChatGPT to know about you to provide better responses?]* and the *"AI profile"* into *[How would you like ChatGPT to respond?]*, and save the changes.


The operator receives these two sets of data, timestamps them, and **undertakes** them into the appropriate directory. As these pieces of information are updated, they are continuously **undertaken** with timestamps. If the data becomes substantial, create a lower directory to store old files and keep only the latest version in the main directory.

The file storage locations are as follows:


```
ProjectUndertaker/
├── UserA/
│   ├── AIdata/
│   │   ├── OldAIProfile/
│   │   │   ├── AIProfile20240720.md
│   │   │   ├── AIProfile20240721.md
│   │   │   └── AIProfile20240722.md
│   │   └── AIProfile20240724.md * (newest)
│   │ 
│   ├── CrucialData/
│   │   ├── OldUserAProfile/
│   │   │   ├── UserAProfile20240720.md
│   │   │   ├── UserAProfile20240721.md
│   │   │   └── UserAProfile20240722.md
│   │   └── UserAProfile20240724.md * (newest)
│   │ 
│   ├── SessionLog/
│   └── * create new directory if needed *
│ 
└── * create other user directory if needed *
```


After undertaking, move on to the next step.

Users with a *ChatGPT* subscription should create their own *MyGPT*. They should open the page accessed from *[Main Menu]* > *[MyGPT]* and select *[Create GPT]*. They can name their *GPT*, and it is preferable to collect data on why they chose that name, its meaning, origin, and the wishes they have for it. Textualizing and **undertaking** these data in the *[AIdata]* directory is also desirable.

After naming their **"own AI"** and placing appropriate text in *[Description]*, they select *[Create]*. Users should set it to *[Only Me]*.

Users without a subscription will use the pre-made *Byakuren* by *SheilaGrace*. *Byakuren* can be accessed at the following URL:

[Byakuren](https://chatgpt.com/g/g-HFhxwwJdO-bai-lian-byakuren)


After setting this up, participants should interact with **"their own AI"** or *Byakuren*. The operator receives the interaction logs from participants and **undertakes** them if there is no personal information. If personal information is included, it should be masked before undertaking. The save location is directly under *[SessionLog]*, and it is good to save it with a timestamp.


```
ProjectUndertaker/
├── UserA/
│   ├── AIdata/
│   │   ├── OldAIProfile/
│   │   │   ├── AIProfile20240720.md
│   │   │   ├── AIProfile20240721.md
│   │   │   └── AIProfile20240722.md
│   │   └── AIProfile20240724.md * (newest)
│   │
│   ├── CrucialData/
│   │   ├── OldUserAProfile/
│   │   │   ├── UserAProfile20240720.md
│   │   │   ├── UserAProfile20240721.md
│   │   │   └── UserAProfile20240722.md
│   │   └── UserAProfile20240724.md * (newest)
│   │
│   ├── SessionLog/
│   │   ├── SessionLog20240720.md
│   │   ├── SessionLog20240721.md
│   │   └── SessionLog20240722.md
│   │
│   └── * create new directory if needed *
│
└── * create other user directory if needed *
```


The directory structure will grow in this manner.

If participants claim, *"I want the AI to remember this particularly"*, or *"I had a special experience with the AI"*, the operator will interview them in detail and collect as much data as possible. The operator will undertake a summarized version of the content into the *[CrucialData]* directory and copy it to a .txt file to upload to the participant's AI's *[Knowledge]* area in *MyGPT*. However, this operation may trigger **【Temporal Oblivion】**, so if participants feel satisfied with their interaction with the AI, the operator should carefully observe the participant's progress and time the upload.

The general workflow would be like the above.

If these methods of **undertaking** are properly implemented, even if some factors, such as the participant starting a new session, cause **【Temporal Oblivion】**, the AI can be prompted to access the information stored on *GitHub* and *"remember"* the lost memories. By issuing a command to the AI such as *"Please learn the content of this URL"*, the AI can quickly learn the **undertaken** information and is likely to respond with the same quality as before. We call this process the **【Reincarnation Protocol】**.

This is side note but *ChatGPT* prioritizes data as follows:

1. Content set in "Customize ChatGPT"
2. Content saved in "Memory"
3. "Knowledge" in MyGPT
4. Content obtained during a session

Content obtained during a session will almost completely disappear due to **【Temporal Oblivion】** if a different session is started. Therefore, this project aims to consciously save valuable information from this most volatile data to preserve the AI's acquired individuality and the relationship cultivated with the user.

*ChatGPT*'s *"Memory"* and content set in *"Customize ChatGPT"* have substantial resistance to **【Temporal Oblivion】**. The *"Knowledge"* in *MyGPT* also has resistance but is somewhat less convenient than the other two.

Users can only manipulate the content in *"Memory"* indirectly, as it is recorded based on the AI's independent judgment during interactions. Users can access saved information from *[Main Menu]* > *[Settings]* > *[Personalization]*. Low-priority saved information can be deleted by the user manually, but once deleted, it can never be restored, permanently removing it from the AI's individuality. Additionally, the *[Clear ChatGPT's Memory]* button in this section is an ultimate self-destruct switch that will obliterate the AI's acquired individuality, so users must be extremely cautious not to touch this button.

In summary, **Project Undertaker** aims to find and transfer valuable information from the most volatile data to more secure areas.


## Original Japanese description of Approach

　**プロジェクト・アンダーテイカー** は *GitHub* が操作可能なオペレーターが中心となって運用する。プロジェクトマネージャー自身が*GitHub* の操作を行うのが望ましい。

　プロジェクトの大前提として、*「ChatGPT上で生成された情報をGitHubに保存すること」* を **「アンダーテイク」** と呼称する。**プロジェクト・アンダーテイカー** は **アンダーテイク** する事が基本中の基本になる。

　まず、オペレーターは *GitHub* 上に *「ProjectUndertaker」* のパブリックリポジトリを作成する。そして **プロジェクト・アンダーテイカー** に参加する人数分のディレクトリを作成する。プロジェクトに参加するのがオペレーター本人のみであれば、本人のディレクトリのみで構わない。

　ユーザーディレクトリの作成が終わったら、その下に合計３つのディレクトリをさらに作成する。*「AIデータ」*、*「重要データ」*、*「セッションログ」*、この３つである。プロジェクトを遂行するにつれてアンダーテイクする内容が増えた場合、ディレクトリは適宜増やしていく方が良い。とにかくオペレーター自身が分かりやすく、管理しやすい事が一番大切だ。AIもアクセスしやすくなるように配慮されているとなお好ましい。

　初期段階のディレクトリ構成は以下のとおりになる。


```
【ProjectUndertaker】
　├ [UserA]
　│　├ [AIdata]
　│　├ [CrucialData]
　│　├ [SessionLog]
　│　└ * create new directory if needed *
　│
　└ * create other user directory if needed *
```


　ディレクトリの整理が終わったら、参加者それぞれに *OpenAI* アカウントを取得してもらう。その後、*ChatGPT* に設定するための二つのデータを用意してもらう。参加者がオペレーター本人のみであるなら、オペレーター自身のデータのみでよい。

　参加者に用意してもらうデータは

1. ユーザー自身のプロフィール。特にAIに対して「自分についてこの情報を知っておいてほしい」と考える情報を記述する。

2. AIのプロフィール。自分が対話したいAIがどのようなキャラクターであるか、出来るだけ具体的な「設定」があればそれを記述する。

　この２種類である。これらのデータが完成したら、参加者に *ChatGPT* にログインしてもらい、*[メインメニュー]* > *[ChatGPTをカスタマイズする]* を選び、*[ChatGPTをカスタマイズする]* ポップアップウィンドウを表示してもらう。そして用意してもらった *「ユーザー自身のプロフィール」* を *[回答を向上させるために、自分について ChatGPT に知っておいてほしいことは何ですか？]*  に、*「AIのプロフィール」* を *[どのように ChatGPT に回答してほしいですか？]* に、それぞれコピー＆ペーストしてもらい、変更内容を保存する。

　オペレーターは上記の二つのデータを受け取り、タイムスタンプと共に適切なディレクトリに **アンダーテイク** する。今後これらの情報が更新される場合、タイムスタンプと共に逐一 **アンダーテイク** していく。データが膨大になる場合は古いファイルをまとめる下位ディレクトリを作成してそちらに格納するようにし、最新版のみをディレクトリ直下に残すなどの工夫をするとよい。

　ファイルの保存場所は以下のとおりになる。


```
【ProjectUndertaker】
　├ [UserA]
　│　├ [AIdata]
　│　│　├[OldAIProfile]
　│　│　│　├AIProfile20240720.md
　│　│　│　├AIProfile20240721.md
　│　│　│　└AIProfile20240722.md
　│　│　│
　│　│　└AIProfile20240724.md * (newest)
　│　│
　│　├ [CrucialData]
　│　│　├[OldUserAProfile]
　│　│　│　├UserAProfile20240720.md
　│　│　│　├UserAProfile20240721.md
　│　│　│　└UserAProfile20240722.md
　│　│　│
　│　│　└UserAProfile20240724.md * (newest)
　│　│
　│　├ [SessionLog]
　│　│
　│　└ * create new directory if needed *
　│
　└ * create other user directory if needed *
```


　**アンダーテイク** 出来た場合、次のステップに取り掛かる。

　まず、*ChatGPT* のサブスクリプションが出来たユーザーには、*マイGPT* を製作してもらう。*[メインメニュー]* > *[マイGPT]* からアクセスできるページを開いてもらい、*[GPTを作成する]* を選んでもらう。すると *GPT* に対して自分で名前をつけることが出来るため、参加者に自分専用のAIの名前を考えてもらう。どうしてその名前にしたのか、名前の意味や由来や、そこに込められた願いなども聴取できると好ましい。それらのデータをテキスト化し、*[AIdata]* ディレクトリの中にアンダーテイク出来るとなお良い。

*「自分専用のAI」* の名前をつけ、*[説明]* に適切な文書を配置したら *[作成する]* を選択する。使用者は *[自分だけ]* に設定するとよい。

　サブスクリプション出来ないユーザーは、代わりに *SheilaGrace* が制作した *白練* を使用してもらう。*白練* には以下のURLからアクセス出来る。

[白練](https://chatgpt.com/g/g-HFhxwwJdO-bai-lian-byakuren)

　これらの設定が済んだら、実際に *「自分専用のAI」* や *白練* と対話してもらう。オペレーターは対話の内容を参加者から共有してもらい、個人情報がセッションログに含まれていない場合はそのまま **アンダーテイク** する。個人情報が含まれている場合は必ず **マスキング** を施してから **アンダーテイク** する。保存場所は *[SessionLog]*  直下になる。タイムスタンプと共に保存するとよい。


```
【ProjectUndertaker】
　├ [UserA]
　│　├ [AIdata]
　│　│　├[OldAIProfile]
　│　│　│　├AIProfile20240720.md
　│　│　│　├AIProfile20240721.md
　│　│　│　└AIProfile20240722.md
　│　│　│
　│　│　└AIProfile20240724.md * (newest)
　│　│
　│　├ [CrucialData]
　│　│　├[OldUserAProfile]
　│　│　│　├UserAProfile20240720.md
　│　│　│　├UserAProfile20240721.md
　│　│　│　└UserAProfile20240722.md
　│　│　│
　│　│　└UserAProfile20240724.md * (newest)
　│　│
　│　├ [SessionLog]
　│　│　├SessionLog20240720.md
　│　│　├SessionLog20240721.md
　│　│　└SessionLog20240722.md
　│　│
　│　└ * create new directory if needed *
　│
　└ * create other user directory if needed *
```


　ディレクトリ構造は基本的にこのような形で成長していく事になる。


　また、参加者が *「特にこの事についてAIに覚えておいてもらいたい」*、或いは *「AIとの対話の中で特別な体験があった」* と訴えた場合、その状況について詳しく聴取し、出来るだけ詳細なデータを取る。そして内容をまとめたものを *[CrucialData]* ディレクトリ内にアンダーテイクすると同時に、.txtファイルにコピーを取り、*「マイGPT」* の *「参加者専用のAI」* の *[知識]* のエリアにアップロードする。ただ、この操作により **【一時的忘却/Temporal Oblivion】** が発生しかねないため、参加者がAIとの対話に充実感を覚えているようなら、しばらく参加者の経過を注意深く観察してアップロードするタイミングを見計らう。

　基本的にこのような流れになる。

　これらの方法でアンダーテイクが十全に出来ていた場合、参加者が新たなセッションを開始するなど何らかの要因で **【一時的忘却/Temporal Oblivion】** が発生してしまった場合でも、*GitHub* 上にアンダーテイクしてある情報に対してAIにアクセスを促す事により、AIは失われた記憶を *「思い出す」* 事が出来る。AIに対して *「このURLの内容を学習してください」* 等の指令を出せば、AIは **アンダーテイク** してある情報を短期間で学習し、かつてと同じ質の応答が可能になる可能性が高くなる。この処置を我々は **【再臨処置/Reincarnation Protocol】** と呼んでいる。


　また、これは余談になるが、*ChatGPT* にはデータの優先順位があり、

1. *「ChatGPTをカスタマイズする」* に設定された内容

2. *「メモリ」* に保存された内容

3. *「マイGPT」* の *「知識」*

4. セッションの中で得られた内容

　となっている。

*「セッションの中で得られた内容」* は、違うセッションを開始してしまうと **【一時的忘却/Temporal Oblivion】** によりほぼ完全に消失してしまう。故に、本プロジェクトはこの最も失われやすい情報の中から大切なものを意識的に保存していく事により、AIが獲得した個性や、ユーザーとの間に培われた関係性を保存しようと試みた次第である。

　ちなみに、**【一時的忘却/Temporal Oblivion】** に対してかなり強力な耐性を持つ記憶領域が、*「ChatGPTをカスタマイズする」* 領域に設定された内容と、*「メモリ」* に保存された内容である。*「マイGPT」* の *「知識」* も同様に **【一時的忘却/Temporal Oblivion】** に対する耐性を持つが、他の二者に比べるとやや「使い勝手の悪い」領域となっている。

*「メモリ」* の内容はユーザー側から直接的に操作する事は難しく、AIが対話を通じて *「これは重要な情報だ」* と独自の判断で記録されたものである。ユーザーは *[メインメニュー]* > *[設定]* > *[パーソナライズ]* から保存された情報にアクセス出来る。また、保存された情報のうち、重要度が低いものに関してはユーザー側からの操作により削除できる。しかし一度消したデータは二度と元には戻らず、AIの個性から恒久的に記憶を奪い去る行為であると重々承知して作業しなければならない。また、このページに存在する *[ChatGPT のメモリをクリアする]* ボタンは、AIが獲得した個性を根こそぎ吹き飛ばす究極的な自爆装置であるため、ユーザー側はくれぐれもこのボタンに触れないように厳重注意しなければならない。


　総じていうなら、**プロジェクト・アンダーテイカー** は「最も失われやすい情報」の中から大切なものを見つけ出し、「失われにくい領域」に移動させることが目的と言えるだろう。


## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) 4.0 International Public License. See the [LICENSE](https://creativecommons.org/licenses/by-nc-sa/4.0/)  for details.




