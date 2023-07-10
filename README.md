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
- install cholatey </p>
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
  
- choco install minikube kubernetes-cli </p>
  - curl.exe -LO "https://dl.k8s.io/release/v1.27.3/bin/windows/amd64/kubectl.exe" </p>
  - curl.exe -LO "https://dl.k8s.io/v1.27.3/bin/windows/amd64/kubectl.exe.sha256" </p>
- winget install minikube

# agente ativo dockerhub desktop ou virtual machine
minikube start --driver=docker --cpus=2 --memory=2000m --disk-size=20000mb --nodes=3
minikube start --driver=docker

# commando
minikube update-context
- Export /.kube/config

