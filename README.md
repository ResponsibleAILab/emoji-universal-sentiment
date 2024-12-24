# Unlocking Cross-Lingual Sentiment Analysis through Emoji Interpretation: A Multimodal Generative AI Approach
This repository contains three files related to emoji sentiment analysis and processing. Below is an explanation of each file and its purpose:


## Files overview
### 1. Sentiment of emojis  
[**standalone_emoji_sentiment_with_pixel_icon_descriptions_by_GPT-4o.txt**](https://github.com/ResponsibleAILab/emoji-universal-sentiment/blob/main/standalone_emoji_sentiment_with_pixel_icon_descriptions_by_GPT-4o.txt)<br>
This file contains a dataset mapping emojis to their sentiment scores (+1: positive, 0: neutral, -1: negative) as inferred by GPT-4o using pixel, icon, and description representations. Each row corresponds to an emoji and its associated sentiment score.
### 2. Collecting emoji representation
[**emoji_representation_gathering.py**](https://github.com/ResponsibleAILab/emoji-universal-sentiment/blob/main/emoji_representation_gathering.py)  <br>
This script collects representations of emojis from Emojipedia.org and Unicode.org  
### 3. Combine multiple emoji sentiment 
[**sentiment_algorithms_by_standalone_emoji.py**](https://github.com/ResponsibleAILab/emoji-universal-sentiment/blob/main/sentiment_algorithms_by_standalone_emoji.py)  <br>
This script includes algorithms designed to infer text sentiment using standalone emojis, such as BSA, DPM, Majority Voting, and Position-Aware Sentiment algorithms. 

## Installation
Ensure the following libraries are installed before executing the Python scripts:

```bash
pip install emoji
```

## Citation
If you find this project useful for your research and applications, please cite using this BibTeX:
```bibtex
@misc{jahan2024unlockingcrosslingualsentimentanalysis,
      title={Unlocking Cross-Lingual Sentiment Analysis through Emoji Interpretation: A Multimodal Generative AI Approach},
      author={Rafid Ishrak Jahan and Heng Fan and Haihua Chen and Yunhe Feng},
      year={2024},
      eprint={2412.17255},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2412.17255},
}
```
