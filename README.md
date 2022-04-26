# CNN
Model1:
	final train: 0.9217 / Val: 0.9180
	epoch1: 0.4910 0.7171 
	epoch2: 0.7866 0.8358
	epoch3: 0.8531 0.8727
	epoch4: 0.8781 0.8893
	epoch5: 0.8904 0.8981
	#params 149834
	Avg epoch time: 9s ~ 10s
	Model Aech:
		Conv2D: 64 each(5, 5), strides=(2,2), activation=relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Dense: 64, activation='relu'
		Dense: 10, activation='softmax'
	Optimizers: SGD, lr 0.0001, momentum 0.9, epochs 10, batch size 32

Model2:
	final train: 0.9325 0.9370
	epoch1: 0.4889 0.6504
	epoch2: 0.7332 0.8063
	epoch3: 0.8338 0.8562
	epoch4: 0.8679 0.8814
	epoch5: 0.8851 0.8920
	#params 149834
	Avg epoch time 9s ~ 10s
	model Arch: Same as Model 1
	Optimizers: epochs 15, ... SAME
	
Model3
	final train: 0.9412 0.9444 
	epoch1: 0.4906 0.7059
	epoch2: 0.7799 0.8276
	epoch3: 0.8487 0.8644
	epoch4: 0.8740 0.8849
	epoch5: 0.8871 0.8941
	#params 149834
	Avg epoch time 9s ~ 10s
	model Arch Same as Model 1
	Optimizers epochs 20, ...SAME
	
model4:
	final train: 0.9959 0.9848  
	epoch1: 0.9480 0.9790
	epoch2: 0.9821 0.9837
	epoch3: 0.9864 0.9844
	epoch4: 0.9898 0.9856
	epoch5: 0.9921 0.9863
	#params 149834
	Avg epoch time 9s ~ 10s
	model Arch Same as Mode1
	Optimizers lr 0.05, ...SAME
model5:
	final train:  0.9893 0.9861
	epoch1: 0.8103 0.9116
	epoch2: 0.9230 0.9420
	epoch3: 0.9458 0.9568
	epoch4: 0.9580 0.9644
	epoch5: 0.9657 0.9699
	#params 149834
	Avg epoch time 9s ~ 10s
	model Arch Same as Model1
	Optimizers lr 0.001, ...SAME
model6:
	final train: 0.9999 0.9906
	epoch1: 0.9247 0.9671
	epoch2: 0.9778 0.9822
	epoch3: 0.9842 0.9839
	epoch4: 0.9874 0.9863
	epoch5: 0.9910 0.9881
	#params  149834
	Avg epoch time 9s ~ 10s
	model Arch Same as Model1
	Optimizers lr 0.01, ...SAME
model7:
	final train: 0.1000 0.9912
	epoch1: 0.9461 0.9791
	epoch2:	0.9830 0.9864
	epoch3:	0.9885 0.9872
	epoch4: 0.9908 0.9877
	epoch5: 0.9927 0.9884
	#params 
	Avg epoch time 9s ~ 10s
	model Arch
		Conv2D: 32 each(3, 3), relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Conv2D: 32, each(3, 3), relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Dense: 64, relu
		Dense: 32, relu
		Dense: 10, softmax
	Optimizers SAME
model8:	
	final train: 0.9837 0.9710
	epoch1: 0.8571 0.9232
	epoch2: 0.9439 0.9447
	epoch3: 0.9549 0.9601
	epoch4: 0.9627 0.9572
	epoch5: 0.9668 0.9563
	#params
	Avg epoch time 9s ~ 10s
	model Arch:
		Conv2D: 16, each(3, 3), strides(2, 2), relu
		MaxPooling2D: pool_size(2, 2), strides=(2, 2)
		Conv2D: 32, each(3, 3), strides(2, 2), relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Dense: 64, relu
		Dense: 32, relu
		Dense: 10, softmax
	Optimizers SAME
model9:
	final train: 1.0000 0.9914
	epoch1: 0.9472 0.9806
	epoch2: 0.9829 0.9866
	epoch3: 0.9886 0.9822
	epoch4: 0.9910 0.9882
	epoch5: 0.9928 0.9883
	#params
	Avg epoch time 9s ~ 10s
	model Arch:
		Conv2D: 32, each(3, 3), relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Conv2D: 32, each(5, 5), relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Dense: 32, relu
		Dense: 10, softmax
		Optimizers SAME
model10:
	final train: 1.0000 0.9881
	epoch1: 0.9282 0.9733
	epoch2: 0.9785 0.9754
	epoch3: 0.9852 0.9846
	epoch4: 0.9892 0.9847
	epoch5: 0.9928 0.9844
	#params
	Avg epoch time 9s ~ 10s
	model Arch: 
		Conv2D: 128, each(3, 3), relu
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Dense: 32, relu
		Dense: 10, softmax
	Optimizers: Same
model11:
	final train: 0.9992 0.9902
	epoch1: 0.9581 0.9838
	epoch2: 0.9843 0.9880
	epoch3: 0.9893 0.9864
	epoch4: 0.9916 0.9888
	epoch5: 0.9935 0.9899
 	#params
	Avg epoch time 9s ~ 10s
	model Arch SAME as Model9
	Optimizers Batch 16, ...Same
model12:
	final train: 0.9993 0.9897
	epoch1: 0.9231 0.9736
	epoch2: 0.9766 0.9814
	epoch3: 0.9835 0.9842
	epoch4: 0.9870 0.9861
	epoch5: 0.9887 0.9859
	#params
	Avg epoch time 9s ~ 10s
	model Arch Same as Model 9
	Optimizers Batch 64, ...SAME
model13:
	final train: 0.9990 0.9906
	epoch1: 0.9434 0.9766
	epoch2: 0.9820 0.9850
	epoch3: 0.9880 0.9846
	epoch4: 0.9911 0.9860
	epoch5: 0.9934 0.9882
	#params
	Avg epoch time 9s ~ 10s
	model Arch:
		Conv2D: 32, each(3, 3), tanh
	 	MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Conv2D: 32, each(3, 3), tanh
		MaxPooling2D: pool_size(2, 2), strides(2, 2)
		Dense: 64, tanh
		Dense: 32, tanh
		Dense: 10, softmax
	Optimizers: Same opt3
model14:
	final train: 
	epoch1: 0.9560 0.9771
	epoch2: 0.9835 0.9836
	epoch3: 0.9883 0.9876
	epoch4: 0.9911 0.9847
	epoch5: 0.9932 0.9879
	#params
	Avg epoch time 9s ~ 10s
	model Arch: Same as Model 13 but wit SELU
	Optimizers: Same opt3
model15:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model16:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model17:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model18:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model19:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model20:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model21:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
model22:
	final train: 
	epoch1: 
	epoch2:
	epoch3:
	epoch4:
	epoch5:
	#params
	Avg epoch time 9s ~ 10s
	model Arch
	Optimizers
