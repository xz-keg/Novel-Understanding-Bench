# 1M Novel Understanding Bench(Personal)

personal benchmark on Evaluating Long(1 million) Context Understanding Using Long Novel Comprehension

Analyse novel(=new) novels. Problems are designed as soon as new chapters are released. Context Length=500-1000k.
Manual Evaluation for personal interest. Sometimes the answer does not match the default correct answer but the model includes more detailed conditions, this will be viewed as "correct".

Previously only Gemini has 1M context length, now deepseek also offers its 1M context model so now we can compare.

Also includes some agent-based methods. Although they currently perform worse than model-based methods due to overlap and missing memory between sessions. 

# Results: 

# Season 1: 20 problems. 

# Model-based methods(high thinking enabled):

Deepseek V4 Pro(Max): 17

Gemini 3.1 Pro: 15

Deepseek V4 Pro: 13

Deepseek V4 Lite: 12

Claude 4.6 Opus thinking: 7

# Model Extension methods:

GPT 5.5 Pro (extended thinking): 16

Gemini 3 Deepthink: 13

GPT 5.4 Pro (extended thinking): 9

GPT 5.4 Pro (normal thinking): 6


# Agent-based methods:

Kimi 2.6 Agent Swarm: 5

Minimax 2.5 agent: 0

Kimi 2.5 Agent Swarm: 0




