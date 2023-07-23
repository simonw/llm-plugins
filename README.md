# The LLM plugins directory

[LLM](https://llm.datasette.io/) is a command-line tool for executing Large Language Models such as GPT-3.5, GPT-4, PaLM 2 and more.

This repository lists available [plugins](https://llm.datasette.io/en/stable/plugins/index.html) for LLM.

Background on this project:

- [The LLM CLI tool now supports self-hosted language models via plugins](https://simonwillison.net/2023/Jul/12/llm/)

## Available plugins

- **[llm-gpt4all](https://github.com/simonw/llm-gpt4all)** adds support for various models released by the [GPT4All](https://gpt4all.io/) project that are optimized to run locally on your own machine. These models include versions of Vicuna, Orca, Falcon and MPT - here's [a full list of models](https://observablehq.com/@simonw/gpt4all-models).
- **[llm-palm](https://github.com/simonw/llm-palm)** adds support for Google's [PaLM 2 model](https://developers.generativeai.google/).
- **[llm-replicate](https://github.com/simonw/llm-replicate)** adds support for remote models hosted on [Replicate](https://replicate.com/), including Llama 2 from Meta AI.
- **[llm-claude](https://github.com/tomviner/llm-claude)** by Tom Viner adds support for Claude and Claude Instant by Anthropic.
- **[llm-mpt30b](https://github.com/simonw/llm-mpt30b)** adds support for the [MPT-30B](https://huggingface.co/mosaicml/mpt-30b) local model.
- **[llm-markov](https://github.com/simonw/llm-markov)** adds a simple model that generates output using a [Markov chain](https://en.wikipedia.org/wiki/Markov_chain). This example is used in the tutorial [Writing a plugin to support a new model](https://llm.datasette.io/en/latest/plugins/tutorial-model-plugin.html).

## Build your own

The tutorial [Writing a plugin to support a new model](https://llm.datasette.io/en/stable/plugins/tutorial-model-plugin.html) has detailed instructions on writing your own plugin.
