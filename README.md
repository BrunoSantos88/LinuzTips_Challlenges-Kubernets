# LinuzTips_Challlenges-Kubernets

- Link https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/ </P>
  
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
  - choco install kubernetes-cli
  - curl.exe -LO "https://dl.k8s.io/release/v1.27.3/bin/windows/amd64/kubectl.exe" </p>
  - curl.exe -LO "https://dl.k8s.io/v1.27.3/bin/windows/amd64/kubectl.exe.sha256" </p>
- winget install minikube

# agente ativo dockerhub desktop ou virtual machine
minikube start --driver=docker --cpus=2 --memory=2000m --disk-size=20000mb --nodes=3
minikube start --driver=docker

# commando
minikube update-context
- Export /.kube/config

# commandos minikube

-   minikube start                   iniciar minikube
- --driver=docker                    Driver
- --cpus=4                           CPU
- --nodes 2 -p multinode-demo        Cluster capacidade
- --memory 4096                      memoria
- --disk-size 100gb                  Disco
- -kubernetes-version=v1.11.10       Versão

