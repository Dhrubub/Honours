# Installation and Testing
This folder contains the final code files used for generating data, training and testing for this project.

Download the relevant data from: https://drive.google.com/drive/folders/1RR3hjPjS-JBPq091lx_c-Uv1xTZ5u4nS?usp=sharing

The folder contains 3 subfolders for datasets 1, 2 and 3. Each of these folders contains 3 folders: training, validation and testing which is split in ratios of 70:10:20 respectively.

Download the relevant models from: https://drive.google.com/drive/folders/1uqshCcdpHeq-HPh3i4bixM9etdFaVQnM?usp=sharing

combined_models/ currently contains one model DaViT_B which is trained on all 3 datasets. The 3 datasets were individually split into a train:validation:test ration of 70:10:20

Edit the lines with the relevant path and model name of the model to use.

```python
model_path = "./models"
m = "daViT_B"
```

To run this code and test the model, open terminal on a Mac and copy the following commands:

``` bash
python3 -m venv venv
source venv/bin/activate

pip3 install -r req.txt

```

Open testing.ipynb and run the code blocks. The final code block will prompt you to select an image.

From the data/ folder, select any subfolder (1, 2, 3) which relate to datasets 1, 2 and 3 and select the testing folder. Select any image you would like to test.

