# iChatGPT 
命令行下与chatGPT聊天。

# Installation
`pip3 install -r requirements.txt`

## Configuration

1. Create account on [OpenAI's ChatGPT](https://chat.openai.com/)
2. 生成api key备用

## Command line
`python3 chatbotcli.py --api_key <api_key>`

```
 $ python3 chatbotcli.py -h

    ChatGPT - Official ChatGPT API
    Repo: ichatgpt

Type '!help' to show a full list of commands
Press Esc followed by Enter or Alt+Enter to send a message.

usage: chatbotcli.py [-h] --api_key API_KEY [--temperature TEMPERATURE] [--no_stream] [--base_prompt BASE_PROMPT]
             [--proxy PROXY] [--top_p TOP_P] [--reply_count REPLY_COUNT] [--enable-internet]

options:
  -h, --help            show this help message and exit
  --api_key API_KEY     OpenAI API key
  --temperature TEMPERATURE
                        Temperature for response
  --no_stream           Disable streaming
  --base_prompt BASE_PROMPT
                        Base prompt for chatbot
  --proxy PROXY         Proxy address
  --top_p TOP_P         Top p for response
  --reply_count REPLY_COUNT
                        Number of replies for each prompt
  --enable_internet     Allow ChatGPT to access the internet (beta)
```