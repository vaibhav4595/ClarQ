# ClarQ: A large-scale and diverse dataset for Clarification Question Generation

This dataset is meant for training and evaluation of Clarification Question Generation Systems. The details and the methodology used in the creation of the dataset can be found in the [paper](https://arxiv.org/abs/2006.05986). The work was published in ACL 2020.

## Link to the Dataset

The dataset can be found at [https://drive.google.com/drive/folders/1aqTiRgFq1pGVZhqJ_rDksZZg8v8m_3eX?usp=sharing](https://drive.google.com/drive/folders/1aqTiRgFq1pGVZhqJ_rDksZZg8v8m_3eX?usp=sharing).

## Details 

There are two files in the above link. "train.json" is meant for training whereas "test.json" is meant for evaluation.
Each line in the file is a json consisting the following keys:`
| Key | Description |
|:--- |:---         |
| id  | Id of the example|
| context | Text of the post |
| cquestion | The corresponding clarification question to the post |
| answer | The answer to the post |

## License

<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png">
This dataset is licensed under the Creative Commons Attribution 4.0 International License.

## References
If you find the data useful and use it for your work, please consider citing the following:
```
@misc{kumar2020clarq,
    title={ClarQ: A large-scale and diverse dataset for Clarification Question Generation},
    author={Vaibhav Kumar and Alan W. black},
    year={2020},
    eprint={2006.05986},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
