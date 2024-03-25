# Tutorial: PyTorch Modules on the hook
This interactive tutorial gives an introduction to using hooks in PyTorch for visualization and debugging.

The notebook covers:
- What are hooks?
- Why are they useful?
- How does the forward hook work? Example: What happens to an image inside a ResNet?
- How does the backward hook work? Example: How can we inspect the gradient in each layer? How can we modify the gradients?

### Installation
Clone the repository to your computer.
Create a new `venv` with 
```
python -m venv venv-pytorch-hooks
```
and activate it:
```
source venv-pytorch-hooks/bin/activate
```
Afterwards, you can enter the folder `tutorial-pytorch-hooks` with 
```
cd tutorial-pytorch-hooks
```
and install the requirements
```
pip install requirements.txt
```

If you execute the notebook, make sure that you choose the newly setup environment!
