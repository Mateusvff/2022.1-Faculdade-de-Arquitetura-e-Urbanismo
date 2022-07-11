# Plano de Metodologia e Processos

### Histórico de Versões

**Data** | **Versão** | **Descrição** | **Autor(es/as)** | **Revisor**
--- | --- | --- | --- | ---
28/06/2022 | 0.1 | Versão Inicial | Mateus Franco | Letícia Aires
09/07/2022 | 0.2 | Adição do conteúdo dos tópicos 1, 2, 3, 4 e 5 | Letícia Aires | Matheus Costa

## 1. Introdução

A fim de se atingir resultado previsto ao projeto, elaboraram-se metodologias organizacionais a fim de guiar ações e padronizar processos. Desse modo, entregas de resultado são apresentadas de forma mais rápida e sistemática, assim como a dinâmica do grupo. 

Nesse sentido, o presente documento visa informar metodologias, processos e práticas a serem utilizadas ao longo da avaliação.

## 2. Metodologias

### 2.1. Gerenciamento de Projetos (SCRUM)

Com o fito de tornar mais eficiente o gerenciamento da equipe, optou-se pela utilização de metodologias ágeis, em especial o SCRUM, o qual se fundamenta nos seguintes princípios:

* Desenvolvimento iterativo com base em sprints
* Priorização orientada a valor
* Estabelecimento de prazos
* Colaboração
* Controle empírico do processo
* Auto-organização

Desse modo, em se estabelecendo períodos iterativos com prazos e objetivos determinados, são quantificados o andamento e as metas do projeto. Nessa ótica, a dinâmica é otimizada e se pode observar colaboração em grupo e entregas de valor quantitativo mais expressivo.

## 3. Políticas e regras

### 3.1. Política de Commit

Os commits realizados devem ser pequenos e significativos, de forma que cada um possua uma única funcionalidade (commits atômicos). Ademais, estes devem seguir estrutura padronizada pré-acordada. Isto é, deve-se realizar o commit da seguinte forma:

#### Estrutura

<tipo> (#n° da issue): descrição sucinta do commit em letras minúsculas
Co-authored-by: user <email>

#### Tipos:

* 🚀 quando adicionar código do front-end `:rocket:`
* 💾 quando adicionar código do back-end `:floppy_disk:`
* 🔁 quando alguma alteração for feita `:repeat:`
* 🆒 quando melhorias de formato/estrutura do código `:cool:`
* 🐎 quando melhorar o desempenho `:racehorse:`
* ❌ quando resolver memory leaks `:x:`
* 📝 quando escrever documentação `:pencil:`
* 🐛 quando consertar um problema `:bug:`
* 🔥 quando remover código ou arquivos `:fire:`
* 💚 quando consertar problemas de Integração Contínua `:green_heart:`
* ✅ quando adicionar testes `:white_check_mark:`
* 🔒 quando lidar com segurança `:lock:`
* ⬆️ quando realizar o upgrade de dependências `:arrow_up:`
* ⬇️ quando realizar downgrade de dependências `:arrow_down:`

#### Exemplo de commit
`🔁(#10): inserção de novo tópico`

### 3.2. Política de Branch

#### Main

A branch main deve abarcar somente o código já testado, versionado e revisado, ou seja, pronto para ser entregue ao usuário final. Alem disso, a branch deve originar da branch develop por meio de Pull Requests.

#### Development

Nesta branch consta a versão mais atualizada do código e deve sempre se manter atualizada com a main. Vale ressaltar que esta branch é base para as branches feature.

#### Feature

As branches feature são mecanismos temporários de desenvolvimento de código com função específica de cumprir determinado objetivo de uma issue, assim, a branch development deve ser sua origem e fim.

Nomenclatura utilizada: feature/(#n° da issue)_nome_da_issue

## 4. Ferramentas 

**Ícones** | **Ferramentas** | **Função** 
--- | --- | --- 
 |Discord| Aplicativo para condução de reuniões remotas 
 |Github | Site responsável  por abarcar o repositório
 |Whatsapp| Aplicativo de mensagem de texto para comunicação trivial
 |Mkdocs| Site para a documentação do projeto

## 5. Referências

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J.Interação Humano-Computador e Experiência do usuário. 2021. Autopublicação. ISBN: 978-65-00-19677-1

> COHN, Mike. **Desenvolvimento de Software com Scrum**: Aplicando Métodos Ágeis com Sucesso. 2021. Disponível em: [https://books.google.com.br/books](https://books.google.com.br/books?hl=pt-BR&lr=&id=gbgpDwAAQBAJ&oi=fnd&pg=PP1&dq=scrum&ots=LKeHqsPUgZ&sig=K6qMsH0Oq#v=onepage&q=scrum&f=false). Acesso em: 10 de jul. de 2022.

