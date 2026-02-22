# Ollama
# Run Ollama On Your Own Machine

**Project Link:** [View Project](https://learn.nextwork.org/thoughtful_turquoise_shy_bee/docs/ai-ollama-setup)

**Author:** Rajvardhan Jagtap  
**Email:** rajjagtap20320@gmail.com

---

---

## Introducing Today's Project!

In this project, I’m going to install Ollama and run AI models right on my own machine.

My goal is to get away from the cloud and understand how local AI actually works under the hood. I want to see what it’s really capable of, especially when it comes to keeping data private and seeing how fast these models can run on local hardware.

I’m diving into this because I’m deep into AI and Machine Learning, and I want to get my hands dirty with the interactive building process. It’s a huge step for my capstone project, in helping me figure out how to use local LLMs for the real-world use cases I'm working on. Honestly, I just love everything about Tech and want to keep pushing what I know.

### Key tools and concepts

The key tools I used include Ollama and open source models like Gemma and Qwen. Key concepts I learnt include:

* Running LLMs locally
* Ollama
* RAG
* System Prompts
* Custom AI personas

### Challenges and wins

This project took me approximately 45 minutes.

The most interesting part was creating a custom persona using a Modelfile.
It’s pretty cool how you can take a base model and, with just a few lines of instructions, turn it into something like Nova and give it a personality of its own.

---

## Installing Ollama for Local AI

In this step, I'm going to install Ollama, a tool that lets us run large language models directly on our machines, with no API costs and full privacy. No data leaves our machine.

![Image](http://learn.nextwork.org/thoughtful_turquoise_shy_bee/uploads/ai-ollama-setup_h4n8k2m6)

### Verifying the installation

I verified Ollama is running by using a curl request to http://localhost:11434. 

The response I saw was "Ollama is running..."

---

## Pulling My First AI Model

In this step, I'm going to check our current models and then pull 
qwen2.5:0.5b.

Then we're going to chat with it!

![Image](http://learn.nextwork.org/thoughtful_turquoise_shy_bee/uploads/ai-ollama-setup_b5c9d3f7)

### Understanding model sizes

I pulled the model using the command ollama pull qwen2.5:0.5b.

The 0.5b means the model is "small" compared to the larger versions like 7b or 70b. Since it only takes up about 400MB, it's super lightweight and runs fast on my machine while still being really capable for what I need.

---

## Chatting with My Local AI

I started chatting with my local AI by running the model using ollama run qwen2.5:0.5b.

To test it out, I first asked what the capital of India is, and it responded to the point with New Delhi. Then, I asked it to compose a poem on Mom's love, and it wrote some really beautiful paragraphs so quickly!

It’s crazy to see this happening right on my machine. This is way different from using cloud AI because the data never leaves my computer; it’s all private and stays right here.

![Image](http://learn.nextwork.org/thoughtful_turquoise_shy_bee/uploads/ai-ollama-setup_n1p5r9t3)

---

## Exploring Local AI Limitations

In this step, I'm going to test the limits of what my local AI actually knows.
 Local AI models can't know anything about me personally or access my private files and emails because they’re only trained on general info from the internet.So, we use RAG to give the AI access to our own data and get those personalized answers we want.

![Image](http://learn.nextwork.org/thoughtful_turquoise_shy_bee/uploads/ai-ollama-setup_d8r4t6w1)

### Understanding RAG

The AI couldn't answer because it’s trained on general internet data; it doesn’t know anything about me or my private files and emails.

That’s exactly why RAG exists. It stands for Retrieval Augmented Generation, and it’s basically a way to give the AI access to my own data. 
It lets the model "look up" my documents so it can give me personalized answers based on my own info.

---

## Creating a Custom AI Persona

My Custom Persona (Nova) vs. The Base Model

The base model is like a textbook; it’s super smart and gives me all the facts, but it’s a bit dry and formal. 
Nova, on the other hand, is like a supportive parent who’s also a coder. She’s friendly, uses emojis, and actually encourages me while I'm learning.

The Explanation Style: The base model goes deep into technical stuff like "static vs. dynamic" and "memory locations," which is great, but can be a lot to take in. Nova keeps it simple. She uses the "Box" analogy to make it click and breaks everything down step-by-step so I don't feel overwhelmed.

The Interaction: The base model just gives me a big wall of info and asks what language I like. Nova actually talks to me—she starts with a warm greeting, uses relatable parent analogies, and even asks follow-up questions to make sure I’m actually following along.

![Image](http://learn.nextwork.org/thoughtful_turquoise_shy_bee/uploads/ai-ollama-setup_j3k7m2n8)

---

## Wrapping Up

I did this project today to learn how to set up Ollama and run these kinds of models locally. But honestly, I did it because of my genuine interest in tech and this whole field of AI. I’m just really interested in this and want to learn how these systems actually work on the inside.

This project definitely met my goals. It’s one thing to hear about AI, but it’s another thing to actually get it running on your own machine and see it work.

Another skill I want to learn is RAG (RetrievalAugmented Generation). Now that I can run the models, I want to learn how to give them access to my own data so they can give me even more personalized answers.

---

---
