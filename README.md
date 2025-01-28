# Pytorch Essential Functions

The Python scripts in this directory were ripped from a private repo of mine to use in open-source projects and Kaggle competitions. Might try to wrap this in an installable module eventually but in the meantime it's easier to just copy scripts into current working notebooks with the following:

```python
# Try to import the pytorch-essentials directory, download it from GitHub if it doesn't work
try:
    from src import <module>
except:
    # Get the essentials scripts
    print("[INFO] Couldn't find pytorch-essential scripts... downloading them from GitHub.")
    !git clone https://github.com/kyle-deprow/pytorch-essentials
    !mv pytorch-essentials/src .
    !rm -rf pytorch-essentials
    from src import <module>
```
