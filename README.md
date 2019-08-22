# python\_and\_tensorflow
Le dépôt visant à se preparer au premier stage

[Python\_Software\_Foundation](https://www.python.org/)  
`python --version`  
`python3 --version`  

[TensorFlow](https://www.tensorflow.org/)  

## Choix d'un __I__ntegrated __D__evelopment __E__nvironment  
Prepa' Descartes Tours 2013-2015 : [Pyzo](https://pyzo.org/)  
Inside Linux N°15 Hors-Serie p.70 : [Spyder](https://www.spyder-ide.org/)  
Inside Linux N°15 Hors-Serie p.71 : [Jupyter](https://jupyter.org/)  

## Installation Anaconda  
[Download\_Page](https://www.anaconda.com/distribution/)  
[Installation\_Guide](https://docs.anaconda.com/anaconda/install/linux/)  
`anaconda-navigator`  

## _Deep Learning Cookbook_, de Douwe Osinga (edition O'REILLY)  
[Depot\_GitHub](https://github.com/DOsinga/deep_learning_cookbook)  

```
	git clone https://github.com/DOsinga/deep_learning_cookbook.git
	cd deep_learning_cookbook
	python3 -m venv venv3
	source venv3/bin/activate
	pip install -r requirements.txt
	pip uninstall tensorflow
	pip install tensorflow-gpu
	jupyter notebook
	git checkout <notebook_to_reset> ipynb
```

