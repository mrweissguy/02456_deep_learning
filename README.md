# 02456 Deep Learning final project
### *Controlled generation of proteins using conditionalcharacter-level rnn* 
**Project: 6, Bioinformatics - Can be generate specific proteins?**

This repository contains code for the 02456 deep learning F19 final report.

It contains:
* datasets used for experiments in the report.
	* PennTreeBank charcter and word level datasets
* jupyter notebooks 
	* network and results from traning on PTB using DropConnect.
	* network and results from traning on protein data using a conditional model to generate proteins.


Weights for the models can be downloaded [here](https://drive.google.com/open?id=19vBZTCBuMbjjYgclTQPA_jlOcTKXK0e5).


### Prerequisites

The notebooks is created using python 3.7. To run the code in jupyter notebooks, be sure to install [Anaconda](https://www.anaconda.com/distribution/) or run it in [google colab](https://colab.research.google.com/).

To run the notebooks install the libraries listed below:

* pytorch


The installation process is straight forward.

```
pip install torch
```


To recreate the results from the report, please look at each individual notebooks. As default, they are set to continue training on the weights in the nets folder.

To simply load the results and see the train/valid error during training, run the load function in the notebook. The correct model with the correct parameters will needed to be instantiated before it can be run. 

<!-- ### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo -->

<!-- ## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
``` -->

<!-- ### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system -->

## Built With

* [Pytorch](https://www.tensorflow.org) - Deep Learning platform

<!-- ## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).  -->

## Authors
* **Aleksander Frese** - *Grakn and politician dataset (dataset 4)*
* **Johan Weiss** - *Neural Graph Learning (dataset 1-3)*

<!-- See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project. -->

<!-- ## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details -->

## Acknowledgments

* Professor: Ole Winther
* Teaching Assistant: Alexander R. Johansen

* Project proposer: Jose Juan Almagro Armenteros

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.



