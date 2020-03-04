# python\_and\_tensorflow
Le dépôt visant à se preparer au premier stage

[Python\_Software\_Foundation](https://www.python.org/)  
`python --version`  
`python3 --version`  

[Tutorial - Virtual Environments and Packages](https://docs.python.org/3/tutorial/venv.html)  

[Norme _P_ython _E_nhancement _P_roposal 8](https://www.python.org/dev/peps/pep-0008/)  
[_PY_thon _P_ackage _I_ndex - Flake8](https://pypi.org/project/flake8/)  

[TensorFlow](https://www.tensorflow.org/)  

## Choix d'un _I_ntegrated _D_evelopment _E_nvironment  
Prepa' Descartes Tours 2013-2015 : [Pyzo](https://pyzo.org/)  
Inside Linux N°15 Hors-Serie p.70 : [Spyder](https://www.spyder-ide.org/)  
Inside Linux N°15 Hors-Serie p.71 : [Jupyter](https://jupyter.org/)  

## Installation Anaconda  
[Download\_Page](https://www.anaconda.com/distribution/)  
[Installation\_Guide](https://docs.anaconda.com/anaconda/install/linux/)  
`anaconda-navigator`  

## _Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow_, de Aurelien Geron (edition O'REILLY)  
[Depot\_GitHub](https://github.com/ageron/handson-ml2)  

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

