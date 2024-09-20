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

## Usage

Import the `claude_tokenizer` crate into your Rust project:

```rust
use claude_tokenizer;
```

Then, you can use the `tokenize` and `count_tokens` functions:

```rust
let text = "Hello, world!";
let tokens = tokenize(text).unwrap();
let token_count = count_tokens(text).unwrap();

println!("Tokens: {}", tokens);
println!("Token count: {}", token_count);
```

## License

The Claude Tokenizer Crate is licensed under the MIT License.

MIT License

Copyright (c) 2024 Tom Dallimore

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
