---
layout: post
title: "Reunião Semanal — 23/10/2025"
date: 2025-10-23 14:00:00 -0300
tags: [reunião, semanal]
---

**Resumo.**  
Durante esta reunião, Carlos, Caroline, Eder, João, Liviany e Luiz discutiram questões técnicas sobre o repositório do SMNA, o uso e interpretação dos dados de radiância e convencionais, problemas na execução de scripts no ambiente Egeon, o andamento do sistema de monitoramento, a operacionalização do SMNA, o seminário e apresentação sobre o GODEX, além do desenvolvimento e uso do Jedi para assimilação de dados, destacando a necessidade de um ambiente corporativo para o desenvolvimento conjunto.

---

## Pauta
🔹 **Repositório Git do SMNA** – regularização das permissões e contribuições em andamento
🔹 **readDiag** – status das modificações no repositório, testes e validação dos dados de vento
🔹 **SMNA na operação** – retorno da equipe operacional sobre a nova versão e rodada comparativa
🔹 **Sistema de monitoramento (SMNAMonitoringApp)** – andamento das melhorias e implantação na EGEON
🔹 **Seminário GODEX** – definição da data e preparação dos materiais
🔹 **Trabalhos com o JEDI** – andamento e integração com demais atividades
🔹 **Assuntos gerais** – espaço aberto para contribuições e informes

---

## Decisões e encaminhamentos

- **Decisão 1:** Confirmar o uso das variáveis `iuse` e `iusev` conforme o tipo de dado (radiância ou convencional).  
- **Decisão 2:** Priorizar a criação de um ambiente corporativo para o desenvolvimento do JEDI, substituindo contas pessoais.  
- **Encaminhamento:** Resolver problemas de execução de scripts no ambiente Egeon, especialmente relacionados a `cartopy` e conectividade.  
- **Encaminhamento:** Continuar o acompanhamento da pré-operação do SMMA e da migração para nova máquina.  
- **Encaminhamento:** Preparar uma apresentação sobre o workshop do GODEX.  

---

## Ações definidas

### João Gerd Zell de Mattos
- Revisar e esclarecer a utilização das variáveis `iuse` e `iusev` nas rotinas para dados de radiância e convencionais.  
- Acompanhar o andamento da operacionalização do SMNA e a migração para a nova máquina.  

### Caroline Viezel
- Realizar testes de execução do readDiag envolvendo a lista automática de canais e auxiliar no desenvolvimento de solução para isso.  
- Enviar as figuras geradas no `statecount` para João, auxiliar na validação do código.  
- Testar a versão do JEDI disponibilizada por João e reportar os resultados.  
- Auxiliar no esclarecimento sobre a interpretação de dados de radiância no sistema.  

### Éder Paulo Vendrasco
- Preparar o ambiente do JEDI no repositório da organização para facilitar o desenvolvimento conjunto.  
- Organizar os scripts e documentação do JEDI para facilitar o uso por outros membros do grupo.  
- Participar da próxima reunião com atualizações sobre o avanço do JEDI.  

### Luiz Sapucci
- Continuar avaliando os problemas na execução dos scripts no ambiente Egeon e colaborar na identificação das causas.  
- Preparar a apresentação para o workshop sobre o GODEX.  
- Ajudar a testar e validar a versão do JEDI disponibilizada por João. 

### Carlos Frederico Bastarz
- Auxiliar na resolução dos problemas relacionados aos erros na execução do código e na interface do sistema de monitoramento.  
- Aconselhar sobre a estabilidade do ambiente remoto e da conexão para execução dos scripts.
- Continuar o desenvolvimento do Sistema de monitoramento (SMNAMonitoringApp).


---

## Pendências / próximos passos
- Revisar comportamento de `iuse`/`iusev` e enviar documentação ao grupo.  
- Concluir testes do JEDI com LFS e validar integração no repositório corporativo.  
- Resolver falhas do ambiente Egeon e confirmar estabilidade de rede.  
- Organizar e documentar o ambiente JEDI para colaboração contínua.  
- Realizar apresentação sobre workshop do GODEX.

---

## Observações complementares
Foi discutida a importância de registrar as reuniões como *memórias* (e não atas formais), mantendo transparência e rastreabilidade das edições via histórico do repositório. Destacou-se que o foco do grupo, após a entrega do SMNA, passa a ser o avanço do sistema JEDI e sua integração com o MONAN.  

---

## Atualizações posteriores

