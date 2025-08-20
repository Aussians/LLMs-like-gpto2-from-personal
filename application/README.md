# Building a User Interface to Interact With the Instruction Finetuned GPT Model






![Chainlit UI example](https://sebastianraschka.com/images/LLMs-from-scratch-images/bonus/chainlit/chainlit-sft.webp?2)



To implement this user interface, we use the open-source [Chainlit Python package](https://github.com/Chainlit/chainlit).

&nbsp;
## Step 1: Install dependencies

First, we install the `chainlit` package via

```bash
pip install chainlit
```

(Alternatively, execute `pip install -r requirements-extra.txt`.)

&nbsp;
## Step 2: Run `app` code

The [`app.py`](app.py) file contains the UI code based. Open and inspect these files to learn more.

This file loads and uses the GPT-2 weights we generated. This requires that you execute the [`../ch07.py`](../ch07.py) file first.

Excecute the following command from the terminal to start the UI server:

```bash
chainlit run app.py
```

Running commands above should open a new browser tab where you can interact with the model. If the browser tab does not open automatically, inspect the terminal command and copy the local address into your browser address bar (usually, the address is `http://localhost:8000`).
