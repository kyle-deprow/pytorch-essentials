# Pytorch Essential Functions

The Python scripts in this directory were ripped from a private repo of mine to use in open-source projects and Kaggle competitions. Might try to wrap this in an installable module eventually but in the meantime it's easier to just copy scripts into current working notebooks with the following:

```python
# Try to import the going_modular directory, download it from GitHub if it doesn't work
try:
    from going_modular.going_modular import data_setup, engine
except:
    # Get the going_modular scripts
    print("[INFO] Couldn't find going_modular scripts... downloading them from GitHub.")
    !git clone https://github.com/kyle-deprow/pytorch-essentials
    !mv pytorch-essentials/src .
    !rm -rf pytorch-essentials
    from src import <module>
```
