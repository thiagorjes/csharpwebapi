# csharpweapi

Exemplos: [csharpwebapi-examples](https://github.com/thiagorjes/csharpwebapi-examples)

Snippet criado para ser usado com webapi facilitando a criacao de m&eacute;todos vazios, m&eacute;todos para repositorios, m&eacute;todos para controladores de servico e classe controladora de servico. A id&eacute;ia &eacute; utilizar o padr&atilde;o de desenvolvimento que consiste em Controller, Repository, Model/DBContext para criar um webservice rest json.

**Uso:**

-  Crie as pastas Models, Interfaces, Controllers e Services
-  crie os modelos como preferir (sugest&atilde;o: scaffold! sempre)
-  Dentro da Pasta Interfaces crie o arquivo IGenericRepository.cs.
-  Abra o arquivo IGenericRepository.cs e digite RepoInterface e tecle enter.
-  O conte&uacute;do do arquivo de Interface ser&aacute; criado.
-  Dentro da Pasta Services crie o arquivo EntidadeRepository.cs, onde Entidade se refere ao nome da classe existente em Models. 
-  Abra o arquivo EntidadeRepository.cs e digite RepoClass e tecle enter.
-  O conte&uacute;do do arquivo de Repositorio ser&aacute; criado.
-  Dentro da Pasta Controllers crie o arquivo EntidadeController.cs.
-  Abra o arquivo EntidadeController.cs e digite CtrlClass e tecle enter.
-  O conte&uacute;do do arquivo de Controller ser&aacute; criado.
- A estrutura final deve ser algo do tipo:

**Projeto:**

      |_Controllers:
      |     |_EntidadeController.cs
      |_Interfaces:
      |     |_IGenericRepository.cs
      |_Services:
      |     |_EntidadeRepository.cs
      |_Models:
      |     |_ProjetoContext.cs
      |     |_Entidade.cs
      |_Demais arquivos.


**Para auxiliar na utilização do snippet, faça o download dos exemplos em:**
     [csharpwebapi-examples](https://github.com/thiagorjes/csharpwebapi-examples)

Outros Snippets existem, mas ser&atilde;o descontinuados.

Agradecimentos especiais à comunidade #WindowsInsiderBrasil (agora no Discord)
e à equipe do Microsoft Virtual Academy.

feedback: thiagorjes@outlook.com/thiagorjes@gmail.com  (assunto:csharpwebapi)

