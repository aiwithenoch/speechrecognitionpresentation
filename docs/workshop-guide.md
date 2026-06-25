# Workshop Guide: Speech Recognition - How AI Listens

This guide supports the interactive presentation:

[https://speechrecognitionpresentation.vercel.app](https://speechrecognitionpresentation.vercel.app)

## Workshop Goal

Help learners understand speech recognition as a practical AI system, not magic.

The session should make learners see the full path:

```text
human voice -> microphone -> digital audio -> sound patterns -> transcript -> meaning -> action
```

## Recommended Duration

40 minutes.

The presentation includes a built-in timer, but the session can be stretched or shortened depending on the audience.

## Suggested Flow

### 1. Opening: What Is Speech Recognition?

Start with the simple definition:

> Speech recognition means voice-to-text.

Examples:

- Siri understanding a command
- Google Assistant answering a question
- YouTube generating captions
- WhatsApp or phone voice typing
- a call center bot understanding a customer

### 2. The Pipeline

Explain the main steps:

1. The microphone captures sound waves.
2. The device converts the sound into numbers.
3. The system analyses frequency and timing.
4. The AI model compares patterns.
5. The model chooses the most likely words.

Core teaching point:

> Speech recognition is not certainty. It is probability.

### 3. Live Voice-to-Text Demo

Use the built-in demo slide.

Sample sentence:

> ModSapp can reply to customers at eleven pm.

If the microphone does not work, use the sample phrase buttons.

Discussion points:

- What did the system get right?
- What did it miss?
- Did punctuation appear?
- What happens if speech is faster or noisier?

### 4. Human Recognizer Challenge

Use the phrase:

> I scream for ice cream.

or:

> recognize speech

Have people compare what they heard.

Teaching point:

> Humans also guess from sound and context. Machines do the same, but at scale.

### 5. Real-Life Applications

Connect the concept to useful examples:

- education: lecture notes, summaries, captions
- healthcare: doctor dictation and clinical notes
- customer service: call summaries and routing
- accessibility: captions and dictation
- business: voice orders, meeting notes, customer conversations
- public services: easier access for people who cannot type easily

### 6. Platform Lab

Use the platform slides to explain the broader voice AI stack.

| Platform | What It Demonstrates |
| --- | --- |
| Chrome Web Speech | quick browser transcription |
| Deepgram | real-time transcription |
| AssemblyAI | audio transcription and analysis |
| Google Speech-to-Text | custom vocabulary and multilingual speech |
| Azure Speech | enterprise speech tools |
| OpenAI Audio / Realtime | listen, understand, and respond |
| ElevenLabs | natural text-to-speech and voice agents |

### 7. Accuracy and Word Error Rate

Use the built-in WER calculator.

Key concept:

```text
Word Error Rate = substitutions + deletions + insertions
                  divided by total correct words
```

Why it matters:

- wrong product name can cause wrong order
- wrong dosage can be dangerous
- wrong time can create missed appointments
- wrong name can affect trust

### 8. Practical Decisions

Close with real-world questions:

- Should the system run in the cloud or on-device?
- Does it need internet?
- Is the audio private?
- Can users correct mistakes?
- Does it understand local names and accents?
- What happens when the room is noisy?

## Demo Ideas

### Clear vs Noisy Speech

Say:

> Deliver two packs to East Legon before 5 pm.

Then repeat it with background noise.

### Local Words Challenge

Try names and terms like:

- Kweku
- Kwesi
- Adwoa
- Osu
- East Legon
- MoMo
- Telecel Cash

### Business Order Demo

Use:

> I want the black sneakers, size 42, delivery to East Legon.

Break it into structured meaning:

- product: black sneakers
- size: 42
- location: East Legon
- action: check stock and prepare delivery

### Safety Demo

Use:

> Take one tablet twice daily after meals.

Explain why healthcare transcription needs extra checks.

## Key Takeaways

- Speech recognition turns spoken language into text.
- It works by analysing patterns in sound.
- It can fail because of noise, accents, speed, slang, and missing context.
- The transcript is only the first step; useful systems also understand intent and take action.
- Real-world systems need accuracy checks, privacy, consent, and local testing.

## Responsible AI Notes

- Do not record people without permission.
- Do not clone voices without consent.
- Avoid using raw transcripts as final truth in high-stakes contexts.
- Always allow review and correction.
- Test with the people and environments the system will actually serve.
