# Polish ModernBERT

This anonymous repository accompanies the paper:

**Polish ModernBERT: The Long and Short of Polish Language Understanding**

The repository provides the
LongContext benchmark and the NKJP-NER* resources used in the paper. The
repository will be de-anonymized and released publicly upon publication.

## Model checkpoints

The following checkpoints will be available as assets of the repository release:

| Model | Context length | Parameters | Archive |
|---|---:|---:|---|
| Polish ModernBERT Base | 512 | 149M | `pl-modernbert-base-512.tar` |
| Polish ModernBERT Base | 8K | 149M | `pl-modernbert-base-8192.tar` |
| Polish ModernBERT Large | 512 | 475M | `pl-modernbert-large-512.tar` |
| Polish ModernBERT Large | 8K | 475M | `pl-modernbert-large-8192.tar` |

Each archive contains the model weights, configuration, and tokenizer files
required to load the model with Hugging Face Transformers.

### Loading a checkpoint

After downloading and extracting an archive:

```bash
tar -xzf pl-modernbert-base-512.tar
```

```python
from transformers import AutoModel, AutoTokenizer

model_path = "pl-modernbert-base-512"

tokenizer = AutoTokenizer.from_pretrained(model_path)
model = AutoModel.from_pretrained(model_path)
```

## LongContext

LongContext is a five-task Polish benchmark for long-document understanding:

- SCOTUS-Dom
- SCOTUS-Dec
- ECtHR-PL-AVA
- ECtHR-PL-VA
- BookSummary

The corresponding training, validation, and test splits are provided under:

```text
longcontext/
```

## NKJP-NER*

The `nkjp_ner_star/` directory contains the resources used for the NKJP-NER*
sequence-labeling task, including the preprocessing procedure and split
definitions.

```text
nkjp_ner_star/
```

## Repository structure

```text
.
├── longcontext/          # LongContext benchmark
├── nkjp_ner_star/        # NKJP-NER* resources
├── README.md
└── LICENCES.md
```

The four model checkpoints are distributed as repository release assets.

## Licenses

The model checkpoints and newly created resources are distributed under the
licenses specified in the corresponding directories. Resources derived from
existing datasets remain subject to their original licenses and terms of use.

## Anonymity

This repository has been prepared for anonymous peer review. Author names,
affiliations, and identifying metadata will be added after the review process.
