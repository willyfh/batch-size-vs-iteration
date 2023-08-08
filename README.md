# The Relationship of Batch Size and Number of Iterations
In order to achieve a similar performance when using a different batch size, gradient accumulation is often applied. However, there is also an assumption that adjusting the number of epochs (to maintain the number of iterations accross different batch sizes) can also help to achieve a similar performance.

This small experiment attempts to address the following questions:

1) Do we need to increase the number of epochs, i.e., fix the number of iterations, as we increase the batch size?
2) Or do we need to fix the number of epochs, i.e., decrease the number of iterations, as we increase the batch size?

Note: While other hyperparameters, such as the learning rate, may also impact the results, I maintain consistent values for these parameters across all experiments.

## Dataset

## Architecture

## Results
