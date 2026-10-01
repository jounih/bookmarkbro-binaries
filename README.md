# Bookmark Bro binaries

Large files the Bookmark Bro apps download on demand, kept out of the app
download itself. Each one is a GitHub release asset with a SHA-256
checksum, which the app verifies before using it.

| Release | File | What |
|---|---|---|
| `minilm-coreml-v1` | `MiniLM-CoreML-v1.zip` | all-MiniLM-L6-v2 converted to Core ML (fp16, mean pooling and L2 normalisation built in, 256-token input), plus its tokenizer. Used for on-device semantic search. |

## Licences

- all-MiniLM-L6-v2 by sentence-transformers, Apache License 2.0:
  https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2
- The Core ML conversion is unmodified in its weights and is distributed
  under the same licence.
