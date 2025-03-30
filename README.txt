# chatGPT-prompt-engineering-for-python (Early Exploration - Circa ChatGPT 3.5)

**Preface:** This repository was created in the early days of ChatGPT 3.5 to explore the potential of using a meta-language for coding that could be understood by both programmers and emerging AI models. The following preface is based on an initial conversation with a chatbot, supplemented with my own insights into the general process. While the landscape of AI and prompt engineering has evolved significantly since then, this repository is maintained for historical reference and to capture the initial ideas surrounding this concept.

---

It seems you're exploring the idea of using a meta-language for coding that is interpretable by both programmers and AI. You're using prompts or "prompt strings" as examples to illustrate your point.

A meta-language is essentially a language used to describe another language, and it can be a powerful tool for enabling communication between humans and AI. By defining a meta-language that is interpretable by both humans and AI, it becomes easier to create code that is both understandable and optimizable by both parties.

In your first example, you're using a Python code snippet to resize an image and extract the red pixel values. The prompt string "{image location:str} -> {resize 4098,4098} -> {red pixels values:list} in python" can be interpreted as follows:

- "{image location:str}" specifies that the input is an image file location, which is a string.
- "-> {resize 4098,4098}" indicates that the image will be resized to a specific size, in this case, 4098 x 4098 pixels.
- "-> {red pixels values:list}" indicates that the output will be a list of red pixel values from the resized image.

By defining the prompt string in this way, both humans and AI can understand the steps required to perform this image processing task.

In your second example, you're using a prompt string to retrieve the moon phase and position based on a specific datetime and location. The prompt string "{datetime:datetime,location:tuple} => {moon phase:str,moon position:tuple}" can be interpreted as follows:

- "{datetime:datetime,location:tuple}" specifies that the input is a datetime and location tuple.
- "=> {moon phase:str,moon position:tuple}" indicates that the output will be a string representing the moon phase, as well as a tuple representing the moon's position.

Again, by defining the prompt string in this way, both humans and AI can understand the steps required to retrieve this information.

Overall, the use of a meta-language can be a powerful tool for enabling communication between humans and AI in the realm of coding. By defining a meta-language that is interpretable by both parties, it becomes easier to create code that is both understandable and optimizable by both humans and AI. I encourage you to explore this idea further and see what other prompt strings or meta-languages you can come up with!

---

**LLMs and Prompt Engineering (Initial Understanding):**

Regarding the LLM (Large Language Model) and prompt engineering, here's how the prompt input works (based on the understanding at the time of this repository's creation):

1.  The prompt: `{token_string_probability_mask}`
2.  Reply: `{most_probable:token_string_probability_mask + token} -> next({most_probable:token_string_probability_mask + token}) -> ... -> {low_probability_stop_function}`

General prompt engineering involves designing the bitmask or prompt. In that vein, here is your prompt for the day: `7361792068656c6c6f,696e207370616e697368` (This appears to be a hexadecimal representation of "hello, in spanish").

---

**Prompt String Meta-Language:**

This repository introduces a simple meta-language called **Prompt String** for describing computational tasks. The general syntax follows the pattern:
