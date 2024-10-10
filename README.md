# 👋 Os fundamentos do GitHub

## 🤓 Visão geral do curso e resultados de aprendizado

O objetivo deste curso é dar a você uma breve introdução ao GitHub. Também forneceremos materiais para aprendizado adicional e algumas ideias para você começar na nossa plataforma. 🚀

## :octocat: Git e GitHub

Git é um **sistema de controle de versão distribuído (VCS)**, o que significa que é uma ferramenta útil para rastrear facilmente as mudanças no seu código, colaborar e compartilhar. Com o Git, você pode acompanhar as alterações feitas no seu projeto, sempre tendo um registro do que foi feito e revertendo facilmente para uma versão anterior, se necessário. Isso também facilita o trabalho em equipe—várias pessoas podem colaborar no mesmo projeto e mesclar suas alterações em uma fonte final!

O GitHub é uma forma de usar o mesmo poder do Git totalmente online, com uma interface fácil de usar. Ele é amplamente utilizado no mundo do software e além, para colaborar e manter o histórico de projetos.

O GitHub é o lar de algumas das tecnologias mais avançadas do mundo. Quer você esteja visualizando dados ou criando um novo jogo, há uma comunidade e um conjunto de ferramentas no GitHub que podem ajudá-lo a avançar para o próximo passo. Este curso começa com os fundamentos do GitHub, mas exploraremos mais detalhes adiante.

## :octocat: Compreendendo o fluxo do GitHub

O fluxo do GitHub é um fluxo de trabalho leve que permite que você experimente e colabore em seus projetos de forma fácil, sem o risco de perder o trabalho anterior.

### Repositórios

Um repositório é onde seu trabalho de projeto acontece—pense nele como a pasta do seu projeto. Ele contém todos os arquivos e o histórico de revisões do seu projeto. Você pode trabalhar sozinho ou convidar outras pessoas para colaborar com você nesses arquivos.

### Clonagem

Quando um repositório é criado no GitHub, ele é armazenado remotamente na ☁️. Você pode clonar um repositório para criar uma cópia local no seu computador e usar o Git para sincronizar os dois. Isso facilita a correção de problemas, adicionar ou remover arquivos, e enviar commits maiores. Você também pode usar a ferramenta de edição de sua escolha em vez da interface do GitHub. Clonar um repositório também baixa todos os dados do repositório que o GitHub tem naquele momento, incluindo todas as versões de cada arquivo e pasta do projeto! Isso pode ser útil se você experimentar no projeto e perceber que preferia uma versão anterior.
Para saber mais sobre clonagem, leia ["Clonando um Repositório"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Commitando e enviando
**Commitar** e **enviar** são as formas de adicionar as alterações feitas na sua máquina local ao repositório remoto no GitHub. Assim, seu professor e/ou colegas podem ver seu trabalho mais recente quando você estiver pronto para compartilhá-lo. Você pode fazer um commit quando fizer mudanças no seu projeto que queira "marcar". Também pode adicionar uma **mensagem de commit** útil para lembrar a si mesmo ou aos seus colegas o que foi feito (ex: "Adicionada uma README com informações sobre nosso projeto").

Quando tiver um commit ou múltiplos commits prontos para adicionar ao repositório, você pode usar o comando push para adicionar essas mudanças ao repositório remoto. Committing e pushing podem parecer novos no início, mas garantimos que você se acostumará 🙂

## 💻 Termos do GitHub para saber

### Repositórios 
Já mencionamos repositórios, são onde o seu trabalho acontece, mas vamos falar mais sobre os detalhes! À medida que você trabalhar mais no GitHub, terá muitos repositórios, o que pode parecer confuso no início. Felizmente, seu ["painel do GitHub"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ajuda a navegar facilmente pelos seus repositórios e ver informações úteis sobre eles. Certifique-se de estar logado para vê-lo!

Repositórios também contêm arquivos **README**. Você pode adicionar um README ao seu repositório para explicar por que seu projeto é útil, o que os outros podem fazer com ele e como usá-lo. Estamos usando este README para comunicar como aprender Git e GitHub com você. 😄
Para saber mais sobre repositórios, leia ["Criando, Clonando e Arquivando Repositórios"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Sobre READMEs"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-readmes).

### Branches
Você pode usar branches no GitHub para isolar trabalhos que não quer mesclar no projeto final ainda. Branches permitem desenvolver funcionalidades, corrigir bugs ou experimentar novas ideias de forma segura, sem interferir no restante do repositório. Normalmente, você cria um novo branch a partir do branch principal do repositório—main. Isso cria uma nova cópia do seu repositório para experimentos. Quando estiver satisfeito ou tiver revisado com colegas, você pode mesclar as mudanças no branch principal.
Para saber mais sobre branches, leia ["Sobre Branches"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
Um fork é outra maneira de copiar um repositório, mas geralmente é usado quando você quer contribuir com o projeto de outra pessoa. Forkar um repositório permite experimentar mudanças livremente, sem afetar o projeto original, e é muito popular quando contribuindo para projetos de software open source!
Para saber mais sobre forks, leia ["Forkando um repositório"](https://docs.github.com/pt/github/getting-started-with-github/fork-a-repo).

### Pull requests
Ao trabalhar com branches, você pode usar um pull request para informar a outros sobre as mudanças que deseja fazer e pedir o feedback deles. Uma vez aberto, você pode discutir e revisar as alterações com colaboradores e adicionar mais mudanças, se necessário. Você pode designar pessoas específicas como revisores do seu pull request, indicando que quer o feedback delas! Quando o pull request estiver pronto, pode ser mesclado no branch principal.
Para saber mais sobre pull requests, leia ["Sobre Pull Requests"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues
Issues são uma forma de rastrear melhorias, tarefas ou bugs no GitHub. Issues são ótimas para manter o controle das tarefas que você deseja trabalhar no projeto e deixar os outros saberem o que você pretende fazer. Você também pode usar issues para informar sobre bugs em projetos open source ou sugerir novos recursos.

Para projetos maiores, você pode controlar várias issues em um quadro de projetos. Os projetos do GitHub ajudam a organizar e priorizar seu trabalho. Leia mais sobre eles [neste documento "Sobre quadros de projetos"](https://docs.github.com/pt/github/managing-your-work-on-github/about-project-boards). Você provavelmente não precisará de um quadro para suas tarefas, mas para projetos maiores, eles são ótimos para organizar o trabalho em equipe.
Você também pode vincular pull requests e issues para mostrar que uma correção está em andamento e fechar a issue automaticamente ao mesclar o pull request.
Para saber mais sobre issues e vinculá-las aos seus pull requests, leia ["Sobre Issues"](https://docs.github.com/pt/github/managing-your-work-on-github/about-issues).

### Seu perfil de usuário

Sua página de perfil conta a história do seu trabalho através dos repositórios em que você está interessado, das contribuições que fez e das conversas que teve. Você também pode mostrar ao mundo quem você é com seu README de perfil. Use seu perfil para que futuros empregadores conheçam mais sobre você!
Para saber mais sobre seu perfil e como gerenciar seu README de perfil, leia ["Gerenciando seu README de perfil"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Usando markdown no GitHub

Você pode adicionar estilos divertidos aos seus issues, pull requests e arquivos com ["Markdown"](https://guides.github.com/features/mastering-markdown/). Isso ajuda a organizar as informações e tornar mais fácil para os outros lerem. Você também pode adicionar gifs e imagens para comunicar melhor sua mensagem!
Para saber mais sobre como usar a versão do Markdown no GitHub, leia ["Sintaxe básica de escrita e formatação"](https://docs.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax).

### Engajando com a comunidade do GitHub

A comunidade GitHub é vasta. Existem muitos tipos de pessoas que usam GitHub diariamente—estudantes como você, desenvolvedores profissionais, hobbystas em projetos open source, e exploradores que estão começando no mundo do desenvolvimento de software. Existem várias maneiras de interagir com a comunidade maior do GitHub, e aqui estão três lugares para começar:

#### Estrelando repositórios

Se você encontrar um repositório interessante ou quiser acompanhar, dê uma estrela! Quando você estrela um repositório, isso também ajuda a gerar recomendações no github.com/explore. Para acessar seus repositórios estrelados, vá ao seu perfil.
Para saber mais sobre como dar estrelas em repositórios, leia ["Salvando Repositórios com Estrelas"](https://docs.github.com/pt/github/getting-started-with-github/saving-repositories-with-stars).

#### Seguindo usuários

Você pode seguir pessoas no GitHub para receber notificações sobre a atividade delas e descobrir projetos em suas comunidades. Ao seguir um usuário, a atividade pública dele aparecerá no seu painel, assim você pode ver todas as coisas legais em que ele está trabalhando.
Para saber mais sobre seguir usuários, leia ["Seguindo pessoas"](https://docs.github.com/pt/github/getting-started-with-github/following-people).

#### Explorando GitHub Explore

GitHub Explore é um ótimo lugar para fazer isso... explorar 😄. Você pode encontrar novos projetos, eventos e desenvolvedores para interagir.

Você pode acessar o GitHub Explore no site [github.com/explore](https://github.com/explore). Quanto mais você interagir com o GitHub, mais personalizada será a sua visão do Explore.

## 📝 Próximos passos opcionais

* Abra um pull request e informe ao seu professor que você concluiu este curso.  
* Crie um novo arquivo markdown neste repositório. Informe o que você aprendeu e o que ainda te deixa confuso! Experimente diferentes estilos!
* Crie seu README de perfil. Deixe o mundo saber um pouco mais sobre você! O que você está interessado em aprender? No que você está trabalhando? Qual é o seu hobby favorito? Saiba mais sobre como criar seu README de perfil no documento, ["Gerenciando seu README de perfil"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Vá ao seu painel de usuário e crie um novo repositório. Experimente os recursos dentro desse repositório para se familiarizar com eles.
* [Conte-nos o que você gostou ou não gostou sobre o conteúdo deste curso](https://support.github.com/contact/education). O que você gostaria de ver mais? O que seria interessante ou útil na sua jornada de aprendizado?

## 📚 Recursos
* [Um vídeo curto explicando o que é o GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Recursos de aprendizado sobre Git e GitHub](https://docs.github.com/pt/github/getting-started-with-github/git-and-github-learning-resources)
* [Entendendo o fluxo do GitHub](https://guides.github.com/introduction/flow/)
* [Como usar branches no GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiais interativos de treinamento sobre Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub Learning Lab](https://lab.github.com/)
* [Fórum da comunidade educacional](https://education.github.community/)
* [Fórum da comunidade GitHub](https://github.community/)
