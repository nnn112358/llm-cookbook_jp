![figures/C0/readme.jpg](figures/C0/readme.jpg)

# 開発者向け大規模言語モデルハンドブック - LLM Cookbook

## プロジェクト概要

本プロジェクトは開発者向けの大規模言語モデルハンドブックです。国内開発者の実際のニーズに対応し、LLMの全方位入門実践を主軸としています。本プロジェクトはAndrew Ng先生の大規模言語モデル系列講座内容に基づき、元の講座内容を選別・翻訳・再現・最適化し、Prompt Engineeringから RAG開発、モデル微調整まで全ての流れをカバーしています。国内の学習者に最も適した方法で、国内開発者がLLM関連プロジェクトを学習・入門する方法を指導します。

異なる内容の特徴に応じて、合計11のAndrew Ng先生の大規模言語モデル講座を翻訳・再現し、国内学習者の実際の状況と組み合わせて、異なる講座を分級・順序付けしました。初学者はまず我々の必修クラス講座を体系的に学習し、LLMのすべての方向に入門するために必要な基礎スキルと概念を習得してから、選択的に我々の選修クラス講座を学習し、自分の興味のある方向で継続的に探求・学習することができます。

もしあなたが非常に気に入っているが、我々がまだ再現していないAndrew Ng先生の大規模言語モデル講座がある場合、すべての開発者が我々の既存講座の形式と書き方を参考にして講座を再現し、PRを提出することを歓迎します。PR審査通過後、講座内容に応じて講座を分級・統合します。すべての開発者の貢献を歓迎します！

**オンライン読書アドレス：[開発者向けLLM入門講座 - オンライン読書](https://datawhalechina.github.io/llm-cookbook/)**

**PDFダウンロードアドレス：[開発者向けLLM入門チュートリアル - PDF](https://github.com/datawhalechina/llm-cookbook/releases/tag/v1%2C0%2C0)**

**英語原版アドレス：[Andrew Ngの大規模言語モデル系列講座](https://learn.deeplearning.ai)**

## プロジェクトの意義

LLMは徐々に人々の生活を変えており、開発者にとって、LLMが提供するAPIに基づいて迅速・便利により強力な能力を持ち、LLMを統合したアプリケーションを開発し、より新しく実用的な能力を便利に実現することは、急務の重要な能力です。

Andrew Ng先生とOpenAIが協力して発表した大規模言語モデル系列チュートリアルは、大規模言語モデル時代の開発者の基礎スキルから出発し、大規模言語モデルAPI、LangChainアーキテクチャに基づいて大規模言語モデルの強力な能力を結合したアプリケーションを迅速に開発する方法を分かりやすく紹介しています。その中で、《Prompt Engineering for Developers》チュートリアルはLLMに入門する開発者向けで、開発者にとってPromptを構築し、OpenAIが提供するAPIに基づいて要約、推論、変換など多種の常用機能を実現する方法を分かりやすく紹介し、LLM開発の入門の古典チュートリアルです；《Building Systems with the ChatGPT API》チュートリアルはLLMに基づいてアプリケーションプログラムを開発したい開発者向けで、ChatGPT APIに基づいて完全な対話システムを構築する方法を簡潔で効果的かつ体系的で全面的に紹介しています；《LangChain for LLM Application Development》チュートリアルは古典的な大規模言語モデルオープンソースフレームワークLangChainと結合し、LangChainフレームワークに基づいて実用機能を備え、能力全面的なアプリケーションプログラムを開発する方法を紹介し、《LangChain Chat With Your Data》チュートリアルはこれに基づいてさらにLangChainアーキテクチャを使用して個人プライベートデータと結合してパーソナライズ大規模言語モデルアプリケーションを開発する方法を紹介しています；《Building Generative AI Applications with Gradio》、《Evaluating and Debugging Generative AI》チュートリアルはそれぞれ2つの実用ツールGradioとW&Bを紹介し、開発者がこれら2つのツールを結合して生成式AIアプリケーションを構築・評価する方法を指導します。

上述のチュートリアルは開発者がLLMに基づいて実際にアプリケーションプログラムを構築する道を開くための学習に非常に適用できます。そのため、我々はこの系列講座を中国語に翻訳し、その範例コードを再現し、その中の1つのビデオに中国語字幕を追加し、国内中国語学習者の直接使用をサポートし、中国語学習者がLLM開発をより良く学習することを支援します；我々は同時に効果がほぼ相当する中国語Promptを実現し、学習者が中国語文脈下でのLLMの学習使用を感じることをサポートし、多言語文脈下でのPrompt設計とLLM開発を対比して習得します。将来、我々はより多くのPrompt高級技巧を加入し、本講座内容を豊富にし、開発者がより多く、より巧妙なPromptスキルを習得することを支援します。

## プロジェクト対象者

基礎的なPython能力を持ち、LLMに入門したいすべての開発者。

## プロジェクトのハイライト

《ChatGPT Prompt Engineering for Developers》、《Building Systems with the ChatGPT API》等のチュートリアルはAndrew Ng先生とOpenAIが共同発表した公式チュートリアルとして、予見可能な将来においてLLMの重要な入門チュートリアルになりますが、現在はまだ英語版のみをサポートし、国内のアクセスに制限があるため、中国語版で国内でスムーズにアクセスできるチュートリアルを構築することは重要な意義を持ちます；同時に、GPTは中国語、英語に対して異なる理解能力を持つため、本チュートリアルは多回の対比・実験後に効果がほぼ相当する中国語Promptを確定し、学習者がChatGPTの中国語文脈下での理解と生成能力を向上させる方法を研究することをサポートします。


## 学習ガイド

本チュートリアルは基礎的なPython能力を持ち、LLMに入門したいすべての開発者に適用されます。

本チュートリアルの学習を開始したい場合、事前に以下を備える必要があります：

1. 少なくとも1つのLLM API（最好はOpenAI、他のAPIの場合、[他のチュートリアル](https://github.com/datawhalechina/llm-universe)を参考してAPI呼び出しコードを修正する必要がある場合があります）
2. Python Jupyter Notebookを使用できること

本チュートリアルは合計11の講座を含み、必修クラス、選修クラスの2つのカテゴリーに分かれています。必修クラス講座は我々が初学者がLLMに入門するために学習するのに最も適していると考える講座で、LLMのすべての方向に入門するために必要な基礎スキルと概念を含み、我々は必修クラス講座に対して読書に適したオンライン読書とPDF版も制作しました。必修クラス講座を学習する際は、我々が列挙した順序に従って学習することを推奨します；選修クラス講座は必修クラス講座の拡張延長で、RAG開発、モデル微調整、モデル評価など多くの方面を含み、学習者が必修クラス講座を習得した後に自分の興味のある方向と講座を選択して学習するのに適しています。

必修クラス講座には以下が含まれます：

1. 開発者向けPrompt Engineering。Andrew Ng先生の《ChatGPT Prompt Engineering for Developers》講座に基づいて構築、LLMに入門する開発者向けで、開発者にとってPromptを構築し、OpenAIが提供するAPIに基づいて要約、推論、変換など多種の常用機能を実現する方法を分かりやすく紹介し、LLM開発入門の第一歩です。
2. ChatGPTに基づく質問応答システムの構築。Andrew Ng先生の《Building Systems with the ChatGPT API》講座に基づいて構築、開発者がChatGPTが提供するAPIに基づいて完全で全面的な知能質問応答システムを開発する方法を指導します。コード実践を通じて、ChatGPTに基づく質問応答システム開発の全プロセスを実現し、大規模言語モデルに基づく開発の新しいパラダイムを紹介し、大規模言語モデル開発の実践基礎です。
3. LangChainを使用したアプリケーションプログラム開発。Andrew Ng先生の《LangChain for LLM Application Development》講座に基づいて構築、LangChainを深く紹介し、学習者がLangChainの使用方法を理解し、LangChainに基づいて完全で強力な能力を持つアプリケーションプログラムを開発することを支援します。
4. LangChainを使用した個人データアクセス。Andrew Ng先生の《LangChain Chat with Your Data》講座に基づいて構築、LangChainが提供する個人データアクセス能力を深く拡張し、開発者がLangChainを使用してユーザー個人データにアクセスし、パーソナライズサービスを提供する大規模言語モデルアプリケーションを開発する方法を指導します。

選修クラス講座には以下が含まれます：

1. Gradioを使用した生成式AIアプリケーション構築。Andrew Ng先生の《Building Generative AI Applications with Gradio》講座に基づいて構築、開発者がGradioを使用してPythonインターフェースプログラムを通じて迅速・高効率に生成式AIのユーザーインターフェースを構築する方法を指導します。
2. 生成式AIの評価改善。Andrew Ng先生の《Evaluating and Debugging Generative AI》講座に基づいて構築、wandbと結合し、体系化された方法とツールセットを提供し、開発者が効果的に生成式AIモデルを追跡・デバッグすることを支援します。
3. 大規模言語モデルの微調整。Andrew Ng先生の《Finetuning Large Language Model》講座に基づいて構築、laminiフレームワークと結合し、ローカルで個人データに基づいてオープンソース大規模言語モデルを便利・高効率に微調整する方法を講述します。
4. 大規模言語モデルと意味検索。Andrew Ng先生の《Large Language Models with Semantic Search》講座に基づいて構築、検索拡張生成に対して、より正確・高効率な検索拡張LLM生成効果を実現するための多種の高級検索技巧を講述します。
5. Chromaに基づく高級検索。Andrew Ng先生の《Advanced Retrieval for AI with Chroma》講座に基づいて構築、Chromaに基づく高級検索技術を紹介し、検索結果の正確性を向上させることを目指します。
6. 高級RAGアプリケーションの構築と評価。Andrew Ng先生の《Building and Evaluating Advanced RAG Applications》講座に基づいて構築、高品質RAGシステムの構築と実現に必要な核心技術と評価フレームワークを紹介します。
7. LangChainのFunctions、Tools、Agents。Andrew Ng先生の《Functions, Tools and Agents with LangChain》講座に基づいて構築、LangChainの新しい構文に基づいてAgentを構築する方法を紹介します。
8. Prompt高級技巧。CoT、自己一致性など多種のPrompt高級技巧の基礎理論とコード実装を含みます。

その他の資料には以下が含まれます：

**二ヶ国語字幕ビデオアドレス：[Andrew Ng x OpenAIのPrompt Engineering講座専門翻訳版](https://www.bilibili.com/video/BV1Bo4y1A7FU/?share_source=copy_web)**

**中英二ヶ国語字幕ダウンロード：[《ChatGPT プロンプトエンジニアリング》非公式版中英二ヶ国語字幕](https://github.com/GitHubDaily/ChatGPT-Prompt-Engineering-for-Developers-in-Chinese)**

**ビデオ解説：[開発者向けPrompt Engineering解説（デジタルノマド大会）](https://www.bilibili.com/video/BV1PN4y1k7y2/?spm_id_from=333.999.0.0)**


ディレクトリ構造説明：

    content：元の講座に基づいて再現した二ヶ国語版コード、実行可能なNotebook、更新頻度最高、更新速度最速。
    
    docs：必修クラス講座テキストチュートリアル版オンライン読書ソースコード、読書に適したMarkdown。
    
    figures：画像ファイル。

## 謝辞

**コア貢献者**

- [邹雨衡 - プロジェクト責任者](https://github.com/logan-zou)（Datawhaleメンバー - 対外経済貿易大学大学院生）
- [左春生-プロジェクト責任者](https://github.com/LinChentang)（コンテンツクリエイター-Datawhaleメンバー）
- [長琴 - プロジェクト発起人](https://yam.gift/)（コンテンツクリエイター - Datawhaleメンバー - AIアルゴリズムエンジニア）
- [玉琳 - プロジェクト発起人](https://github.com/Sophia-Huang)（コンテンツクリエイター - Datawhaleメンバー）
- [徐虎 - チュートリアル編纂者](https://github.com/xuhu0115)（コンテンツクリエイター - Datawhaleメンバー）
- [刘伟鸿 - チュートリアル編纂者](https://github.com/Weihong-Liu)（コンテンツクリエイター - 江南大学非正規大学院生）
- [Joye - チュートリアル編纂者](https://Joyenjoye.com)（コンテンツクリエイター - データサイエンティスト）
- [高立业](https://github.com/0-yy-0)（コンテンツクリエイター - Datawhaleメンバー - アルゴリズムエンジニア）
- [邓宇文](https://github.com/GKDGKD)（コンテンツクリエイター - Datawhaleメンバー）
- [魂兮](https://github.com/wisdom-pan)（コンテンツクリエイター - フロントエンドエンジニア）
- [宋志学](https://github.com/KMnO4-zx)（コンテンツクリエイター - Datawhaleメンバー）
- [韩颐堃](https://github.com/YikunHan42)（コンテンツクリエイター - Datawhaleメンバー）
- [陈逸涵](https://github.com/6forwater29) (コンテンツクリエイター - Datawhale意向メンバー - AI愛好者)
- [仲泰](https://github.com/ztgg0228)（コンテンツクリエイター - Datawhaleメンバー）
- [万礼行](https://github.com/leason-wan)（コンテンツクリエイター - ビデオ翻訳者）
- [王熠明](https://github.com/Bald0Wang)（コンテンツクリエイター - Datawhaleメンバー）
- [曾浩龙](https://yetingyun.blog.csdn.net)（コンテンツクリエイター - Datawhale意向メンバー）
- [小饭同学](https://github.com/xinqi-fan)（コンテンツクリエイター）
- [孙韩玉](https://github.com/sunhanyu714)（コンテンツクリエイター - アルゴリズム量化配備エンジニア）
- [张银晗](https://github.com/YinHan-Zhang)（コンテンツクリエイター - Datawhaleメンバー）
- [左春生](https://github.com/LinChentang)（コンテンツクリエイター - Datawhaleメンバー）
- [张晋](https://github.com/Jin-Zhang-Yaoguang)（コンテンツクリエイター - Datawhaleメンバー）
- [李娇娇](https://github.com/Aphasia0515)（コンテンツクリエイター - Datawhaleメンバー）
- [邓恺俊](https://github.com/Kedreamix)（コンテンツクリエイター - Datawhaleメンバー）
- [范致远](https://github.com/Zhiyuan-Fan)（コンテンツクリエイター - Datawhaleメンバー）
- [周景林](https://github.com/Beyondzjl)（コンテンツクリエイター - Datawhaleメンバー）
- [诸世纪](https://github.com/very-very-very)（コンテンツクリエイター - アルゴリズムエンジニア）
- [Zhang Yixin](https://github.com/YixinZ-NUS)（コンテンツクリエイター - IT愛好者）
- Sarai（コンテンツクリエイター - AIアプリケーション愛好者）


**その他**

1. [@Sm1les](https://github.com/Sm1les)、[@LSGOMYP](https://github.com/LSGOMYP)の本プロジェクトへの支援に特別感謝します；
2. [GithubDaily](https://github.com/GitHubDaily)が提供した二ヶ国語字幕に感謝します；
3. 何かアイデアがありましたらDatawhaleまでご連絡ください。また、皆様のIssues提出も歓迎します；
4. チュートリアルに貢献していただいた以下の皆様に特別感謝します！

<a href="https://datawhalechina.github.io/llm-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=datawhalechina/llm-cookbook" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=datawhalechina/llm-cookbook&type=Date)](https://star-history.com/#datawhalechina/llm-cookbook&Date)


## フォローする

<div align=center>
<p>下のQRコードをスキャンして公式アカウントをフォロー：Datawhale</p>
<img src="figures/qrcode.jpeg" width = "180" height = "180">
</div>
DatawhaleはデータサイエンスとAI分野に特化したオープンソース組織で、多くの分野の大学と知名企業の優秀な学習者を集め、オープンソース精神と探求精神を持つチームメンバーのグループを統合しています。WeChatで公式アカウントDatawhaleを検索して参加できます。

## LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />この作品は<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">クリエイティブ・コモンズ 表示 - 非営利 - 継承 4.0 国際 ライセンス</a>の下にライセンスされています。
