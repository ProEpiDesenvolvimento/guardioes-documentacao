# 📋 Requisitos do Sistema — Guardiões da Saúde

Este documento apresenta os **requisitos elicitados** a partir da análise do projeto [Guardiões da Saúde](https://github.com/ProEpiDesenvolvimento).  
Os requisitos foram categorizados entre **funcionais (RF)** e **não funcionais (RNF)**, priorizados e descritos conforme suas respectivas áreas do sistema.

---

## 🔹 Requisitos Funcionais (RF)

| ID | Descrição | Prioridade | Categoria | Status | Observações |
|----|------------|-------------|------------|----------|--------------|
| RF01 | Permitir que o usuário registre sintomas de saúde. | Alta | Aplicativo | Implementado | Form principal do app. |
| RF02 | Permitir envio automático da localização ao registrar sintomas. | Alta | Geolocalização | Implementado | Utiliza GPS do dispositivo. |
| RF03 | Exibir mapa com visualização de casos próximos. | Média | Visualização | Implementado | Usa API de mapas. |
| RF04 | Permitir que o usuário receba notificações sobre surtos próximos. | Alta | Comunicação | Implementado | Push notifications. |
| RF05 | Permitir cadastro e login de usuários. | Alta | Autenticação | Implementado | Email e senha. |
| RF06 | Disponibilizar informações oficiais sobre saúde pública. | Média | Conteúdo | Implementado | Dados da OMS e Ministério da Saúde. |
| RF07 | Permitir coleta anônima de dados de sintomas. | Alta | Privacidade | Implementado | Anonimização de dados. |
| RF08 | Disponibilizar painel administrativo para autoridades de saúde. | Alta | Administração | Parcial | Foco em dashboards de monitoramento. |
| RF09 | Permitir filtragem de dados por região, data e tipo de sintoma. | Média | Visualização | Implementado | Filtros no painel e app. |
| RF10 | Exibir estatísticas e gráficos sobre sintomas reportados. | Alta | Dashboard | Implementado | Power BI / ChartJS integrado. |
| RF11 | Enviar relatórios diários agregados de sintomas às autoridades. | Média | Backend | Planejado | Processamento em lote. |


---

## 🔸 Requisitos Não Funcionais (RNF)

| ID | Descrição | Categoria | Prioridade | Status |
|----|------------|------------|-------------|---------|
| RNF01 | O sistema deve estar disponível 24h por dia, 7 dias por semana. | Disponibilidade | Alta | Implementado |
| RNF02 | O sistema deve suportar até 50 mil usuários simultâneos. | Desempenho | Alta | Planejado |
| RNF03 | Os dados do usuário devem ser armazenados com criptografia. | Segurança | Alta | Implementado |
| RNF04 | A interface deve ser intuitiva e acessível (WCAG 2.1). | Usabilidade | Média | Parcial |
| RNF05 | O sistema deve ser compatível com Android e iOS. | Portabilidade | Alta | Implementado |
| RNF06 | O tempo médio de resposta deve ser inferior a 3 segundos. | Desempenho | Média | Parcial |
| RNF07 | O backend deve ser escalável horizontalmente. | Arquitetura | Alta | Implementado |
| RNF08 | O código deve seguir boas práticas e padrões REST. | Manutenibilidade | Média | Implementado |
| RNF09 | A coleta de dados deve obedecer à LGPD. | Conformidade | Alta | Implementado |

---

## 🔍 Observações Gerais

- As funcionalidades foram elicitadas a partir da análise do código, issues e documentação pública do repositório oficial.
- Os requisitos de interoperabilidade e escalabilidade estão parcialmente implementados.
- As próximas versões devem incluir indicadores de qualidade e métricas de uso.

---

## 📚 Próximos Passos

1. Validar os requisitos com o time do projeto.  
2. Priorizar as melhorias para versões futuras.  
3. Criar rastreabilidade entre requisitos, módulos e testes.  

---
