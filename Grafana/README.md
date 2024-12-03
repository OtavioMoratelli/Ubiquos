Configuração:<br/>
Após a instalação, o grafana estará acessível no endereço http://localhost:3000. Por padrão, o Grafana usa a porta 3000, mas isso pode ser alterado no arquivo de configuração grafana.ini, localizado no local de instalação do Grafana.<br/>
Ao entrar pela primeira vez, será necessário um login e uma senha. Por padrão, o usuário é 'admin' e a senha também é 'admin'. Após o login, será necessário configurar uma nova senha.

Agora, após fazer o login e acessar o Grafana, devemos adicionar uma nova conexão entre o Grafana e o banco de dados desejado, que pode estar instalado localmente ou na web. O Grafana suporta múltiplas conexões simultâneas, permitindo gerar gráficos com dados de diferentes bancos de dados.
<br/>
![image](https://github.com/user-attachments/assets/596050fc-ddfd-43ec-9fe9-5763c0c52fee)
<br/>
<br/>

Aqui, podemos ver sugestões de bancos de dados e procurar por um específico, como, por exemplo, o PostgreSQL.<br/>
![image](https://github.com/user-attachments/assets/54bd2a3e-5130-4422-9efc-eab6428b0641)
<br/>
<br/>

Após selecionar o banco de dados desejado, podemos configurar um nome para identificar essa conexão no Grafana, a URL de conexão do banco, o nome do banco e o usuário e senha com acesso ao banco. É recomendado que o usuário do banco de dados tenha apenas acesso de leitura aos dados, por questões de segurança, mas isso não é obrigatório.
<br/>
No caso do PostgreSQL, por padrão, ele usa a porta local 5432. Os demais valores de configuração podem ser deixados como estão.
![image](https://github.com/user-attachments/assets/7edcc128-163f-4fe0-8ac9-25e7728175c8)
<br/>
<br/>
Agora que o Grafana está conectado ao banco de dados, podemos criar diversos gráficos usando os dados presentes nele, além de aproveitar os diversos plugins disponíveis para expandir as possibilidades de aplicação do Grafana.

