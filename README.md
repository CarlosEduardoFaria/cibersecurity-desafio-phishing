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
<img src="./1_acesso_root.png" alt="1 - Acesso root">

- 2 - acesso a ferramenta setoolkit
<img src="./2_acesso_ferramenta_setoolkit.png" alt="2 - acesso a ferramenta setoolkit">

- 3 - Social-Engineering Attacks (Op-1)
<img src="./3_Social_Engineering_Attacks.png" alt="Social-Engineering Attacks">

- 4 - Web Site Attack Vectors (Op-2)
<img src="./4_Web_Site_Attack_Vectors.png" alt="Web Site Attack Vectors">

- 5 - Credential Harvester Attack Method (Op-3)
<img src="./5_Credential_Harvester_Attack_Method.png" alt="Credential Harvester Attack Method">

- 6 - Site Cloner (Op-2)
<img src="./6_Site_Cloner.png" alt="Site Cloner">

- 7 - Configuração Concluída
<img src="./7_Configuração_Concluída.png">

- 8.1 - Acesso a Pagina Fake
<img src="./8_1_Acesso_Pagina_Fake.png" alt="Acesso a Pagina Fake">

- 8.2 - Login da Pagina Fake
<img src="./8_2_Login_Pagina_Fake.png" alt="Login da Pagina Fake">

<i>Obs: Funciona tanto com http quanto para https, entretanto alguns sites possuem proteção contra o clone de sites.</i>