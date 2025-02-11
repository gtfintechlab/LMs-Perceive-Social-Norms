# LMs-Perceive-Social-Norms
This repository contains the Jupyter Notebooks, prompts, and prompt outputs for the NAACL 2025 Findings paper "[How Inclusively do LMs Perceive Social and Moral Norms?](https://arxiv.org/abs/2502.02696)" In this work, we investigate how inclusively LMs perceive norms across demographic groups (e.g., gender, age, and income). We prompt 11 LMs on rules-of-thumb (RoTs) and compare how their outputs align with the existing responses of 100 human annotators from the [Social Chemistry 101 Dataset](https://github.com/mbforbes/social-chemistry-101).

## Code
The Jupyter Notebooks are located in `scripts`.

`scripts/llm_annotation.ipynb` : To create prompts and output LM annotations for different RoT.

`scripts/llm_parse.ipynb`: Parsing the LM responses. This is only the parsing code.
 
`scripts/analyze_outputs.ipynb` : Analysis, metrics, and graph creations.
 
### Environment and Setup
The notebooks can be run with the ``` environment.yml ``` file.

```
conda env create --file environment.yml
```

## Data

### Prompt Outputs

The prompt outputs are located in `data/llm_prompt_outputs/rot`.

### Social Chemistry 101 Dataset
In this work, we utilize the Social Chemistry 101 Dataset, a learn-to-reason dataset on social and moral norms.
Following prior work, we also obtained the dataset's demographic information by contacting the dataset’s creators. This was used for our analysis. If you want that information, please contact the authors of Social Chemistry 101.

## Cite
Please cite our paper if you find our findings useful. 

```c
@misc{galarnyk2025inclusivelylmsperceivesocial,
      title={How Inclusively do LMs Perceive Social and Moral Norms?}, 
      author={Michael Galarnyk and Agam Shah and Dipanwita Guhathakurta and Poojitha Nandigam and Sudheer Chava},
      year={2025},
      eprint={2502.02696},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2502.02696}, 
}
```
