# Facies_Classification

Facies is a body of a rock with specified characteristics, which can be any observable attribute of rocks (such as their overall appearance, composition or condition of formation),
and the changes that may occur in those attributes over a geographic area. It is the sum total characteristics of a rock including its chemical, physical, and biological features
that distinguishes it from adjacent rock. Facies classification refers to assigning a rock type or a class to specific rock examples on the basis of measured rock properties.
Classification of rocks is fundamental to geology and a variety of useful classification schemes may be employed, depending upon the circumstances. 

Rocks of the Council Grove Group fall into the large category of sedimentary rocks that, in this project, is subdivided intothe nine discrete facies (classes of rocks)as follows:

* Nonmarine sandstone ( SS )
* Nonmarine coarse siltstone ( CSiS )
* Nonmarine fine siltstone ( FSiS )
* Marine siltstone and shale ( SiSh )
* Mudstone (limestone) ( MS )
* Wackestone (limestone) ( WS )
* Dolomite ( D )
* Packstone-grainstone (limestone) ( PS )
* Phylloid-algal bafflestone (limestone) ( BS )

To classify a new rock as one of the above types, in this project I have built and trained an Artificial Neural Network which learns its weights from the features present in the
well log data set. Before the classification part, I have also visulaized the features present in the dataset using the seaborn library in python. The final results are visulaized
by plotting the log curves.

All the code is present in the jupyter notebook that you can see and probably modify to build a model that can perform the above task with much higher accuracy!
