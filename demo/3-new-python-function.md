# New Python function

```text
LlamaIndex relies on NLTK under the hood.

Write a new Python function that downloads NTLK's `punkt` and `stopwords`
to `/tmp/llama-index/`.

NTLK documentation:
- #fetch https://www.nltk.org/data.html
- #fetch https://www.nltk.org/nltk_data/

This project is hosted in Azure Functions. Make sure that the new function
is executed when the Function App starts, so that the NLTK data files
are available for LlamaIndex to use.

Remember to add a unit test for the new function.

Make a plan and then implement `download_nltk_data` function.
```

## Remark

In this demo Copilot implements both the new function and its unit test.
Beware that some consider this a really back practice:

> ### The Sacred Rule: Humans Write Tests
>
> Now we come to the most important principle in AI-assisted development.
> It’s so important that I’m going to repeat it in multiple ways until it’s
> burned into your memory:
>
> **Never. Let. AI. Write. Your. Tests.**
>
> Source: [field-notes-from-shipping-real-code-with-claude](https://diwank.space/field-notes-from-shipping-real-code-with-claude#:~:text=The%20Sacred%20Rule%3A%20Humans%20Write%20Tests)
