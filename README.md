# IAC-Docker
essa é uma IAC(infrastructure as code) de um deploy de docker em uma maquina remota utilizando ansible, atualmente esse deploy só serve para maquinas ubuntu/debian. O Docker é uma plataforma de código aberto que facilita a criação, o gerenciamento e a execução de aplicações em contêineres. Um contêiner é um ambiente isolado que contém tudo o que uma aplicação precisa para rodar, incluindo bibliotecas, dependências e o próprio código. Isso garante que a aplicação funcione de forma consistente, independentemente do ambiente em que está sendo executada.

Pré-requisitos:

1. Python3 ou versões posteriores;
2. Componente PIP;

Para usar esta IaC, siga os passos abaixo:

1. Crie um ambiente virtual na sua máquina:

```bash
python3 -m venv <seu_ambiente_virtual>
source <seu_ambiente_virtual>/bin/activate
```

2. Instale as bibliotecas:
```bash
pip install -r requirements.txt
```
3. Agora, execute a automação:
```
ansible-playbook IAC-docker.yml -K --ask-become-pass
