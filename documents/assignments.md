# Every day assignments

---

## 2024-11-11

🎒 Today’s Assignments

1. Complete the Intro Unit – “Foundational Large Language Models & Text Generation”, which is:

    - [Optional] Listen to the summary [podcast episode](https://youtu.be/mQDlCZZsOyo) for this unit (created by [NotebookLM](https://notebooklm.google.com/?original_referer=https:%2F%2Fwww.google.com%23&pli=1)).
    - Read the [“Foundational Large Language Models & Text Generation” whitepaper](https://www.kaggle.com/whitepaper-foundational-llm-and-text-generation). Introduction:

        The advent of Large Language Models (LLMs) represents a seismic shift in the world of artificial intelligence. Their ability to process, generate, and understand user intent is fundamentally changing the way we interact with information and technology.
        An LLM is an advanced artificial intelligence system that specializes in processing, understanding, and generating human-like text. These systems are typically implemented as a deep neural network and are trained on massive amounts of text data. This allows them to learn the intricate patterns of language, giving them the ability to perform a variety of tasks, like machine translation, creative text generation, question answering, text summarization, and many more reasoning and language oriented tasks. This whitepaper dives into the timeline of the various architectures and approaches building up to the large language models and the architectures being used at the time of publication. It also discusses fine- tuning techniques to customize an LLM to a certain domain or task, methods to make the training more efficient, as well as methods to accelerate inference. These are then followed by various applications and code examples.

2. Complete Unit 1 – “Prompt Engineering”, which is:

    - [Optional] Listen to the summary [podcast episode](https://youtu.be/F_hJ2Ey4BNc) for this unit (created by NotebookLM).
    - Read the [“Prompt Engineering” whitepaper](https://www.kaggle.com/whitepaper-prompt-engineering). Introducton:

        When thinking about a large language model input and output, a text prompt (sometimes accompanied by other modalities such as image prompts) is the input the model uses to predict a specific output. You don’t need to be a data scientist or a machine learning engineer – everyone can write a prompt. However, crafting the most effective prompt can be complicated. Many aspects of your prompt affect its efficacy: the model you use, the model’s training data, the model configurations, your word-choice, style and tone, structure, and context all matter. Therefore, prompt engineering is an iterative process. Inadequate prompts can lead to ambiguous, inaccurate responses, and can hinder the model’s ability to provide meaningful output. You don’t need to be a data scientist or a machine learning engineer – everyone can write a prompt.
        When you chat with the Gemini chatbot, you basically write prompts, however this whitepaper focuses on writing prompts for the Gemini model within Vertex AI or by using the API, because by prompting the model directly you will have access to the configuration such as temperature etc.
        This whitepaper discusses prompt engineering in detail. We will look into the various prompting techniques to help you getting started and share tips and best practices to become a prompting expert. We will also discuss some of the challenges you can face while crafting prompts.

    - Complete [this code lab](https://www.kaggle.com/code/markishere/day-1-prompting) on Kaggle where you’ll learn prompting fundamentals. Make sure you phone verify your account before starting, it's necessary for the code labs.

💡What You’ll Learn

Today you’ll explore the evolution of LLMs, from transformers to techniques like fine-tuning and inference acceleration. You’ll also get trained in the art of prompt engineering for optimal LLM interaction.

The code lab will walk you through getting started with the Gemini API and cover several prompt techniques and how different parameters impact the prompts.

📋 Reminders

- Tomorrow at 11:00 am ET / 4:00 pm GMT,  Paige Bailey is hosting the first livestream on our YouTube channel to discuss the assignments with the course authors and other special guests from Google. Tomorrow’s guests are Mohammadamin Barekatain, Lee Boonstra, Logan Kilpatrick, Daniel Mankowitz, Majd Merey Al, Anant Nawalgaria, Aliaksei Severyn and Chuck Sugnet. It’ll be recorded in case you’re unable to attend.
- Discord is the best place to ask questions – specifically in the #5dgai-q-and-a channel. In addition to other participants, several Googlers are there to help. During the livestream, we'll also pick several questions from Discord to discuss. You'll get Kaggle swag if your question is chosen!
- We created a new channel in Discord called #5dgai-announcements that will be used exclusively for course announcements from us.
- We want this course community to be positive and supportive. Please follow Kaggle’s community guidelines found [here](https://www.kaggle.com/community-guidelines).

Happy learning and see you tomorrow!

### First Livestream

Today’s livestream starts at 11:00 am ET / 4:00 pm GMT. [Click here to join](https://www.youtube.com/watch?v=dnGuDNhD3Ag&list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es&index=1)!

Paige Bailey will be discussing the assignments with the course authors and other special guests from Google. Today’s guests are Mohammadamin Barekatain, Lee Boonstra, Logan Kilpatrick, Daniel Mankowitz, Majd Merey Al, Anant Nawalgaria, Aliaksei Severyn and Chuck Sugnet. It will be recorded in case you’re unable to attend.

To simplify timezone complexities, we made a single playlist of all scheduled livestreams this week with clear start times [here](https://www.youtube.com/playlist?list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es).

## 2024-11-12

🎒 Today’s Assignments

- Complete Unit 2: “Embeddings and Vector Stores/Databases”, which is:
  - [Optional] Listen to the [summary podcast](https://youtube.com/watch?v=1CC39K76Nqs) episode for this unit (created by [NotebookLM](https://notebooklm.google.com/?original_referer=https:%2F%2Fwww.google.com%23&pli=1)).
  - Read the [“Embeddings and Vector Stores/Databases” whitepaper](https://kaggle.com/whitepaper-embeddings-and-vector-stores). Introduction:

    Modern machine learning thrives on diverse data—images, text, audio, and more. This whitepaper explores the power of embeddings, which transform this heterogeneous data into a unified vector representation for seamless use in various applications. We'll guide you through:

    - Understanding Embeddings: Why they are essential for handling multimodal data and their diverse applications.
    - Embedding Techniques: Methods for mapping different data types into a common vector space.
    - Efficient Management: Techniques for storing, retrieving, and searching vast collections of embeddings.
    - Vector Databases: Specialized systems for managing and querying embeddings, including practical considerations for production deployment.
    - Real-World Applications: Concrete examples of how embeddings and vector databases are combined with large language models (LLMs) to solve real-world problems.

    Throughout the whitepaper, code snippets provide hands-on illustrations of key concepts.

  - Complete these code labs on Kaggle:
    - [Build](https://www.kaggle.com/code/markishere/day-2-document-q-a-with-rag) a RAG question-answering system over custom documents
    - [Explore](https://www.kaggle.com/code/markishere/day-2-embeddings-and-similarity-scores) text similarity with embeddings
    - [Build](https://www.kaggle.com/code/markishere/day-2-classifying-embeddings-with-keras) a neural classification network with Keras using embeddings

💡 What You’ll Learn

Today you will learn about the conceptual underpinning of embeddings and vector databases and how they can be used to bring live or specialist data into your LLM application. You’ll also explore their geometrical powers for classifying and comparing textual data.

📋 Reminders and Announcements

- Here is the [recording from this morning’s livestream](https://www.youtube.com/watch?v=kpRyiJUUFxY). Fortunately our recording did not have any of the technical glitches as today's livestream.
- The 2nd livestream is tomorrow with Paige Bailey and special guests: Omid Fatemieh, Jinhyuk Lee, Alan Li, Iftekhar Naim, Anant Nawalgaria, Yan Qiao, and Xiaoqi Ren.
- Unfortunately, to ensure a fix to our livestream issues moving forward, we need to push back our broadcast time. We'll send another email with updated livestream info soon.
- Be sure to ask all your questions about the podcast, readings, and code lab in the [#5dgai-q-and-a](https://discord.gg/gNrC9Xut) channel on Discord. You'll get Kaggle swag if your question is chosen for discussion during the livestream!

Happy learning and see you tomorrow.

### Second Livestream

Today’s livestream starts at 2PM PST/ 5PM EST/ 10:00 PM UTC. [Click here to join](https://youtube.com/watch?v=86GZC56rQCc&list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es&index=3)!

Paige Bailey will be joined by Omid Fatemieh, Jinhyuk Lee, Alan Li, Iftekhar Naim, Anant Nawalgaria, Yan Qiao, and Xiaoqi Ren to discuss embeddings and vector stores/databases. It will be recorded in case you’re unable to attend.

For the complete list of scheduled livestreams and past recordings, check out this [YouTube playlist](https://www.youtube.com/playlist?list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es).

See you soon.

## 2024-11-13

🎒 Today’s Assignments

- Complete Unit 3: “Generative AI Agents”, which is:
  - [Optional] Listen to the summary [podcast episode](https://youtu.be/H4gZd4BCrDQ) for this unit (created by [NotebookLM](https://notebooklm.google/)).
  - Read the [“Generative AI Agents” whitepaper](https://www.kaggle.com/whitepaper-agents).
  - Complete these code labs on Kaggle:
    - [Talk](https://www.kaggle.com/code/markishere/day-3-function-calling-with-the-gemini-api) to a database with function calling
    - [Build](https://www.kaggle.com/code/markishere/day-3-building-an-agent-with-langgraph/) an agentic ordering system in LangGraph

💡 What You’ll Learn

Learn to build sophisticated AI agents by understanding their core components and the iterative development process.

The code labs cover how to connect LLMs to existing systems and to the real world. Learn about function calling by giving SQL tools to a chatbot, and learn how to build a LangGraph agent that takes orders in a café.

📋 Reminders and Announcements

- Here is the [recording from Day 2’s livestream](https://www.youtube.com/live/86GZC56rQCc?si=trAoT7PVtYC5LQ7B).
- The next livestream is tomorrow at 2pm PST/ 5pm EST/ 10pm UTC. [Click here to join](https://www.youtube.com/watch?v=HQUtMWoTAD4&list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es&index=3)! Livestream guests: Alan Blount, Wes Dyer, Steven Johnson, Patrick Marlow, Anant Nawalgaria, and Julia Wiesinger.
- Find a [complete list of scheduled livestreams and past recordings here](https://www.youtube.com/playlist?list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es).
- Be sure to ask all your questions about the podcast, readings, and code lab on [Discord](https://discord.gg/gNrC9Xut).
- Additionally, we’ve added 2 new channels on Discord to enhance discussion:
  - [#5dgai-question-forum](https://discord.gg/kaggle) is a Discord forum (a special type of channel) where you can create specific threads, which will help finding answers easier in the future.
  - [#5dgai-course-content](https://discord.gg/kaggle) is a Discord channel for deeper discussion of course content only (excluding technical troubleshooting questions).

Happy learning and see you tomorrow.

## 2024-11-14

## 2024-11-15
