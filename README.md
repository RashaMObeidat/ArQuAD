# ArQuAD: An Expert-Annotated Arabic Machine Reading Comprehension Dataset

## Overview

ArQuAD is an expert-annotated Arabic Machine Reading Comprehension (MRC) dataset. It comprises 16,020 questions posed by language experts on passages extracted from the most frequently visited Arabic Wikipedia articles. Each question's answer is a text segment from the corresponding reading passage.

## Citation

If you use ArQuAD in your research, please cite the following paper:

```bibtex
@article{obeidat2024arquad,
  title={ArQuAD: An Expert-Annotated Arabic Machine Reading Comprehension Dataset},
  author={Obeidat, Rasha and Al-Harbi, Marwa and Al-Ayyoub, Mahmoud and Alawneh, Luay},
  journal={Cognitive Computation},
  pages={1--20},
  year={2024},
  publisher={Springer}
}

## Dataset Description

ArQuAD consists of 16,020 question-answer pairs created by Arabic language specialists with BA and MA degrees. The passages are sourced from 1335 of the most viewed Arabic Wikipedia articles, covering a wide range of topics including sports, politics, technology, religion, and more.

### Structure

The dataset is provided in both CSV and SQuAD JSON formats with the following columns:
- `passage`: The original passage from Wikipedia.
- `question`: The question posed by the annotator.
- `answer`: The minimal text span from the passage that answers the question.

### Statistics

The dataset includes:
- Total pairs: 16,020
- Passages: 4,005
- Domains covered: Various (sports, politics, technology, etc.)

### Key Features

- **Expert-Annotated**: Questions and answers are created by language experts, ensuring high quality and relevance.
- **Diverse**: Covers a wide range of topics to ensure comprehensive testing of MRC models, also includes a mix of factoid and non-factoid questions.

## Usage

Download the CSV file from the repository to use this dataset and load it into your preferred data analysis tool.


## Contact
or any questions or issues regarding the dataset, please contact:
Rasha Obeidat:rmobeidat@just.edu.jo (or any of the authors)
