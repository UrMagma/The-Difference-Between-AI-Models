There are a lot of artificial intelligence (AI) models out there; they are being developed every day. Now, some would ask if there is a real difference between them. Here we’re going to be going over some tests, performance, and overall intelligence. I will be using already open-sourced tests and other information to do this. Some models might not be tested in different tasks or subjects.

**Hallucination**

When AI hallucinates, this means that it is providing incorrect or misleading responses.  Some causes of AI hallucinations are insufficient data during training, assumptions made by itself, or it could be biases in the training data. AI hallucinations are a big problem; some real-world cases for this are personal/medical diagnoses, trading, and financial. I'm sure a lot of people would be upset if they received an incorrect diagnosis for their health.

I've gathered the hallucination information from Google, a trusted source. Here’s how they say AI hallucinations occur. Since AI learns to make predictions using patterns found in the data it was trained on, its accuracy mostly depends on the quality of that data. Let’s say some of the data is incorrect or misleading. Now, our model is getting trained on bad data. Which means it won't learn the correct patterns. Google's example for this is if you train AI based on damaged tissue, without providing data on healthy tissue. The model could falsely predict whether the tissue is healthy or unhealthy.

We're about to look into some of the different models and their hallucination rates. To ensure we understand what this means, let's discuss what the hallucination rate entails. AI hallucination rates are the percentage chance of the model giving you incorrect, misleading, or flawed information. Not too in-depth, but it should give you the understanding you're looking for. Now, let's look at some data for this.
Source: https://github.com/vectara/hallucination-leaderboard/blob/main/img/top25_hallucination_rates_with_logo_2025-08-07_v2.png

<img width="4337" height="2975" alt="image" src="https://github.com/user-attachments/assets/d919667f-afe6-4319-af01-997279e7b73d" />

Although this chart doesn't give us information on what task they were doing when running these, it was likely summarizing documents. Hallucination rates vary by the task they are performing. Using the data above, we can see Gemini-2.0-Flash has a 0.7% chance of giving you bad information. Runners-up are Gemini-2.0-Pro and o3-mini-high, giving 0.8%. We see GPT-5-high 12 rows down from the top, sitting at 1.4%. Grok-2, GLM-4.5-Air, and Nova-Pro-V1 are the highest on this list at 1.9% While Claude and DeepSeek are not on this chart, I'd like to go over them briefly. Claude-3.7-Sonnet-Think is a model with a 4.5% chance to hallucinate. Claude has other models, such as Claude-3.5-Sonnet. DeepSeek-R1-0528 is another capable model by a Chinese company. R1 has a hallucination rate of 7.7%, which is higher than every model mentioned.

**Thinking** 

The most capable models of AI have “thinking”. Now, don't look at this the way humans think; it is completely different. When models think, they process the information and make predictions based on what they learned from a lot of data, more than you have on every device in the room. All a model does when it thinks is analyze, identify, and generate. When we humans think, we use our consciousness, self-awareness, and opinions. We can make decisions in unknown territory, but AI cannot. 

Before getting into the charts below, let's talk about what “Thinking” and “Dynamic Thinking” mean. “Thinking” is static AI, which means it can process, analyze, recognize patterns, learn from experience, and make predictions based on its programming. “Dynamic Thinking” is when AI learns new patterns from continuously new data, responds to our real-time feedback, and adapts its behaviors.

<img width="1671" height="722" alt="image" src="https://github.com/user-attachments/assets/a26409f0-c616-4b7d-ab7c-0845777a3fb9" />

https://storage.googleapis.com/deepmind-media/gemini/gemini_v2_5_report.pdf

On the **left**, we see the American Invitational Mathematics Examination (AIME). This is a math competition for high school students. First 2.0-Flash (No Thinking) has about a 30% chance to pass. With thinking, we see it jump to about 45%. Moving onto 2.5-Flash and 2.5-Pro, 2.5-Flash has about a 70% chance, while 2.5-Pro has almost a 90% chance.

In the **middle**, Google Proof Q&A (GPQA) is exactly what the name suggests. Going in the same order as above, we see 2.0-Flash (No Thinking) at about 65%, 2.0-Flash (With Thinking) with about 70%, 2.5-Flash (Dynamic Thinking) with slightly over 80%, and finally 2.5-Pro (Dynamic Thinking) near 90%.

Going all the way over to the **right**, 2.0-Flash is slightly above 30%, 2.0-Flash (Thinking) is slightly above 40%, 2.5-Flash (Dynamic) is at about 60%, and finally 2.5-Pro (Dynamic) sits around 70-80%

Above these tests only go over Gemini, which is Google's AI. Let’s look at GPT, another popular AI made by OpenAI.

Source: https://openai.com/index/introducing-gpt-5/

<img width="1064" height="1186" alt="image" src="https://github.com/user-attachments/assets/2e020f9a-a19e-4c82-b8c2-1a4e52ef44ef" />

OpenAI provides us with a few different models here. While this is not the same test, it's still claimed to be “Expert-level math”. Starting with GPT-5 Pro (with Python), it has a 32.1% chance to pass, GPT-5 still with Python, just not the Pro model, goes down slightly to 26.3%. Finally going to GPT-5 with no tools, which is the most accurate as it is just bare bones GPT, it drops significantly to 13.5%.

I understand this might not be well written, as I am just starting out with public writing.
