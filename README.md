# Phishing para captura de senhas do Facebook
Modificado - Michelle Vilela

### Ferramentas usadas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ``` e a senha do seu kali
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ``` 1
- Vetor de ataque: ``` Web Site Attack Vectors ```  2
- Método de ataque: ```Credential Harvester Attack Method ```  3
- Método de ataque: ``` Site Cloner ```  2
- Cole a URL do site que voce quer clonar, no nosso caso coloquei a url ``` http://www.facebook.com ``` e apertei enter
- O programa clonou a pagina do facebook e entregou um link, após isso colocamos o login e senha e o site te redireciona para o site oficial do facebook
- Obtendo o endereço da máquina: ``` ifconfig ```

### Resutados

![Alt text](./passwd.png "Optional title")
