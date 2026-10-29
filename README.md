\# TrustClean



LLM-assisted data cleaning for messy Hindi, Hinglish, and English datasets,

with a verification step so every fix can be trusted.



\## Problem

Real-world records often mix Devanagari Hindi, Hinglish (Hindi in English

letters), and English. The same name or place can appear in many spellings,

which breaks duplicate detection and analysis. Existing cleaning tools

mostly assume clean, English-only data.



\## Goals

\- Build an open benchmark of real messy datasets with labeled errors

\- Compare rule-based, ML, and LLM-based cleaning

\- Provide a hybrid tool: the LLM suggests fixes, a validator checks them

\- Provide a visual interface to review, approve, or reject changes



\## Repository structure

\- `data/` datasets and annotations

\- `benchmark/` evaluation scripts and baselines

\- `src/` the hybrid cleaning tool

\- `ui/` visualization interface

\- `notebooks/` dataset profiling and experiments

\- `docs/` annotation guidelines and literature notes



\## Status

Phase 1: literature review and dataset collection (Months 1-2)



\## License

Code: MIT. Data: CC BY 4.0.

