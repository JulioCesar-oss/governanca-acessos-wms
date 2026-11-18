# Governança de Acessos e Arquitetura de Permissões em WMS (Supply Chain)

## 🎯 Visão Geral do Projeto
Este projeto aborda a reestruturação completa da **gestão de acessos e permissões** no sistema WMS (Bluesoft) do Centro de Distribuição (CD 801). Após a fase de implantação, identificou-se um cenário crítico de perfis homogêneos e irrestritos, onde diferentes cargos operacionais e administrativos compartilhavam o mesmo nível sistêmico. O objetivo foi redesenhar a arquitetura de acessos com base em matriz de responsabilidades, mitigar riscos operacionais, eliminar gargalos e instituir um fluxo de governança contínua.

---

## 🔍 O Problema
No primeiro mês de análise aprofundada dos fluxos do CD, detectou-se uma anomalia sistêmica herdada, possivelmente, de facilidades adotadas durante a implementação inicial do software para acelerar a operação:
* **Perfil Único Indiscriminado:** Separadores, conferentes e analistas operavam com acessos idênticos ou excessivos para suas funções reais.
* **Vícios Operacionais e Quebra de Cadeia de Responsabilidade:** Sem delimitação sistêmica de alçada, funções críticas eram executadas por colaboradores não autorizados, gerando desvios de processo, falta de rastreabilidade e responsabilizações diluídas ("quem faz tudo, não faz nada").
* **Insegurança Sistêmica:** Risco elevado de exclusões, edições indevidas de estoque ou liberações de fluxo sem o devido crivo gerencial.

---

## 🛠️ A Abordagem e Solução

Para resolver o cenário sem travar a operação diária do Centro de Distribuição, o projeto foi estruturado em quatro frentes estratégicas:

1. **Mapeamento e Diagnóstico com Stakeholders:**
   * Alinhamento direto com os responsáveis de cada setor para confrontar o *job description* com a prática sistêmica real.
2. **Desenho da Árvore de Acessos por Cargo:**
   * Criação de uma matriz hierárquica e modular de permissões no WMS, segmentando estritamente o que cada função (Separador, Conferente, Analista) precisa para executar o seu papel — eliminando privilégios desnecessários.
3. **Gestão de Mudança e Tratamento de Ofensores:**
   * Condução da transição para mitigar a resistência inicial à restrição de acessos.
   * Identificação de "ofensores" operacionais, mapeando se a resistência ocorria por déficit de treinamento, falhas de gestão de atividades ou processos mal desenhados.
4. **Governança Contínua (Single Point of Approval):**
   * Implementação de um novo fluxo corporativo: a partir da reestruturação, **qualquer solicitação de inclusão, alteração ou remoção de acesso passou obrigatoriamente por um aceite técnico prévio**, garantindo controle centralizado.

---

## 📈 Resultados e Impactos de Negócio

* **Rastreabilidade Confiável:** Capacidade de auditar exatamente qual usuário executou cada transação crítica no WMS, eliminando ambiguidades em auditorias e desvios.
* **Foco Operacional e Redução de Erros:** Redução drástica de "atalhos" e erros humanos causados por manipulação de telas alheias à rotina do colaborador.
* **Governança e Higiene Sistêmica:** Estabilização do ambiente sistêmico, com alçadas claras, maior disciplina operacional e segurança contra rupturas logísticas.

---

## 🛠️ Tecnologias e Conceitos Aplicados
* **Sistemas:** WMS (Bluesoft).
* **Conceitos:** RBAC (*Role-Based Access Control*), Mapeamento de Processos, Arquitetura de Permissões, Gestão de Mudança (*Change Management*), Governança de TI/Negócios, Supply Chain.
