# LMs-Perceive-Social-Norms
[![arXiv](https://img.shields.io/badge/arXiv-2502.02696-b31b1b)](https://arxiv.org/abs/2502.02696)
[![YouTube Presentation](https://img.shields.io/badge/YouTube-Video-red?logo=youtube)](https://youtu.be/2v18R02mq8I)

This work, accepted to **NAACL 2025 Findings**, studies how inclusively large language models (LLMs) perceive social and moral norms across demographic groups (e.g., gender, age, income).  

- 📘 **Paper**: [How Inclusively do LMs Perceive Social and Moral Norms?](https://arxiv.org/abs/2502.02696)
- 🎥 **Presentation**: [YouTube Video](https://youtu.be/2v18R02mq8I)
- 🤖 **Prompt Outputs**: [LLM Prompt Outputs](data/llm_prompt_outputs/rot)
- 🗂️ **Dataset**: [Social Chemistry 101 by Forbes et al. (2020)](https://github.com/mbforbes/social-chemistry-101)
  
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
