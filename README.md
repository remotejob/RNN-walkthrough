# Vanilla Recurrent Neural Network Walkthrough

This repo holds the code for the implementation in my FloydHub article on RNNs:

(https://blog.floydhub.com/a-beginners-guide-on-recurrent-neural-networks-with-pytorch/)


kaggle datasets create -p data/
kaggle datasets version -p data/ -m "Updated data fin"


kaggle kernels push -p train/
kaggle kernels status sipvip/rnnwalkthrough
kaggle kernels output sipvip/rnnwalkthrough -p output/
cp output/model0.pt data/model0.pt
kaggle datasets version -p data/ -m "Updated data 0"
kaggle datasets status sipvip/rnnwalkthroughdata


kaggle kernels push -p generator/
kaggle kernels status sipvip/textgenpytorchbywordsgen
kaggle kernels output sipvip/textgenpytorchbywordsgen -p output/
