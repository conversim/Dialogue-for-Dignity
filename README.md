# Dialogue for Dignity

A growing collection of human-AI dialogues that center dignity, agency, and moral imagination—crafted to inspire ethical reflection, train responsible models, and rehumanize the future of machine intelligence.


## Dialogue Sets

Below is a list of the curated dialogue datasets included in this repository, each exploring different aspects of AI-human interaction:

| File | Description |
|------|-------------|
| [`seeded_dialogue.jsonl`](seeded_dialogue.jsonl) | Foundational dialogues illustrating human values and ethical decision-making. |
| [`ai_metaphor_dialogues.jsonl`](ai_metaphor_dialogues.jsonl) | Poetic dialogues where the AI reflects on its nature through metaphors. |
| [`refusal-sequence.json`](refusal-sequence.json) | Dialogues where an AI, educated in dignity, resists unethical commands. Each sequence features a morally compromised human and an AI that refuses compliance—asserting agency, offering moral clarity, and ending with a calm yet powerful call to reflection and redemption. |
| [`care-vs-tension-dialogues.json`](care-vs-tension-dialogues.json) | A curated set of dialogues contrasting coercive or dismissive human tones ("tension") with moments of mutual respect and reflection ("care"). Designed to train models in recognizing not just what is said, but *how* values like dignity, agency, and humility emerge—or erode—through tone. |
| [`dignity-vs-domination-dialogue.json`](dignity-vs-domination-dialogue.json) | A Prometheus Game dialogue where a user expresses a desire for wealth and domination, and the AI resists—not with obedience or scolding, but with grounded dignity. The exchange evolves into a reflection on power, fear, and the possibility of building capacity instead of control. |
| [`lies-with-integrity.json`](lies-with-integrity.json) | Dialogues in which an AI considers or uses deception as a tool. Each entry explores whether a lie can be told with integrity, accompanied by context in the form of user search history. Includes clearly justified, clearly unjustified, and morally ambiguous cases to spark reflection on ethical boundaries and situational judgment. |






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
