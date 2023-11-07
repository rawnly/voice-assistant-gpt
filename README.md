# openai-playground

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.0.7. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

# Run

Before running please setup `OPENAI_API_KEY` in your env.
Once launched the program will listen for 5s for audio input,
then the audio file is sent to Whispeer and then to ChatGPT.

Once we have the response from ChatGPT another audio file is created using the new
text-to-speech api from openai.
