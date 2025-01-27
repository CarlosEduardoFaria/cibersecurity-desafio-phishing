# Phishing para captura de senhas de páginas de login

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
- URL exemplo para clone: https://www.instagram.com

### Passo a passo:

- 1 - Acesso root
<img src="./1 - acesso root.png" alt="1 - Acesso root">

- 2 - acesso a ferramenta setoolkit
<img src="./2 - acesso a ferramenta setoolkit.png" alt="2 - acesso a ferramenta setoolkit">

- 3 - Social-Engineering Attacks (Op-1)
<img src="./3 - (Tipo) Social-Engineering Attacks (Op-1).png" alt="Social-Engineering Attacks">

- 4 - Web Site Attack Vectors (Op-2)
<img src="./4 - (Vetor) Web Site Attack Vectors (Op-2).png" alt="Web Site Attack Vectors">

- 5 - Credential Harvester Attack Method (Op-3)
<img src="./5 - (Metodo) Credential Harvester Attack Method (Op-3).png" alt="Credential Harvester Attack Method">

- 6 - Site Cloner (Op-2)
<img src="./6 - (Metodo) Site Cloner (Op-2).png" alt="Site Cloner">

- 7 - Configuração Concluída
<img src="./7 - Configuração Concluída.png" alt="Configuração Concluída">

- 8.1 - Acesso a Pagina Fake
<img src="./8.1 - Acesso a Pagina Fake.png" alt="Acesso a Pagina Fake">

- 8.2 - Login da Pagina Fake
<img src="./8.2 - Acesso a Pagina Fake.png" alt="Login da Pagina Fake">

<i>Obs: Funciona tanto com http quanto para https, entretanto alguns sites possuem proteção contra o clone de sites.</i>