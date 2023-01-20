# LinuzTips_Challlenges-Kubernets
Desafio 1
- Executar o minikube 3 nó.
- prestar atençao. so vai com  --force no final do commando.
- Instalar dependencias Kubectl, minikube etc

-Após isso, criar giropops.yaml --- touch giropops.yaml
 -- kubectl apply -f giropops.yaml
 
- Terminado desafio.

* Lembrando não da para cria .sh e executar, tem que executar os commando linha por linha.

* Link semana 1 https://github.com/BrunoSantos88/LinuxTipsCertifiedContainersExpert


#minikube Windows
choco install minikube kubernetes-cli
winget install minikube

#agente ativo dockerhub desktop ou virtual machine
minikube start --driver=docker --cpus=2 --memory=2000m --disk-size=20000mb --nodes=3
minikube start --driver=virtualbox
