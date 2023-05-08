# Curso-FrontEnd
#### EBAC

# GIT
## Conceitos de versionamento
  - Histórico
  - Controle de versão
  - Quem alterou
  - O quê alterou
  - Quando alterou
  - Todos os arquivos
  - Evolução contínua
  
  Arquivo A | Versão 1 | Versão 2
  Arquivo B | Versão 1 | Versão 2
  
  ## Instalação do Git
  https://git-scm.com/

  - Win: https://git-scm.com/download/win
  - Lin: (apt-get): sudo apt-get install git
  - MAC: (brew): brew install git

  ## Criar conta do GitHub

  ## Clonar o projeto
  git clone https://github.com/denielzbzn/curso-frontend.git

  ## Commits
  Informação de alteração
  - após testado todo sei código
  - git add *
  - git commit -m "mensagem"
  - git push (envia as alterações direto para o GitHub)
  - git pull (trás as alterações do GitHub para a Máquina)

  ## GitFlow
  Fluxo do Git

  ### Branchs
  São ramificações / versões paralelas

  - main / master
  - develop
    - versionamento 0.1.10 (terceiro numero - correções corriqueiras / bug)
      - versionamento 0.2.11 (segundo numero - alteraçoes grandes e importantes)
        - versionamento 1.0.0 (primeiro numero - Após tudo concluído e está pronto para enviar para a master)
  - DOD Definition of Done: Critérios de Aceite (somente quando tudo estiver aprovado que fecha a versão e envia para a ramificação Master)

  - git checkout -b dev (cria uma branch)
  - git checkout master/main (mudar de branch)
  

  ### Merge
  Mescla de Branchs
  Você pode precisar resolver conflitos manualmente

  - git fetch --all
  - git merge master/main

  ### Pull Requests
  Mescla de banchs no repositório
  Permite o Code Review
  O repositório resolve os conflitos automaticamente

  ### Configura o GitFlow

  - git flow init
  - git flow feature start {nome da feature}
  


