O projeto Hello World é uma tradição consagrada pelo tempo na programação de computadores. É um exercício simples que você começa quando aprende algo novo. Vamos começar com o GitHub!

Você aprenderá como:

Crie e use um repositório
Iniciar e gerenciar um novo ramo
Faça alterações em um arquivo e envie-as para o GitHub como commits
Abrir e mesclar um pedido pull

O que é o GitHub?
O GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Ele permite que você e outros trabalhem juntos em projetos de qualquer lugar.

Este tutorial ensina os fundamentos do GitHub, como repositórios, ramificações, commits, e solicitações de pull . Você criará seu próprio repositório Hello World e aprenderá o fluxo de trabalho de solicitação pull do GitHub, uma maneira popular de criar e revisar o código.

Nenhuma codificação necessária
Para concluir este tutorial, você precisa de uma conta do GitHub.com e acesso à Internet. Você não precisa saber como codificar, usar a linha de comando ou instalar o Git (o software de controle de versão do GitHub é construído).

Etapa 1. Crie um Repositório
Um repositório é geralmente usado para organizar um único projeto. Repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e conjuntos de dados - qualquer coisa que seu projeto precisar. Recomendamos incluir um README ou um arquivo com informações sobre seu projeto. O GitHub facilita a adição de um ao mesmo tempo em que você cria seu novo repositório. Ele também oferece outras opções comuns, como um arquivo de licença.

Seu hello-world repositório pode ser um lugar onde você armazena ideias, recursos ou até mesmo compartilha e discute coisas com outras pessoas.

Para criar um novo repositório

No canto superior direito, ao lado do seu avatar ou identicon, clique em +e selecione Novo repositório.
Nomeie seu repositório hello-world.
Escreva uma breve descrição.
Selecione Inicializar este repositório com um README.

Clique em Criar repositório

Etapa 2. Criar um Branch
A ramificação é a maneira de trabalhar em diferentes versões de um repositório de uma só vez.

Por padrão, seu repositório tem um ramo chamado master que é considerado o ramo definitivo. Usamos ramificações para experimentar e fazer edições antes de enviá-las master.

Quando você cria um ramo fora do master ramo, você está fazendo uma cópia,
ou instantâneo, master como era naquele momento. Se alguém fizesse
alterações no arquivo master enquanto você estava trabalhando no seu arquivo, você
poderia receber essas atualizações.

Este diagrama mostra:

O masterramo
Um novo ramo chamado feature(porque estamos fazendo 'recurso de trabalho' neste ramo)
A jornada que feature leva antes de ser mesclada com a master

Você já salvou versões diferentes de um arquivo? Algo como:

story.txt
story-joe-edit.txt
story-joe-edit-reviewed.txt
As filiais atingem objetivos semelhantes nos repositórios do GitHub.

Aqui no GitHub, nossos desenvolvedores, escritores e designers usam
ramificações para manter correções de bugs e trabalhos de recursos separados 
de nossa master ramificação (feature). Quando uma mudança está pronta,
eles mesclam sua ramificação com a master.

Para criar um novo ramo
Vá para o seu novo repositório hello-world.
Clique no menu suspenso no topo da lista de arquivos que diz branch: master .
Digite um nome de ramificação readme-edits na nova caixa de texto da ramificação.
Selecione a caixa azul Create branch ou pressione “Enter” no seu teclado.

Agora você tem dois ramos master e readme-edits. Eles parecem
exatamente o mesmo, mas não por muito tempo! Em seguida, adicionaremos
nossas alterações à nova ramificação.

Etapa 3. Fazer e Confirmar Mudanças
Bravo! Agora, você está na visualização de código da sua arquivo readme-edits,
que é uma cópia de master. Vamos fazer algumas edições.

No GitHub, as alterações salvas são chamadas de commit. Cada commit tem uma mensagem de commit associada, que é uma descrição explicando porque uma mudança em particular foi feita. As mensagens de confirmação
capturam o histórico de suas alterações, para que outros colaboradores possam
entender o que você fez e por quê.

Faça e confirme alterações
Clique no README.md arquivo.
Clique no  ícone de lápis no canto superior direito da visualização de arquivos para edição.
No editor, escreva um pouco sobre você.
Escreva uma mensagem de confirmação que descreva suas alterações.
Clique no botão Confirmar commit.

Etapa 4. Abrir uma Solicitação de Pull
Nice edits! Agora que você tem alterações em um ramo master, você pode abrir uma Requests pull.

Pull Requests é o coração da colaboração no GitHub. Quando você abre uma
solicitação de recebimento , está propondo suas alterações e solicitando que
alguém revise e inclua sua contribuição e as mescle em sua ramificação.
Pedidos pull mostram diffs , ou diferenças, do conteúdo de ambos os branches. 
As alterações, adições e subtrações são mostradas em verde e vermelho.

Assim que você fizer um commit, você pode abrir um pedido pull e iniciar uma discussão, antes mesmo de o código terminar.

Ao usar o sistema @mention do GitHub na sua mensagem de solicitação pull,você pode solicitar feedback de pessoas ou equipes específicas, estejam elas no final do corredor ou a 10 fusos horários de distância.

Você pode até mesmo abrir solicitações pull em seu próprio repositório e mesclá-las você mesmo. É uma ótima maneira de aprender o fluxo do GitHub antes de trabalhar em projetos maiores.

Abra uma solicitação pull para alterações no README

Clique no Na guia Pull Request, na página Pull Request, clique no botão verde New pull request.

Na caixa Exemplo de Comparações, selecione o ramo que você criou readme-edits, para comparar com mastero original.

Analise suas alterações nos diffs na página Compare, verifique se eles são o que você deseja enviar.

Quando estiver satisfeito com as mudanças que deseja enviar, clique no botão verde grande Pull Request.

Dê ao seu pedido de solicitação um título e escreva uma breve descrição de suas alterações.

Quando você terminar sua mensagem, clique em Criar Pull Request.

Etapa 5. Mesclar seu pedido pull
Nesta etapa final, é hora de unir suas alterações - mesclar sua readme-edits ramificação o arquivo master.

Clique no botão verde mesclagem de pull request para mesclar as alterações para a master.
Clique em Confirmar mesclagem .
Vá em frente e exclua a ramificação, já que suas alterações foram incorporadas, com o botão Excluir ramificação na caixa roxa.

Comemore!
Ao concluir este tutorial, você aprendeu a criar um projeto e fazer uma solicitação de pull no GitHub!
Veja o que você realizou neste tutorial:
Criado um repositório de código aberto
Iniciou e gerenciou um novo ramo
Alterou um arquivo e confirmou essas alterações no GitHub
Abriu e fundiu uma Pull Request
Dê uma olhada no seu perfil do GitHub e você verá seus novos quadrados de contribuição !

Para saber mais sobre o poder das Pull Request, recomendamos a leitura do guia de fluxo do GitHub . Você também pode visitar o GitHub Explore e se envolver em um projeto de código aberto
