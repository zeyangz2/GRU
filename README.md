# GRU
train GRU mdoel with stroke therapist and patient data

We collected some sample data in file trial2.csv to train the network.

Feel free to change the hyperparameters in config_1.json. Recommand to directly use config_2.json.

Uncomment the lines in run.py to save your predicted results.

Use this jupyter notebook to get a 3D graph of predicted trajectory. You can use the results I got from file: saved test&predict results
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zeyangz2/GRU/blob/master/3D%20graph%20GRU%20results.ipynb)

Model architecture:

![model](https://github.com/zeyangz2/GRU/assets/73300066/95a95957-fd1a-4b7d-9d37-0f9272e9f271)


results:

# 3D prediction graph
(red line for ground truth and green line for our prediction)

![3d](https://github.com/zeyangz2/GRU/assets/73300066/05d50f9c-c96f-473a-a1e5-2026ea215c0c)




## **z_axis:**

![results_2_try](https://github.com/zeyangz2/GRU/assets/73300066/49d33d09-217f-4c70-b9b8-a3f85d53656e)


**z_axis model loss:**

point by point prediction test loss: 
mae:  21.149654617941962

![Model Loss](https://github.com/zeyangz2/GRU/assets/73300066/9c3f64d2-d98c-4fd6-8b07-92b4bd765c18)



## **y_axis:**

![results_2_try](https://github.com/zeyangz2/GRU/assets/73300066/f337d2c2-c405-412b-a93e-e7de0e8f2198)


**y_axis model loss:**

point by point prediction test loss: 
mae:  34.590864224617455

![Model Loss](https://github.com/zeyangz2/GRU/assets/73300066/ec06b321-b249-436c-8f76-3377829e9988)



## **x_axis:**

![results_2_try](https://github.com/zeyangz2/GRU/assets/73300066/e868b396-a959-461b-b334-6efcbc46a000)


**x_axis model loss:**

point by point prediction test loss: 
mae:  20.647305644118134

![Model Loss](https://github.com/zeyangz2/GRU/assets/73300066/cea4e4d7-ec36-449d-80c7-bee7f2b6f54f)


more updates later...


