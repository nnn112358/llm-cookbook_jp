![figures/readme.jpg](figures/readme.jpg)

# 開発者向け大規模言語モデルハンドブック - LLM Cookbook

## プロジェクト概要

本プロジェクトは開発者向けの大規模言語モデルハンドブックで、日本国内の開発者の実際のニーズに対応し、LLMの全方位的な入門実践を主眼としています。本プロジェクトは Andrew Ng 先生の大規模モデルシリーズコースの内容に基づき、オリジナルコースの内容を選別、翻訳、再現、最適化し、Prompt Engineering から RAG 開発、モデルファインチューニングまでの全プロセスをカバーし、日本国内の学習者に最も適した方法で、開発者がLLM関連プロジェクトを学習し、入門する方法を指導します。

異なる内容の特徴に応じて、私たちは合計11のAndrew Ng先生の大規模モデルコースを翻訳・再現し、日本国内の学習者の実情に合わせて、異なるコースをレベル分けし、順序付けしました。初心者はまず私たちの必修コースを体系的に学習し、LLMのすべての方向で習得すべき基礎スキルと概念を身につけ、その後選択的に選択コースを学習し、自分の興味のある方向で継続的に探求と学習を行うことができます。

もしあなたが非常に気に入っているが、まだ再現していないAndrew Ng先生の大規模モデルコースがあれば、私たちは既存のコースのフォーマットと書き方を参考にして、コースを再現しPRを提出することを歓迎します。PRの審査が通過した後、コース内容に基づいてコースをレベル分けし統合します。すべての開発者の貢献を歓迎します！

**オンライン閲覧アドレス：[開発者向けLLM入門コース - オンライン閲覧](https://datawhalechina.github.io/llm-cookbook/)**

**PDFダウンロードアドレス：[開発者向けLLM入門チュートリアル - PDF](https://github.com/datawhalechina/llm-cookbook/releases/tag/v1%2C0%2C0)**

**英語原版アドレス：[Andrew Ngの大規模モデルに関するシリーズコース](https://learn.deeplearning.ai)**

## プロジェクトの意義

LLMは人々の生活を徐々に変えつつあり、開発者にとって、LLMが提供するAPIに基づいて、より強力な能力を持ち、LLMを統合したアプリケーションを迅速かつ便利に開発し、より斬新で実用的な機能を便利に実現する方法は、緊急に学習すべき重要な能力です。

Andrew Ng先生とOpenAIが共同で推出した大規模モデルシリーズチュートリアルは、大規模モデル時代の開発者の基礎スキルから出発し、大規模モデルAPIとLangChainアーキテクチャに基づいて、大規模モデルの強力な能力を組み合わせたアプリケーションを迅速に開発する方法を分かりやすく紹介しています。その中で、『Prompt Engineering for Developers』チュートリアルはLLMに入門する開発者向けに、開発者がPromptを構築し、OpenAIが提供するAPIに基づいて要約、推論、変換などの多様な一般的な機能を実現する方法を分かりやすく紹介しており、LLM開発に入門するための古典的なチュートリアルです。『Building Systems with the ChatGPT API』チュートリアルはLLMに基づいてアプリケーションを開発したい開発者向けに、ChatGPT APIに基づいて完全な対話システムを構築する方法を簡潔で効果的かつ体系的に紹介しています。『LangChain for LLM Application Development』チュートリアルは古典的な大規模モデルオープンソースフレームワークLangChainと組み合わせて、LangChainフレームワークに基づいて実用的な機能と包括的な能力を持つアプリケーションを開発する方法を紹介し、『LangChain Chat With Your Data』チュートリアルはさらにLangChainアーキテクチャを使用して個人のプライベートデータと組み合わせて個人化された大規模モデルアプリケーションを開発する方法を紹介しています。『Building Generative AI Applications with Gradio』、『Evaluating and Debugging Generative AI』チュートリアルはそれぞれGradioとW&Bという2つの実用的なツールを紹介し、開発者がこれらのツールを組み合わせて生成AIアプリケーションを構築し、評価する方法を指導しています。

上記のチュートリアルは、開発者がLLMに基づいて実際にアプリケーションを構築する道を開くための学習に非常に適しています。そのため、私たちはこのシリーズのコースを日本語に翻訳し、そのサンプルコードを再現し、そのうちの1つのビデオに日本語字幕を追加し、日本国内の日本語学習者が直接使用できるようにサポートし、日本語学習者がLLM開発をよりよく学習できるようにしています。また、効果がほぼ同等の日本語Promptも実装し、学習者が日本語環境でのLLMの学習と使用を体験し、多言語環境でのPrompt設計とLLM開発を比較して習得できるようにサポートしています。将来的には、より多くのPrompt高度なテクニックを追加し、このコースの内容を豊かにし、開発者がより多く、より巧妙なPromptスキルを習得できるようにします。

## プロジェクト対象者

基礎的なPython能力を持ち、LLMに入門したいすべての開発者。

## プロジェクトのハイライト

『ChatGPT Prompt Engineering for Developers』、『Building Systems with the ChatGPT API』などのチュートリアルは、Andrew Ng先生とOpenAIが共同で推出した公式チュートリアルとして、予見可能な将来にLLMの重要な入門チュートリアルになるでしょう。しかし、現在は英語版のみをサポートしており、日本国内からのアクセスが制限されているため、日本語版を作成し、日本国内でスムーズにアクセスできるチュートリアルを構築することは重要な意義があります。同時に、GPTは日本語と英語に対して異なる理解能力を持っています。本チュートリアルは、複数の比較と実験の後、効果がほぼ同等の日本語Promptを確定し、学習者がChatGPTの日本語環境での理解と生成能力を向上させる方法を研究することをサポートします。


## 学習ガイド

本チュートリアルは、基礎的なPython能力を持ち、LLMに入門したいすべての開発者に適しています。

本チュートリアルの学習を開始する場合、事前に以下を準備する必要があります：

1. 少なくとも1つのLLM API（OpenAIが最適です。他のAPIの場合は、[他のチュートリアル](https://github.com/datawhalechina/llm-universe)を参考にしてAPIコールコードを修正する必要があるかもしれません）
2. Python Jupyter Notebookを使用できること

本チュートリアルは合計11のコースを含み、必修コースと選択コースの2つのカテゴリに分かれています。必修コースは、初心者がLLMに入門するために最も適していると考えるコースで、LLMのすべての方向で習得すべき基礎スキルと概念を含んでいます。必修コースについては、読みやすいオンライン版とPDF版も作成しました。必修コースを学習する際は、私たちがリストした順序で学習することをお勧めします。選択コースは必修コースの拡張と延長で、RAG開発、モデルファインチューニング、モデル評価など多くの側面を含み、学習者が必修コースを習得した後、自分の興味のある方向とコースを選択して学習するのに適しています。

必修コースには以下が含まれます：

1. 開発者向けのPrompt Engineering。Andrew Ng先生の『ChatGPT Prompt Engineering for Developers』コースに基づいて構築され、LLMに入門する開発者向けに、開発者がPromptを構築し、OpenAIが提供するAPIに基づいて要約、推論、変換などの多様な一般的な機能を実現する方法を分かりやすく紹介し、LLM開発に入門する最初のステップです。
2. ChatGPTに基づくQ&Aシステムの構築。Andrew Ng先生の『Building Systems with the ChatGPT API』コースに基づいて構築され、開発者がChatGPTが提供するAPIに基づいて完全かつ包括的なインテリジェントQ&Aシステムを開発する方法を指導します。コード実践を通じて、ChatGPTに基づくQ&Aシステム開発の全プロセスを実装し、大規模モデル開発の新しいパラダイムを紹介し、大規模モデル開発の実践基礎です。
3. LangChainを使用したアプリケーション開発。Andrew Ng先生の『LangChain for LLM Application Development』コースに基づいて構築され、LangChainについて詳しく紹介し、学習者がLangChainの使用方法を理解し、LangChainに基づいて完全で強力な機能を持つアプリケーションを開発できるよう支援します。
4. LangChainを使用した個人データへのアクセス。Andrew Ng先生の『LangChain Chat with Your Data』コースに基づいて構築され、LangChainが提供する個人データアクセス機能を深く拡張し、開発者がLangChainを使用してユーザーの個人データにアクセスし、パーソナライズされたサービスを提供する大規模モデルアプリケーションを開発する方法を指導します。

選択コースには以下が含まれます：

1. Gradioを使用した生成AIアプリケーションの構築。Andrew Ng先生の『Building Generative AI Applications with Gradio』コースに基づいて構築され、開発者がGradioを使用してPythonインターフェースプログラムを通じて生成AIのためのユーザーインターフェースを迅速かつ効率的に構築する方法を指導します。
2. 生成AIの評価と改善。Andrew Ng先生の『Evaluating and Debugging Generative AI』コースに基づいて構築され、wandbと組み合わせて、開発者が生成AIモデルを効果的に追跡し、デバッグするための体系的な方法とツールを提供します。
3. 大規模言語モデルのファインチューニング。Andrew Ng先生の『Finetuning Large Language Model』コースに基づいて構築され、laminiフレームワークと組み合わせて、個人データに基づいてオープンソースの大規模言語モデルをローカルで便利かつ効率的にファインチューニングする方法を説明します。
4. 大規模モデルと意味検索。Andrew Ng先生の『Large Language Models with Semantic Search』コースに基づいて構築され、検索拡張生成に対応し、より正確かつ効率的な検索拡張LLM生成効果を実現するための多様な高度な検索技術を説明します。
5. Chromaに基づく高度検索。Andrew Ng先生の『Advanced Retrieval for AI with Chroma』コースに基づいて構築され、Chromaに基づく高度検索技術を紹介し、検索結果の精度を向上させることを目的としています。
6. 高度RAGアプリケーションの構築と評価。Andrew Ng先生の『Building and Evaluating Advanced RAG Applications』コースに基づいて構築され、高品質RAGシステムを構築し実装するために必要な主要技術と評価フレームワークを紹介します。
7. LangChainのFunctions、Tools、Agents。Andrew Ng先生の『Functions, Tools and Agents with LangChain』コースに基づいて構築され、LangChainの新しい構文に基づいてAgentを構築する方法を紹介します。
8. Prompt高度テクニック。CoT、自己一貫性などの多様なPrompt高度テクニックの基礎理論とコード実装を含みます。

その他の資料には以下が含まれます：

**バイリンガル字幕付きビデオアドレス：[Andrew Ng x OpenAIのPrompt Engineeringコースプロフェッショナル翻訳版](https://www.bilibili.com/video/BV1Bo4y1A7FU/?share_source=copy_web)**

**日英バイリンガル字幕ダウンロード：[『ChatGPTプロンプトエンジニアリング』非公式版日英バイリンガル字幕](https://github.com/GitHubDaily/ChatGPT-Prompt-Engineering-for-Developers-in-Chinese)**

**ビデオ解説：[開発者向けPrompt Engineering解説（デジタルノマド大会）](https://www.bilibili.com/video/BV1PN4y1k7y2/?spm_id_from=333.999.0.0)**


ディレクトリ構造の説明：

    content：オリジナルコースに基づいて再現されたバイリンガルコード、実行可能なNotebook、更新頻度が最も高く、更新速度が最も速い。
    
    docs：必修コースのテキストチュートリアル版オンライン閲覧ソースコード、読みやすいMarkdown。
    
    figures：画像ファイル。

## 謝辞

**コアコントリビューター**

- [邹雨衡-项目负责人](https://github.com/logan-zou)（Datawhale成员-对外经济贸易大学研究生）
- [左春生-项目负责人](https://github.com/LinChentang)（内容创作者-Datawhale成员）
- [长琴-项目发起人](https://yam.gift/)（内容创作者-Datawhale成员-AI算法工程师）
- [玉琳-项目发起人](https://github.com/Sophia-Huang)（内容创作者-Datawhale成员）
- [徐虎-教程编撰者](https://github.com/xuhu0115)（内容创作者-Datawhale成员）
- [刘伟鸿-教程编撰者](https://github.com/Weihong-Liu)（内容创作者-江南大学非全研究生）
- [Joye-教程编撰者](https://Joyenjoye.com)（内容创作者-数据科学家）
- [高立业](https://github.com/0-yy-0)（内容创作者-DataWhale成员-算法工程师）
- [邓宇文](https://github.com/GKDGKD)（内容创作者-Datawhale成员）
- [魂兮](https://github.com/wisdom-pan)（内容创作者-前端工程师）
- [宋志学](https://github.com/KMnO4-zx)（内容创作者-Datawhale成员）
- [韩颐堃](https://github.com/YikunHan42)（内容创作者-Datawhale成员）
- [陈逸涵](https://github.com/6forwater29) (内容创作者-Datawhale意向成员-AI爱好者)
- [仲泰](https://github.com/ztgg0228)（内容创作者-Datawhale成员）
- [万礼行](https://github.com/leason-wan)（内容创作者-视频翻译者）
- [王熠明](https://github.com/Bald0Wang)（内容创作者-Datawhale成员）
- [曾浩龙](https://yetingyun.blog.csdn.net)（内容创作者-Datawhale 意向成员-JLU AI 研究生）
- [小饭同学](https://github.com/xinqi-fan)（内容创作者）
- [孙韩玉](https://github.com/sunhanyu714)（内容创作者-算法量化部署工程师）
- [张银晗](https://github.com/YinHan-Zhang)（内容创作者-Datawhale成员）
- [张晋](https://github.com/Jin-Zhang-Yaoguang)（内容创作者-Datawhale成员）
- [李娇娇](https://github.com/Aphasia0515)（内容创作者-Datawhale成员）
- [邓恺俊](https://github.com/Kedreamix)（内容创作者-Datawhale成员）
- [范致远](https://github.com/Zhiyuan-Fan)（内容创作者-Datawhale成员）
- [周景林](https://github.com/Beyondzjl)（内容创作者-Datawhale成员）
- [诸世纪](https://github.com/very-very-very)（内容创作者-算法工程师）
- [Zhang Yixin](https://github.com/YixinZ-NUS)（内容创作者-IT爱好者）
- Sarai（内容创作者-AI应用爱好者）

**その他**

1. 特に [@Sm1les](https://github.com/Sm1les)、[@LSGOMYP](https://github.com/LSGOMYP) の本プロジェクトへのサポートと支援に感謝します。
2. [GithubDaily](https://github.com/GitHubDaily) が提供したバイリンガル字幕に感謝します。
3. ご意見があればDatawhaleにご連絡ください。Issuesを多く提出していただくことも歓迎します。
4. チュートリアルに貢献してくださった以下の方々に特に感謝します！

<a href="https://datawhalechina.github.io/llm-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=datawhalechina/llm-cookbook" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=datawhalechina/llm-cookbook&type=Date)](https://star-history.com/#datawhalechina/llm-cookbook&Date)

## フォローしてください

<div align=center>
<p>以下のQRコードをスキャンして公式アカウントをフォロー：Datawhale</p>
<img src="figures/qrcode.jpeg" width = "180" height = "180">
</div>
DatawhaleはデータサイエンスとAI分野に特化したオープンソース組織で、多くの分野の大学や有名企業の優秀な学習者を集め、オープンソース精神と探求精神を持つチームメンバーのグループを集約しています。WeChatで公式アカウントDatawhaleを検索して参加できます。

## ライセンス
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />本作品は<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">クリエイティブ・コモンズ 表示 - 非営利 - 継承 4.0 国際ライセンス</a>の下でライセンスされています。
