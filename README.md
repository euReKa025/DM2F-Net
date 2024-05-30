### README OF DIP PROJECT

**Environment setup:**

* Prepare the dataset.

   * Make a directory `./data` and create a symbolic link for uncompressed data, e.g., `./data/RESIDE`.

## Training

1. Set the path of datasets in tools/config.py
2. Run by ```python train_improve.py```


## Testing

1. Set the path of five benchmark datasets in tools/config.py.
2. Put the trained model in `./ckpt/` or your path.
3. Run by ```python test.py```

