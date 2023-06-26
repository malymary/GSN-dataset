# GSN Dataset

The dataset was generated with the aim of reproducing the experimental results of ["GSN: A Graph-Structured Network for Multi-Party Dialogues"](https://github.com/morning-dews/GSN-Dialogues) by restructuring the [Molweni Dataset](https://github.com/HIT-SCIR/Molweni).

### Training, Validation, Testing

All three subsets can be found in the **GSN_dataset** folder. They are stored as json files with corresponding names.

### Generating the Dataset

The input data and code necessary to generate the dataset can be found in the **molweni_for_gsn** folder.

To generate the dataset, run:

```
python generate.ipynb
```
