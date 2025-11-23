---
layout: post
title: "Ciclo de Vida do Software: Fundamentos das Etapas de Desenvolvimento"
date: 2018-07-02 10:18:00
categories: Engenharia_de_Software
---

#### O Problema da Falta de Processo

Já viu um software crítico falhar em produção porque foi implementado sem análise prévia? Ou sistemas sem documentação que confundem até quem os criou? Esses cenários são comuns quando **etapas fundamentais do desenvolvimento são ignoradas**.

Falhas devem ser descobertas **antes** da entrega. As etapas do ciclo de vida existem justamente para garantir qualidade, atender requisitos e evitar problemas em produção.

Este artigo apresenta as fases clássicas do desenvolvimento de software — base para metodologias modernas e processos organizacionais maduros.

---

#### As Fases do Desenvolvimento de Software

O processo de desenvolvimento segue etapas sistemáticas que garantem qualidade e reduzem riscos:

![tabelaEtapasComuns](https://raw.githubusercontent.com/Tvitor/tvitor.github.io/master/assets/Tabela%201%202018-07-02%2010-48.PNG)

---

#### 1. Especificação de Requisitos

**Objetivo:** Definir **o que** o sistema deve fazer, com o usuário como peça-chave.

#### Coleta de Requisitos
O usuário descreve suas necessidades em **linguagem natural** e diagramas, apresentando como deseja que o sistema funcione.

![Diagrama](https://raw.githubusercontent.com/Tvitor/tvitor.github.io/master/assets/dados%202018-07-02.PNG)

#### Análise de Requisitos
Após a coleta, inicia-se a análise, que envolve:
- Reconhecimento do problema
- Modelagem da solução
- Definição de características **funcionais** e **não funcionais**

#### Requisitos Funcionais vs. Não Funcionais

**Funcionais:** Ações específicas que o sistema deve executar  
*Exemplo:* "Permitir agendamento de consultas por CPF"

**Não Funcionais:** Atributos de qualidade (não são "triviais"!)  
*Exemplo:* "Tempo de resposta < 2 segundos", "Disponibilidade 99.9%", "Conformidade LGPD"

![requisitos](https://raw.githubusercontent.com/Tvitor/tvitor.github.io/master/assets/levantamento%20de%20requisitos%202018-07-02.PNG)

#### Modelagem
Nesta fase, compreendemos:
- Fluxos de informação
- Controle de processos
- Comportamento do sistema

![dados](https://raw.githubusercontent.com/Tvitor/tvitor.github.io/master/assets/dados%202018-07-02.PNG)

#### Documentação de Especificação
Ao final, produz-se o **Documento de Especificação de Requisitos de Software (ERS)**, que pode incluir:
- Especificação funcional (contrato entre cliente e desenvolvedor)
- Manual preliminar do usuário
- Validação dos requisitos pelo usuário

**Artefatos produzidos:**
- Estudo de viabilidade
- Levantamento e análise de requisitos
- Especificação de requisitos
- Validação de requisitos

---

#### 2. Projeto (Design)

**Objetivo:** Definir **como** o sistema será construído.

Nesta fase, desenvolve-se a arquitetura do sistema através de:

**Propriedades Estruturais**
- Organização de módulos e componentes
- Interação entre objetos
- Definição de interfaces

**Propriedades Não Funcionais**
- Capacidade e escalabilidade
- Confiabilidade
- Segurança
- Performance

---

#### 3. Implementação (Codificação)

**Objetivo:** Transformar o design em código funcional.

Esta é a fase onde a linguagem de programação é aplicada. **Documentar o código é essencial** — conhecer diferentes linguagens e suas características pode ser determinante para:
- Desempenho do sistema
- Tempo de desenvolvimento
- Manutenibilidade futura

**Boas práticas:**
- Código limpo e legível
- Comentários em lógicas complexas
- Versionamento (Git)
- Padrões de código (linters, formatters)

---

#### 4. Testes

**Objetivo:** Garantir que o software funciona conforme especificado.

Testes devem começar **cedo** no ciclo de desenvolvimento, revisando especificação, projeto e codificação.

#### Estratégias de Teste

#### **Caixa Preta (Black Box)**
Foca em **requisitos funcionais** do ponto de vista do usuário. Não examina o código interno.

**Técnicas:**
- Testes de caso de uso
- Particionamento de equivalência (dados válidos vs. inválidos)
- Testes baseados em grafo (relacionamentos entre objetos)
- Análise de valor limite
- Tabelas de decisão
- Transições de estado

#### **Caixa Branca (White Box)**
Examina a **estrutura interna** do código e seus componentes.

**Técnicas:**
- Cobertura de código (linhas, branches)
- Teste de fluxo de dados
- Teste de caminho lógico

---

#### 5. Manutenção

**Objetivo:** Manter o software funcional e relevante após a entrega.

Todo software precisa de **mudanças contínuas** para não se tornar obsoleto. A manutenção envolve ações preventivas e corretivas.

#### Tipos de Manutenção

![tabelaManutencao](https://raw.githubusercontent.com/Tvitor/tvitor.github.io/master/assets/Tabela%202%202018-07-02%2010-48.PNG)

**Corretiva:** Corrigir defeitos descobertos  
**Adaptativa:** Ajustar a mudanças no ambiente (APIs, regulamentações)  
**Perfectiva:** Melhorar desempenho ou usabilidade  
**Preventiva:** Refatorar código para evitar problemas futuros

---

#### 6. Documentação

**Objetivo:** Facilitar manutenção e suporte técnico.

Uma documentação completa, preenchida em **todas as fases**, garante:
- Manutenção eficiente
- Atendimento eficaz do suporte
- Transferência de conhecimento

#### Tipos de Documentação

**Documentação de Usuário**
- Manuais de uso
- Tutoriais
- FAQs

**Documentação Técnica**
- Fluxogramas
- Código-fonte comentado
- Processos e regras de negócio
- Arquitetura do sistema

#### Documentação em Metodologias Ágeis

Na modelagem ágil, **documente apenas o necessário**:
- A documentação deve ter **mais benefício que custo**
- Foco em documentação eficiente e econômica
- Energia da equipe voltada para entregar valor

**Princípio:** O benefício de criar e manter a documentação deve ser **maior** que o esforço necessário.

---

#### Conclusão

As etapas do desenvolvimento de software (especificação → projeto → implementação → testes → manutenção → documentação) são **fundamentais** para:

✅ Garantir qualidade  
✅ Reduzir riscos  
✅ Atender requisitos do cliente  
✅ Facilitar manutenção  
✅ Permitir evolução do sistema  

Entender esses processos é essencial para construir e manter software de qualidade, independentemente da metodologia escolhida (cascata, ágil, DevOps).

---

**Referências:**
- Pressman, R. *Engenharia de Software*. McGraw-Hill.
- Sommerville, I. *Software Engineering*. Pearson.
- IEEE Std 830. *Recommended Practice for Software Requirements Specifications*.

**Tags:** #EngenhariaDeSoftware #CicloDeVida #Requisitos #Testes #Manutenção