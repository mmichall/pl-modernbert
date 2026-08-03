# Polish ModernBERT

This anonymous repository accompanies the paper:

**Polish ModernBERT: The Long and Short of Polish Language Understanding**

The repository provides the LongContext benchmark and the NKJP-NER*
resources used in the paper. The repository will be de-anonymized and
released publicly upon publication.

## Model checkpoints

The following four model checkpoints will be released publicly upon
publication:

| Model | Context length | Parameters | Planned archive |
|---|---:|---:|---|
| Polish ModernBERT Base | 512 | 149M | `pl-modernbert-base-512.tar` |
| Polish ModernBERT Base | 8K | 149M | `pl-modernbert-base-8192.tar` |
| Polish ModernBERT Large | 512 | 475M | `pl-modernbert-large-512.tar` |
| Polish ModernBERT Large | 8K | 475M | `pl-modernbert-large-8192.tar` |

Each archive will contain the model weights, configuration, and tokenizer
files required to load the model with Hugging Face Transformers.

After public release, a checkpoint will be loadable as follows:

```bash
tar -xf pl-modernbert-base-512.tar
