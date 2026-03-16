# LLM Best Practices

This document outlines best practices when working with Large Language Models (LLMs) such as GPT-based systems.

## 1. Be Clear and Specific

Clear prompts produce better results.

Instead of:
Write about marketing

Use:
Write a 500-word beginner guide explaining social media marketing for small businesses.

## 2. Provide Context

The more context you give, the better the output.

Example:

You are a marketing strategist. Create a marketing plan for a small coffee shop launching in Manila.

## 3. Use Structured Prompts

Structured prompts improve reliability.

Example:

Task: Write a blog post  
Audience: Small business owners  
Tone: Professional but simple  
Length: 700 words

## 4. Break Complex Tasks into Steps

LLMs perform better when tasks are broken down.

Example:

Step 1: Research the topic  
Step 2: Create an outline  
Step 3: Write the article  

## 5. Use Iteration

Rarely will the first output be perfect.

Refine prompts by asking:
- Expand this section
- Simplify the explanation
- Rewrite in a more engaging tone

## 6. Validate Critical Information

LLMs can hallucinate.

Always verify:
- statistics
- sources
- technical instructions

## 7. Use Role Prompting

Assign a role to guide the output.

Example:

Act as a senior software engineer and explain this Python code.

## 8. Use Examples (Few-shot prompting)

Providing examples improves accuracy.

Example:

Input: Hello  
Output: Hi there!

Input: Good morning  
Output: Hello! Have a great day.

Input: How are you?
