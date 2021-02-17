# nlp-examples

```
021-02-17 13:31:03.618845: I tensorflow/compiler/jit/xla_cpu_device.cc:41] Not creating XLA devices, tf_xla_enable_xla_devices not set
2021-02-17 13:31:03.619030: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX2 FMA
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2021-02-17 13:31:03.711151: I tensorflow/compiler/mlir/mlir_graph_optimization_pass.cc:116] None of the MLIR optimization passes are enabled (registered 2)
Epoch 1/3
1875/1875 [==============================] - 2s 731us/step - loss: 0.4638 - accuracy: 0.8708
Epoch 2/3
1875/1875 [==============================] - 1s 744us/step - loss: 0.1129 - accuracy: 0.9656
Epoch 3/3
1875/1875 [==============================] - 1s 724us/step - loss: 0.0723 - accuracy: 0.9776
```

```
INFO:plaidml:Opening device "llvm_cpu.0"
Epoch 1/3
60000/60000 [==============================] - 8s 126us/step - loss: 0.2625 - acc: 0.9230
Epoch 2/3
60000/60000 [==============================] - 7s 124us/step - loss: 0.1075 - acc: 0.9667
Epoch 3/3
60000/60000 [==============================] - 8s 127us/step - loss: 0.0730 - acc: 0.9773
```

```
INFO:plaidml:Opening device "metal_amd_radeon_pro_5300m.0"
Epoch 1/3
60000/60000 [==============================] - 7s 119us/step - loss: 0.2596 - acc: 0.9235 
Epoch 2/3
60000/60000 [==============================] - 6s 105us/step - loss: 0.1044 - acc: 0.9677
Epoch 3/3
60000/60000 [==============================] - 6s 106us/step - loss: 0.0721 - acc: 0.9771
```

```
INFO:plaidml:Opening device "opencl_amd_radeon_pro_5300m_compute_engine.0"
Epoch 1/3
60000/60000 [==============================] - 11s 191us/step - loss: 0.2645 - acc: 0.9233  
Epoch 2/3
60000/60000 [==============================] - 9s 142us/step - loss: 0.1084 - acc: 0.9664
Epoch 3/3
60000/60000 [==============================] - 9s 142us/step - loss: 0.0738 - acc: 0.9766
```
