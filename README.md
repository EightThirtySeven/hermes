# Hermes AsyncAPI Specification (Incomplete)
An AsyncAPI specification of the [Hermes](https://docs.snips.ai/reference/hermes) protocol for voice assistants.

## Generating HTML Docs
Use the AsyncAPI Node generator.
### Installation
```bash
$ node install -g @asyncapi/generator
$ node install -g @asyncapi/html-template
```
### Usage
```bash
$ ag hermes.yml -o docs @asyncapi/html-template
```
