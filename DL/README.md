## Project Structure
In the **notebooks** folder there are the 4 python notebooks used for this project, that are:
- [encoderchestx.ipynb](https://github.com/Absoluty02/DLA/blob/main/DL/notebooks/encoderchestx.ipynb), which contains the code to train the AutoencoderCNN and the VAE
- [mapper](https://github.com/Absoluty02/DLA/tree/main/DL/notebooks/mapper), which is a folder that contains the notebooks of the two versions of the FF_mapper (that are [embedding](https://github.com/Absoluty02/DLA/tree/main/DL/notebooks/mapper/embedding) and [token](https://github.com/Absoluty02/DLA/tree/main/DL/notebooks/mapper/token))
- [transformerchestx.ipynb](https://github.com/Absoluty02/DLA/blob/main/DL/notebooks/transformerchestx.ipynb), which contains the code for the statistical analysis on the transformer
- [chestxrays.ipynb](https://github.com/Absoluty02/DLA/blob/main/DL/notebooks/chestxrays.ipynb), which contains the code of the **final architecture** plus the computed metrics

In the **pth** folder there are the 4 pth files used in the final architecture, divided in 2 folders:
- the [encoder](https://github.com/Absoluty02/DLA/tree/main/DL/pth/encoder) folder contains the pth of the encoder
- the [mapper](https://github.com/Absoluty02/DLA/tree/main/DL/pth/mapper) folder contains 2 folders, one for each approach, which are [embedding](https://github.com/Absoluty02/DLA/tree/main/DL/pth/mapper/embedding) (with two models, respectively for GPT2 and BioGPT pre-trained transformers) and [token](https://github.com/Absoluty02/DLA/tree/main/DL/pth/mapper/token)

We fine-tuned also GPT2 pre-trained transformer, but since the pth file is too large to be inserted here, you can download from Kaggle ([here](https://www.kaggle.com/models/emanueleconforti/gpt2_fine_tuned))

