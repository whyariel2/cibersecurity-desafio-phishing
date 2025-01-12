# Phishing para captura de senhas do Facebook (Desafio Original)

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![image](https://github.com/user-attachments/assets/d423f022-a7bf-46c6-ad70-e81594bf1e59)

# Phishing para captura de senhas do Facebook pelo Zphisher
### Por conta do setoolkit não estar pegando corretamente a senha na hora do phishing decidi usar o Zphisher

### Configurando o Zphisher no Kali Linux

- Clonando repositório do git: ```git clone --depth=1 https://github.com/htr-tech/zphisher.git```
- Acessando repositório na maquina: ```cd zphisher```
- Executando o Zphisher: ```./zphisher.sh```
- Selecionando Site a clonar: ```[01] Facebook```
- Tipo de página: ```[01] Traditional Login Page```
- Escolhendo onde hospedar site do phishing: ```[01] Localhost```

### Site clonado
![image](https://github.com/user-attachments/assets/b8e603a8-44bb-4430-a2ac-46361371b9bc)

### Resultados

![image](https://github.com/user-attachments/assets/e733a4ac-e54f-4c24-aae3-0c90a6e59bad)


