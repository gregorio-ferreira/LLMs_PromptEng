# Prompt engineering: intro to different LLMs


________________________________________________
# From DeepLearning.AI:
## ChatGPT Prompt Engineering for Developers

While taking the free course [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) I downloaded all the notebooks, so I could continue learning and playing with them.

Here I will add some other experiments and keep the sources I'm consulting or learning from.

I hope it will help anyone else in their journey to learn how to take advantage of LLMs better and upskill.

### Notes on using the OpenAI API outside of the course's classroom

To install the OpenAI Python library:
```
!pip install openai
```

The library needs to be configured with your account's secret key, which is available on the [website](https://platform.openai.com/account/api-keys). 

You can either set it as the `OPENAI_API_KEY` environment variable before using the library:
 ```
 !export OPENAI_API_KEY='sk-...'
 ```

Or, set `openai.api_key` to its value:

```
import openai
openai.api_key = "sk-..."
```

### SUMMARY:

- Principles
    - Write clear and specific instructions
    - Give the model time to "think"
- Iterative prompt development
- Capabilities: Summarizing, Inferring, Transforming, Expanding.
- ChatBot capabilities.