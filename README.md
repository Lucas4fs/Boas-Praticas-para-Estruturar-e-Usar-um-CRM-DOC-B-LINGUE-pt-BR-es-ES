# 📚 Boas Práticas para Estruturar e Usar um CRM

> Documento bilíngue em português do Brasil e espanhol.

<a id="selecao-de-idioma"></a>

## 🌐 Seleção de idioma / Selección de idioma

Escolha o idioma / Elige el idioma:

- [Português BR](#portugues-br)
- [Español ES](#espanol-es)

---

<a id="portugues-br"></a>

## 🇧🇷 Português BR

[↩ Voltar à seleção de idioma](#selecao-de-idioma)

# Boas Práticas para Estruturar e Usar um CRM

> Guia prático para tornar o CRM compreensível, padronizado e útil para a tomada de decisões.

---

## 📑 Índice

1. [Objetivo do CRM](#portugues-br-secao-1)
2. [Princípios fundamentais](#portugues-br-secao-2)
3. [Estrutura básica do CRM](#portugues-br-secao-3)
4. [Padronização de cadastros](#portugues-br-secao-4)
5. [Definição do funil de vendas](#portugues-br-secao-5)
6. [Regras para preenchimento dos dados](#portugues-br-secao-6)
7. [Nomenclatura e organização dos campos](#portugues-br-secao-7)
8. [Gestão de atividades e interações](#portugues-br-secao-8)
9. [Qualidade e governança dos dados](#portugues-br-secao-9)
10. [Indicadores e relatórios](#portugues-br-secao-10)
11. [Perfis de acesso e responsabilidades](#portugues-br-secao-11)
12. [Automação e integrações](#portugues-br-secao-12)
13. [Rotina de utilização do CRM](#portugues-br-secao-13)
14. [Erros comuns a evitar](#portugues-br-secao-14)
15. [Checklist de implementação](#portugues-br-secao-15)
16. [Conclusão](#portugues-br-secao-16)

---

<a id="portugues-br-secao-1"></a>
## 1. Objetivo do CRM

Um CRM — *Customer Relationship Management*, ou Gestão de Relacionamento com o Cliente — deve ser mais do que um local para armazenar contatos. Ele precisa funcionar como uma **fonte confiável de informações sobre clientes, oportunidades, interações e resultados comerciais**.

Um CRM bem estruturado deve permitir que a empresa:

- Saiba quem são seus clientes e potenciais clientes;
- Entenda em que etapa cada oportunidade se encontra;
- Identifique o próximo passo de cada negociação;
- Registre o histórico de contatos e decisões;
- Evite perda de informações quando um profissional muda de função;
- Acompanhe a produtividade e os resultados da equipe;
- Gere relatórios consistentes para apoiar decisões;
- Reduza tarefas manuais e retrabalho;
- Melhore a experiência do cliente.

> **Regra principal:** qualquer profissional autorizado deve conseguir abrir um registro no CRM e compreender rapidamente seu contexto, seu histórico e sua situação atual.

---

<a id="portugues-br-secao-2"></a>
## 2. Princípios fundamentais

### 2.1. Clareza antes da complexidade

O CRM deve apresentar somente as informações necessárias para cada processo. Excesso de campos, telas e opções aumenta a dificuldade de uso e reduz a qualidade dos dados.

Antes de criar um campo, pergunte:

1. Essa informação será utilizada?
2. Quem precisa dela?
3. Qual decisão ela ajuda a tomar?
4. Pode ser obtida automaticamente?
5. É realmente diferente de outro campo já existente?

Se a resposta não for clara, o campo provavelmente não deve ser criado.

### 2.2. Padronização

Todos os profissionais devem registrar informações seguindo as mesmas regras. A padronização permite comparar registros, criar filtros confiáveis e gerar relatórios consistentes.

Exemplos de itens que devem ser padronizados:

- Nomes de empresas e contatos;
- Telefones e e-mails;
- Segmentos de clientes;
- Origem dos leads;
- Etapas do funil;
- Motivos de perda;
- Tipos de atividade;
- Formatos de datas e valores;
- Responsáveis pelos registros.

### 2.3. Atualização contínua

Um CRM desatualizado perde valor rapidamente. Cada interação relevante deve gerar uma atualização no registro correspondente.

O CRM deve responder, a qualquer momento:

- O que aconteceu recentemente?
- Qual é o status atual?
- Quem é o responsável?
- Qual é o próximo passo?
- Quando a próxima ação deve acontecer?

### 2.4. Responsabilidade compartilhada

A qualidade do CRM não é responsabilidade apenas da área de tecnologia, marketing ou operações. Cada usuário deve ser responsável pela qualidade dos dados que cria ou altera.

### 2.5. Registro baseado em fatos

Os dados devem refletir acontecimentos reais, e não percepções vagas.

Evite registrar:

- “Cliente interessado” sem explicar o motivo;
- “Retornar em breve” sem data definida;
- “Está quase fechando” sem evidência concreta;
- “Sem resposta” sem informar os canais e as tentativas realizadas.

Prefira registros objetivos, como:

> “Cliente confirmou interesse no plano Premium e solicitou proposta até 15/10. Próximo contato agendado para 17/10 por telefone.”

---

<a id="portugues-br-secao-3"></a>
## 3. Estrutura básica do CRM

A estrutura pode variar conforme a plataforma, mas normalmente envolve os seguintes objetos ou entidades:

| Entidade | O que representa | Exemplos de informações |
|---|---|---|
| **Empresa/Conta** | Organização ou empresa relacionada à negociação | Nome, segmento, porte, cidade, site |
| **Contato** | Pessoa que trabalha ou se relaciona com a empresa | Nome, cargo, e-mail, telefone, perfil |
| **Lead** | Pessoa ou empresa que ainda precisa ser qualificada | Origem, interesse, canal, status |
| **Oportunidade/Negócio** | Possibilidade concreta de venda | Valor, etapa, probabilidade, previsão de fechamento |
| **Atividade** | Interação ou tarefa realizada/agendada | Ligação, reunião, e-mail, visita, tarefa |
| **Produto/Serviço** | Item que pode ser vendido | Nome, categoria, preço, margem |
| **Campanha** | Ação responsável por gerar ou influenciar contatos | Nome, canal, período, investimento |
| **Ticket/Solicitação** | Demanda de atendimento ou suporte | Categoria, prioridade, status, solução |

### 3.1. Relação entre os registros

A relação entre os objetos deve ser lógica e fácil de entender. Um exemplo de estrutura é:

```text
Empresa
├── Contatos
├── Oportunidades
│   ├── Atividades
│   ├── Produtos ou serviços
│   └── Propostas
├── Tickets de atendimento
└── Histórico de interações
```

### 3.2. Evite duplicidade de informação

Uma informação deve ser registrada em um único local sempre que possível.

Por exemplo:

- O segmento da empresa deve ficar no cadastro da empresa, não repetido manualmente em cada oportunidade;
- O cargo do contato deve ficar no contato, não apenas em uma anotação;
- O valor do negócio deve ficar no registro da oportunidade, não somente no histórico de atividades.

Isso reduz divergências e facilita a manutenção dos dados.

---

<a id="portugues-br-secao-4"></a>
## 4. Padronização de cadastros

### 4.1. Cadastro de empresas

Defina previamente quais dados são obrigatórios para criar uma empresa.

Campos recomendados:

- Razão social ou nome oficial;
- Nome comercial, quando aplicável;
- CNPJ ou identificador empresarial;
- Site;
- Segmento de atuação;
- Porte da empresa;
- Cidade e estado;
- País;
- Número estimado de funcionários;
- Status do relacionamento;
- Responsável pela conta;
- Origem do cadastro.

### 4.2. Cadastro de contatos

Campos recomendados:

- Nome completo;
- Cargo ou função;
- Departamento;
- E-mail corporativo;
- Telefone ou celular;
- Empresa relacionada;
- Papel na decisão de compra;
- Preferência de contato;
- Consentimento de comunicação, quando aplicável;
- Status do contato.

### 4.3. Cadastro de leads

O lead deve conter informações suficientes para permitir a qualificação inicial.

Campos recomendados:

- Nome;
- Empresa;
- Canal de origem;
- Campanha de origem;
- Produto ou serviço de interesse;
- Região;
- Perfil ou segmento;
- Data de entrada;
- Responsável;
- Status de qualificação;
- Última interação;
- Próximo passo.

### 4.4. Identificação de duplicidades

Antes de criar um registro, o usuário deve pesquisar se a empresa, o contato ou o lead já existe.

Utilize critérios como:

- CNPJ ou identificador fiscal;
- E-mail;
- Domínio do site;
- Telefone;
- Nome da empresa;
- Nome completo do contato.

> **Boa prática:** se houver dúvida, atualize o registro existente em vez de criar um novo.

### 4.5. Formatos recomendados

| Item | Padrão recomendado | Exemplo |
|---|---|---|
| Nome de empresa | Nome oficial ou nome comercial definido | Empresa Exemplo Ltda. |
| Telefone | Código do país + DDD + número | +55 11 99999-9999 |
| Data | Formato único definido pela empresa | 15/10/2026 |
| Moeda | Moeda explícita no campo ou relatório | R$ 25.000,00 |
| E-mail | Letras minúsculas e sem espaços | contato@empresa.com.br |
| Estado | Sigla oficial | SP |
| País | Nome padronizado ou código definido | Brasil |

---

<a id="portugues-br-secao-5"></a>
## 5. Definição do funil de vendas

O funil deve representar o processo real da empresa, e não uma lista genérica de etapas.

### 5.1. Exemplo de etapas

| Etapa | Definição | Critério para entrar | Critério para sair |
|---|---|---|---|
| **Lead recebido** | Novo contato capturado | Lead criado no CRM | Dados mínimos verificados |
| **Qualificação** | Verificação de perfil e necessidade | Contato possui potencial | Necessidade e aderência confirmadas |
| **Diagnóstico** | Entendimento do problema do cliente | Reunião ou conversa iniciada | Problema, urgência e envolvidos identificados |
| **Solução apresentada** | Produto ou serviço apresentado | Necessidade mapeada | Cliente recebeu a solução adequada |
| **Proposta enviada** | Proposta comercial encaminhada | Valor e escopo definidos | Cliente confirmou recebimento e avaliação |
| **Negociação** | Discussão de preço, prazo ou condições | Proposta em avaliação | Acordo alcançado ou negociação encerrada |
| **Fechado ganho** | Venda concluída | Cliente aceitou e formalizou | Pedido, contrato ou pagamento registrado |
| **Fechado perdido** | Oportunidade encerrada sem venda | Motivo de perda conhecido | Registro finalizado e classificado |

### 5.2. Regras para uma boa etapa

Cada etapa deve ter:

- Nome curto e compreensível;
- Descrição objetiva;
- Critério de entrada;
- Critério de saída;
- Responsável principal;
- Ações esperadas;
- Tempo máximo recomendado;
- Indicador associado.

### 5.3. Não confunda etapa com atividade

A **etapa** representa o estado da oportunidade.

A **atividade** representa uma ação realizada ou planejada.

Exemplo:

- Etapa: **Proposta enviada**;
- Atividade: **Ligar para o cliente em 17/10 para confirmar dúvidas**.

Uma oportunidade não deve permanecer parada em uma etapa sem um próximo passo definido.

### 5.4. Motivos de perda

O motivo de perda deve ser obrigatório ao encerrar uma oportunidade como perdida.

Use uma lista padronizada, por exemplo:

- Preço acima do orçamento;
- Cliente escolheu concorrente;
- Falta de prioridade;
- Sem orçamento disponível;
- Prazo incompatível;
- Solução sem aderência;
- Contato não respondeu;
- Projeto cancelado;
- Dados insuficientes;
- Outro — com justificativa obrigatória.

Evite o motivo genérico “outros” sem uma descrição complementar.

---

<a id="portugues-br-secao-6"></a>
## 6. Regras para preenchimento dos dados

### 6.1. Campos obrigatórios e opcionais

Um campo deve ser obrigatório somente quando sua ausência impedir o processo ou prejudicar significativamente a análise.

**Campos geralmente obrigatórios:**

- Nome do registro;
- Responsável;
- Origem;
- Etapa ou status;
- Próximo passo;
- Data prevista da próxima ação;
- Valor, quando se tratar de oportunidade;
- Motivo de perda, quando aplicável.

**Campos geralmente opcionais:**

- Informações que ainda não estão disponíveis;
- Dados que podem ser enriquecidos posteriormente;
- Observações complementares.

### 6.2. Use listas controladas

Sempre que possível, utilize listas suspensas, caixas de seleção e campos padronizados em vez de campos de texto livre.

Prefira:

- `Indústria`
- `Varejo`
- `Serviços`
- `Tecnologia`

Em vez de permitir variações como:

- “Indústria”;
- “industrial”;
- “Ind.”;
- “setor industrial”.

### 6.3. Escreva observações com contexto

Uma boa anotação deve informar:

1. Data ou período da interação;
2. Pessoa envolvida;
3. Assunto tratado;
4. Resultado;
5. Próximo passo;
6. Responsável pelo próximo passo;
7. Prazo.

**Modelo recomendado:**

```text
[DATA] — [TIPO DE INTERAÇÃO]
Participantes: [nomes e cargos]
Assunto: [tema principal]
Resumo: [principais pontos discutidos]
Resultado: [decisão ou situação atual]
Próximo passo: [ação objetiva]
Responsável: [nome]
Prazo: [data]
```

**Exemplo:**

```text
15/10/2026 — Reunião de diagnóstico
Participantes: Ana Souza — Cliente; Carlos Lima — Comercial
Assunto: Necessidade de automatização do atendimento
Resumo: O cliente recebe aproximadamente 2.000 solicitações mensais e tem dificuldade para acompanhar os prazos.
Resultado: Demonstrou interesse em avaliar a solução de atendimento integrada.
Próximo passo: Enviar proposta com os módulos Atendimento e Relatórios.
Responsável: Carlos Lima
Prazo: 18/10/2026
```

### 6.4. Evite abreviações desconhecidas

Use abreviações somente quando forem conhecidas por toda a equipe e estiverem documentadas em um glossário.

Evite anotações como:

> “Falei c/ o decisor, budget ok, aguardando retorno do jurídico.”

Prefira:

> “Conversei com o responsável pela decisão. O orçamento foi aprovado e a proposta está em análise pelo departamento jurídico.”

---

<a id="portugues-br-secao-7"></a>
## 7. Nomenclatura e organização dos campos

### 7.1. Nomes claros

O nome de um campo deve permitir que o usuário compreenda seu significado sem precisar consultar outra pessoa.

Prefira:

- `Data prevista de fechamento`;
- `Origem do lead`;
- `Motivo de perda`;
- `Responsável pela oportunidade`.

Evite:

- `Data 2`;
- `Orig.`;
- `Tipo A`;
- `Flag comercial`.

### 7.2. Descrições e exemplos

Campos que podem gerar dúvida devem conter uma descrição ou exemplo.

Exemplo:

> **Probabilidade de fechamento:** percentual estimado de conclusão da oportunidade, baseado na etapa do funil e nas evidências disponíveis.

### 7.3. Agrupamento lógico

Organize os campos por blocos:

1. Identificação;
2. Contato;
3. Qualificação;
4. Dados comerciais;
5. Relacionamento;
6. Operação;
7. Consentimento e privacidade;
8. Auditoria e histórico.

### 7.4. Evite campos redundantes

Não crie campos com significados semelhantes sem documentar a diferença.

Exemplo de possível confusão:

- `Status do lead`;
- `Situação do lead`;
- `Fase do contato`;
- `Classificação comercial`.

Se todos significam praticamente a mesma coisa, mantenha apenas um campo ou defina claramente a função de cada um.

### 7.5. Campos derivados

Sempre que possível, calcule automaticamente informações derivadas de outros campos.

Exemplos:

- Idade da oportunidade;
- Dias desde a última interação;
- Faixa de valor;
- Percentual de conversão;
- Tempo em cada etapa;
- Classificação de prioridade.

Isso reduz erros de preenchimento manual.

---

<a id="portugues-br-secao-8"></a>
## 8. Gestão de atividades e interações

### 8.1. Toda oportunidade deve ter um próximo passo

O campo **próximo passo** deve ser objetivo e acionável.

Evite:

- “Acompanhar”;
- “Ver depois”;
- “Retornar”; 
- “Em negociação”.

Prefira:

- “Enviar proposta revisada até 18/10”;
- “Ligar para Ana em 20/10 às 10h”;
- “Solicitar aprovação do desconto ao gerente”;
- “Agendar demonstração com o time técnico”.

### 8.2. Registre atividades no momento adequado

As atividades devem ser registradas:

- Antes da ação, quando forem tarefas planejadas;
- Logo após a ação, quando representarem uma interação concluída;
- Com data, responsável e resultado.

### 8.3. Tipos de atividade padronizados

Crie uma lista simples e consistente:

- Ligação;
- E-mail;
- Reunião;
- Videoconferência;
- Demonstração;
- Visita;
- Mensagem;
- Tarefa interna;
- Proposta enviada;
- Contrato enviado;
- Atendimento realizado.

### 8.4. Atividades futuras e atrasadas

A equipe deve acompanhar regularmente:

- Atividades vencidas;
- Atividades previstas para o dia;
- Atividades da semana;
- Oportunidades sem atividade futura;
- Oportunidades sem interação recente.

Uma oportunidade sem atividade futura deve ser considerada um sinal de risco.

---

<a id="portugues-br-secao-9"></a>
## 9. Qualidade e governança dos dados

### 9.1. Defina um responsável pelo CRM

A empresa deve indicar pelo menos um responsável por:

- Manter padrões e regras;
- Avaliar solicitações de novos campos;
- Remover ou consolidar informações duplicadas;
- Acompanhar a qualidade dos dados;
- Treinar usuários;
- Documentar mudanças;
- Coordenar revisões periódicas.

### 9.2. Crie um dicionário de dados

O dicionário de dados deve explicar os principais campos do CRM.

| Campo | Definição | Tipo | Obrigatório? | Valores permitidos | Responsável |
|---|---|---|---|---|---|
| Origem do lead | Canal que gerou o primeiro contato | Lista | Sim | Site, indicação, evento, mídia paga, prospecção | Marketing |
| Etapa | Estado atual da oportunidade | Lista | Sim | Qualificação, diagnóstico, proposta, negociação | Comercial |
| Motivo de perda | Razão principal do encerramento sem venda | Lista | Condicional | Preço, concorrente, sem orçamento, sem prioridade | Comercial |
| Data prevista de fechamento | Data estimada para conclusão | Data | Sim | Data válida | Comercial |

### 9.3. Auditorias periódicas

Realize verificações mensais ou trimestrais para encontrar:

- Registros duplicados;
- Empresas sem contatos;
- Oportunidades sem valor;
- Oportunidades sem próxima atividade;
- Leads sem responsável;
- Registros sem origem;
- Datas de fechamento vencidas;
- Oportunidades paradas há muito tempo;
- Campos preenchidos com valores inválidos;
- Clientes sem atualização recente.

### 9.4. Indicadores de qualidade

| Indicador | Fórmula ou critério | Objetivo |
|---|---|---|
| **Completude** | Campos preenchidos ÷ campos esperados | Medir se os registros possuem informações suficientes |
| **Duplicidade** | Registros duplicados ÷ total de registros | Reduzir cadastros repetidos |
| **Atualidade** | Registros atualizados no período ÷ total de registros ativos | Identificar dados desatualizados |
| **Aderência ao processo** | Registros que seguem as regras ÷ total auditado | Verificar o uso correto do CRM |
| **Oportunidades com próximo passo** | Oportunidades com ação futura ÷ total de oportunidades abertas | Evitar negociações sem acompanhamento |
| **Taxa de conversão** | Oportunidades ganhas ÷ oportunidades encerradas | Avaliar o desempenho do funil |

### 9.5. Política de correção

Quando um problema for encontrado:

1. Identifique a origem do erro;
2. Corrija os registros afetados;
3. Verifique se há outros casos semelhantes;
4. Oriente os usuários envolvidos;
5. Atualize a documentação, se necessário;
6. Monitore o indicador novamente.

---

<a id="portugues-br-secao-10"></a>
## 10. Indicadores e relatórios

Os relatórios devem responder perguntas de negócio, e não apenas apresentar números.

### 10.1. Perguntas que o CRM deve responder

- Quantos leads entraram no período?
- Quais canais geram leads mais qualificados?
- Quantas oportunidades estão abertas?
- Qual é o valor total do pipeline?
- Quanto tempo as oportunidades permanecem em cada etapa?
- Quais negócios estão atrasados?
- Qual é a taxa de conversão por etapa?
- Quais são os principais motivos de perda?
- Qual é o ciclo médio de vendas?
- Quais clientes estão sem interação recente?
- Qual é a previsão de receita?

### 10.2. Indicadores comerciais essenciais

| Indicador | O que mostra |
|---|---|
| **Leads recebidos** | Volume de novos potenciais clientes |
| **Leads qualificados** | Quantidade de leads com perfil e necessidade identificados |
| **Taxa de qualificação** | Percentual de leads que se tornam oportunidades ou são aprovados |
| **Oportunidades abertas** | Volume de negociações em andamento |
| **Pipeline** | Soma dos valores das oportunidades abertas |
| **Pipeline ponderado** | Valor das oportunidades ajustado pela probabilidade de fechamento |
| **Taxa de conversão** | Percentual de oportunidades que avançam ou são ganhas |
| **Ciclo de vendas** | Tempo médio entre entrada e fechamento |
| **Ticket médio** | Valor médio das vendas |
| **Taxa de ganho** | Percentual de oportunidades fechadas como ganhas |
| **Motivos de perda** | Principais causas de não conversão |
| **Receita realizada** | Valor efetivamente vendido ou recebido |

### 10.3. Relatórios compreensíveis

Todo relatório deve apresentar:

- Nome claro;
- Objetivo;
- Período analisado;
- Fonte dos dados;
- Definição dos indicadores;
- Filtros aplicados;
- Data da última atualização;
- Responsável pela manutenção;
- Observações sobre limitações.

### 10.4. Evite excesso de dashboards

É melhor ter poucos painéis úteis do que muitos painéis que ninguém consulta.

Uma estrutura recomendada:

- **Dashboard executivo:** visão geral de receita, pipeline e conversão;
- **Dashboard comercial:** atividades, oportunidades e previsão;
- **Dashboard de marketing:** origem, campanhas e qualidade dos leads;
- **Dashboard de atendimento:** volume, prazo e satisfação;
- **Dashboard de qualidade:** completude, duplicidade e atualização dos dados.

### 10.5. Definições precisam ser consistentes

Antes de divulgar um indicador, documente sua fórmula.

Exemplo:

> **Taxa de conversão de oportunidades:** oportunidades fechadas como ganhas divididas pelo total de oportunidades encerradas no período, excluindo oportunidades canceladas por erro de cadastro.

Sem uma definição, duas equipes podem calcular o mesmo indicador de maneiras diferentes.

---

<a id="portugues-br-secao-11"></a>
## 11. Perfis de acesso e responsabilidades

### 11.1. Acesso por função

O usuário deve ter acesso às informações necessárias para realizar seu trabalho, respeitando as regras de segurança e privacidade.

Exemplo de perfis:

| Perfil | Permissões recomendadas |
|---|---|
| **Administrador** | Configurações, usuários, integrações e governança |
| **Gestor comercial** | Visualização da equipe, relatórios e oportunidades da área |
| **Vendedor** | Criação e atualização dos próprios leads, contatos e oportunidades |
| **Marketing** | Leads, campanhas, origem e relatórios de aquisição |
| **Atendimento** | Clientes, contatos, tickets e histórico de relacionamento |
| **Financeiro** | Informações comerciais e financeiras autorizadas |
| **Leitura** | Consulta sem alteração de dados |

### 11.2. Princípio do menor privilégio

Cada usuário deve possuir somente as permissões necessárias para sua função. Isso reduz riscos de alteração indevida, exposição de dados e exclusão acidental.

### 11.3. Responsabilidades por registro

Defina claramente quem é responsável por:

- Criar o registro;
- Atualizar o status;
- Corrigir dados;
- Encerrar oportunidades;
- Validar informações;
- Acompanhar atividades;
- Excluir ou arquivar registros.

### 11.4. Histórico de alterações

Sempre que possível, mantenha o histórico de:

- Usuário que alterou o registro;
- Data e hora da alteração;
- Campo alterado;
- Valor anterior;
- Novo valor.

---

<a id="portugues-br-secao-12"></a>
## 12. Automação e integrações

A automação deve simplificar o processo, não escondê-lo ou torná-lo incompreensível.

### 12.1. Boas aplicações da automação

- Criar leads a partir de formulários;
- Distribuir leads por região ou especialidade;
- Enviar tarefas de acompanhamento;
- Alertar sobre oportunidades paradas;
- Atualizar status após uma ação;
- Notificar gestores sobre negócios relevantes;
- Impedir avanço sem campos essenciais;
- Enviar confirmações e lembretes;
- Sincronizar informações com sistemas autorizados.

### 12.2. Regras para automações

Toda automação deve ter:

- Nome claro;
- Objetivo documentado;
- Gatilho definido;
- Condições de execução;
- Ação realizada;
- Responsável;
- Critério de sucesso;
- Plano de tratamento de erro;
- Registro ou histórico de execução.

### 12.3. Não automatize um processo confuso

Antes de automatizar, verifique se:

1. O processo é conhecido pela equipe;
2. As etapas estão bem definidas;
3. Os campos necessários existem;
4. Os responsáveis estão identificados;
5. As exceções foram consideradas;
6. O resultado pode ser auditado.

### 12.4. Integrações

Integrações devem evitar a criação de múltiplas fontes conflitantes.

Defina para cada informação:

- Qual é o sistema de origem;
- Qual é o sistema de destino;
- Quem pode alterar o dado;
- Com que frequência ocorre a sincronização;
- Como conflitos são resolvidos;
- O que acontece quando a sincronização falha.

---

<a id="portugues-br-secao-13"></a>
## 13. Rotina de utilização do CRM

### 13.1. Rotina diária do usuário

- Verificar atividades do dia;
- Atualizar atividades concluídas;
- Registrar novas interações;
- Conferir oportunidades sem próximo passo;
- Atualizar etapas quando houver mudança real;
- Revisar tarefas atrasadas;
- Registrar decisões e compromissos.

### 13.2. Rotina semanal da equipe

- Revisar o pipeline;
- Identificar oportunidades paradas;
- Conferir previsões de fechamento;
- Avaliar atividades atrasadas;
- Atualizar prioridades;
- Analisar conversões e perdas;
- Corrigir registros críticos.

### 13.3. Rotina mensal de gestão

- Avaliar indicadores do período;
- Comparar resultados com metas;
- Analisar origem e qualidade dos leads;
- Revisar motivos de perda;
- Verificar a qualidade dos dados;
- Avaliar se o funil ainda representa o processo real;
- Identificar necessidade de treinamento;
- Consolidar sugestões de melhoria.

### 13.4. Reuniões baseadas no CRM

As reuniões comerciais e de relacionamento devem utilizar o CRM como fonte principal.

Cada oportunidade discutida deve apresentar:

- Situação atual;
- Valor;
- Etapa;
- Última interação;
- Próximo passo;
- Risco ou impedimento;
- Previsão de fechamento;
- Responsável.

> Se a informação existe apenas em planilhas pessoais, mensagens ou memória dos profissionais, ela ainda não está adequadamente registrada no CRM.

---

<a id="portugues-br-secao-14"></a>
## 14. Erros comuns a evitar

### 14.1. Criar campos sem propósito

Campos que não são utilizados aumentam a complexidade e reduzem a adesão.

### 14.2. Permitir texto livre para tudo

Textos livres dificultam filtros, agrupamentos e relatórios. Use listas controladas quando houver opções conhecidas.

### 14.3. Criar uma etapa para cada situação

O funil deve ser simples. Situações específicas podem ser registradas em campos complementares ou atividades.

### 14.4. Não registrar perdas

Oportunidades perdidas também geram aprendizado. Sem motivo de perda, a empresa não identifica padrões de melhoria.

### 14.5. Manter oportunidades abertas indefinidamente

Crie regras para revisar, requalificar, arquivar ou encerrar oportunidades que estejam paradas por muito tempo.

### 14.6. Usar o CRM apenas para cobrança

O CRM deve ajudar a equipe a trabalhar melhor. Se for utilizado somente como instrumento de controle, os profissionais podem registrar dados de forma superficial.

### 14.7. Alterar regras sem comunicação

Mudanças em campos, etapas ou relatórios devem ser comunicadas, documentadas e acompanhadas de orientação.

### 14.8. Confundir volume com qualidade

Mais registros não significam necessariamente melhores resultados. A empresa deve acompanhar a qualidade, a completude e a utilidade dos dados.

### 14.9. Ignorar privacidade e segurança

Colete apenas os dados necessários, controle acessos e observe as políticas internas e a legislação aplicável, incluindo a LGPD quando houver tratamento de dados pessoais no Brasil.

---

<a id="portugues-br-secao-15"></a>
## 15. Checklist de implementação

### Estrutura

- [ ] Os objetos principais do CRM estão definidos;
- [ ] As relações entre empresa, contato, lead e oportunidade são claras;
- [ ] Não existem campos duplicados ou sem finalidade;
- [ ] Os campos estão agrupados de forma lógica;
- [ ] As descrições dos campos estão disponíveis.

### Funil

- [ ] As etapas representam o processo real;
- [ ] Cada etapa possui critério de entrada e saída;
- [ ] Existe um próximo passo para cada oportunidade aberta;
- [ ] Motivos de perda estão padronizados;
- [ ] Há regras para oportunidades paradas.

### Dados

- [ ] Os campos obrigatórios são realmente necessários;
- [ ] Os formatos de cadastro estão documentados;
- [ ] Listas controladas são utilizadas;
- [ ] Duplicidades são identificadas;
- [ ] Os dados possuem responsável;
- [ ] Existe rotina de auditoria.

### Relatórios

- [ ] Cada indicador possui uma definição;
- [ ] Os relatórios informam período e filtros;
- [ ] A fonte de cada dado é conhecida;
- [ ] Os dashboards respondem a perguntas de negócio;
- [ ] Há poucos relatórios, mas eles são utilizados.

### Pessoas e processos

- [ ] Os perfis de acesso estão definidos;
- [ ] As responsabilidades estão claras;
- [ ] Os usuários receberam treinamento;
- [ ] Existe um canal para dúvidas e sugestões;
- [ ] Mudanças no CRM são comunicadas;
- [ ] O uso do CRM é incorporado às reuniões e rotinas.

### Automação e segurança

- [ ] As automações possuem documentação;
- [ ] Integrações têm sistemas de origem e destino definidos;
- [ ] Falhas de sincronização são monitoradas;
- [ ] O histórico de alterações está disponível;
- [ ] Os acessos respeitam o princípio do menor privilégio;
- [ ] As regras de privacidade são observadas.

---

<a id="portugues-br-secao-16"></a>
## 16. Conclusão

Um CRM compreensível e confiável depende menos da quantidade de funcionalidades e mais da qualidade da estrutura, das regras e dos hábitos da equipe.

As melhores práticas podem ser resumidas em sete pontos:

1. **Defina o propósito de cada informação.**
2. **Padronize nomes, campos, etapas e valores.**
3. **Registre fatos, decisões e próximos passos.**
4. **Mantenha os dados atualizados e sem duplicidades.**
5. **Use indicadores com fórmulas e definições claras.**
6. **Atribua responsabilidades e controle acessos.**
7. **Revise continuamente o processo com base no uso real.**

> Um CRM bem utilizado não é apenas um banco de dados. É a memória operacional da empresa e uma ferramenta para transformar informações em decisões melhores.

---

**Versão:** 1.0  
**Finalidade:** Padronização de estrutura, uso e interpretação de dados em CRM.  
**Revisão recomendada:** A cada seis meses ou sempre que houver mudança relevante no processo comercial, de atendimento ou de marketing.

---

<a id="espanol-es"></a>

## 🇪🇸 Español ES

[↩ Volver a la selección de idioma](#selecao-de-idioma)

# Buenas Prácticas para Estructurar y Usar un CRM

> Guía práctica para volver el CRM comprensible, estandarizado y útil para la toma de decisiones.

---

## 📑 Índice

1. [Objetivo del CRM](#espanol-es-secao-1)
2. [Principios fundamentales](#espanol-es-secao-2)
3. [Estructura básica del CRM](#espanol-es-secao-3)
4. [Estandarización de registros](#espanol-es-secao-4)
5. [Definición del embudo de ventas](#espanol-es-secao-5)
6. [Reglas para el llenado de los datos](#espanol-es-secao-6)
7. [Nomenclatura y organización de los campos](#espanol-es-secao-7)
8. [Gestión de actividades e interacciones](#espanol-es-secao-8)
9. [Calidad y gobernanza de los datos](#espanol-es-secao-9)
10. [Indicadores e informes](#espanol-es-secao-10)
11. [Perfiles de acceso y responsabilidades](#espanol-es-secao-11)
12. [Automatización e integraciones](#espanol-es-secao-12)
13. [Rutina de uso del CRM](#espanol-es-secao-13)
14. [Errores comunes a evitar](#espanol-es-secao-14)
15. [Checklist de implementación](#espanol-es-secao-15)
16. [Conclusión](#espanol-es-secao-16)

---

<a id="espanol-es-secao-1"></a>
## 1. Objetivo del CRM

Un CRM — *Customer Relationship Management*, o Gestión de la Relación con el Cliente — debe ser más que un lugar para almacenar contactos. Necesita funcionar como una **fuente confiable de información sobre clientes, oportunidades, interacciones y resultados comerciales**.

Un CRM bien estructurado debe permitir que la empresa:

- Sepa quiénes son sus clientes y potenciales clientes;
- Entienda en qué etapa se encuentra cada oportunidad;
- Identifique el próximo paso de cada negociación;
- Registre el historial de contactos y decisiones;
- Evite la pérdida de información cuando un profesional cambia de función;
- Acompañe la productividad y los resultados del equipo;
- Genere informes consistentes para apoyar decisiones;
- Reduzca tareas manuales y retrabajo;
- Mejore la experiencia del cliente.

> **Regla principal:** cualquier profesional autorizado debe poder abrir un registro en el CRM y comprender rápidamente su contexto, su historial y su situación actual.

---

<a id="espanol-es-secao-2"></a>
## 2. Principios fundamentales

### 2.1. Claridad antes que complejidad

El CRM debe presentar solo la información necesaria para cada proceso. El exceso de campos, pantallas y opciones aumenta la dificultad de uso y reduce la calidad de los datos.

Antes de crear un campo, pregunte:

1. ¿Se utilizará esta información?
2. ¿Quién la necesita?
3. ¿Qué decisión ayuda a tomar?
4. ¿Puede obtenerse automáticamente?
5. ¿Es realmente distinta de otro campo ya existente?

Si la respuesta no es clara, probablemente el campo no deba crearse.

### 2.2. Estandarización

Todos los profesionales deben registrar información siguiendo las mismas reglas. La estandarización permite comparar registros, crear filtros confiables y generar informes consistentes.

Ejemplos de elementos que deben estandarizarse:

- Nombres de empresas y contactos;
- Teléfonos y correos electrónicos;
- Segmentos de clientes;
- Origen de los leads;
- Etapas del embudo;
- Motivos de pérdida;
- Tipos de actividad;
- Formatos de fechas y valores;
- Responsables de los registros.

### 2.3. Actualización continua

Un CRM desactualizado pierde valor rápidamente. Cada interacción relevante debe generar una actualización en el registro correspondiente.

El CRM debe responder, en cualquier momento:

- ¿Qué ocurrió recientemente?
- ¿Cuál es el estado actual?
- ¿Quién es el responsable?
- ¿Cuál es el próximo paso?
- ¿Cuándo debe ocurrir la próxima acción?

### 2.4. Responsabilidad compartida

La calidad del CRM no es responsabilidad solo del área de tecnología, marketing u operaciones. Cada usuario debe ser responsable de la calidad de los datos que crea o modifica.

### 2.5. Registro basado en hechos

Los datos deben reflejar sucesos reales, y no percepciones vagas.

Evite registrar:

- “Cliente interesado” sin explicar el motivo;
- “Regresar pronto” sin fecha definida;
- “Está casi cerrado” sin evidencia concreta;
- “Sin respuesta” sin informar los canales y los intentos realizados.

Prefiera registros objetivos, como:

> “Cliente confirmó interés en el plan Premium y solicitó propuesta hasta el 15/10. Próximo contacto agendado para el 17/10 por teléfono.”

---

<a id="espanol-es-secao-3"></a>
## 3. Estructura básica del CRM

La estructura puede variar según la plataforma, pero normalmente involucra los siguientes objetos o entidades:

| Entidad | Qué representa | Ejemplos de información |
|---|---|---|
| **Empresa/Cuenta** | Organización o empresa relacionada con la negociación | Nombre, segmento, tamaño, ciudad, sitio web |
| **Contacto** | Persona que trabaja o se relaciona con la empresa | Nombre, cargo, correo electrónico, teléfono, perfil |
| **Lead** | Persona o empresa que aún debe ser cualificada | Origen, interés, canal, estado |
| **Oportunidad/Negocio** | Posibilidad concreta de venta | Valor, etapa, probabilidad, previsión de cierre |
| **Actividad** | Interacción o tarea realizada/planificada | Llamada, reunión, correo, visita, tarea |
| **Producto/Servicio** | Ítem que puede venderse | Nombre, categoría, precio, margen |
| **Campaña** | Acción responsable de generar o influenciar contactos | Nombre, canal, periodo, inversión |
| **Ticket/Solicitud** | Demanda de atención o soporte | Categoría, prioridad, estado, solución |

### 3.1. Relación entre los registros

La relación entre los objetos debe ser lógica y fácil de entender. Un ejemplo de estructura es:

```text
Empresa
├── Contactos
├── Oportunidades
│   ├── Actividades
│   ├── Productos o servicios
│   └── Propuestas
├── Tickets de atención
└── Historial de interacciones
```

### 3.2. Evite la duplicidad de información

Una información debe registrarse en un único lugar siempre que sea posible.

Por ejemplo:

- El segmento de la empresa debe quedar en el registro de la empresa, no repetido manualmente en cada oportunidad;
- El cargo del contacto debe quedar en el contacto, no solo en una anotación;
- El valor del negocio debe quedar en el registro de la oportunidad, no solamente en el historial de actividades.

Esto reduce divergencias y facilita el mantenimiento de los datos.

---

<a id="espanol-es-secao-4"></a>
## 4. Estandarización de registros

### 4.1. Registro de empresas

Defina previamente qué datos son obligatorios para crear una empresa.

Campos recomendados:

- Razón social o nombre oficial;
- Nombre comercial, cuando aplique;
- CNPJ u identificador empresarial;
- Sitio web;
- Segmento de actividad;
- Tamaño de la empresa;
- Ciudad y estado;
- País;
- Número estimado de empleados;
- Estado de la relación;
- Responsable de la cuenta;
- Origen del registro.

### 4.2. Registro de contactos

Campos recomendados:

- Nombre completo;
- Cargo o función;
- Departamento;
- Correo corporativo;
- Teléfono o móvil;
- Empresa relacionada;
- Papel en la decisión de compra;
- Preferencia de contacto;
- Consentimiento de comunicación, cuando aplique;
- Estado del contacto.

### 4.3. Registro de leads

El lead debe contener información suficiente para permitir la cualificación inicial.

Campos recomendados:

- Nombre;
- Empresa;
- Canal de origen;
- Campaña de origen;
- Producto o servicio de interés;
- Región;
- Perfil o segmento;
- Fecha de entrada;
- Responsable;
- Estado de cualificación;
- Última interacción;
- Próximo paso.

### 4.4. Identificación de duplicidades

Antes de crear un registro, el usuario debe buscar si la empresa, el contacto o el lead ya existe.

Utilice criterios como:

- CNPJ u identificador fiscal;
- Correo electrónico;
- Dominio del sitio web;
- Teléfono;
- Nombre de la empresa;
- Nombre completo del contacto.

> **Buena práctica:** si hay duda, actualice el registro existente en lugar de crear uno nuevo.

### 4.5. Formatos recomendados

| Ítem | Estándar recomendado | Ejemplo |
|---|---|---|
| Nombre de empresa | Nombre oficial o nombre comercial definido | Empresa Ejemplo Ltda. |
| Teléfono | Código del país + DDD + número | +55 11 99999-9999 |
| Fecha | Formato único definido por la empresa | 15/10/2026 |
| Moneda | Moneda explícita en el campo o informe | R$ 25.000,00 |
| Correo electrónico | Letras minúsculas y sin espacios | contato@empresa.com.br |
| Estado | Sigla oficial | SP |
| País | Nombre estandarizado o código definido | Brasil |

---

<a id="espanol-es-secao-5"></a>
## 5. Definición del embudo de ventas

El embudo debe representar el proceso real de la empresa, y no una lista genérica de etapas.

### 5.1. Ejemplo de etapas

| Etapa | Definición | Criterio para entrar | Criterio para salir |
|---|---|---|---|
| **Lead recibido** | Nuevo contacto captado | Lead creado en el CRM | Datos mínimos verificados |
| **Cualificación** | Verificación de perfil y necesidad | Contacto con potencial | Necesidad y adecuación confirmadas |
| **Diagnóstico** | Entendimiento del problema del cliente | Reunión o conversación iniciada | Problema, urgencia y participantes identificados |
| **Solución presentada** | Producto o servicio presentado | Necesidad mapeada | Cliente recibió la solución adecuada |
| **Propuesta enviada** | Propuesta comercial enviada | Valor y alcance definidos | Cliente confirmó recepción y evaluación |
| **Negociación** | Discusión de precio, plazo o condiciones | Propuesta en evaluación | Acuerdo alcanzado o negociación cerrada |
| **Cerrado ganado** | Venta concluida | Cliente aceptó y formalizó | Pedido, contrato o pago registrado |
| **Cerrado perdido** | Oportunidad cerrada sin venta | Motivo de pérdida conocido | Registro finalizado y clasificado |

### 5.2. Reglas para una buena etapa

Cada etapa debe tener:

- Nombre corto y comprensible;
- Descripción objetiva;
- Criterio de entrada;
- Criterio de salida;
- Responsable principal;
- Acciones esperadas;
- Tiempo máximo recomendado;
- Indicador asociado.

### 5.3. No confunda etapa con actividad

La **etapa** representa el estado de la oportunidad.

La **actividad** representa una acción realizada o planificada.

Ejemplo:

- Etapa: **Propuesta enviada**;
- Actividad: **Llamar al cliente el 17/10 para confirmar dudas**.

Una oportunidad no debe permanecer parada en una etapa sin un próximo paso definido.

### 5.4. Motivos de pérdida

El motivo de pérdida debe ser obligatorio al cerrar una oportunidad como perdida.

Use una lista estandarizada, por ejemplo:

- Precio por encima del presupuesto;
- Cliente eligió al competidor;
- Falta de prioridad;
- Sin presupuesto disponible;
- Plazo incompatible;
- Solución sin adecuación;
- Contacto no respondió;
- Proyecto cancelado;
- Datos insuficientes;
- Otro — con justificación obligatoria.

Evite el motivo genérico “otros” sin una descripción complementaria.

---

<a id="espanol-es-secao-6"></a>
## 6. Reglas para el llenado de los datos

### 6.1. Campos obligatorios y opcionales

Un campo debe ser obligatorio solo cuando su ausencia impida el proceso o perjudique significativamente el análisis.

**Campos generalmente obligatorios:**

- Nombre del registro;
- Responsable;
- Origen;
- Etapa o estado;
- Próximo paso;
- Fecha prevista de la próxima acción;
- Valor, cuando se trate de oportunidad;
- Motivo de pérdida, cuando aplique.

**Campos generalmente opcionales:**

- Información que aún no está disponible;
- Datos que pueden enriquecerse posteriormente;
- Observaciones complementarias.

### 6.2. Use listas controladas

Siempre que sea posible, utilice listas desplegables, casillas de selección y campos estandarizados en lugar de campos de texto libre.

Prefiera:

- `Industria`
- `Retail`
- `Servicios`
- `Tecnología`

En lugar de permitir variaciones como:

- “Industria”;
- “industrial”;
- “Ind.”;
- “sector industrial”.

### 6.3. Escriba observaciones con contexto

Una buena anotación debe informar:

1. Fecha o periodo de la interacción;
2. Persona involucrada;
3. Asunto tratado;
4. Resultado;
5. Próximo paso;
6. Responsable del próximo paso;
7. Plazo.

**Modelo recomendado:**

```text
[FECHA] — [TIPO DE INTERACCIÓN]
Participantes: [nombres y cargos]
Asunto: [tema principal]
Resumen: [principales puntos discutidos]
Resultado: [decisión o situación actual]
Próximo paso: [acción objetiva]
Responsable: [nombre]
Plazo: [fecha]
```

**Ejemplo:**

```text
15/10/2026 — Reunión de diagnóstico
Participantes: Ana Souza — Cliente; Carlos Lima — Comercial
Asunto: Necesidad de automatización de la atención
Resumen: El cliente recibe aproximadamente 2.000 solicitudes mensuales y tiene dificultad para seguir los plazos.
Resultado: Mostró interés en evaluar la solución de atención integrada.
Próximo paso: Enviar propuesta con los módulos Atención e Informes.
Responsable: Carlos Lima
Plazo: 18/10/2026
```

### 6.4. Evite abreviaciones desconocidas

Use abreviaciones solo cuando sean conocidas por todo el equipo y estén documentadas en un glosario.

Evite anotaciones como:

> “Hablé c/ el decisor, budget ok, esperando retorno del jurídico.”

Prefiera:

> “Hablé con la persona responsable de la decisión. El presupuesto fue aprobado y la propuesta está en análisis por el departamento jurídico.”

---

<a id="espanol-es-secao-7"></a>
## 7. Nomenclatura y organización de los campos

### 7.1. Nombres claros

El nombre de un campo debe permitir que el usuario comprenda su significado sin necesidad de consultar a otra persona.

Prefiera:

- `Fecha prevista de cierre`;
- `Origen del lead`;
- `Motivo de pérdida`;
- `Responsable de la oportunidad`.

Evite:

- `Fecha 2`;
- `Orig.`;
- `Tipo A`;
- `Flag comercial`.

### 7.2. Descripciones y ejemplos

Los campos que pueden generar duda deben contener una descripción o ejemplo.

Ejemplo:

> **Probabilidad de cierre:** porcentaje estimado de conclusión de la oportunidad, basado en la etapa del embudo y en las evidencias disponibles.

### 7.3. Agrupamiento lógico

Organice los campos por bloques:

1. Identificación;
2. Contacto;
3. Cualificación;
4. Datos comerciales;
5. Relación;
6. Operación;
7. Consentimiento y privacidad;
8. Auditoría e historial.

### 7.4. Evite campos redundantes

No cree campos con significados similares sin documentar la diferencia.

Ejemplo de posible confusión:

- `Estado del lead`;
- `Situación del lead`;
- `Fase del contacto`;
- `Clasificación comercial`.

Si todos significan prácticamente lo mismo, mantenga solo un campo o defina claramente la función de cada uno.

### 7.5. Campos derivados

Siempre que sea posible, calcule automáticamente información derivada de otros campos.

Ejemplos:

- Edad de la oportunidad;
- Días desde la última interacción;
- Rango de valor;
- Porcentaje de conversión;
- Tiempo en cada etapa;
- Clasificación de prioridad.

Esto reduce errores de llenado manual.

---

<a id="espanol-es-secao-8"></a>
## 8. Gestión de actividades e interacciones

### 8.1. Toda oportunidad debe tener un próximo paso

El campo **próximo paso** debe ser objetivo y accionable.

Evite:

- “Acompañar”;
- “Ver después”;
- “Regresar”;
- “En negociación”.

Prefiera:

- “Enviar propuesta revisada hasta el 18/10”;
- “Llamar a Ana el 20/10 a las 10h”;
- “Solicitar aprobación del descuento al gerente”;
- “Agendar demostración con el equipo técnico”.

### 8.2. Registre actividades en el momento adecuado

Las actividades deben registrarse:

- Antes de la acción, cuando sean tareas planificadas;
- Poco después de la acción, cuando representen una interacción concluida;
- Con fecha, responsable y resultado.

### 8.3. Tipos de actividad estandarizados

Cree una lista simple y consistente:

- Llamada;
- Correo;
- Reunión;
- Videoconferencia;
- Demostración;
- Visita;
- Mensaje;
- Tarea interna;
- Propuesta enviada;
- Contrato enviado;
- Atención realizada.

### 8.4. Actividades futuras y vencidas

El equipo debe acompañar regularmente:

- Actividades vencidas;
- Actividades previstas para el día;
- Actividades de la semana;
- Oportunidades sin actividad futura;
- Oportunidades sin interacción reciente.

Una oportunidad sin actividad futura debe considerarse una señal de riesgo.

---

<a id="espanol-es-secao-9"></a>
## 9. Calidad y gobernanza de los datos

### 9.1. Defina un responsable del CRM

La empresa debe indicar al menos un responsable para:

- Mantener estándares y reglas;
- Evaluar solicitudes de nuevos campos;
- Eliminar o consolidar información duplicada;
- Acompañar la calidad de los datos;
- Capacitar usuarios;
- Documentar cambios;
- Coordinar revisiones periódicas.

### 9.2. Cree un diccionario de datos

El diccionario de datos debe explicar los principales campos del CRM.

| Campo | Definición | Tipo | ¿Obligatorio? | Valores permitidos | Responsable |
|---|---|---|---|---|---|
| Origen del lead | Canal que generó el primer contacto | Lista | Sí | Sitio web, recomendación, evento, medios pagados, prospección | Marketing |
| Etapa | Estado actual de la oportunidad | Lista | Sí | Cualificación, diagnóstico, propuesta, negociación | Comercial |
| Motivo de pérdida | Razón principal del cierre sin venta | Lista | Condicional | Precio, competidor, sin presupuesto, sin prioridad | Comercial |
| Fecha prevista de cierre | Fecha estimada para la conclusión | Fecha | Sí | Fecha válida | Comercial |

### 9.3. Auditorías periódicas

Realice verificaciones mensuales o trimestrales para encontrar:

- Registros duplicados;
- Empresas sin contactos;
- Oportunidades sin valor;
- Oportunidades sin próximo paso;
- Leads sin responsable;
- Registros sin origen;
- Fechas de cierre vencidas;
- Oportunidades paradas por mucho tiempo;
- Campos rellenados con valores inválidos;
- Clientes sin actualización reciente.

### 9.4. Indicadores de calidad

| Indicador | Fórmula o criterio | Objetivo |
|---|---|---|
| **Completitud** | Campos rellenados ÷ campos esperados | Medir si los registros poseen información suficiente |
| **Duplicidad** | Registros duplicados ÷ total de registros | Reducir registros repetidos |
| **Actualidad** | Registros actualizados en el periodo ÷ total de registros activos | Identificar datos desactualizados |
| **Adherencia al proceso** | Registros que siguen las reglas ÷ total auditado | Verificar el uso correcto del CRM |
| **Oportunidades con próximo paso** | Oportunidades con acción futura ÷ total de oportunidades abiertas | Evitar negociaciones sin seguimiento |
| **Tasa de conversión** | Oportunidades ganadas ÷ oportunidades cerradas | Evaluar el rendimiento del embudo |

### 9.5. Política de corrección

Cuando se encuentre un problema:

1. Identifique el origen del error;
2. Corrija los registros afectados;
3. Verifique si hay otros casos similares;
4. Oriente a los usuarios involucrados;
5. Actualice la documentación, si es necesario;
6. Monitoree el indicador nuevamente.

---

<a id="espanol-es-secao-10"></a>
## 10. Indicadores e informes

Los informes deben responder preguntas de negocio, y no solo presentar números.

### 10.1. Preguntas que el CRM debe responder

- ¿Cuántos leads entraron en el periodo?
- ¿Qué canales generan leads más cualificados?
- ¿Cuántas oportunidades están abiertas?
- ¿Cuál es el valor total del pipeline?
- ¿Cuánto tiempo permanecen las oportunidades en cada etapa?
- ¿Qué negocios están atrasados?
- ¿Cuál es la tasa de conversión por etapa?
- ¿Cuáles son los principales motivos de pérdida?
- ¿Cuál es el ciclo medio de ventas?
- ¿Qué clientes están sin interacción reciente?
- ¿Cuál es la previsión de ingresos?

### 10.2. Indicadores comerciales esenciales

| Indicador | Qué muestra |
|---|---|
| **Leads recibidos** | Volumen de nuevos potenciales clientes |
| **Leads cualificados** | Cantidad de leads con perfil y necesidad identificados |
| **Tasa de cualificación** | Porcentaje de leads que se convierten en oportunidades o son aprobados |
| **Oportunidades abiertas** | Volumen de negociaciones en curso |
| **Pipeline** | Suma de los valores de las oportunidades abiertas |
| **Pipeline ponderado** | Valor de las oportunidades ajustado por la probabilidad de cierre |
| **Tasa de conversión** | Porcentaje de oportunidades que avanzan o son ganadas |
| **Ciclo de ventas** | Tiempo medio entre entrada y cierre |
| **Ticket medio** | Valor medio de las ventas |
| **Tasa de ganancia** | Porcentaje de oportunidades cerradas como ganadas |
| **Motivos de pérdida** | Principales causas de no conversión |
| **Ingresos realizados** | Valor efectivamente vendido o recibido |

### 10.3. Informes comprensibles

Todo informe debe presentar:

- Nombre claro;
- Objetivo;
- Periodo analizado;
- Fuente de los datos;
- Definición de los indicadores;
- Filtros aplicados;
- Fecha de la última actualización;
- Responsable del mantenimiento;
- Observaciones sobre limitaciones.

### 10.4. Evite exceso de dashboards

Es mejor tener pocos paneles útiles que muchos paneles que nadie consulta.

Una estructura recomendada:

- **Dashboard ejecutivo:** visión general de ingresos, pipeline y conversión;
- **Dashboard comercial:** actividades, oportunidades y previsión;
- **Dashboard de marketing:** origen, campañas y calidad de los leads;
- **Dashboard de atención:** volumen, plazo y satisfacción;
- **Dashboard de calidad:** completitud, duplicidad y actualización de los datos.

### 10.5. Las definiciones deben ser consistentes

Antes de divulgar un indicador, documente su fórmula.

Ejemplo:

> **Tasa de conversión de oportunidades:** oportunidades cerradas como ganadas divididas por el total de oportunidades cerradas en el periodo, excluyendo oportunidades canceladas por error de registro.

Sin una definición, dos equipos pueden calcular el mismo indicador de maneras diferentes.

---

<a id="espanol-es-secao-11"></a>
## 11. Perfiles de acceso y responsabilidades

### 11.1. Acceso por función

El usuario debe tener acceso a la información necesaria para realizar su trabajo, respetando las reglas de seguridad y privacidad.

Ejemplo de perfiles:

| Perfil | Permisos recomendados |
|---|---|
| **Administrador** | Configuraciones, usuarios, integraciones y gobernanza |
| **Gestor comercial** | Visualización del equipo, informes y oportunidades del área |
| **Vendedor** | Creación y actualización de sus propios leads, contactos y oportunidades |
| **Marketing** | Leads, campañas, origen e informes de adquisición |
| **Atención** | Clientes, contactos, tickets e historial de relación |
| **Finanzas** | Información comercial y financiera autorizada |
| **Lectura** | Consulta sin alteración de datos |

### 11.2. Principio del menor privilegio

Cada usuario debe poseer solo los permisos necesarios para su función. Esto reduce riesgos de modificaciones indebidas, exposición de datos y eliminación accidental.

### 11.3. Responsabilidades por registro

Defina claramente quién es responsable de:

- Crear el registro;
- Actualizar el estado;
- Corregir datos;
- Cerrar oportunidades;
- Validar información;
- Acompañar actividades;
- Eliminar o archivar registros.

### 11.4. Historial de cambios

Siempre que sea posible, mantenga el historial de:

- Usuario que modificó el registro;
- Fecha y hora del cambio;
- Campo modificado;
- Valor anterior;
- Nuevo valor.

---

<a id="espanol-es-secao-12"></a>
## 12. Automatización e integraciones

La automatización debe simplificar el proceso, no ocultarlo o volverlo incomprensible.

### 12.1. Buenas aplicaciones de la automatización

- Crear leads a partir de formularios;
- Distribuir leads por región o especialidad;
- Enviar tareas de seguimiento;
- Alertar sobre oportunidades paradas;
- Actualizar estado tras una acción;
- Notificar a gestores sobre negocios relevantes;
- Impedir avance sin campos esenciales;
- Enviar confirmaciones y recordatorios;
- Sincronizar información con sistemas autorizados.

### 12.2. Reglas para automatizaciones

Toda automatización debe tener:

- Nombre claro;
- Objetivo documentado;
- Disparador definido;
- Condiciones de ejecución;
- Acción realizada;
- Responsable;
- Criterio de éxito;
- Plan de tratamiento de error;
- Registro o historial de ejecución.

### 12.3. No automatice un proceso confuso

Antes de automatizar, verifique si:

1. El proceso es conocido por el equipo;
2. Las etapas están bien definidas;
3. Existen los campos necesarios;
4. Están identificados los responsables;
5. Se consideraron las excepciones;
6. El resultado puede auditarse.

### 12.4. Integraciones

Las integraciones deben evitar la creación de múltiples fuentes conflictivas.

Defina para cada información:

- ¿Cuál es el sistema de origen?;
- ¿Cuál es el sistema de destino?;
- ¿Quién puede modificar el dato?;
- ¿Con qué frecuencia ocurre la sincronización?;
- ¿Cómo se resuelven los conflictos?;
- ¿Qué ocurre cuando la sincronización falla?.

---

<a id="espanol-es-secao-13"></a>
## 13. Rutina de uso del CRM

### 13.1. Rutina diaria del usuario

- Verificar actividades del día;
- Actualizar actividades completadas;
- Registrar nuevas interacciones;
- Comprobar oportunidades sin próximo paso;
- Actualizar etapas cuando haya un cambio real;
- Revisar tareas vencidas;
- Registrar decisiones y compromisos.

### 13.2. Rutina semanal del equipo

- Revisar el pipeline;
- Identificar oportunidades paradas;
- Comprobar previsiones de cierre;
- Evaluar actividades vencidas;
- Actualizar prioridades;
- Analizar conversiones y pérdidas;
- Corregir registros críticos.

### 13.3. Rutina mensual de gestión

- Evaluar indicadores del periodo;
- Comparar resultados con metas;
- Analizar origen y calidad de los leads;
- Revisar motivos de pérdida;
- Verificar la calidad de los datos;
- Evaluar si el embudo aún representa el proceso real;
- Identificar necesidad de capacitación;
- Consolidar sugerencias de mejora.

### 13.4. Reuniones basadas en el CRM

Las reuniones comerciales y de relación deben utilizar el CRM como fuente principal.

Cada oportunidad discutida debe presentar:

- Situación actual;
- Valor;
- Etapa;
- Última interacción;
- Próximo paso;
- Riesgo u obstáculo;
- Previsión de cierre;
- Responsable.

> Si la información existe solo en hojas de cálculo personales, mensajes o memoria de los profesionales, aún no está adecuadamente registrada en el CRM.

---

<a id="espanol-es-secao-14"></a>
## 14. Errores comunes a evitar

### 14.1. Crear campos sin propósito

Campos que no se utilizan aumentan la complejidad y reducen la adhesión.

### 14.2. Permitir texto libre para todo

Textos libres dificultan filtros, agrupamientos e informes. Use listas controladas cuando existan opciones conocidas.

### 14.3. Crear una etapa para cada situación

El embudo debe ser simple. Situaciones específicas pueden registrarse en campos complementarios o actividades.

### 14.4. No registrar pérdidas

Las oportunidades perdidas también generan aprendizaje. Sin motivo de pérdida, la empresa no identifica patrones de mejora.

### 14.5. Mantener oportunidades abiertas indefinidamente

Cree reglas para revisar, recalificar, archivar o cerrar oportunidades que estén paradas por mucho tiempo.

### 14.6. Usar el CRM solo para cobranza

El CRM debe ayudar al equipo a trabajar mejor. Si se utiliza únicamente como instrumento de control, los profesionales pueden registrar datos de forma superficial.

### 14.7. Cambiar reglas sin comunicación

Los cambios en campos, etapas o informes deben comunicarse, documentarse y acompañarse de orientación.

### 14.8. Confundir volumen con calidad

Más registros no significan necesariamente mejores resultados. La empresa debe acompañar la calidad, la completitud y la utilidad de los datos.

### 14.9. Ignorar privacidad y seguridad

Recoja solo los datos necesarios, controle accesos y observe las políticas internas y la legislación aplicable, incluida la LGPD cuando haya tratamiento de datos personales en Brasil.

---

<a id="espanol-es-secao-15"></a>
## 15. Checklist de implementación

### Estructura

- [ ] Los objetos principales del CRM están definidos;
- [ ] Las relaciones entre empresa, contacto, lead y oportunidad son claras;
- [ ] No existen campos duplicados o sin finalidad;
- [ ] Los campos están agrupados de forma lógica;
- [ ] Las descripciones de los campos están disponibles.

### Embudo

- [ ] Las etapas representan el proceso real;
- [ ] Cada etapa posee criterio de entrada y salida;
- [ ] Existe un próximo paso para cada oportunidad abierta;
- [ ] Motivos de pérdida están estandarizados;
- [ ] Hay reglas para oportunidades paradas.

### Datos

- [ ] Los campos obligatorios son realmente necesarios;
- [ ] Los formatos de registro están documentados;
- [ ] Se utilizan listas controladas;
- [ ] Se identifican duplicidades;
- [ ] Los datos tienen responsable;
- [ ] Existe rutina de auditoría.

### Informes

- [ ] Cada indicador posee una definición;
- [ ] Los informes informan periodo y filtros;
- [ ] Se conoce la fuente de cada dato;
- [ ] Los dashboards responden a preguntas de negocio;
- [ ] Hay pocos informes, pero se utilizan.

### Personas y procesos

- [ ] Los perfiles de acceso están definidos;
- [ ] Las responsabilidades están claras;
- [ ] Los usuarios recibieron capacitación;
- [ ] Existe un canal para dudas y sugerencias;
- [ ] Los cambios en el CRM son comunicados;
- [ ] El uso del CRM está incorporado a las reuniones y rutinas.

### Automatización y seguridad

- [ ] Las automatizaciones poseen documentación;
- [ ] Las integraciones tienen sistemas de origen y destino definidos;
- [ ] Las fallas de sincronización son monitorizadas;
- [ ] El historial de cambios está disponible;
- [ ] Los accesos respetan el principio del menor privilegio;
- [ ] Se observan las reglas de privacidad.

---

<a id="espanol-es-secao-16"></a>
## 16. Conclusión

Un CRM comprensible y confiable depende menos de la cantidad de funcionalidades y más de la calidad de la estructura, de las reglas y de los hábitos del equipo.

Las mejores prácticas pueden resumirse en siete puntos:

1. **Defina el propósito de cada información.**
2. **Estandarice nombres, campos, etapas y valores.**
3. **Registre hechos, decisiones y próximos pasos.**
4. **Mantenga los datos actualizados y sin duplicidades.**
5. **Use indicadores con fórmulas y definiciones claras.**
6. **Asigne responsabilidades y controle accesos.**
7. **Revise continuamente el proceso con base en el uso real.**

> Un CRM bien utilizado no es solo una base de datos. Es la memoria operacional de la empresa y una herramienta para transformar información en mejores decisiones.

---

**Versión:** 1.0  
**Finalidad:** Estandarización de estructura, uso e interpretación de datos en CRM.  
**Revisión recomendada:** Cada seis meses o siempre que haya un cambio relevante en el proceso comercial, de atención o de marketing.
