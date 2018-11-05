Image-classification
====================

This repo will contain image classificaion done in various settings.

MNIST
-----

| Model       | Train acc | Train loss   | Val avg loss   | Val acc    | Num Epochs | Batch size | Optimizer | Learning rate | Loss function             | Notes                  |
|-------------|:---------:|:------------:|:--------------:|:----------:|------------|------------|-----------|:-------------:|---------------------------|------------------------|
| Base        | 57397     | 9280.193998  | 0.0007         | 98.55%     | 20         | 64         | Adam      | 3e-4          | Categorical crossentropy  |                        |
| v1          | 57077     | 10061.503338 | 0.0007         | 98.43%     | 20         | 64         | Adam      | 3e-4          | Categorical crossentropy  | Added random rotations |
| v2          | 58219     | 6137.954557  | 0.0006         | 98.67%     | 20         | 64         | Adam      | 3e-4          | Categorical crossentropy  | Added 50 neurons to fc1|


 
