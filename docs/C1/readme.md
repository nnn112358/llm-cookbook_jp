# 第一部分 開発者向けプロンプトエンジニアリング

Prompt（プロンプト）は、元々NLP研究者が下流タスクのために設計した、タスク専用の入力形式またはテンプレートでしたが、ChatGPTが大規模言語モデルの新時代を引き起こした後、Promptは大規模言語モデルとの対話入力の代名詞となりました。つまり、我々は一般的に**大規模言語モデルへの入力をPrompt、大規模言語モデルが返す出力をCompletion**と呼びます。

ChatGPTなどのLLM（大規模言語モデル）の出現により、自然言語処理のパラダイムはPretrain-Finetune（事前訓練-微調整）からPrompt Engineering（プロンプトエンジニアリング）へと変化しています。強力な自然言語理解・生成能力を持ち、多様なタスク処理を実現できるLLMにとって、合理的なPrompt設計は、その能力の上限と下限を大きく決定します。**Prompt Engineeringとは、特定のタスクに対して大規模言語モデルの能力を最大限に発揮できるPromptを構築する技術**です。LLMを十分かつ効率的に使用するために、Prompt Engineeringは不可欠なスキルです。

LLMは徐々に人々の生活を変えており、開発者にとって、LLMが提供するAPIに基づいて迅速かつ便利により強力な能力を持ち、LLMを統合したアプリケーションを開発し、より新しく実用的な能力を便利に実現することは、早急に学習すべき重要な能力です。APIに基づいてLLMを統合したアプリケーションを効率的に開発するには、まずLLMを合理的かつ効率的に使用する方法、つまりPrompt Engineeringの構築方法を学ぶことが最重要です。第一部分の開発者向けプロンプトエンジニアリングは、Andrew Ng先生とOpenAIが協力して発表した《ChatGPT Prompt Engineering for Developers》チュートリアルに基づいており、LLMに入門する開発者向けに、**開発者にとってPromptを構築し、OpenAIが提供するAPIに基づいて要約、推論、変換など多種の常用機能を実現する方法**を分かりやすく紹介し、LLM開発入門の第一歩です。LLMに入門したい開発者は、この部分のPrompt Engineering技術を十分に習得し、上述の技術に基づいてパーソナライズされたカスタム機能を実現できる必要があります。

この部分の主な内容には以下が含まれます：Prompt作成の原則と技術；テキスト要約（ユーザーレビューの要約など）；テキスト推論（感情分類、主題抽出など）；テキスト変換（翻訳、自動校正など）；拡張（メール作成など）など。

**目次：**

1. はじめに Introduction @邹雨衡
2. Promptの構築原則 Guidelines @邹雨衡
3. Promptの反復最適化方法 Itrative @邹雨衡
4. テキスト要約 Summarizing @玉琳
5. テキスト推論 @长琴
6. テキスト変換 Transforming @玉琳
7. テキスト拡張 Expand @邹雨衡
8. チャットボット @长琴
9. まとめ @长琴
