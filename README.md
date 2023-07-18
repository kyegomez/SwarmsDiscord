# SwarmsDiscord 🤖
![Swarms Discord](swarms3.jpeg)


SwarmsDiscord is an open-source Discord bot designed with swarming intelligence to streamline and automate discord communication. 🌍 

## Purpose 🎯
At Swarms, we're transforming the landscape of AI from siloed AI agents to a unified 'swarm' of intelligence. Through relentless iteration and the power of collective insight from our 1500+ Agora researchers, we're developing a groundbreaking framework for AI collaboration. Our mission is to catalyze a paradigm shift, advancing Humanity with the power of unified autonomous AI agent swarms. 🚀🧠🔬

## Installation 📦
```bash
git clone https://github.com/kyegomez/swarmsdiscord.git
cd swarmsdiscord
```

## Setup Environment Variables 🌐
To run the bot, you need to setup the following environment variables:

```bash
DISCORD_TOKEN=[Your Discord Token]
PINECONE_TOKEN=[Your Pinecone Token]
DEBUG_GUILD=[Your Debug Guild]
DEBUG_CHANNEL=[Your Debug Channel]
DATA_DIR=[Your Data Directory]
```

## Run 🚀
```bash
python main.py
```

## Core Functionality 🎛️
- Message queueing for debug service, deferring debug messages to avoid hitting rate limits 📩
- Pickling service for conversation persistence across restarts 🥒
- Discord bot settings like activity type, command prefix, etc 🤖
- Adding various services as discord.py cogs, including:
    - ModerationsService 🛠️
    - SWARMSComCon (main SWARMS Bot service) 🤖🌍
    - DrawDallEService (Draw with DALL-E service) 🎨
    - ImgPromptOptimizer 🖼️
    - IndexService 📑
    - TranslationService 🌐 (optional)
    - SearchService 🔎 (optional)
    - TranscribeService 📝

## Contribution 👥
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License 📄
[MIT](https://choosealicense.com/licenses/mit/)

---
This project is part of the [Swarms](https://swarms.com/) initiative 🚀

![Swarms Logo](swarms_logo.png)