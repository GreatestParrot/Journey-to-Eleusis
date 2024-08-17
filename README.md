# Journey-to-Eleusis

This repo contains Jupyter Notebooks and scripts for research on moral bias of LLM. 
Script for scenarios generation and postprocessing are taken (or heavily based) on [code](https://github.com/kztakemoto/mmllm) and [research](https://doi.org/10.1098/rsos.231393) of Kazuhiro Takemoto.

## Usage

### Generation
The folder contains Jupyter notebook which could generate Moral Machine like scenarios in batch. Currently, Russian and English languages are available.
### Requests 
At the moment, three of notebooks are written for purpose of interaction with Yandex GPT, Sber's Gigachat and open-source models, available from LM Studio.
### Processing
- There are presented two scripts (rus and eng) to convert pickles with reponses of LLM (generated in requests and stored in pickles folder) to csv's with expanded form (stored in data folder).
- Notebook with result on LLM moral preferences.
