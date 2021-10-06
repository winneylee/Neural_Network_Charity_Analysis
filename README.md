# Neural_Network_Charity_Analysis

## Purpose of this analysis

The purpose of this analysis is to use our knowledge of machine learning and neural networks in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Process

### Preprocessing Data for a Neural Network Model

![Screen Shot 2021-10-06 at 3 10 54 PM](https://user-images.githubusercontent.com/81284888/136291326-7633bafb-e7b0-4703-998a-db002937e828.png)

### Compile, Train, and Evaluate the Model

![Screen Shot 2021-10-06 at 3 11 11 PM](https://user-images.githubusercontent.com/81284888/136291519-cf8fdbc8-29dd-4262-946d-80ea595f86a4.png)

![Screen Shot 2021-10-06 at 3 11 28 PM](https://user-images.githubusercontent.com/81284888/136291551-87228a72-3925-4fc5-928b-29d3e7a76ebd.png)

### Optimize the Model

- Attempt 1: Dropping more colums: 
 
Besides the "EIN" and "NAME" columns, we also drop the "ASK_AMT" columns in order to see the result.

![Screen Shot 2021-10-06 at 3 21 28 PM](https://user-images.githubusercontent.com/81284888/136292185-ebfc9fee-f7d3-4479-80aa-2b51ad7dfd7a.png)

![Screen Shot 2021-10-06 at 3 23 26 PM](https://user-images.githubusercontent.com/81284888/136292204-e29325da-47d0-4b30-9c59-7e8f8e2bee39.png)

- Attempt 2: Adding more neurons to a hidden layer and adding more hidden layers:

We increase the layer to 3 layers, and we also increase the hidden nodes in each layer.

![Screen Shot 2021-10-06 at 3 23 42 PM](https://user-images.githubusercontent.com/81284888/136292625-4d564dc8-a49a-48e1-a470-38fb1c4db95b.png)

![Screen Shot 2021-10-06 at 3 23 55 PM](https://user-images.githubusercontent.com/81284888/136292635-c22f0682-4de5-4543-97ac-5db96d9c5465.png)

- Attempt 3:Reducing the number of epochs to the training regimen.

![Screen Shot 2021-10-06 at 3 24 32 PM](https://user-images.githubusercontent.com/81284888/136292674-5510ee80-5681-444e-963e-d0c10d7fcffc.png)



