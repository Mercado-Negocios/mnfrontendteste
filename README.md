# Implementação do Layout - Teste Desenvolvedor FrontEnd
O teste consiste na implementação de um exemplo de **case** para sites exclusívos, onde o desenvolvedor receberá o layout de uma determinada tela e deverá implementa-lá.

## 1 - Requisito: Desenvolvimento tela da home
O layout consiste basicamente na home de um site, responsiva e adaptável para mobile.

Todas as imagens e PDS's do layout estão disponibilizados no repositório do projeto, na pasta [layout arquivos](https://github.com/Mercado-Negocios/mnfrontendteste/tree/master/layout_arquivos).

Todas as informações podem ser implementadas de forma estática, os selects (usar JS ou AngularJS para fazer as opções dos selects), as thumbs (usar JS ou AngularJS para repetir as thumbs no numero de vezes solicitado pelo layout, não copiar o e colar a thumb) e demais informações de página. Disponibilizamos a imagem [instrucoes layout](https://github.com/Mercado-Negocios/mnfrontendteste/blob/master/layout_arquivos/instrucoes-layout.jpg) que contem dicas caso o framework utilizado para desenvolver a página seja AngularJS 1.6.

Os efeitos de `hover` que não estiverem presentes na página (botão presente na thumb, por exemplo) fica a critério do desenvolvedor, poder mostrar sua criatividade.

**É de suma importância se atentar ao responsivo da página e se possível, chegar até o layout mobile**

## 2 - Requisito: Desenvolvimento da overlay de login
O texto com a palavra `login` estará posicionado no lugar de "Olá Vitor Caponi | SAIR", presente no canto superior direito do layout.
 - Clicou em login, abrirá uma overlay com os campos de `usuario` e `senha`, além de um botão com `esqueci minha senha` e `entrar`. Ao preencher os campos de usuário e senha e clicar em `entrar` a overlay deverá ser fechada e o texto inicial `login` deverá ficar no botão que está no layout "Olá Vitor Caponi | Sair". O botão de `sair` deverá voltar para o texto `login`.

Não será fornecido um layout para esta overlay, estando o desenvolvedor livre para mostrar sua criatividade e conhecimentos.

## Informações importantes

### Regras
- Você tem 24h para realizar o teste, assim que receber o email com o teste e fizer o **fork** do projeto;
- Faça o fork do projeto em seu GitHub, desenvolva, commita e de push;
- Ao finalizar o teste, envie para o email que recebeu o teste um email com o link do seu github contendo o fork do projeto;
- Em último caso, se não conseguir utilizar o git você pode enviar um .zip com o projeto.

### Essencial
- HTML5 Semantico e focado em SEO (se possível);
- Uso de CSS3 e seus recursos;
- JavaSript seguindo boas práticas.

### Ganha pontos extras
- Estruturar HTML com frameworks como BootStrap (versão 3 ou 4) e materializecss;
- A pagína deve ser responsiva;
- Utilizar SASS;
- Desenvolver a parte de JS com AngularJS 1.6;
- Utilizar Gulp para minificar e tratar arquivos (html, css, imagens, etc...). É possível utilizar o gulp para fazer cross-browser também;
- Gerar pasta com o projeto buildado e tratado pelo Gulp.

### Dicas
- A framework de JS escolhida fica a critério do desenvolvedor. Pode utlizar jquery, angular 2+ ou oq for mais confortável, porém, se fizer com AngularJS 1.6 terá pontos extras, já que o mesmo é utilizado no dia a dia aqui na Mercado de Negócios;
- O uso de bibliotecas feitas com jquery/angular (entre outros) é permitida;
- Não se preocupe em realizar todas as requisições. Tenha senso de priporidade e faça o que conseguir. O importante é tentar;
- O login pode ser feito de forma simulada, usando variáveis para controle e exibição (abrir e fechar o login, mostrar o nome do usuário logado);
- O teste não exige nenhum desenvolvimento de backEnd.
