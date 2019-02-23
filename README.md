# We The Force TensorFlow.js Training MNIST model with Node.js for Mahle

This code train MNIST (using the layers API) under Node.js for a Mahle project.

This model will compute accuracy after one pass through the training dataset
(80 samples) and evaluate 80 images from the test data set for accuracy after each epoch.

Prepare the node environment:

```sh
$ npm install
# Or
$ yarn
```

Run the training script:

```sh
$ node main.js
```

If you are running on a Linux system that is [CUDA compatible](https://www.tensorflow.org/install/install_linux), try installing the GPU
package and replacing the require statement:

```sh
$ npm install @tensorflow/tfjs-node-gpu
# Or
$ yarn add @tensorflow/tfjs-node-gpu
```

After installing the package, replace `require('@tensorflow/tfjs-node')` with `require('@tensorflow/tfjs-node-gpu');` in main.js
