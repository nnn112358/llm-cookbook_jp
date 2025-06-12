本コースでは`from llama import BasicModelRunner`のようなコードをたくさん見ることになります。多くの学生が`llama`ライブラリをインストールする必要があると思うかもしれませんが、そうではありません。<b>インストールする必要があるのは`lamini`ライブラリです</b>。`llama`は`lamini`ライブラリのサブセットに過ぎません。以下は`lamini`ライブラリのインストールと使用方法の説明です。

## インストール
`lamini`ライブラリのインストールは非常に簡単で、以下のコマンドを実行するだけです：

`pip install lamini`

## 登録
次に[lamini公式サイト](https://www.lamini.ai/)でアカウントを登録し、api keyを取得して、`lamini`ライブラリの全機能を使用する必要があります。
![lamini公式サイト](../../figures/Finetuning%20Large%20Language%20Models/lamini官网.png)

アカウント登録はGoogleメール（デフォルト）または他のメールを使用できます。登録完了後、公式サイトの左上角の`Account`をクリックすると、自分のapi keyと残り使用量を確認できます。

![lamini公式サイト](../../figures/Finetuning%20Large%20Language%20Models/lamini官网_apikey.png)

## 使用方法
### 1. デフォルト方式
`lamini`はデフォルトで、ユーザーディレクトリに設定ファイル`~/.powerml/configure_llama.yaml`を作成し、以下の方式で設定情報を書き込む必要があります：

```
production:
    key: "<YOUR-KEY-HERE>"
```

ユーザーディレクトリは、Windowsシステムでは一般的に`C:\Users\Administrator`、Linux/macOSでは一般的に`~/`です。

### 2. 簡便方式
デフォルト方式が面倒なため、より便利な方法を提供します。`llama`の`LLMEngine`または`BasicModelRunner`クラスを使用する必要がある場合、クラスパラメータ`config`に直接`production.key`を書き込むだけです。例えば：

```
llm = LLMEngine(
    id="example_llm",
    config={"production.key": "<YOUR-KEY-HERE>"}
    )
```

または：
```
non_finetuned = BasicModelRunner("meta-llama/Llama-2-7b-hf", 
                config={"production.key": "<YOUR-KEY-HERE>"})

```

`<YOUR-KEY-HERE>`を`lamini`公式サイトのapi keyに置き換えるだけです。

コードでapi keyが漏洩することを心配する場合は、ChatGPTを使用する方法を参考に、設定ファイルを使用して`production.key`を保存することができます。ここでは詳しく展開しません。
