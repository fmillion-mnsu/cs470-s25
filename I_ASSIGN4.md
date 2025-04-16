# Activity 4 – CS 470, Spring 2025

Artificial intelligence and human-computer interaction may not have an obvious strong relationship, but AI is actually very deeply related to HCI. Consider the following:

* An AI agent can help reduce **cognitive load**. 
    * But a *poorly implemented* AI agent could actually *increase* cognitive load!
* Generative AI such as LLMs involves the AI system's **mental model**; a disconnect between what *your* mental model is and the AI's model can result in misunderstandings and poor or hallucinated output.
    * The mental model concept also applies to user understanding of what AI is capable of. Users may build a mental model surrounding AI that equates it to a person.
* AI systems are evaluated for usability - **user testing** - just like any software. However, with an AI system such as an LLM, there is significant emphasis on studying *how users prompt the system* versus their *intents*, and how well the LLM is able to interpret and respond appropriately.
    * Have you ever been frustrated when talking with an automated customer service system that asks for what you want "in a few words" but still can't seem to understand what you're asking for?
* AI offers multiple **modalities of interaction**. Traditional chatbots might use a typical chat-style interface, but other options such as voice interaction (e.g. voice assistants), visual input or output, and others are used.
* AI systems on their own can offer significant **accessibility** improvements. However, an AI system tuned specifically for accessibility can offer a higher degree of utility.
    * Question: can we blame a person with a disability who uses AI for accessibility, if the AI makes a mistake? Assuming that the user might not have a way to validate the AI's output?

In this assignment, you'll explore how AI can be used as a highly effective learning tool, while understanding the potential negative effects of "lazy" usage.

## Instructions

1. Select a **complex computer science topic**. You can choose from this list, or come up with your own, but avoid elementary foundational topics.

    * B-trees and variants (B+ trees, 2-3-4 tree, dancing tree, Bx tree...)
    * Advanced heap types (Binomial heap, AF-heap, 2-3 heap, Beap, D-ary heap...)
    * Bit-slice trees
    * Multi-way trees (SPQR tree, Spaghetti stack, Fusion tree, Fenwick tree...)
    * Advanced hashtables and related (Hash trie, Rolling hash, Koorde...)
    * Advanced graph structures (Scene graph, And-inverter graph, Multigraph...)
    * Lightmap data structure
    * E-graphs

2. Ask an AI system of your choice about the topic you chose in a *naive* fashion.

    By this, I mean to simply ask the AI in a "lazy" way - i.e. "What is a bit-slice tree"?

    Review the response given.

3. Consider how well the response the AI gave you helped you understand the topic.

    You might find that you want to ask follow-up questions. Perhaps something the AI described is not clear to you. Or perhaps the AI made assumptions about your level of background knowledge.

4. Now, consider how you can **improve the output** of the AI with **prompt engineering.**

    > Prompt engineering broadly describes the process of writing prompts that improve an AI's performance, utility, or accuracy. 
    >
    > Prompt engineering is a discipline unto itself, and there are many strategies that you can use. Do some of your own research on prompt engineering.
    >
    > A few hints:
    >
    > * You can include domains of knowledge you already understand, to help the AI tailor the response to be more useful to you. For example: "I understand how linked lists, stacks, queues and binary search trees work. Can you explain ___..."
    > * You can instruct the AI to take on the role of a certain character style to shape the response. For example: "You are a computer science professor" or "You are a helpful friend who has a degree in computer science".
    > * You can also ask the AI to provide you with code in a given language, or to illustrate a use case of your topic in code.
    
    There is no "limit" as to how much you engineer your prompt to shape the AI response - the more specific and in-depth your prompt, the more likely you are to get a more useful output!

5. Start a **new** chat (so that the question you asked already is not part of the AI's "memory" for the conversation). Now, issue a stronger prompt to ask about your topic. Your updated prompt will almost certainly be significantly longer! 

6. Compare and contrast the responses you got from the AI for your simple prompt versus your engineered prompt. Which one was more useful to you? Why?

## Submission

Write a document that includes the following:

* Your topic
* The prompts you used (both the initial naive prompt and the engineered prompt) along with the AI's response to each prompt
* A short (1-2 pargraphs) reflection on how your prompt engineering effort changed the AI's output, whether the new output was more useful (or less useful!) and why that might be. Also, describe anything you may have learned as you explored prompt engineering that you will be able to put to use as you apply AI to your work and career in the future.

This assignment is worth 50 points and is due April 29, 2025 at 11:59 PM.
