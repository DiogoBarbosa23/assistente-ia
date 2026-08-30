# Assistente de IA

Assistente web desenvolvido para auxiliar usuários na criação de prompts mais claros, estruturados e completos para ferramentas de Inteligência Artificial.

A versão atual foi desenvolvida inicialmente para ser incorporada a uma página do **WordPress**, funcionando diretamente no navegador, sem necessidade de backend ou instalação de dependências.

O sistema conduz o usuário por uma conversa simples, coleta as informações fornecidas e transforma esse conteúdo em um **prompt estruturado**, pronto para ser utilizado em diferentes ferramentas de IA.

## Funcionalidades

* Chat interativo para coleta das informações do usuário
* Fluxo guiado para construção do prompt
* Geração automática de prompt estruturado
* Armazenamento do histórico da conversa no navegador
* Recuperação do histórico após recarregar a página
* Cópia do prompt para a área de transferência
* Botão para limpar a conversa
* Confirmação antes de apagar o histórico
* Notificações visuais para ações realizadas
* Acesso rápido a diferentes ferramentas de IA:

  * ChatGPT
  * Gemini
  * Claude
  * DeepSeek
* Interface responsiva
* Funcionamento diretamente no navegador
* Possibilidade de incorporação em páginas WordPress

## Como funciona

O usuário começa descrevendo o que precisa.

O assistente conduz a criação do prompt através de um fluxo simples:

1. O usuário descreve a **tarefa**.
2. O assistente solicita o **contexto**.
3. O usuário fornece os **detalhes finais**, como formato, regras ou estilo.
4. O sistema reúne as informações fornecidas.
5. Um prompt estruturado é gerado automaticamente.
6. O usuário pode copiar o resultado e utilizá-lo em uma ferramenta de Inteligência Artificial.

### Estrutura do prompt

O prompt gerado atualmente é organizado em seções:

* **Objetivo**
* **Contexto**
* **Processo**
* **Regras**
* **Formato de saída**
* **Critério de qualidade**

A estrutura busca transformar uma solicitação comum em uma instrução mais clara e organizada para ferramentas de IA.

## Tecnologias

* HTML5
* JavaScript
* Tailwind CSS
* LocalStorage
* APIs nativas do navegador

O projeto utiliza recursos externos para o carregamento do Tailwind CSS e da fonte Roboto.

## Como executar

A versão atual não necessita de instalação de dependências ou configuração de servidor.

Basta abrir o arquivo HTML em um navegador moderno.

```text
1. Baixe ou clone o repositório
2. Abra o arquivo index.html
3. Utilize o assistente pelo navegador
```

## Utilização no WordPress

O projeto foi originalmente desenvolvido para ser utilizado dentro de uma página WordPress.

O código pode ser incorporado em uma página que permita a utilização de HTML personalizado.

Dessa forma, o assistente pode ser disponibilizado diretamente dentro de um site sem precisar de uma aplicação externa na versão atual.

## Estrutura atual

Neste estágio, o projeto está concentrado em um único arquivo:

```text
assistente-ia/
└── index.html
```

O arquivo contém:

* estrutura HTML da interface;
* estilos e classes do Tailwind CSS;
* lógica do chat;
* geração dos prompts;
* gerenciamento do histórico;
* integração com os botões das ferramentas de IA.

Essa estrutura simplificada faz parte do estágio inicial do projeto.

## Estado do projeto

O projeto possui uma **versão funcional inicial**.

A arquitetura atual foi mantida simples para permitir que a ferramenta seja utilizada diretamente em uma página web ou incorporada ao WordPress.

A estrutura poderá ser modificada conforme novas funcionalidades forem desenvolvidas.

## Roadmap

Possíveis evoluções futuras:

* [ ] Separar HTML, CSS e JavaScript
* [ ] Melhorar a organização e arquitetura do código
* [ ] Aprimorar o fluxo de criação de prompts
* [ ] Criar diferentes tipos ou modelos de prompts
* [ ] Adicionar novas ferramentas de IA
* [ ] Melhorar a interface e experiência do usuário
* [ ] Adicionar configurações personalizáveis
* [ ] Criar uma aplicação independente
* [ ] Transformar o projeto em um programa completo
* [ ] Avaliar diferentes formas de distribuição
* [ ] Avaliar futura comercialização do projeto

O roadmap pode ser alterado conforme o projeto evoluir.

## Próximos passos

A intenção é evoluir gradualmente o projeto a partir da versão web atual.

A primeira implementação tem como objetivo validar a ideia e disponibilizar o assistente de forma simples através de páginas web e WordPress.

Futuramente, o projeto poderá evoluir para uma aplicação independente, com uma arquitetura mais robusta e novas funcionalidades.

## Demonstração

Uma demonstração online poderá ser disponibilizada futuramente.

## Contribuições

O projeto encontra-se em desenvolvimento.

Alterações, melhorias e novas funcionalidades poderão ser incorporadas conforme o projeto evoluir.

## Licença e Direitos Autorais

Este projeto **não possui uma licença open source**.

Todos os direitos sobre o código-fonte, estrutura, implementação e demais elementos originais deste projeto são reservados ao autor.

**Não é concedida permissão para:**

* copiar ou redistribuir o código;
* modificar e redistribuir o projeto;
* utilizar o código em projetos próprios sem autorização;
* comercializar ou disponibilizar versões derivadas;
* reproduzir a implementação ou utilizá-la como base para outro produto.

O projeto está disponível no GitHub para fins de **visualização, acompanhamento do desenvolvimento e demonstração**, mas sua publicação não representa uma autorização para uso, reprodução ou redistribuição.

Qualquer utilização além desses fins deverá ser previamente autorizada pelo autor.

A estratégia de licenciamento e distribuição comercial do projeto poderá ser definida futuramente.

---

**Desenvolvido por Diogo Barbosa.**
