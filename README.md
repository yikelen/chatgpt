# ChatGPT-API

基于[OpenAI GPT-3.5 Turbo API](https://platform.openai.com/docs/guides/chat)的演示。

1. 配置环境和安装项目依赖

    > 首先，您需要安装[Node.js。](https://nodejs.org/)

    ```shell
    npm i
    ```

2. 制作一个副本`.env.example`，然后将其重命名为`.env`
3. 将您的[OpenAI API 密钥](https://platform.openai.com/account/api-keys)添加到`.env`
    ```
    OPENAI_API_KEY=sk-xxx...
    ```
4. 运行
    ```shell
    npm run dev
    ```

## Deploy With Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/TsingYi1263/ChatGPT&env=OPENAI_API_KEY&envDescription=OpenAI%20API%20Key&envLink=https://platform.openai.com/account/api-keys)

用Vercel部署，Fork到自己的仓库，填写自己的OpenAI API Key后部署即可。
