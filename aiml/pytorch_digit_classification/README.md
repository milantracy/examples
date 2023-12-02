Overview
----

An example to build, train, and evaluate a PyTorch model.

How to
----

1. Create a python virtual environment:

```
python -m venv venv
source venv/bin/activate
```

2. Install dependencies
```
pip install -r requirements.txt
// or pip install -r requirements_macos.txt
```

3. Train the model:

```
python train.py
```

A model for inference `simplenet.path` will be created.


4. Evaluate the model:

```
python evaluate.py
```

The outut will be like: `Accuracy on test dataset: 0.97`