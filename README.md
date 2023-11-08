# Marketplace Product Auto-Tagger using Monkey-Patch 🙈 

Example of how Monkey-Patch can be used to auto-tag products based on their description and name for a marketplace app.

## Installation

1. Install dependencies from requirements.txt

```bash
pip install -r requirements.txt
```

2. Create a `.env` file based on the `.env.example` file and fill in the required information. 

**Note**: You'll need an [OpenAI API key](https://openai.com/blog/openai-api) to use this. *Also note*, this demo uses the [BestBuy Product API](https://bestbuyapis.github.io/api-documentation/#products-api) , but you can use any API you want. Just make sure to update the code accordingly. If you want to use BestBuy, you'll need to create an account and get an API key from them.

3. Run the app

```bash
python app.py
```

