# Shared challenge brief

## Context

Brainforge helps executive teams turn AI pressure into a practical roadmap, trusted context layer, and governed agents that work inside the business. This challenge tests how you turn an ambiguous request into a useful, testable system.

## Choose one track

### Track 1: Voice agent for Brainforge

Build a help voice agent that can answer questions using the live content on https://brainforge.ai. It should be useful for visitors asking about Brainforge's services, approach, partnerships, case studies, industries, or next steps. A strong implementation may also support a plausible outbound sales conversation, but answering live website queries is the required centre of gravity.

### Track 2: Evaluation framework for a software engineering agent

Build a small harness that runs software engineering tasks, captures what the agent did, evaluates the result, and uses its logs to improve or inform a later run.

## Expectations for both tracks

- Define a narrow user and use case before building.
- Build a working vertical slice.
- Instrument the system so an operator can understand what happened.
- Define how you evaluate success and failure.
- Handle a few failure cases deliberately.
- Document tradeoffs, limitations, and next steps.

The choice of framework, model, voice provider, gateway, and language is yours. We care about system design and engineering judgement, not vendor choice.

## Time box

- 15 minutes: scope the problem and sketch the design
- 90 minutes: build the core path
- 30 minutes: add logging and evaluation
- 20 minutes: test failure cases
- 15 minutes: prepare the demo and README
- 10 minutes: record limitations and next steps

## Deliverables

- Working code or local demo
- Run instructions
- Architecture diagram or equivalent explanation
- Five-minute demo
- Known limitations and next steps
- Most interesting `session.jsonl`, if available
- Short note describing AI coding tool use
