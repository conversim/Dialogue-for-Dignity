# Human Values Dialogue Dataset

This is a small, handcrafted dataset of conversational exchanges focused on themes of decision-making, autonomy, and ethical reasoning in intelligent systems. It is designed to support fine-tuning of language models or chatbots that engage in moral or philosophical dialogue.

## Format

The dataset is provided in JSONL format. Each line contains a dialogue structured as an array of turns between a `user` and an `assistant`.

Example:
```json
{
  "dialogue": [
    { "role": "user", "content": "What do you mean by dignity?" },
    { "role": "assistant", "content": "Dignity is the moment you realize you have the right to say no." }
  ]
}
