# Github Actions

Git actions é uma das formas da aplicação de versionamento de código que geram variaveis de ambiente por meio do GitHub. Além disso ele permite automatizar, customizar e executar os workflows de
desenvolvimento de software diretamente do seu repositório GitHub. Você pode descobrir, criar e compartilhar actions para executar qualquer trabalho que você queira, incluindo
CI/CD, e também combinar actions para criar um workflow totalmente customizado.

<center><img width="80%" src="https://guides.github.com/activities/hello-world/branching.png"></center>

Podemos verificar na imagem acima como é realizado o sistema de versionamento pelo github actions.

> # Mas o que seria CI/CD?

A integração contínua é uma prática de desenvolvimento de software de DevOps em que os desenvolvedores, com frequência, juntam suas alterações de código em um repositório central. Depois disso, criações e testes são executados.

Os principais objetivos da integração contínua são encontrar e investigar bugs mais rapidamente, melhorar a qualidade do software e reduzir o tempo que leva para validar e lançar novas atualizações de software.

<center><img width="80%" src="https://www.edureka.co/blog/content/ver.1531719070/uploads/2018/07/Asset-33-1.png"></center>

Esta etapa é que chamamos de continus monitoring ja que consigamos acessar cada etapa do CI/CD.

# Nesta pasta so criamos o arquivo de deploy, todo o restante é realizado utilizando ferramentas do github.

É possivel verificar cada etapa da pipeline acessando a pasta `.github/workflows`
--