## EDDSNet

`Pytorch` is used for training and evaluating this architecture. An early project, just as a reference for subsequent improvements...

#### Packages
* [train.py](train.py) contains script for training the network
* [test.py](test.py) contains script for rendering predicted images to submit on [cityscapes](https://www.cityscapes-dataset.com/)  websites
* [benchmark.py](benchmark.py) is for evaluating inference time.
* [config.json](config.json) is where you can set the path to datasets.
* [datasets](datasets) contains tools for datasets loader (**camvid, pascal, cityscapes and sunrgb)**
* [models](models) contains the architecture of our model and other ones for evaluating performance.

#### Third Party Project Reference

- [**LightNetPlusPlus**](https://github.com/ansleliu/LightNetPlusPlus)

- [**PyTorch_Semantic_Segmentation**](https://github.com/charlesCXK/PyTorch_Semantic_Segmentation)

