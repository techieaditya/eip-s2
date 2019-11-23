
# 1. Epoch Logs
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 12s 207us/step - loss: 0.5578 - acc: 0.8436 - val_loss: 0.1389 - val_acc: 0.9728
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 6s 102us/step - loss: 0.2587 - acc: 0.9237 - val_loss: 0.0556 - val_acc: 0.9893
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 6s 100us/step - loss: 0.2046 - acc: 0.9388 - val_loss: 0.0550 - val_acc: 0.9859
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1716 - acc: 0.9470 - val_loss: 0.0472 - val_acc: 0.9872
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1574 - acc: 0.9476 - val_loss: 0.0350 - val_acc: 0.9918
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1417 - acc: 0.9512 - val_loss: 0.0327 - val_acc: 0.9911
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1329 - acc: 0.9514 - val_loss: 0.0296 - val_acc: 0.9927
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 6s 99us/step - loss: 0.1265 - acc: 0.9526 - val_loss: 0.0252 - val_acc: 0.9928
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1221 - acc: 0.9532 - val_loss: 0.0250 - val_acc: 0.9926
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1176 - acc: 0.9531 - val_loss: 0.0235 - val_acc: 0.9942
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1135 - acc: 0.9548 - val_loss: 0.0262 - val_acc: 0.9929
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1081 - acc: 0.9556 - val_loss: 0.0218 - val_acc: 0.9938
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1076 - acc: 0.9548 - val_loss: 0.0222 - val_acc: 0.9933
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 6s 103us/step - loss: 0.1044 - acc: 0.9565 - val_loss: 0.0227 - val_acc: 0.9930
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 6s 100us/step - loss: 0.1044 - acc: 0.9558 - val_loss: 0.0225 - val_acc: 0.9935
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 6s 100us/step - loss: 0.0990 - acc: 0.9575 - val_loss: 0.0219 - val_acc: 0.9943
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 6s 101us/step - loss: 0.1006 - acc: 0.9556 - val_loss: 0.0225 - val_acc: 0.9939
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 6s 100us/step - loss: 0.0985 - acc: 0.9570 - val_loss: 0.0228 - val_acc: 0.9940
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 6s 99us/step - loss: 0.0957 - acc: 0.9573 - val_loss: 0.0241 - val_acc: 0.9937
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 6s 99us/step - loss: 0.0974 - acc: 0.9560 - val_loss: 0.0196 - val_acc: 0.9943



# 2. model.evaluate() 
 [0.019637924702302554, 0.9943]
 
# 3. Steps Taken
I.Selecting appropriate filter size.
Increased the dropout value.
Set the bias value to false
tinkered with scheduler learning rate, turns out what was provided was quite good.
