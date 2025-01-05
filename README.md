# Deepseek Coder

This package uses Deepseek Coder 1.3B Instruct-tuned Language Model for code generation in the terminal.

A GPU is not required but makes the responses faster.

It's based on:
- [Aider](https://aider.chat/)
- [vLLM](https://docs.vllm.ai/en/latest/)

### Installation
```sh
pip install deepseek-coder
```

### Usage
```sh
deepseek-coder
```

The first time you run `deepseek-coder` the model weights will be downloaded which can take a while.

```sh
tail -f /tmp/deepseek_coder.log # this will show the download progress
```

#### Options
```sh
deepseek-coder --logpath /path/to/logs
```

### Backlog
- [] improve Aider default prompts and prevent multiple completions due to "improperly formatted response"
- [] env var for tokens
- [] multi-platform tests