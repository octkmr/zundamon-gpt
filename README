# GPTに質問したらずんだもんが答えてくれるやつなのだ

## 準備
### ChatGPT API
1. OpenAIのAPIキーを発行するのだ。
https://platform.openai.com/account/api-keys

2. 発行したAPIキーをここにセットするのだ。APIの使用は有料なので気をつけるのだ。

### VOICEVOX ENGINE

1. VOICEVOXの機能を利用できるHTTPサーバなのだ。Docker公式イメージがあるので、これを使うのだ。
```
docker pull voicevox/voicevox_engine:cpu-ubuntu20.04-latest
docker run --rm -p '127.0.0.1:50021:50021' voicevox/voicevox_engine:cpu-ubuntu20.04-latest
```
詳しくは公式を見るのだ。
https://github.com/VOICEVOX/voicevox_engine

### 起動
パッケージインストールして、ローカル環境を立ち上げるのだ。
```
npm i
```
```
npm run server
```