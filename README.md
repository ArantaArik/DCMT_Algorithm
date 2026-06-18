# DCMT: Dialect-Controlled Machine Translation

This repository contains the implementation of the Marian-DCMT framework and the Sasak Multi-Dialect Dataset developed for English-to-Sasak machine translation with multi-dialect outputs.

# Sasak Multi-Dialect Dataset

This research focuses on developing a machine translation system capable of generating translations in multiple Sasak dialects from a single English input. Sasak is a low-resource language spoken in Lombok, Indonesia, and exhibits substantial dialectal variation.

The dataset includes parallel English–Sasak sentence pairs annotated with five Sasak dialects:

- Kuto-Kute (Pemenang)
- Ngeno-Ngene (Selaparang)
- Ngento-Ngente (Suralaga)
- Meno-Mene (Pejanggik)
- Mriak-Meriku (Pujut)

The proposed Marian-DCMT model extends the Marian-MT architecture by incorporating dialect-aware conditioning mechanisms, enabling the generation of dialect-specific translations within a unified framework.
