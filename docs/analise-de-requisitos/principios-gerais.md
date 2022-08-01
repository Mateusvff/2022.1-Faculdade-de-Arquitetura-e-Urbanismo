# Princípios Gerais do Projeto

### Histórico de Versões

**Data** | **Versão** | **Descrição** | **Autor(es/as)** | **Revisor**
--- | --- | --- | --- | ---
30/07/2022 | 0.1 | Criação do documento | Matheus Costa | Caio César
30/07/2022 | 0.2 | Adição dos tópicos Introdução e Princípios gerais | Matheus Costa | Caio César
31/07/2022 | 0.2.1 | Descrição dos tópicos das diretrizes | Matheus Costa | Caio César

***


## 1. Introdução

Ainda dentro da fase de [análise de requisitos](../planejamento/processo-de-design.md) prevista dentro do Ciclo de Vida de Mayhew, existe a etapa dos Princípios Gerais de Projeto.

Barbosa e Silva (2010, p. 264) citam Mayhew, quando dizem que "princípios costumam representar objetivos gerais e de alto nível; diretrizes, regras gerais comumente observadas na prática; e padrões, soluções específicas a certos contextos bem delimitados, envolvendo certos usuários desempenhando determinadas tarefas.". Os autores ainda explicam que alguns conjuntos de diretrizes visam motivar designers a seguir uma certa padronização para assegurar aparência e comportamento (_look and feel_) semelhantes
com o que os desenvolvedores ou alguma outra organização propuseram, mas que apesar disso, essas diretrizes frequentemente são recomendações genéricas e descontextualizadas da teoria ou base empírica que lhes deram origem.

## 2. Sobre Princípios gerais e diretrizes

Diante do exposto anteriormente, Barbosa e Silva (2010, p. 265-278) afirmam que os princípios e diretrizes comumente utilizados no processo de design da interação e da interface giram em torno de alguns tópicos. São eles:

- **Correspondência com as expectativas dos usuários**: de acordo com Barbosa e Silva (2010), devemos nos certificar de que **o usuário consegue determinar** os relacionamentos entre: intenções e ações possíveis; entre ações e seus efeitos no sistema; entre o estado real do sistema e o que é percebido pela visão, audição ou tato; entre o estado percebido do sistema e as necessidades, intenções e expectativas do usuário;

- **Simplicidade nas estruturas das tarefas**: segundo Barbosa e Silva (2010, p. 267), é Norman quem recomenda simplificar a estrutura das tarefa, reduzindo a quantidade de planejamento e resolução de problemas que elas requerem. Possíveis **tarefas desnecessariamente complexas podem ser reestruturadas**, e aqui são apresentadas quatro abordagens tecnológicas para simplificar essas estruturas:
    
    - a) manter a tarefa a mesma, mas fornecendo diversas formas de apoio para que os usuários consigam aprender e realizar a tarefa;
    - b) usar tecnologia para tornar visível o que seria invisível, melhorando o feedback e a capacidade de o usuário se manter no controle da tarefa; 
    - c) automatizar a tarefa ou parte dela, mantendo-a igual; 
    - d) modificar a natureza da tarefa.

- **Equilíbrio entre controle e liberdade do usuário**: aqui é ressaltada a importância de manter o usuário no controle. A sensação de o usuário estar "no comando" o faz aprender mais rápido, mas é necessário buscar um **equilíbrio entre o controle sem restrições do usuário e uma interface limitante**. "O caminho mais rápido ou preferencial pode ser o de “menor resistência”, mas usuários que queiram explorar diferentes alternativas e cenários devem conseguir fazê-lo." (BARBOSA; SILVA; 2010, p. 267, apud TOGNAZZINI, 2003);

- **Consistência e padronização**: para facilitar o aprendizado e uso de um sistema, Norman (1988) recomenda **assegurar a consistência da interface** com o modelo conceitual embutido no sistema. Os usuários não devem ter de se perguntar se palavras, situações ou ações diferentes significam a mesma coisa, como por exemplo: utilizar rótulos "_Salvar_" e "_Gravar_" indiscriminadamente em um mesmo sistema pode confundir o usuário;

- **Promoção da eficiência do usuário**: visto que pessoas são mais custosas do que máquinas, e uma economia de tempo e esforço do usuário costumam trazer mais benefícios do que economias semelhantes de processamento ou armazenamento, este tópico considera que em primeiro lugar vem a eficiência do usuário, e não a do computador. Barbosa e Silva (2010) trazem diversas indicações de outros autores, as quais, em conjunto, constroem basicamente uma ideia de que **o sistema deve possuir uma certa inteligência** e apresentar algumas funcionalidades, como: proporcionar ao usuário a oportunidade de continuar trabalhando com outras partes do sistema, enquanto um processamento pode ocorrer em _backgorund_, evitando perda de produtividade e desperdício de dinheiro por parte do usuário; se manter informado sobre o usuário, sendo capaz de saber se é a primeira vez que o usuário acessou o sistema, onde ele estava quando deixou o sistema na última sessão, etc.; promover a eficiência de usuários frequentes fornecendo atalhos e aceleradores, facilitando o uso, como por exemplo com teclas de atalho; entre outras.

- **Antecipação das necessidades do usuário**: as aplicações devem tentar prever o que o usuário quer e precisa, em vez de esperar que os usuários busquem ou coletem informações ou invoquem ferramentas. **O software deve tomar iniciativa** e fornecer informações adicionais úteis, em vez de apenas responder precisamente a pergunta que o usuário tiver feito. (BARBOSA; SILVA; 2010, p. 273, apud COOPER, 1999);

- **Visibilidade e reconhecimento**: antes de executar uma ação, é necessário **tornar visível para os usuários o que é possível realizar** e como as ações devem ser feitas. Para isso, a interface deve oferecer ações que correspondam a intenções do usuário.;

- **Conteúdo relevante e expressão adequada**: é destacado pelos autores Reevs e Nass (1996) que uma interação polida segue **quatro máximas: qualidade, quantidade, relação (ou relevância) e modo (ou clareza)**. A máxima da *qualidade* afirma que não devemos dizer nada que saibamos não ser verdade ou para o que não tenhamos evidências, ou seja, não devemos mentir ou especular. A máxima da *quantidade* diz respeito à quantidade de informação comunicada: a contribuição de uma fala deve ser tão informativa quanto necessário para os objetivos da conversa, e não mais. A máxima da quantidade está fortemente relacionada à simplicidade da interface. A máxima da *relação* ou relevância afirma que tudo o que for dito deve ter relação clara com os tópicos da conversa até o momento e ser relevante ao objetivo dos interlocutores. Por fim, a máxima de *modo ou clareza* pede para evitar a prolixidade e ambiguidade, buscar a concisão e ordenar adequadamente a conversa; (BARBOSA; SILVA; 2010)

- **Projeto para erros**: os autores destacam que Norman recomenda projetar para o erro, ou seja, **assumir que qualquer erro potencial será cometido**. Dessa forma, o designer deve ajudar o usuário a se recuperar de um erro, informando-lhe sobre o que ocorreu, as consequências disso e como reverter os resultados indesejados.


## 3. Análise dos princípios gerais e diretrizes para o projeto

## 4. Conclusão

## 5. Referências
> BARBOSA, Simone; SILVA, Bruno. **Interação Humano-Computador**. 1ª Edição. Elsevier, 2010.
