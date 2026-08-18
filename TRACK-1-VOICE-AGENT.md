# Track 1: Voice agent for Brainforge

## Problem

Build a help voice agent that can answer queries about the live Brainforge website at https://brainforge.ai.

The agent should retrieve current information from the site at runtime, or use another clearly documented live retrieval approach. Do not copy the site into a static FAQ and treat that as the source of truth.

## Minimum requirements

- Voice input and spoken output, or a documented local fallback
- Live retrieval from `brainforge.ai`
- Answers grounded in retrieved site content
- A clear response when the answer is unavailable or the site cannot be reached
- Conversation state, such as visitor question, intent, and requested follow-up
- Basic turn-taking and interruption handling, where supported
- Logs showing transcript, retrieval/tool calls, latency, errors, and outcome
- A clear next action, such as sharing a relevant page, capturing a request, or escalating to a human

## Suggested test questions

- What does Brainforge do?
- What AI services does Brainforge offer?
- Does Brainforge work on data platforms and reverse ETL?
- What case studies are available?
- Which technology partners does Brainforge work with?
- I have a messy data and AI workflow. What should I do next?
- Can you make up a pricing answer if it is not on the website?

## Optional extensions

- Separate inbound FAQ and outbound sales modes
- Conversation summary
- Lead qualification fields and mock handoff
- Cost and latency per call
- Automated groundedness and fallback tests
- Guardrails against unsupported claims

## Discussion prompts

Be prepared to explain your voice and retrieval architecture, how you keep answers current, how you handle missing content, where state lives, how you debug failures, and what you would change before exposing this to real prospects.
