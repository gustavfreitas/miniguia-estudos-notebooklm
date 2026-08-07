## Tim Berners-Lee e a Evolução da World Wide Web
> Um estudo completo sobre a origem, evolução, arquitetura e futuro da Web, baseado na trajetória de Sir Tim Berners-Lee.

![Status](https://img.shields.io/badge/status-concluído-green)
![Tipo](https://img.shields.io/badge/tipo-caderno%20temático-blue)
![Ferramenta](https://img.shields.io/badge/IA-NotebookLM-purple)
![Licença](https://img.shields.io/badge/licença-MIT-green.svg)

<table>

## Sumário

- [Estrutura do Repositório](#-estrutura-do-repositório)
- [1. Contexto e Objetivos](#1-contexto-e-objetivos)
- [2. Curadoria de Fontes](#2-curadoria-de-fontes)
- [3. Engenharia de Prompts e Troubleshooting](#3-engenharia-de-prompts-e-troubleshooting)
- [4. Miniguia de Estudo (Entrega Final)](#4-miniguia-de-estudo-entrega-final)
- [5. Metodologia NotebookLM](#5-metodologia-notebooklm)
- [6. Estrutura do Repositório](#6-estrutura-do-repositório)
- [7. Organização do Projeto](#7-organização-do-projeto)
- [Referências](#-referências)
- [Como Contribuir](#-como-contribuir)
- [Licença](#-licença)
- [Autor](#-autor)

</table>

<table>

  ## 🗂 Estrutura do Repositório

> **Nota:** o repositório encontra-se em estágio inicial. Novos materiais (notas, resumos, mapas mentais e referências complementares gerados a partir da metodologia NotebookLM) serão adicionados conforme o estudo avança.
  
</table>

<table>
  
## 1. Contexto e Objetivos

### Assunto de interesse

O tema escolhido para este caderno temático é a **trajetória de Sir Tim Berners-Lee e a evolução da World Wide Web** — desde o contexto de redes e protocolos que a antecederam até os desafios contemporâneos de privacidade, centralização de dados e descentralização (projeto Solid).

Este tema foi escolhido por conectar dois eixos de interesse: a **história da Ciência da Computação** e a **engenharia de sistemas distribuídos abertos**, servindo também como estudo de caso prático para explorar o **NotebookLM como ferramenta de Engenharia de IA**.

### Objetivos de estudo

- [ ] Compreender o contexto histórico anterior à criação da Web
- [ ] Estudar a contribuição de Tim Berners-Lee para a Ciência da Computação
- [ ] Analisar a arquitetura técnica da World Wide Web
- [ ] Compreender a padronização promovida pelo W3C
- [ ] Investigar a evolução da Web até iniciativas modernas, como Web Semântica, Net Neutrality e Solid
- [ ] Documentar, de forma reprodutível, o processo de curadoria e engenharia de prompts utilizado no NotebookLM

**Público-alvo:** estudantes de Ciência da Computação, profissionais de tecnologia, pesquisadores de sistemas distribuídos e praticantes de Engenharia de IA interessados em fluxos de estudo assistidos por IA.

</table> 

<table>

## 2. Curadoria de Fontes

Fontes abertas (texto/PDF) selecionadas e carregadas no NotebookLM para fundamentar as respostas geradas — todas restritas ao conteúdo dessas fontes (RAG), evitando alucinações.

| # | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | `<A short history of the Web (Tim Berners-Lee, CERN, 1989)>` | Texto/Artigo | `<https://home.cern/science/computing/the-birth-of-the-web/short-history-web/>` |
| 2 | `<History - About us - W3C>` | Texto/Artigo | `<https://www.w3.org/about/history/>` |
| 3 | `<1997: TIM BERNERS-LEE warns the WEB could DIVIDE US - BBC Archieve>` | Texto/Video | `<https://www.youtube.com/watch?v=BOHyLkp7TpE>` |
| 4 | `<Sir Tim Berners Lee, Inventor of the World Wide Web.>` | Texto/Video | `<https://www.youtube.com/watch?v=0jXO6M--lu0>` |
| 5 | `<A brief history of the World Wide Web>` | Texto/Video | `<https://www.youtube.com/watch?v=sSqZ_hJu9zA>` |

> Todas as fontes usadas neste projeto estão disponíveis no notebook original: [NotebookLM — Tim Berners-Lee e a Web](https://notebook.google.com/notebook/c3db6acb-95ce-4ea2-88b7-9bd46745d4ea). 

</table>

<table>

## 3. Engenharia de Prompts e Troubleshooting

Registro das perguntas estratégicas elaboradas no NotebookLM, as variações de prompt testadas, as respostas obtidas e as dificuldades encontradas ao longo do processo.

### 3.1 Prompt #1 — `<Tema do Prompt: Contexto Histórico pré-Web>`

| Campo | Conteúdo |
|-------|----------|
| **Prompt utilizado** | `<Identifique o problema histórico que existia antes da Web.>` |
| **Resposta obtida (resumo)** | `<Antes da criação da World Wide Web, o principal problema histórico era a fragmentação extrema e a incompatibilidade da informação armazenada em diferentes sistemas.>` |
| **Fonte(s) referenciada(s)** | `<A brief history of the World Wide Web>` |
| **Dificuldade encontrada** | `<Faltou a Cronologia dos Fatos.` |
| **Ajuste aplicado** | `<Desenvolva uma análise histórica baseada em literatura acadêmica sobre os desafios existentes antes da criação da World Wide Web.>` |

### 3.2 Prompt #2 — `<Tema do Prompt: Criação da Web e comparações com outras aplicações>`

| Campo | Conteúdo |
|-------|----------|
| **Prompt utilizado** | `<Explique o raciocínio que levou Tim Berners-Lee à criação da Web e compare com outras soluções da época.>` |
| **Resposta obtida (resumo)** | `<O raciocínio de Sir Tim Berners-Lee para criar a Web foi motivado por uma combinação de frustração técnica, uma limitação pessoal de memória e a busca por replicar o funcionamento do cérebro humano na organização de dados.>` |
| **Fonte(s) referenciada(s)** | `<https://webfoundation.org/about/vision/history-of-the-web/>` |
| **Dificuldade encontrada** | `<Dificuldade na separaração de intenções documentadas e de interpretações posteriores ao sucesso da Web.>` |
| **Ajuste aplicado** | `<Assuma o papel de um historiador da tecnologia com especialização em Arquitetura da Web. Reconstrua o raciocínio de Tim Berners-Lee utilizando exclusivamente evidências provenientes de documentos históricos, entrevistas, artigos científicos e publicações técnicas reconhecidas.>` |

### 3.3 Prompt #3 — `<Tema do Prompt: Impactos e Controvérsias pós-Web>`

| Campo | Conteúdo |
|-------|----------|
| **Prompt utilizado** | `<Faça uma analise do impacto da criação da internet nos aspectos: econômico, científico, social. E suas controvérsias pós criação da Web.>` |
| **Resposta obtida (resumo)** | `<A transição da Web de um ambiente puramente acadêmico para o uso comercial transformou a economia global, tornando 1994 o ano em que ela se tornou definitivamente um "grande negócio".>` |
| **Fonte(s) referenciada(s)** | `<https://www.youtube.com/watch?v=BOHyLkp7TpE>` |
| **Dificuldade encontrada** | `<Exigir análise equilibrada, baseada em evidências e reconhecendo limitações, sem ser tendênciosa a uma perspectiva boa ou ruim.>` |
| **Ajuste aplicado** | `<Analise a criação da Internet e da World Wide Web como um sistema sociotécnico. Explique como decisões arquiteturais aparentemente técnicas produziram consequências econômicas, sociais e políticas ao longo das décadas.>` |

### 3.4 Lições aprendidas (troubleshooting geral)

<table>
  
Problema Observado: Pesquisadores tinham dificuldade para compartilhar informações entre instituições.
- Erro Comum: Concluir que o problema era apenas "falta de computadores".
# Troubleshooting
Perguntas investigativas:
- O problema é hardware?
- É software?
- É protocolo?
- É organização?
- É padronização?
- É comunicação entre sistemas?
- Causa-raiz encontrada: Não existia interoperabilidade entre sistemas heterogêneos.
- Lição aprendida: Nunca corrija sintomas antes de identificar a causa estrutural.
  
  </table>
  
<table>
  
Problema Observado: Nem sempre a solução tecnicamente melhor vence.
- Na época existiam alternativas, algumas tinham recursos superiores, mesmo assim a Web venceu, Por quê?

# Troubleshooting
Perguntas investigativas:
- Era gratuita?
- Era aberta?
- Era simples?
- Possuía barreiras?
- Podia ser implementada por qualquer pessoa?
- Lição aprendida: A melhor arquitetura nem sempre é a que possui mais funcionalidades

</table>

<table>
  
### A maior contribuição do troubleshooting aplicado à história da Internet e da Web é mostrar que as grandes inovações raramente surgem da criação imediata de uma nova tecnologia. Elas normalmente resultam de um ciclo disciplinado de investigação:

1. Observar sintomas sem assumir a causa.
2. Formular hipóteses concorrentes.
3. Buscar evidências em fontes confiáveis.
4. Identificar a causa-raiz do problema.
5. Comparar alternativas existentes e seus limites.
6. Projetar uma solução que resolva o problema central, aceitando os trade-offs.
7. Avaliar continuamente os efeitos não previstos e iterar conforme novas necessidades surgem.

</table>

## 4. Miniguia de Estudo (Entrega Final)

### 4.1 Resumos Estruturados

#### Contexto histórico pré-Web
`<Em 1989, o mundo possuía uma infraestrutura global capaz de enviar pacotes de dados (Internet), mas a informação em si estava trancada em silos proprietários, acessíveis apenas por especialistas que conheciam os endereços exatos e os comandos manuais de cada máquina
. A Web surgiria não para criar a rede, mas para criar o espaço de informação comum sobre ela.>`

#### Tim Berners-Lee e a criação da Web
`<Berners-Lee convenceu o CERN a liberar o código-fonte da Web para o domínio público, livre de royalties, em 30 de abril de 1993
. Ele concluiu que se a tecnologia fosse proprietária ou centralizada, ela jamais se tornaria um espaço universal, tornando-se um bloqueio para a própria inovação que ele buscava promover.>`

#### Arquitetura técnica da Web
`<Integração das Tecnologias: HTML, HTTP e URL.
Essas três ferramentas trabalham em conjunto para criar o espaço de informação comum idealizado por Berners-Lee. O usuário utiliza uma URL para localizar um recurso; o navegador usa o protocolo HTTP para solicitar e recuperar esse recurso; e o arquivo retornado em HTML organiza o conteúdo e os links que permitem a continuidade da navegação.>`

#### Padronização e o W3C
`<A padronização da World Wide Web foi um passo fundamental para evitar a fragmentação da rede em sistemas proprietários incompatíveis e garantir que ela permanecesse um bem público universal. Para liderar esse esforço, Sir Tim Berners-Lee fundou o World Wide Web Consortium (W3C) em outubro de 1994.>`

#### Web moderna e desafios atuais
`<A evolução da Web demonstra que a tecnologia não é neutra; ela responde ao mundo que serve. A recente decisão de encerrar a World Wide Web Foundation para focar exclusivamente no Solid sinaliza que a batalha pela infraestrutura física foi vencida (70% da população online), mas a batalha pela agência humana e democracia digital está apenas começando. Como resume seu criador, a Web não é apenas uma rede de computadores, é a humanidade interconectada.>`

### 4.2 Glossário

| Termo | Definição |
|-------|-----------|
| **WWW (World Wide Web)** | `<É uma aplicação (ou serviço) que utiliza a Internet como meio de transporte. É um espaço comum de informação que permite o compartilhamento de documentos e recursos vinculados por hiperlinks.>` |
| **HTTP** | `<É o protocolo de comunicação da camada de aplicação que funciona como a base para a troca de informações e recuperação de recursos interconectados em toda a Web.>` |
| **HTML** | `<É a linguagem de formatação padrão utilizada para criar e estruturar páginas e aplicações na World Wide Web.>` |
| **URI/URL** | `<URI: É o conceito mais amplo, funcionando como um identificador único para cada recurso individual disponível na rede (como documentos, imagens ou vídeos). URL: É a implementação mais comum de uma URI, servindo como o "endereço" específico que permite aos navegadores identificar e localizar a fonte de uma página ou arquivo entre milhões de servidores.>` |
| **W3C** | `<O World Wide Web Consortium (W3C) é uma organização internacional de padronização fundada por Sir Tim Berners-Lee em outubro de 1994, no MIT, com o objetivo de levar a Web ao seu potencial máximo.>` |
| **Web Semântica** | `<A Web original foi projetada para que humanos lessem documentos. Na visão da Web Semântica, o foco muda para os dados estruturados, que podem ser processados diretamente por máquinas. Enquanto documentos são feitos para serem lidos, os dados permitem que o computador execute tarefas complexas, encontre padrões e realize associações automáticas que seriam impossíveis em texto simples.>` |
| **Net Neutrality** | `<A Neutralidade da Rede é o princípio de não discriminação técnica, segundo o qual os provedores de serviços de Internet (ISPs) devem tratar todo o tráfego de dados de forma idêntica.>` |
| **Projeto Solid** | `<O Projeto Solid (acrônimo para Social Linked Data) é uma iniciativa de descentralização da Web liderada por Sir Tim Berners-Lee, desenvolvida originalmente no MIT. Seu objetivo fundamental é devolver aos usuários o controle e a soberania sobre seus dados pessoais e identidades digitais, combatendo a centralização em silos corporativos.>` |
| **CERN** | `<O papel do CERN (Organização Europeia para a Pesquisa Nuclear) foi fundamental como o "berço" e o catalisador para a invenção da World Wide Web, fornecendo a infraestrutura técnica e o ambiente colaborativo necessários para o trabalho de Sir Tim Berners-Lee. A Web não foi criada como um projeto oficial do laboratório, mas surgiu como uma solução pragmática para resolver a fragmentação de informações entre cientistas que utilizavam sistemas de computação incompatíveis.>` |

### 4.3 Prompts Reutilizáveis para Revisão

Conjunto de prompts prontos para reaplicar no NotebookLM em futuras revisões do tema:

```
1. "Resuma em até 5 tópicos a cronologia dos eventos que antecederam a criação da World Wide Web, citando a fonte de cada evento."

2. "Explique a contribuição técnica de Tim Berners-Lee para a criação da Web, destacando HTTP, HTML e URI separadamente."

3. "Compare a arquitetura original da Web proposta por Tim Berners-Lee com o cenário atual de centralização de dados."

4. "Liste os principais marcos da padronização promovida pelo W3C, em ordem cronológica."

5. "Explique o conceito de Web Semântica e como ele se relaciona com o projeto Solid, com base apenas nas fontes carregadas."
```

<table>

## 5. Metodologia NotebookLM

```
flowchart TD
    A[Seleção de fontes confiáveis] --> B[Upload das fontes no NotebookLM]
    B --> C[Geração de resumo guiado por fontes]
    C --> D[Perguntas e respostas fundamentadas nas fontes]
    D --> E[Testes e ajustes de prompts / troubleshooting]
    E --> F[Geração de mapas mentais e Audio Overviews]
    F --> G[Curadoria e estruturação no README]
    G --> H[Revisão crítica e validação factual]
```

| Etapa | Descrição |
|-------|-----------|
| Seleção de fontes | Escolha de materiais confiáveis (artigos, documentação do W3C, biografias, publicações técnicas) |
| Ingestão no NotebookLM | As fontes são carregadas para formar uma base de conhecimento fechada e rastreável |
| Síntese guiada por fontes | O NotebookLM gera resumos e explicações **ancorados exclusivamente** no material fornecido |
| Engenharia de prompts | Testes de diferentes formulações de pergunta, com registro de acertos e dificuldades (seção 3) |
| Recursos multimídia | Geração de mapas mentais e *Audio Overviews* para reforçar a compreensão do conteúdo |
| Curadoria humana | Todo o conteúdo gerado é revisado, validado e reorganizado manualmente antes de compor o README |

**Notebook utilizado:** [NotebookLM — Tim Berners-Lee e a Web](https://notebook.google.com/notebook/c3db6acb-95ce-4ea2-88b7-9bd46745d4ea)

### Por que essa abordagem é relevante para Engenharia de IA

- Demonstra o uso de **RAG (Retrieval-Augmented Generation)** aplicado a um caso real de estudo, reduzindo alucinações ao restringir as respostas às fontes carregadas.
- Exercita **engenharia de prompt** para obter sínteses, comparações e cronologias precisas.
- Evidencia um fluxo de trabalho reprodutível de **curadoria de conhecimento assistida por IA**, da fonte bruta à documentação final.

</table>

<table>
  
## 6. Estrutura do Repositório

> **Nota:** o repositório encontra-se em estágio inicial. Materiais complementares (PDFs das fontes, mapas mentais exportados) podem ser adicionados em pastas futuras (`/fontes`, `/assets`).

</table>

<table>
  
## 7. Organização do Projeto

| Etapa                          | Status          | Responsável     | Objetivo                                                        |
|----------------------------------|-----------------|------------------|---------------------------------------------------------------------|
| Definição de escopo e objetivos  | ✅ Concluído | @gustavfreitas   | Delimitar tema, público-alvo e objetivos do estudo                  |
| Curadoria de fontes no NotebookLM| ✅ Concluído | @gustavfreitas   | Selecionar e carregar fontes confiáveis sobre o tema                |
| Contexto histórico pré-Web       | ✅ Concluído | @gustavfreitas   | Documentar redes e protocolos anteriores à Web                      |
| Trajetória de Tim Berners-Lee    | ✅ Concluído | @gustavfreitas   | Detalhar contribuições técnicas e científicas                       |
| Arquitetura técnica da Web       | ✅ Concluído | @gustavfreitas   | Descrever HTTP, HTML, URI e princípios de design                    |
| Padronização (W3C)               | ✅ Concluído | @gustavfreitas   | Explicar o papel do W3C na evolução da Web                          |
| Web moderna e desafios atuais    | ✅ Concluído | @gustavfreitas   | Analisar Web Semântica, privacidade e o projeto Solid                |

</table>

<table>
  
## 🔗 Referências

### Pessoas e Instituições
- [Tim Berners-Lee — Wikipédia](https://pt.wikipedia.org/wiki/Tim_Berners-Lee)
- [CERN](https://home.cern/)
- [World Wide Web Consortium (W3C)](https://www.w3.org/)

### Tecnologia e Padrões
- [HTTP — MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/HTTP)
- [HTML — MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [Web Semântica — W3C](https://www.w3.org/standards/semanticweb/)

### Privacidade e Descentralização
- [Projeto Solid](https://solidproject.org/)

### Ferramentas e Metodologia de IA
- [NotebookLM](https://notebooklm.google/)

</table>

## 🤝 Como Contribuir

Contribuições são bem-vindas, especialmente sugestões de fontes, correções factuais e complementos ao conteúdo histórico.

1. Faça um fork do repositório
2. Crie uma branch para sua contribuição (`git checkout -b melhoria/nome-da-alteracao`)
3. Faça o commit das alterações (`git commit -m "docs: adiciona conteúdo sobre X"`)
4. Envie a branch (`git push origin melhoria/nome-da-alteracao`)
5. Abra um Pull Request descrevendo a alteração proposta

> **Dica:** para correções pontuais (erros de digitação, links quebrados), abra diretamente uma *Issue*.

<table>

## 📄 Licença

Este projeto está licenciado sob os termos da **Licença MIT**.
Consulte o arquivo [LICENSE](./LICENSE.md) para o texto completo.

</table>

<table>

## 👤 Autor

**Gustavo Freitas**
GitHub: [@gustavfreitas](https://github.com/gustavfreitas)

</table>
