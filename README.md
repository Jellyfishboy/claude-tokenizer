# Claude Tokenizer

Claude Tokenizer is a Rust library for tokenizing text using the Anthropic Claude models. It provides functionality to tokenize text and count tokens, which is useful for working with Claude and other large language models.

## Features

- Tokenizer for Anthropic's Claude AI models
- `tokenize` function to convert text into tokens
- `count_tokens` function to calculate the number of tokens in a given text
- Embedded JSON tokenizer data for offline use
- Built on the `tokenizers` library for efficient tokenization

## Installation

Add this to your `Cargo.toml`:

```toml
[dependencies]
claude_tokenizer = "0.2.0"
```

Then, run `cargo build` to build your project.
