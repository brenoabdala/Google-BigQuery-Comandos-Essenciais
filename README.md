# Google BigQuery - Comandos essenciais para utilização diária

<p>Este repositórtio tem como objetivo, mostrar os comandos essencias para utilização diária do BigQuery.</p>
<p>O repositório está dando continuídade ao projeto do repositório (https://github.com/brenoabdala/Google-BigQuery-Configuracao-Inicial.git)</p>
<p><b>Acesse o portal:</b> https://console.cloud.google.com;</p>
<p>No menu lateral seleciona a opção <strong>BigQuery</strong>;</p>

<hr>

### Definição

<p>O BigQuery é uma plataforma de análise de dados totalmente gerenciada, escalável e sem servidor, oferecida pelo Google Cloud. Ela permite a análise de grandes volumes de dados em tempo real, utilizando SQL para consultas rápidas e eficientes. BigQuery é projetado para lidar com grandes conjuntos de dados, oferecendo alta performance e facilidade de uso, sem a necessidade de gerenciar a infraestrutura.</p>

<p>Principais características:</p>

- Escalabilidade automática: Processamento de grandes quantidades de dados sem a necessidade de ajustar recursos manualmente.
- SQL compatível: Facilita a integração com ferramentas e workflows já existentes.
- Análises em tempo real: Consultas rápidas mesmo em conjuntos de dados gigantescos.
- Armazenamento separado do processamento: Oferece flexibilidade e eficiência de custos.
 
<hr>

### COMANDO INSERT - Populando a tabela Clientes

<p>Arquivo anexado no repositório com a 100 registros de testes, a seguir vou deixar um exemplo:</p>

> INSERT INTO `github-449213.githubbasedeteste.clientes-teste` (id, NomeCompleto, Genero, telefone) VALUES
(1001, 'João Silva', 'Masculino', '11987654321')

### COMANDO SELECT - Consutando registros

> SELECT * FROM `github-449213.githubbasedeteste.clientes-teste`;<br>
> SELECT * FROM `github-449213.githubbasedeteste.clientes-teste` where Genero = 'Masculino';
