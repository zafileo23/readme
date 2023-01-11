# cx-copilot

⚡ Building applications with LLMs through composability ⚡

## 🤔 What is cx-copilot?

An open source library that lets you leverage LLMs and latest advancements in AI to automate customer experience interactions. By connecting a Large Language Model (LLM) to your knowledge base and historical support tickets via embeddings & vector searching, you can accurately auto-draft responses to all customer requests.

## Where can it be used?

You can use cx-copilot to auto-draft responses in Helpdesk, Intercom, Support Inboxes, Zendesk, and anywhere else you store & respond to customer requests.

## ⚡️ Installation



## 🚀 Live Demo 



## 📖 How does it work?

The basis of cx-copilot is embedding, vector storing and vector searching. Vector embeddings are a way to represent text as a series of numbers in such a way that you can perform mathematical operations, such as similarity comparison. By first embedding all previous historical customer request tickets using an embedding model (like [text-embedding-ada-002](https://openai.com/blog/new-and-improved-embedding-model/) from OpenAI) and storing the embeddings & the paired response from your company in a vector database, you can then perform a vector search for incoming support tickets, returning the closest-matching tickets based on cosine similarity. The final step is to prompt a Large Language Model (LLM) with your team's responses to the closest-matching historical tickets, generating an auto-drafted response which will answer your customer’s query while conforming to your tone & formatting tendencies.

## 🧰 Integrations 

|-------|---------|
| <img src="https://style.helpscout.com/images/logo/help-scout-logo-circle-blue.svg" alt="Helpscout logo" height="50px"> | Helpscout |
| <img src="https://www.svgrepo.com/download/303161/gmail-icon-logo.svg" alt="Gmail logo" height="50px"> | Gmail |
| <img src="https://cdn.worldvectorlogo.com/logos/intercom-1.svg" alt="Intercom logo" height="50px"> | Intercom (coming soon) |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c8/Zendesk_logo.svg/2560px-Zendesk_logo.svg.png" alt="Zendesk logo" height="50px"> | Zendesk (coming soon) |
| <img src="https://www.svgrepo.com/show/353655/discord-icon.svg" alt="Discord logo" height="50px"> | Discord (coming soon) |

<img src="https://style.helpscout.com/images/logo/help-scout-logo-circle-blue.svg" alt="Helpscout logo" height="50px">   Helpscout

<img src="https://www.svgrepo.com/download/303161/gmail-icon-logo.svg" alt="Gmail logo" height="50px">   Gmail

<img src="https://cdn.worldvectorlogo.com/logos/intercom-1.svg" alt="Intercom logo" height="50px"> (coming soon)

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c8/Zendesk_logo.svg/2560px-Zendesk_logo.svg.png" alt="Zendesk logo" height="50px"> (coming soon) 

<img src="https://www.svgrepo.com/show/353655/discord-icon.svg" alt="Discord logo" height="50px">    Discord (coming soon)

## 📱 Community

Join the [Discord community for cx-copilot](https://discord.gg/XhPnzxhm6y) for support & project updates.

## 👩‍💻 Contributing


| Image | Text |
|-------|------|
| ![](image.svg) | Some text goes here. |
