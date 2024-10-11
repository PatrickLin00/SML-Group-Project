1. Dowlaod the dataset CIFAR-10 from https://www.cs.toronto.edu/~kriz/cifar.html
2. Run Noise_process.ipynb to generate noise datasets.
3. Run X-Y-hyperpara-select.ipynb to do hyper-parameter tuning.
4. Run X-evaluate.ipynb to do cross validation, cross-domain prediction and visualization.

----
Noise_process.ipynb - Used to add different levels of noise to the CIFAR-10 dataset to generate new datasets in the Noise_process.ipynb file: origin_noise_cifar10.npy, small_noise_cifar10.npy, medium_noise_cifar10.npy, and high_noise_cifar10.npy

ViT-origin-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the ViT model using origin datasets.
ViT-small-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the ViT model using small noise datasets.
ViT-medium-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the ViT model using medium noise datasets.
ViT-large-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the ViT model using different large noise datasets.

CNN-origin-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the CNN model using origin datasets.
CNN-small-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the CNN model using small noise datasets.
CNN-medium-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the CNN model using medium noise datasets.
CNN-large-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the CNN model using different large noise datasets.

MLP-origin-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the MLP model using origin datasets.
MLP-small-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the MLP model using small noise datasets.
MLP-medium-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the MLP model using medium noise datasets.
MLP-large-hyperpara-select.ipynb -  Perform Hyperparameter tunin on the MLP model using different large noise datasets.

ViT-evaluate.ipynb - Performance evaluation of the ViT model using different noisy datasets.
CNN-evaluate.ipynb - Performance evaluation of the CNN model using different noisy datasets.
MLP-evaluate.ipynb - Performance evaluation of the MLP model using different noisy datasets.