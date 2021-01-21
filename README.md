# minikube-bare-metal-installation

![](https://img.shields.io/badge/python-3.8-lightgrey)

Script to install minikube along with kubectl on a linux machine. This installs the setup on bare-metal, not on a seprate VM.
This helps to install the kubectl controller and the minikube on the same machine.

In your linux terminal, to get the script
```
wget https://raw.githubusercontent.com/YashIndane/minikube-bare-metal-installation/main/minikube_k8s.py
```

To run

```
python3 minikube_k8s.py
```

On successfull run

![](images/v1.png)

alternative way to run -

```
bash setupmini.sh
```

To check status after setup run this -
```
minikube status
```





