# intro-nvidia-rapid
This is a brief introduction to introduce nvidia rapid for machine learning of structured data using GPU rather than CPU




Learning:
Day 1. On small data GPU is slower when compared to sklearn lib. Maybe because of slower vram when compared to memory directly connected with the CPU.

Also Grid Search in CUML is broken and requires data in pandas dataframe instead of CuDF Dataframe unlike normal model training with cuML


Day 2.


Tried running the same operation with bigger data on GPU. Compile time: 1min 11 sec 

CPU Run Crashed for some reason after exceding the time done by GPU 

