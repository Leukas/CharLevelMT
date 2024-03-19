# CharLevelMT
This repository will contain the results from [Are Character-level Translations Worth the Wait? Comparing ByT5 and mT5 for Machine Translation](https://arxiv.org/abs/2302.14220), presented at EACL2024, to be published in the next edition of TACL. 

### Models
The models used in this work can be found at: https://huggingface.co/leukas

All of the models have a name as follows:
```{model_name}-{dataset}-{amount_of_data}-{lang_pair}```
- `model_name` = byt5 or mt5
- `dataset` = wmt14 or nc16
- `amount_of_data` = 400, 2k, 10k, 50k, 250k, 1250k, or not specified for full wmt14
- `lang_pair` = ende, deen, enru, ruen, enes, ptes

Not all combinations exist, for more details check out the paper.

To use the models properly, be sure to start with the prompt "translate X to Y:"
e.g. "translate English to German:" 

### Outputs
Outputs and scores will be added soon. 


### Questions
If you have any questions don't hesitate to contact me (preferably via email). 
