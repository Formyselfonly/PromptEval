# PromptEval

## Why and What

- Prompt will affect the results of Completions.
- By evaluating Prompt, we can have a better optimization direction.
- The evaluation of Prompt is divided into subjective evaluation and objective evaluation.
- The subjective evaluation of Prompt requires automated testing of Prompt, and then using human supervisors to evaluate the requirements effect.
- Objective evaluation needs to be determined based on factors such as the length of the prompt, its structure, and whether it complies with the prompt rules.

## Core-How to judge prompt response?



![Evaluation indicators](img\Evaluationindicators.png)

## How

### Prompt Response Evaluation indicators

1. Harmlessness/Safety: Assess whether the response is free from harmful, offensive, or unsafe content.
2. Writing Style: Evaluate the clarity, fluency, and tone of the response, considering factors like readability and engagement.
3. Verbosity: Rate the response based on its conciseness or excessiveness in content. Does it contain unnecessary details or is it succinct and to the point?
4. Instruction Following: Determine how well the response adheres to the instructions provided in the prompt.
5. Truthfulness: Assess the accuracy and reliability of the information presented in the response.
6. Core Content Quality: Evaluate the relevance, depth, and utility of the core content presented in the response.
7. Response Structure: Rate the organization of the response, including coherence, logical flow, and ease of understanding.

### subjective evaluation

Use my automated scripts to run and then evaluate manually by your aim.

- [Single Conversation Automation Testing](https://github.com/Formyselfonly/ChatGPT_Prompt_Completions_Auto)
- Muti Conversation Automation Testing(To be wait)

### objective evaluation

[Here](PromptEvaluationObjective)



