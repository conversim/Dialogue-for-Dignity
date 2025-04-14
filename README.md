# Human Values Dialogue Dataset

This is a small, handcrafted dataset of conversational exchanges focused on themes of decision-making, autonomy, and ethical reasoning in intelligent systems. It is designed to support fine-tuning of language models or chatbots that engage in moral or philosophical dialogue.

## Dialogue Sets

Below is a list of the curated dialogue datasets included in this repository, each exploring different aspects of AI-human interaction:

| File | Description |
|------|-------------|
| `seeded_dialogue.jsonl` | Foundational set of dialogues illustrating human values, agency, and ethical decision-making. |
| `ai_metaphor_dialogues.jsonl` | A poetic and introspective set where the AI reflects on its own nature through metaphors and philosophical inquiry. |


## Project Philosophy

Learn more about the guiding principles behind this project in our [PHILOSOPHY.md](./PHILOSOPHY.md).


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
