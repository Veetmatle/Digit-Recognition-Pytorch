### Hello, this is done as a beginning learning project. General information:

`This is a neural network implemented using PyTorch to recognize digits from the MNIST dataset. MNIST consists of handwritten digits (0-9) and is commonly used for training image classification models.`

Basically we work on provided data from MNIST dataset, which is divided into training and testing data.
![image](https://github.com/user-attachments/assets/c7998cd2-b5fc-4e9d-81ba-79fa621bf604)

Later on we define our neural network model CNN using PyTorch. The network uses two convolutional layers followed by a couple of fully connected layers. Dropout is applied to avoid overfitting.
![image](https://github.com/user-attachments/assets/07d11db1-855d-4d97-8dc2-70c4d21f0bfb)

After that we should train and test our data, calculating the average loss and accuracy with each batch.
![image](https://github.com/user-attachments/assets/045ae6a5-0854-4614-8b34-0ffffc8b2a8d)

And we apply it:

![image](https://github.com/user-attachments/assets/76fed64c-1fc7-457e-a38f-2aca70cea09d)

Where result should appear something like this:

![image](https://github.com/user-attachments/assets/19a53e0e-bf82-4ef4-ac95-371bc7ea90bb)

At the end I load my pictures with same pattern as those provided in MNIST dataset and as expected I get decent results.

![image](https://github.com/user-attachments/assets/c4af0d0f-fff9-416e-9e14-4b179b25270c)
![image](https://github.com/user-attachments/assets/6d415e6c-2049-41e2-a677-a8c860903fbf)
![image](https://github.com/user-attachments/assets/69106c0e-583d-4ed5-8a12-b01518ef8eee)
![image](https://github.com/user-attachments/assets/a5715662-a22a-4050-9cb7-ec0d7474c446)


This project can be expanded. Model can be trained to use defferent number formats than this one from MNIST to adapt more widely. It can be used as an example for further pytorch learning, as it's the good beginning one in my opinion.






