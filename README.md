# BERT EENCR Implementation

## Training instructions
If you want to train the model using the training config file
- Follow the [official instructions](https://github.com/allenai/allennlp) to setup a new conda environment and installing allennlp with pip
- Download this repo, replace the installed allennlp library with the contents of the allennlp_modified folder. For me, the allennlp is in ```lib\site-packages\allennlp```
- Open training_config and set the   "train_data_path",  "validation_data_path", and "test_data_path" to the three files inside the "preco dataset" folder
- Run ```allennlp train training_config.json -s ./model_output_folder```

## Using the model
My trained CR model is too large, so I uploaded it [here](https://drive.google.com/file/d/14hnFjmq3a-lq2oml8U4mNzyPObWXasQI/view?usp=sharing)
