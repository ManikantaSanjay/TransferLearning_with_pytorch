# Transfer Learning With Pytorch

### :one: Motive :
Trying to Understand the power of Transfer Learning by making use of a Pre-Trained Model, Resnet-50

### :two: Description : 

i> We are making use of the Imagewoof dataset to create a classification model by  making use of a pre-trained model Resnet-50.

ii> We are achieving a accuracy of over 90% by training with just 10 epochs involved.

iii> We look at how the model performs without the help of the pre-trained model giving an accuracy of just over 30% with the same number of epochs and not performing well enough for further more epochs also.
 

### 3️⃣ About the Dataset :
Imagewoof is a subset of 10 dog breed classes from Imagenet.

The breeds are: Australian terrier, Border terrier, Samoyed, Beagle, Shih-Tzu, English foxhound, Rhodesian ridgeback, Dingo, Golden retriever, Old English sheepdog.

Check the Below URL for the dataset 👇
#### https://s3.amazonaws.com/fast-ai-imageclas/imagewoof2-160.tgz 🔗

### 4️⃣ Libraries Used :

i> PyTorch

ii> MatplotLib

iii> OS

### 5️⃣ Steps involved in the notebook file :

#### Step 1 :  Importing Libraries

#### Step 2 : Downloading Dataset

#### Step 3 : Data Transformations

#### Step 4 : Creating the Train and Test Dataset

#### Step 5 : Setting the Batch Size

#### Step 6 : Creating Data Loaders

#### Step 7 : A Look at Sample Images from the Training Dataloader

#### Step 8 : Making Use of the GPU 

#### Step 9 : Moving Dataloaders to Device

#### Step 10 : Defining the Classification Model

#### Step 11 : Loading the Pre-Trained Model Class

#### Step 12 : Defining the Function for the Training Process

#### Step 13 : Training the Model using the pre-trained model class

#### Step 14 : Plotting graphs for Accuracy vs number of Epochs involved and Loss per Epoch

#### Step 15 : Loading the Non Pre-Trained Model Class

#### Step 16 : Training the model using the above class ☝️

#### Step 17 : Plotting Graphs for Accuracy and Loss Per Epoch

### 6️⃣ Link to Jupyter Notebook File 👇

#### https://github.com/ManikantaSanjay/TransferLearning_with_pytorch/blob/master/Transfer_Learning.ipynb 🔗

### 7️⃣ Conclusion :

From the above models, it is clear that with the help of pre-trained model Resnet-50 we were able to generate a whooping accuracy of over 90% whereas without the pre-trained model, we were barely achieving a mere 30% accuracy which is totally unacceptable and emphasising the importance of <b> Transfer Learning in building Deep Learning Applications .</b>




