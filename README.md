## Comparison of Feature Extraction Techniques for Sequential Hybrid Quantum Neural Network Architectures in Binary Image Classification.  
Using the MNIST Digit, MNIST Fashion and FER-2013 facial expression dataset all adjusted for binary classes, I explore the use of different image preprocessing techniques within the neural network architectures. Specifically, I compare the use of PCA Feature reduction techniques, Matrix product state(MPS) feature reduction technique, and truncation of features within the sequential hybrid neural network architecture.  My results show that PCA is most effective across the simpler and more complex datasets in terms off efficiency and accuracy, while PCA is slightly more effective that using no feature extraction technique.  . MPS on the other hand shows no advantage and might need further tuning. In more complex data sets like FER, convergence stalls resulting in poor accuracy. Further tuning and exploration is necessary to bring the accuracy of FER dataset to be on PAR with the MNIST Dataset. 

The files that begin with Final contain the code for each dataset implementation. 

To Implement this code, Create a virtual environment with a dedicated Kernel using the following code on your terminal. Ensure that Python 3.10 or above and your local package manager such as homebrew for Mac Os is already installed. 

~~~python 

python3.8 -m venv qnn # in this case the virtual environment name is qnn

source qnn/bin/activate

python -m ipykernel install --user --name=knlpennqnn --display-name="penn_qnn_env_Kernelpython3,10  # You can choose your own name for the kernel. 
~~~

You will need to install the following core libraries Along with the more traditional ML Libraries. Installations can be done in a dedicated tab with the virtual environment activated: 
Pennylane
Torch








