# prompt cop
TLDR: Ingests your input tokens + provided context and provides a rough approximation of how many tokens you will be purchasing and what percent of your context window you are occupying

We have a simulated model that mimics frontier lab models which actively (in real-time) takes the input tokens, text, context, etc that you are typing into your LLM and approximates:
- how many input tokens you will consume
- how many output tokens you will consume
- what percent of your available context window are you consuming
- what percent of your available context window are you OPTIMALLY consuming
- How much $$ you can expect to spend on this prompt total

