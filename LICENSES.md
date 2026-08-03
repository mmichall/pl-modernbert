# Licenses and Third-Party Data

This file summarizes the licensing status of the artifacts distributed with the anonymous submission **“Polish ModernBERT: The Long and Short of Polish Language Understanding.”**

This document is provided for attribution and transparency and is not legal advice. Third-party resources remain subject to their original licenses and terms of use. Nothing in this repository grants rights beyond those provided by the corresponding rights holders.

## Anonymous review status

During anonymous peer review, the model checkpoints and repository-specific files are made available solely to support evaluation and reproducibility of the submitted work. A final public license for the model checkpoints and original repository code will be added when the repository is de-anonymized.

## Model checkpoints

The following model checkpoints were trained by the anonymous authors:

- Polish ModernBERT Base (512 tokens)
- Polish ModernBERT Base (8K tokens)
- Polish ModernBERT Large (512 tokens)
- Polish ModernBERT Large (8K tokens)

**Current status:** anonymous-review release; final public license to be specified upon de-anonymization.

The checkpoints may reflect information learned from third-party pretraining corpora. Those source corpora remain subject to their respective licenses and terms.

## LongContext benchmark

### SCOTUS-Dom and SCOTUS-Dec

These tasks are derived from the `pasinit/scotus` dataset and publicly available U.S. Supreme Court materials.

- Source dataset: `pasinit/scotus`
- Source paper/data lineage: the Supreme Court Database and related public court-opinion resources
- License status: no explicit license was identified in the referenced Hugging Face dataset card during preparation of this file

The Polish translations, task formatting, and split files are provided for anonymous review and reproducibility. The original source materials and annotations are not relicensed by this repository. Users are responsible for verifying and complying with the applicable source terms before redistribution or downstream use.

### ECtHR-PL-AVA and ECtHR-PL-VA

These tasks are derived from the `AUEB-NLP/ecthr_cases` dataset.

- Source dataset: `AUEB-NLP/ecthr_cases`
- Source license: **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**
- License text: https://creativecommons.org/licenses/by-nc-sa/4.0/

The Polish translations and task adaptations are distributed under the same license. Users must provide attribution, indicate that translations and task adaptations were made, use the resource only for non-commercial purposes, and distribute adapted material under the same license.

Recommended attribution:

> Chalkidis, I., Fergadiotis, M., Tsarapatsanis, D., Aletras, N., Androutsopoulos, I., and Malakasiotis, P. (2021). Paragraph-level Rationale Extraction through Regularization: A Case Study on European Court of Human Rights Cases. NAACL 2021.

### BookSummary

This task is derived from the `kingkangkr/book_summary_dataset` collection. The source summaries were translated into Polish and paired with supported and unsupported claims generated for this work.

- Source dataset: `kingkangkr/book_summary_dataset`
- License status: no explicit license was identified in the referenced source repository during preparation of this file

The translations, generated claims, labels, and split files are provided for anonymous review and reproducibility. The original summaries are not relicensed by this repository. Before public redistribution, the exact license and provenance of the source collection should be confirmed and documented.

## NKJP-NER*

NKJP-NER* is derived from the manually annotated subcorpus of the National Corpus of Polish (NKJP1M).

- Source resource: NKJP1M / National Corpus of Polish
- Source license: **Creative Commons Attribution 4.0 International (CC BY 4.0)**
- License text: https://creativecommons.org/licenses/by/4.0/

The preprocessing procedure, document-level organization, annotations derived from the source resource, and split definitions are distributed under CC BY 4.0. Appropriate attribution to NKJP and its creators is required, and modifications should be indicated.

Recommended citation:

> Przepiórkowski, A., Bańko, M., Górski, R. L., and Lewandowska-Tomaszczyk, B. (eds.). (2012). *Narodowy Korpus Języka Polskiego*. Wydawnictwo Naukowe PWN.

## Repository-authored metadata and documentation

Files created specifically for this repository, including dataset descriptions, split metadata, checksums, and documentation, remain under the copyright of the anonymous authors during review. A public license will be added upon de-anonymization.

## User responsibilities

By using these materials, users agree to:

1. comply with all applicable third-party licenses and terms of use;
2. preserve required attribution and license notices;
3. indicate translations, transformations, and other modifications;
4. avoid using the legal and human-rights datasets for autonomous high-stakes decision-making; and
5. verify the licensing status of resources marked as unresolved before redistributing them.

## License status summary

| Artifact | Source | Status |
|---|---|---|
| Polish ModernBERT checkpoints | This work | Anonymous-review release; final license pending |
| SCOTUS-Dom / SCOTUS-Dec | `pasinit/scotus` | Source license not explicitly identified; review-only distribution pending verification |
| ECtHR-PL-AVA / ECtHR-PL-VA | `AUEB-NLP/ecthr_cases` | CC BY-NC-SA 4.0 |
| BookSummary | `kingkangkr/book_summary_dataset` | Source license not explicitly identified; review-only distribution pending verification |
| NKJP-NER* | NKJP1M | CC BY 4.0 |
