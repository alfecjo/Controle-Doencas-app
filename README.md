# ☕ Frameworks Web
![Angular](Angular.jpg)

## Este material foi desenvolvido em resposta a disciplina 'FrameWorks Web', a qual faz parte do curso de Pós Graduação em Tecnologia Java, ministrado pela Universidade Tecnológica Federal do Paraná.
🎉 Trata-se do projeto final, construido, utilizando a framework Angular 16, associado a linguagem TypeScript.

🥋 Se você está entrando no Angular agora, bem como TypeScript, vou deixar um comentário apenas para orientá-lo, caso considere o código desta entrega estranho. Existem todos os níveis de dificuldade, entretanto, por não se tratar do uso do padrão para gerenciamento de estados Redux, para ser mais específico, o qual, dentro do Angular recebe o nome @ngrx, os níveis de dificuldade são menores, levando em consideração que a curva de aprendizado para a programação convencional é razoavelmente inferior.

Por esta razão, a dificuldade apresentada no projeto pelo professor e os demais colegas, foi considerada MEDIANA. Foram tratados assuntos como componentes, serviços, roteamento, e manipulação de formulários. Durante o desenvolvimento, aprendi a estruturar um projeto Angular de forma organizada, utilizando módulos para separar funcionalidades e garantir uma arquitetura escalável. Também explorei a poderosa linguagem TypeScript, que adiciona tipagem estática ao JavaScript, trazendo mais segurança ao desenvolvimento.

Caso não entenda de primeira, continue tentando, pois, o sucesso não só reside nos melhores, mas também, nos persistentes, que considero meu caso (_😎tirei nota máxima). Desenvolver software, nada mais é que descartar a possibilidade de desistência, independente de qualquer motivo!

## Deve-se utilizar:

   - O Angular CLI versão 16.0.0 ou superior;
   - Versão específica do TypeScript compatível com a versão do Angular CLI utilizada;
   - Mínimo Angular 16 para garantir compatibilidade;
   - Utilização das versões recomendadas para as principais dependências, conforme especificado no arquivo package.json;
   - Requisitos específicos para Node.js, seguindo as diretrizes do Angular CLI;
   - Outras dependências e bibliotecas conforme necessário para o projeto.

Certifique-se de consultar a documentação oficial do Angular para obter informações detalhadas sobre requisitos e configurações específicas para a versão desejada.

## 🔍 Projeto

### 👨‍💻 Framework Angular - Linguagem TypeScript

- A avaliação da disciplina se dará pela entrega de um projeto de uma aplicação web desenvolvido com o uso do framework Angular, sendo que o tema e o escopo do projeto deverá ser definido pelo aluno logo no início da disciplina. A aplicação deve ser desenvolvida progressivamente durante a disciplina, ou seja, à medida em que o aluno vai estudando o conteúdo semanal. É uma forma de praticar o conteúdo estudado e transformar em aprendizado. As atividades semanais (com entregas que valem nota) estão em sua maioria relacionadas ao projeto. - Desta forma, se o aluno realizar progressivamente as atividades, no final da disciplina, espera-se que ele tenha o projeto concluído para apresentar como produto para a avaliação. No entanto, nas atividades semanais não serão cobradas funcionalidades funcionais e completas, mas apenas o uso mínimo de algumas características do framework. Certamente, o projeto final a ser apresentado como avaliação conterá múltiplos usos destas características e aprofundamentos destes, resultado da motivação do aluno em satisfazer o escopo do projeto proposto.

O projeto para ser contemplado com a nota máxima precisa conter implementado pelo menos a totalidade de uma lista de tópicos pré-definida pelo Professor e ser funcional, ou seja, satisfazer o escopo proposto no início da disciplina. Esta lista de itens está organizada em forma de checklist para melhor orientar o aluno no processo de desenvolvimento do projeto e também para dar uma maior exatidão no cálculo da nota da avaliação. Mas vale salientar que, se o aluno preencher um item e for comprovado que ele não fez ou não sabe explicar, será penalizado com a retirada de nota deste e de outro item feito.

### ⏰ Etapas

  - Definir o tema e escopo do projeto na Atividade 03 (os temas escolhidos podem ser vistos na planilha (somente leitura)).
  - Criar o repositório no GitHub conforme a estrutura de branches do Gitflow.
  - Editar o Readme.md com o checklist de tópicos.
  - Projetar os protótipos das telas e incluir o link no Readme.md
  - Realizar as atividades semanais, tentando tratar como entregas parciais do projeto.
  - Fazer o deploy da aplicação no GitHub Pages e incluir o link no Readme.md
  - Entregar o projeto final.
  - Gravar um vídeo (entrega do link) ou fazer um relatório textual (entrega em PDF) apresentando o projeto desenvolvido de acordo com o checklist.
(o vídeo encontra-se no link YouTube)
    
## 🔚 Projeto Final:

### 👨‍💻 O projeto a ser entregue aqui contempla o que já foi pedido anteriormente nas Entregas Parciais de 1 a 5, além de incluir a persistência dos dados utilizando o Room e o uso de AlertDialogs para exibir mensagens ao usuário.

- Crie um aplicativo que atenda as seguintes funcionalidades:

   - Especifique o tema que trata a aplicação. Este tema deverá ter sido lançado pelo aluno no questionário "Tema do Projeto", e o mesmo precisa ser aprovado previamente pelo professor.    - Não serão aceitos temas repetidos dentro da turma.
   - Cadastre dados lançados pelo usuário, que tenham relação com a regra de negócio proposta para a aplicação (Nesta versão os dados serão persistidos no SQLite através do uso do Room);
   - Crie pelo menos uma Classe de Entidade a ser manipulada dentro da aplicação;
   - Crie pelo menos uma Activity que permita a manipulação dos dados (Inserção, Alteração e Remoção);
   - Exiba um AlertDialog para confirmar a ação do usuário antes de excluir dados persistidos; 
   - Crie pelo menos uma Activity que liste os itens cadastrados no banco de dados;
   - Utilize pelo menos um Adapter Customizado em uma Activity que liste os itens;
   - Crie uma Activity onde mostra-se as informações sobre o que faz o aplicativo, e os dados da autoria dele;
   - Utilize Menus de Opções, onde as ações aparecem com ícones na barra de ação da Activity;
   - Utilize Menu de Ação Contextual, onde as ações aparecem com ícones na barra de ação da Activity;
   - Utilize botões Up na barra de ações das Activities secundárias, para facilitar a volta do usuário destas para as Activities especificadas como pais destas;
   - Forneça alguma possibilidade de configuração ou personalização do aplicativo, e persista estas informações usando SharedPreferences; 
   - O Aplicativo deve suportar dois idiomas, o inglês como padrão e o português Brasileiro como opcional.

 ### 👷 Integrantes:
  - O projeto deverá ser desenvolvido individualmente.

### 💎 Tema:
  - O tema precisa ser único dentre os alunos da turma;
  - O tema só será válido após o aceite do Professor;
  - Os temas já escolhidos e aprovados pelo Professor podem ser vistos na planilha.
  - A aplicação é para uso pessoal, não corporativo, e não deve prever comunicação com outros softwares ou perfis de contas de usuários;
  - A sugestão é que o tema apresente um escopo simples e comum a maioria das aplicações, devendo conter pelo menos o cadastro de uma ou mais entidades e listagem de dados destas entidades. 

### 📑 Exigências Gerais:

  - O projeto precisa ser armazenado no repositório do GitHub ou similar e o endereço do repositório ser informado ao professor.
  - O checklist com os itens implementados deve constar no README.md do repositório do projeto.
  - O projeto precisa ser hospedado do GitHub Pages ou similar e o endereço de acesso deve ser informado no README.md
  - O sistema deve ser implementado contendo as funcionalidades referentes aos tópicos apresentados a seguir. Também serão consideradas as boas práticas de programação em JavaScript/TypeScript, uso adequado de notações e conceitos aprendidos. Ainda, serão avaliados os wireframes/protótipos do sistema.
  - A estrutura de checklist pode ser copiado do projeto roubank no GitHub disponível no seguinte endereço: https://github.com/utfpr-gp/roubank-app 

🕵️ Critérios de aceite e avaliação:
### 👁️‍🗨️ Tópicos/Checklist

  - Criar o repositório no GitHub com a estrutura do Gitflow, ou seja, branches main e develop.
  - Usar componentes de algum framework CSS (Bootstrap, Materialize ou outro).
  - Apresentar as telas com layout responsivo usando ou não algum framework CSS.
  - Construir páginas web com o conceito de componentes. 
  - Criar o layout da aplicação com componentes, ou seja, o cabeçalho e rodapé precisam ser componentes.
  - Usar pelo menos dois tipos de data-binding (Interpolation, Property Binding, Event Binding e Two Way Data Binding).
  - Passar dados via hierarquia de componentes, ou seja, usando @Input ou @Output.
  - Mapear componentes à rotas no módulo de rotas.
  - Criar navegação entre páginas por meio de rotas.
  - Passar dados entre componentes que representam diferentes telas via parâmetros de rotas. 
  - Validar campos do formulário com REGEX e apresentar os erros.
  - Desabilitar o botão de submit enquanto o formulário está inválido.
  - Fazer requisições a API com tratamento da resposta com Promises ou Observables.
  - Cadastrar uma entidade usando uma API (JSON Server).
  - Apresentar uma lista de dados com a diretiva estrutural ngFor.
  - Usar a diretiva ngIf
  - Formatar a apresentação de dados com Pipes.
  - Build e deploy da aplicação.

🎯 Importante:

   - Nos dias de entrega do Projeto Final, caso seja necessário, o professor poderá conversar com cada aluno para que o mesmo apresente o aplicativo criado, explique o código, e tire dúvidas sobre o desenvolvimento de cada funcionalidade.

   - Caso o aluno não saiba apresentar o projeto, o mesma poderá ser recusado e ter a nota zerada.

   - Caso o projeto não compile o mesmo terá a nota zerada.

   - Caso o projeto entregue seja o projeto de outro (como um exemplo passado pelo professor) que foi alterado para atender os requisitos pedidos, o mesmo terá a nota zerada. O aluno pode utilizar os códigos passados na disciplina porém deve criar um projeto novo, e reescrever e não apenas colar o código que irá aproveitar.

# Tecnologia utilizada:

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Java Android](https://img.shields.io/badge/java%20android-%3DDC84.svg?style=for-the-badge&logo=android&logoColor=white)

## Tabela de Conteúdos

- [Instalação](#Instalação)
- [Uso](#Uso)
- [Contribuição](#Contribuição)

## Instalação

1. Clone o repositório ou baixe o arquivo .zip:

```bash
git clone https://github.com/alfecjo/android.git
```
## Uso

1. Execute em sua IDE de preferência. Contudo, o desenvolvimento foi feito no Android Studio! Respeite as orientações de versões, pois arquitetura Android leva muito a sério este assunto, MUITO A SÉRIO (sessão: Deve-se utilizar: acima)!!!

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, abra um problema ou envie uma solicitação pull ao repositório.

Ao contribuir para este projeto, siga o estilo de código existente, [convenções de commit](https://www.conventionalcommits.org/en/v1.0.0/), e envie suas alterações em um branch separado.

Muito obrigado!!





## controle-doencas-app

### Este projeto tem como objetivo implementar requisitos impostos pela disciplína Frameworks a título de avaliação. Trata-se de uma aplicação web que possibilita rastrear comunidades afetadas por doenças infectocontagiosas. (ex: cadastro, alteração, deleção, listagem), sendo o diferencial, a facilidade de uso e operação pelo cliente;

### O frontend da aplicação foi desenvolvido com Angular e o backend foi simulado pela implementação de uma API Fake, usando o JSON Server;

### Endereço de Deploy - GitHub Pages
(https://alfecjo.github.io/controle-doencas-app/cadastro)

### Protótipo
(<https://www.figma.com/file/Ic3EmqlxEY73UzVz18HHWG/controleDoencas?type=design&node-id=7%3A14&t=CIo2pmdvdcptwzRV-1>)

### Vídeo de Apresentação do Projeto
(<https://youtu.be/45DLJ_OVJCg>)

### Checklist

- [x]Criar o repositório no GitHub com a estrutura do Gitflow, ou seja, branches main e develop.
- [x]Usar componentes de algum framework CSS (Bootstrap, Materialize ou outro)
- [x]Apresentar as telas com layout responsivo usando ou não algum framework CSS.
- [x]Construir páginas web com o conceito de componentes.
- [x]Criar o layout da aplicação com componentes, ou seja, o cabeçalho e rodapé precisam ser componentes.
- [x]Usar pelo menos dois tipos de data-binding (Interpolation, Property Binding, Event Binding e Two Way Data Binding).
- [x]Passar dados via hierarquia de componentes, ou seja, usando @Input ou @Output.
- [x]Mapear componentes à rotas no módulo de rotas.
- [x]Criar navegação entre páginas por meio de rotas.
- [x]Passar dados entre componentes que representam diferentes telas via parâmetros de rotas.
- [x]Validar campos do formulário com REGEX e apresentar os erros.
- [x]Desabilitar o botão de submit enquanto o formulário está inválido.
- [x]Fazer requisições a API com tratamento da resposta com Promises ou Observables.
- [x]Cadastrar uma entidade no JSON Server.
- [x]Apresentar uma lista de dados com a diretiva estrutural ngFor.
- [x]Usar a diretiva ngIf
- [x]Formatar a apresentação de dados com Pipes.
- [x]Build e deploy da aplicação.

### Manual de execução

- Clonar o repositório com git clone;
- Fazer checkout no branch develop que contém as modificações mais recentes;
- Abrir o projeto no editor Visual Studio Code (VS Code);
- Através do terminal cmd-VSCode ou do seu Sistema Operacional apontando para o diretório raiz do projeto;
- Instalar as dependências contidas no package.json
  Comando: npm i;
- (Opcional) Instalar o JSON Server globalmente disponível em https://www.npmjs.com/package/json-server
  Comando: npm i -g json-server
  É opcional porque a dependência já vêm cadastrada no arquivo package.json;
- Executar a API Fake (JSON Server) com o seguinte comando:
  Via Execução explícita: json-server --watch db.json
  O comando para execução do JSON Server deve ser aplicado no diretório /dados, ou seja, que contém o arquivo db.json
  Por padrão, a aplicação JSON Server executa no endereço localhost:3000;
- Abrir um novo terminal cmd-VSCode e então executar o projeto Angular
  Comando: ng s -o;
