# Speech Recognition: How AI Listens

An open-source interactive learning resource created by **AI with Enoch** that explains how speech recognition turns human voice into text.

This project breaks down what happens when someone speaks to Siri, Google Assistant, a voice bot, or a voice-to-text app. It explores how microphones capture speech, how AI recognises sound patterns, why accents and background noise affect accuracy, and how speech recognition can improve access to education, healthcare, customer support, and public services.

Built for the **Youth in AI Series: Practical AI Skills for Social Impact**.

## Live Frontend

View the interactive presentation here:

[https://speechrecognitionpresentation.vercel.app](https://speechrecognitionpresentation.vercel.app)

## What This Project Is

This is a browser-based workshop presentation for teaching speech recognition to students, young builders, and non-technical audiences.

The repository contains the open-source learning material and documentation. The Vercel link is the polished front-end version people can open and use during the workshop.

## What Learners Will Understand

By the end of the session, learners should understand:

- what speech recognition means
- how microphones capture human voice
- how sound becomes digital data
- what a spectrogram is
- how AI recognises sound patterns
- why the system makes mistakes
- why accents, noise, slang, and local names matter
- how speech recognition is used in real life
- how platforms like ElevenLabs, OpenAI Audio, Deepgram, AssemblyAI, Google Speech-to-Text, and Azure Speech fit into the voice AI pipeline

## Presentation Breakdown

The presentation is structured as a practical 40-minute learning experience.

| Section | Focus |
| --- | --- |
| Opening | What speech recognition is and why it matters |
| Pipeline | Sound waves, digital audio, spectrograms, and pattern matching |
| Interactive demo | Voice-to-text demo with microphone or backup sample phrases |
| Human recognizer activity | A group activity showing how noisy evidence changes what people hear |
| Modern AI | How neural models improved speech recognition |
| Real-life applications | Assistants, captions, education, healthcare, customer service, accessibility, and business operations |
| Platform lab | Tools for transcription, voice agents, and text-to-speech |
| Accuracy | Word Error Rate and why small mistakes can matter |
| Practical decisions | Cloud vs on-device, privacy, cost, custom words, and local context |

## Hands-On Activities Included

The deck includes practical activities that can be done live:

- **Voice-to-text mini demo**: speak into the browser and watch the transcript appear.
- **Sample phrase fallback**: works even when microphone access is blocked.
- **Human recognizer challenge**: compare what humans hear when speech is clear, fast, quiet, or noisy.
- **Word Error Rate calculator**: type a correct sentence and a bad transcript to see the error rate.
- **Platform lab**: compare where ElevenLabs, OpenAI, Deepgram, AssemblyAI, Google, and Azure fit in the voice AI stack.

## Real-Life Applications Covered

The workshop connects speech recognition to real-world use cases:

- voice assistants
- live captions
- call centers and customer service
- classroom transcription and summaries
- healthcare note-taking
- accessibility tools
- translation
- voice search
- smart cars and smart devices
- business order capture
- public service access

## Project Structure

```text
speechrecognitionpresentation/
├── index.html              # Interactive presentation frontend
├── README.md               # Project overview and learning breakdown
├── docs/
│   └── workshop-guide.md   # Detailed facilitator-friendly workshop guide
├── package.json            # Project metadata
├── vercel.json             # Static Vercel configuration
├── LICENSE                 # MIT license
└── .gitignore
```

## Open Locally

Open `index.html` in any modern browser.

For the best experience, use Chrome because the built-in microphone demo depends on browser speech recognition support.

## Deploy

This project is a static site. It can be deployed on:

- Vercel
- GitHub Pages
- Netlify
- Cloudflare Pages
- any static web host

Current production deployment:

[https://speechrecognitionpresentation.vercel.app](https://speechrecognitionpresentation.vercel.app)

## Notes on Responsible Use

Speech recognition can be powerful, but it should be used carefully.

Important considerations:

- Always get consent before recording or transcribing people.
- Do not clone or synthesize someone else's voice without permission.
- Check accuracy before using transcripts in medical, legal, financial, or high-stakes settings.
- Test with diverse accents, environments, and local vocabulary.
- Give users a way to correct mistakes.

## License

MIT
