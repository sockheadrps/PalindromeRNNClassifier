# PalindromeRNNClassifier
<!-- link image -->
![train](training_plot.png)
![terminal](ter.png)

```
python run.py
```

will create a new model in the saved_models folder.

you will need to update the path in the .env to reflect this model for the following:

You may then either-

(change this stress_test file to use model.keras in stead of polished_model.keras)
```
python stress_test.py
```

or leave the stress test the same, and try to polish the model. (line 16/17)

```python polish_model.py
```

followed by 
```python stress_test.py
```