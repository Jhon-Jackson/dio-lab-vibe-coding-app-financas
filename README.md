# 💸 App de Finanças Pessoais do Jackson com Vibe Coding

PRD Refinado no Copilot WEb:

```
# Documento de Requisitos de Produto (PRD)

## Contexto
Criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
O diferencial é reduzir fricção e aumentar engajamento por meio de linguagem natural e recomendações personalizadas.

## Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Além disso, os aplicativos existentes muitas vezes não se adaptam ao perfil do usuário (ex.: estudante, trabalhador CLT, autônomo).  
A solução proposta busca resolver isso com uma experiência de conversa e recomendações automáticas de economia.

## Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.  
Também inclui usuários que já tentaram outros apps e desistiram por complexidade.

## Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural (com possibilidade futura de entrada por voz).  
2. Classificar automaticamente as transações em categorias simples (alimentação, transporte, lazer).  
3. Definir e acompanhar metas financeiras básicas (ex.: poupar R$100/mês).  
4. Receber dicas de economia do “Agente Financeiro”, com linguagem amigável e eventualmente gamificada.  
5. Visualizar relatórios simples e personalizados, com gráficos minimalistas e insights rápidos.

## Design Universal
O MVP deve ser desenvolvido seguindo os princípios de **Design Universal**, garantindo que o aplicativo ofereça uma experiência inclusiva e acessível para o maior número possível de usuários, independentemente de suas condições físicas, cognitivas ou culturais.

### Conceito de Design Universal
Design Universal é a abordagem de criação de produtos que busca garantir que o maior número possível de pessoas consiga usar e ter uma boa experiência, independentemente de idade, nível de habilidade, condição física ou contexto cultural.  
Em termos simples: projetar para todos, desde o início, sem precisar de adaptações posteriores.

### Princípios básicos
1. Uso equitativo – útil e acessível para diferentes capacidades.  
2. Flexibilidade no uso – permitir várias formas de interação (texto, voz, toques simples).  
3. Uso simples e intuitivo – fácil de entender, mesmo para iniciantes.  
4. Informação perceptível – dados claros, com alternativas visuais e textuais.  
5. Tolerância ao erro – minimizar riscos de ações incorretas.  
6. Baixo esforço físico – interação sem exigir movimentos complexos.  
7. Tamanho e espaço apropriados – interfaces adaptáveis a diferentes dispositivos.

## MVP – Plano de Entregáveis

### Telas Principais
- Tela de Conversa: chat com o “Agente Financeiro”.  
- Tela de Metas: definir e acompanhar objetivos.  
- Tela de Relatórios: visão geral de gastos por categoria.  
- Tela de Configurações: perfil do usuário e preferências.

### Recursos Necessários
- Processamento de linguagem natural (NLP) para entender entradas de texto.  
- Motor de categorização automática (regras simples + IA básica).  
- Banco de dados local/nuvem para armazenar transações.  
- Módulo de relatórios com gráficos simples e acessíveis.  
- Agente Financeiro com mensagens educativas e dicas.

### Validação Inicial
- Teste com 10–20 usuários reais para avaliar:  
  - Facilidade de registrar gastos.  
  - Clareza dos relatórios.  
  - Utilidade das dicas.  
- Métricas de sucesso:  
  - % de usuários que registram gastos por mais de 7 dias seguidos.  
  - Feedback positivo sobre simplicidade.  
  - Engajamento com metas (quantos definem e acompanham).

## Tom Educativo
O app deve falar com o usuário de forma amigável e acessível, como um amigo que ajuda a economizar.  

Exemplo de interação:
Usuário: Gastei 25 reais no almoço hoje.  
Agente Financeiro: Anotado! Esse gasto vai para a categoria "Alimentação".  
Dica: Se você levar marmita 2 vezes por semana, pode economizar até R$200 por mês!

```

Interações com Lovable:
>>Crie um App de finanças pessoais com base no seguinte PRD: Documento de Requisitos de Produto (PRD)
>>corrija o aplicativo, adicionando tela de loguin, aba com possibilidade organizar renda e despesas e metas de poupanças
>>chat nao esta funcioando, nao estar registando nada,
>>consegui fazer loguin porem na aba chat o chat nao entendi quando digo com oque agstei (Não entendi muito bem 🤔. Tente me dizer um gasto, como:
"Gastei 25 reais no almoço"
Ou me peça ajuda digitando "ajuda"!)

Resultado final no lovable:https://lovable.dev/projects/7a48d6e5-5dfe-4309-aa45-02f92e5ec22a

<img width="3840" height="1085" alt="image" src="https://github.com/user-attachments/assets/820fcc02-6cc7-47bf-bc3a-a6ed96277dd1" />

# Funções do Aplicativo de Finanças Pessoais

## Registro de Transações
- Permite registrar gastos e receitas diretamente via chat em linguagem natural.  
- Reconhece valores mesmo com variações de escrita (ex.: "R$", "reais", números soltos).

## Classificação Automática
- As transações são categorizadas automaticamente em grupos simples (alimentação, aluguel, energia, transporte).  
- Reduz a necessidade de entrada manual detalhada.

## Relatórios e Painel
- Dashboard com resumo de **Receitas**, **Despesas** e **Saldo**.  
- Lista de transações recentes com valores positivos e negativos.  
- Relatórios simples e personalizados para dar clareza ao usuário.

## Metas e Orçamento
- Abas específicas para **Orçamento** e **Metas**.  
- Usuário pode definir objetivos financeiros (ex.: poupar um valor mensal).  
- Acompanhamento do progresso em relação às metas.

## Agente Financeiro
- Interação em tom educativo e acessível, oferecendo dicas de economia.  
- Exemplo: sugerir alternativas para reduzir gastos recorrentes.

## Design Universal
- O aplicativo segue os princípios de **Design Universal**, garantindo acessibilidade e inclusão.  
- Interface clara e simples, múltiplas formas de interação (texto, voz), relatórios visuais com contraste adequado e alternativas em texto.  
- Foco em usabilidade para iniciantes e pessoas com diferentes perfis.

## Reflexão
  ### O que funcionou bem?  
        Apesquisa no copilot e a interação com lovable foi bem intuitivo, mesmo com algumas complicações deu para resolver e criar o app  de um jeito menos complicado.
  ### O que não funcionou como o esperado?  
        Eu esperava que Lovable desenrolasse mais em um prompt pois tive que especificar varias veses oque queria no app.
  ###  O que aprendeu sobre conversar com IAs?  
      Uma otima ferramenta para auxiliar em qualquer coisa que vier fazer. gostei e recomendo.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
