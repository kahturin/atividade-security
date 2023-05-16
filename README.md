I. Base de Código:

O VCS utilizado foi o próprio github, nele podemos navegar entre os commits e checar as fases do desenvolvimento desta aplicação, sendo temporal, é possível voltar a avançar em determinados estados de código, em qualquer dia e horário, desde de que tenha sido modificado e subido para este repositório. 

II. Dependências

Este projeto não possui dependencias (frameworks), foi feito em PHP na sua forma pura. 

III. Configurações

As configurações do banco de dados estão aplicadas no arquivo config.php, lá se encontra as informações do banco como usuario, senha, nome do banco... Como utilizei do localhost, as informações neste arquivo podem ser modificadas no seu localhost. 

IV. Serviços de Apoio

Um banco de dados mySQL para armazenar os dados e o Apache como servidor Web, para abrir a aplicação. No meu caso, eu baixei o xampp,
startei o Apache e o mySQL e movi a pasta deste projeto para a pasta htdocs do próprio XAMPP

V. Construa, lance, execute

Este serviço não possui processos de build, release e run. 

VI. Processos

Este serviço não possui este item. 

VII. Vínculo de porta

O Apache está rodando na porta 80
Enquanto o mySQL roda na porta 3306

VIII. Concorrência

Qualquer programa de computador, uma vez executado, está representado por um ou mais processos. No caso desta aplicação, por exemplo, processos PHP rodam como processos filhos do Apache, iniciados sob demanda conforme necessário por volume de requisições.

IX. Descartabilidade

Esta aplicação é o mais simples possível, dependendo apenas do sistema apache e do banco de dados, não é um processo longo de subida. 

X. Dev/prod semelhantes

esta aplicação não passou pelo processo de produção

XI. Logs

esta aplicação não contem logs salvos

XII. Processos de Admin

é possível executar migrações de base de dados no mysql, embora não seja necessário nesta aplicação e ver os scripts comitadoe no repositório do app
