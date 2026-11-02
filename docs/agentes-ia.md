# Desenvolvimento e Experimentação com Agentes de IA — Microsoft Copilot Studio

## 1. Visão geral

Documentação técnica das competências desenvolvidas na criação, configuração e experimentação com agentes de Inteligência Artificial utilizando o Microsoft Copilot Studio.

A experiência compreende configuração de agentes em ambiente de desenvolvimento, utilização de fontes de conhecimento, testes de interpretação documental, geração de respostas e análise de consistência dos resultados.

O objetivo deste documento é apresentar conhecimentos técnicos sobre o funcionamento de agentes de IA e sua possível integração com ferramentas de automação.

## 2. Tecnologias e conceitos

| Tecnologia ou conceito | Aplicação |
|---|---|
| Microsoft Copilot Studio | Criação e configuração de agentes de IA |
| IA generativa | Interpretação de informações e geração de respostas |
| Large Language Models (LLMs) | Modelos de linguagem utilizados por soluções de IA generativa |
| Fontes de conhecimento | Disponibilização de conteúdo para consulta pelo agente |
| Power Automate | Plataforma de automação que pode ser integrada a agentes |
| Microsoft Power Platform | Ecossistema para desenvolvimento de soluções e integrações |
| Prompt Engineering | Estruturação de instruções e definição do comportamento esperado |
| Human-in-the-loop | Validação humana de resultados gerados por IA |

## 3. Criação e configuração de agentes

O Microsoft Copilot Studio permite configurar agentes de IA para interagir com usuários, utilizar fontes de conhecimento e executar ações, conforme as capacidades habilitadas no ambiente.

As atividades de desenvolvimento e experimentação envolveram:

- Criação de agente em ambiente de desenvolvimento.
- Definição de instruções e objetivos de funcionamento.
- Configuração e utilização de recursos de IA generativa.
- Experimentação com fontes de conhecimento.
- Execução de testes de interação.
- Avaliação das respostas produzidas.
- Identificação de ajustes necessários para melhorar a consistência dos resultados.

A criação e os testes iniciais de um agente não significam que ele esteja publicado ou disponível em produção.

## 4. Fontes de conhecimento

Fontes de conhecimento permitem disponibilizar informações para que o agente produza respostas contextualizadas.

Entre os conceitos técnicos envolvidos estão:

- Organização das informações fornecidas ao agente.
- Seleção de conteúdos relevantes.
- Interpretação de documentos.
- Identificação de informações presentes ou ausentes.
- Avaliação da correspondência entre a fonte e a resposta gerada.

### Limitações

A utilização de fontes de conhecimento não garante que todas as respostas sejam corretas.

O agente pode interpretar informações de maneira incompleta, produzir respostas imprecisas ou apresentar conteúdo sem suporte suficiente nas fontes consultadas.

Por isso, a avaliação dos resultados é uma etapa importante do desenvolvimento.

## 5. Engenharia de prompts

A engenharia de prompts envolve a elaboração de instruções que orientam o comportamento de modelos de linguagem.

Alguns princípios relevantes incluem:

**Definição de objetivo:** estabelecer a finalidade da interação.

**Contextualização:** fornecer informações necessárias para a interpretação da solicitação.

**Delimitação de escopo:** indicar quais tarefas o agente deve executar e quais estão fora de suas responsabilidades.

**Formato de resposta:** definir uma estrutura esperada para a saída.

**Tratamento de informações ausentes:** orientar o agente a indicar quando não possui dados suficientes.

**Validação:** verificar se a resposta corresponde às instruções e às informações disponíveis.

Esses princípios contribuem para tornar os testes mais organizados e facilitar a identificação de comportamentos inesperados.

## 6. Experimentação com interpretação documental

Os testes realizados envolveram a utilização de um agente de IA para interpretar conteúdo documental e produzir uma saída textual preliminar.

A experimentação permitiu observar aspectos relacionados a:

- Interpretação de informações fornecidas.
- Organização do conteúdo gerado.
- Identificação de possíveis inconsistências.
- Avaliação da completude das respostas.
- Necessidade de ajustes nas instruções.
- Importância da revisão humana.

A geração de uma resposta preliminar demonstra o funcionamento inicial do agente, mas não comprova a precisão de todas as informações produzidas.

## 7. Integração conceitual com automação

O Copilot Studio pode ser utilizado em conjunto com ferramentas de automação, dependendo das funcionalidades e permissões disponíveis.

Uma arquitetura conceitual pode envolver:

1. Recebimento de uma solicitação.
2. Interpretação da entrada pelo agente.
3. Identificação de uma ação necessária.
4. Acionamento de um fluxo de automação configurado.
5. Recebimento do resultado.
6. Apresentação de uma resposta ao usuário.

Esse modelo representa uma possibilidade tecnológica geral, não uma integração específica declarada como concluída.

## 8. Testes e validação de agentes

A avaliação de agentes de IA exige considerar aspectos diferentes dos testes tradicionais de software.

### Testes funcionais

Verificam se o agente responde às solicitações previstas.

### Testes de consistência

Avaliam se respostas produzidas em situações semelhantes permanecem coerentes.

### Testes de aderência às fontes

Verificam se as informações apresentadas encontram suporte no conteúdo disponibilizado.

### Testes de informações ausentes

Avaliam como o agente se comporta quando os dados fornecidos são insuficientes.

### Revisão humana

Permite identificar problemas de interpretação, informações incorretas e situações que exigem avaliação especializada.

## 9. Desafios técnicos

O
