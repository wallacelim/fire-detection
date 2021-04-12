# fire-detection

## To run the binary classifier
1. Run the `load_data_binary` script. Subsequently, you should find an `X_binary` and `y_binary` pickle file saved into your directory.
2. Run the `fire_detection_binary` script. This should create train and save several models in your directory.
3. While (2) is ongoing, you may observe the training process via the following command:
```bash
tensorboard --logdir=logs/
```
This spins up a TensorBoard client available via `localhost:6006/` (by default)

