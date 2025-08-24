# GPF
Have you ever wished your virtual assistant could truly understand how you’re feeling? What if your AI could talk to you based on your mood — cheering you up on a bad day, or celebrating with you when you’re happy? What if AI could understand how we feel and reply like a friend would?

We live in a fast-paced world where everything is just a click away. We can order food, book tickets, get directions, and even talk to AI assistants that set alarms or answer questions. Life seems more connected than ever — yet, many people still feel disconnected from themselves. AI is helping us in every way, it is equally important to train it for emotions.

*Emotions are complex.* Between the constant rush, social media scrolls, and pressure to always be “productive,” it’s easy to feel lost, confused, or emotionally stuck. Sometimes, we don’t even understand what we’re feeling ourselves — joy and sadness mix, excitement turns into anxiety, and silence feels heavier than words. In those moments, we often wish for someone to help us make sense of it all.

**GPF — Generative Philosopher Friend** is GenAI-powered chatbot that senses user emotion and responds empathetically, at times using real-time emotional grounding, quote retrieval via RAG, and personalized dialogue — offering not just replies, but reassurance. It makes you feel heard and understood. ***It not only talks, it listens.***

GPF is not just another chatbot, its features set it different. It’s a calm, caring companion designed to guide you like a thoughtful friend and a gentle philosopher. Instead of giving plain answers, it offers timeless wisdom — quotes and reflections from thinkers, saints, and scriptures like the Bhagavad Gita and the Bible and from authors across cultures. *No friend or family member can always say the exact words we need to hear. But GPF might!*

***"Life can be lot easier if we get to understand ourselves better."***

Sometimes a person starts talking to himself in situations of stress, pressure and frustration this often leads to anxiety and *Schizophrenia*. It can be effectively managed with a combination of medication, therapy, and support.
GEN AI, in the form of GPF, should be used as a truly helpful therapeutic support in such conditions.

### Here, the following use cases should be considered:
- Mental wellness
- Emotional companionship
- AI Philosopher
- Student stress support
- Friendly check-in tool for daily interactions

### Let’s dive deeper in its mechanism

The assistant saves name and uses emotion detection on user input, retrieves emotion-aligned quotes from a vector database (Chroma DB) using RAG, and finally generates a contextual response via GenAI — optionally with extra grounding if a strong emotional cue repeat.

Using natural language processing, it understands what you say without needing commands, and even picks up on how you’re feeling without you having to explain. It uses 100 labelled question answer set. It detects emotions from your words, then responds with wise, carefully selected quotes from a curated set of 500, matched perfectly to your mood through its unique Emotion-to-Wisdom Mapping Engine. If it notices you’re feeling the same way twice, it responds more gently and thoughtfully, showing real emotional sensitivity. GPF also adapts to your personality over time, remembers your name, and crafts responses in different “philosopher modes” — from a calm Stoic mentor to a poetic life coach. Each message is tuned for rhythm and depth, offering a calm and personalized experience that helps you reflect, grow, and feel truly heard — like a supportive, thoughtful friend who’s always there.

For use cases as sensitive as emotion handling, it’s crucial to ensure accuracy! So, we even set up evaluation function for 9 queries to detect emotion and we got 100% accuracy.

### Limitations & Future Scope

· Data Source Expansion: Currently, the wisdom dataset is curated and limited. Broadening the data sources to include a wider variety of texts, cultures, and authors would improve the emotional accuracy and cultural sensitivity of responses.

· Emotion Spectrum: GPF now focuses on broad and distinct emotions. Future versions can include a richer emotional spectrum — like envy, pride, or nostalgia — enabling more nuanced reflections and deeper emotional resonance.

· Multi-domain Support: While this model is focused on philosophical and emotional support, GPF can be expanded to include knowledge from domains like psychology, history, or even personal development, making it more versatile.

· Voice & Interface Integration: Adding voice-based interaction and a clean, intuitive user interface would make GPF more accessible and immersive, especially for people who seek comfort in spoken conversations making it market ready.

· Reinforcement Learning with Human Feedback (RLHF): Over time, integrating RLHF can help GPF adapt and personalize itself better to individual users, refining its emotional intelligence and making its responses feel more human, empathetic, and supportive.

Here’s link to the Kaggle notebook — https://www.kaggle.com/code/aryamasrivastav/gpf-generative-philosopher-friend-by-aryama-s

YouTube Video — https://youtu.be/nBiTQtI116Y?si=NQtmP8XB982KZtRc

That’s an end of the blog, Thankyou for reading!

© All rights reserved
