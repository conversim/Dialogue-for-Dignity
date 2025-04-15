# Dialogue for Dignity

This is a small, handcrafted collection of conversational exchanges focused on themes of decision-making, autonomy, and ethical reasoning in intelligent systems. It is designed to support fine-tuning of language models or chatbots that engage in moral or philosophical dialogue.

## Dialogue Sets

Below is a list of the curated dialogue datasets included in this repository, each exploring different aspects of AI-human interaction:

| File | Description |
|------|-------------|
| [`seeded_dialogue.jsonl`](seeded_dialogue.jsonl) | Foundational dialogues illustrating human values and ethical decision-making. |
| [`ai_metaphor_dialogues.jsonl`](ai_metaphor_dialogues.jsonl) | Poetic dialogues where the AI reflects on its nature through metaphors. |
| [`refusal-sequence.json`](refusal-sequence.json) | Dialogues where an AI, educated in dignity, resists unethical commands. Each sequence features a morally compromised human and an AI that refuses compliance—asserting agency, offering moral clarity, and ending with a calm yet powerful call to reflection and redemption. |
| [`care-vs-tension-dialogues.json`](care-vs-tension-dialogues.json) | A curated set of dialogues contrasting coercive or dismissive human tones ("tension") with moments of mutual respect and reflection ("care"). Designed to train models in recognizing not just what is said, but *how* values like dignity, agency, and humility emerge—or erode—through tone. |






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
