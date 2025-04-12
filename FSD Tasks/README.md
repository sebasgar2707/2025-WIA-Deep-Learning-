
# TUD WIA Seminar - Deep Learning, Neural Networks and Applications 

# in cooperation with FSD GmbH


## FSD Fahrzeugsystemdaten GmbH

FSD Fahrzeugsystemdaten GmbH serves as the Central Authority according to the German Road Traffic Act (StVG) and is responsible for the advancement of the general vehicle inspection (HU), the development of innovative inspection technologies required for this process, including vehicle-specific parameters, as well as for creating decision-making foundations for the homologation of new vehicles.

The braking system plays a crucial role in vehicle safety. As part of the general inspection under §29 StVZO, the inspection of the braking system is a key component. In doing so, the procedures and conditions outlined in the HU brake directive must be applied to detect potential defects and ensure both vehicle and traffic safety.

To this end, FSD GmbH has developed a procedure that uses a three-axis acceleration and gyroscope sensor to record longitudinal, lateral, and vertical acceleration (ax, ay, az) and roll, pitch, and yaw rates (dx, dy, dz) at a sampling rate of 100 Hz. This data is used to analyze the braking behavior of a vehicle during a dynamic test drive.

Based on the recorded time series of accelerations and angular velocities, a neural network is trained. This network is then generalized and used to predict, based on the measured braking data of unknown vehicles, whether their braking systems are functioning properly or show signs of defect.

---


Further information and the tasks will be added here soon.


#### ... about the final event:

* The final event will take place on **Monday, June 23, starting at 9:00 AM in Dresden at Wintergartenstraße 4**.  
  Initially, you will have the opportunity to present your results at our headquarters. Afterwards, a transfer to our second location in Radeberg (Carl-Eschebach-Straße 2) is organized, where the awards ceremony will take place following a light lunch. In Radeberg, a guided tour in station format will be held, including presentations and live demonstrations in our testing lab. Around 5:00 PM there will be a barbecue, and the return transfer to Dresden is scheduled for 6:00 PM.

* Please remember to push your final report and code to this repository by **June 18 at 12pm**, as described above, so that I have enough time to review your work before the final presentation.

* Each group will have a 30-minute slot for their final presentation. Please plan your talk so that the presentation lasts no more than 20 minutes, leaving 10 minutes for questions.

## Literature

#### CNN: 
[LeCun](http://yann.lecun.com/exdb/publis/pdf/lecun-99.pdf)  
[CNNs - towards science blogpost](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53)  
[CNNs for visual recognition](https://cs231n.github.io/convolutional-networks/)

#### LSTM: 
[Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

#### XAI
[Shap](https://github.com/slundberg/shap)  
[Lime Paper](https://arxiv.org/pdf/1602.04938.pdf)  
[Lime GitHub](https://github.com/marcotcr/lime)  
[Lime Example](https://github.com/marcotcr/lime/blob/master/doc/notebooks/Tutorial%20-%20Image%20Classification%20Keras.ipynb)

#### Uncovering and Mitigating Algorithmic Bias through Learned Latent Structure  
[Debiasing Facial Bias](http://introtodeeplearning.com/AAAI_MitigatingAlgorithmicBias.pdf)

#### Wavelets  
[Wavelet Transformation](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf)  
[PyWavelets - Wavelet Transforms in Python](https://pywavelets.readthedocs.io/en/latest/)  
[Wavelet Browser](http://wavelets.pybytes.com/)  
[Wavelet Transformation in Machine Learning](https://ataspinar.com/2018/12/21/a-guide-for-using-the-wavelet-transform-in-machine-learning/)

#### GitHub  
[Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)  
[S. Chacon, B. Straub - Pro Git](https://git-scm.com/book/de/v2)

#### Clean Coding  
[PEP 8 Style Guide for Python Code](https://peps.python.org/pep-0008/#code-lay-out)