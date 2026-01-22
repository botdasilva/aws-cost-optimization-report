# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 17/12/2026
**Empresa:** Abstergo Industries 
**Responsável:** Gustavo Araujo

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por mim, Gustavo Araujo. O objetivo do projeto foi elencar 3 serviços AWS focados em redução de custos imediatos e otimização de infraestrutura.

## Descrição do Projeto
O projeto focou em migrar serviços de alto custo fixo para modelos de "pagamento por uso" e automação de monitoramento financeiro.

### Etapa 1: 
- **Ferramenta:** Amazon S3 com Intelligent-Tiering
- **Foco:** Armazenamento de dados otimizado.
- **Caso de Uso:** Armazenamento de logs de segurança e backups. O Intelligent-Tiering move arquivos pouco usados para camadas mais baratas automaticamente, reduzindo o custo sem precisar de gestão manual.

### Etapa 2: 
- **Ferramenta:** AWS Lambda
- **Foco:** Execução de código Serverless.
- **Caso de Uso:** Execução de scripts de automação (Python) para tarefas administrativas e varreduras de rede agendadas. Substitui a necessidade de manter uma instância EC2 (servidor) ligada 24/7, pagando apenas quando o código é executado.

### Etapa 3: 
- **Ferramenta:** AWS Budgets
- **Foco:** Controle e governança de custos.
- **Caso de Uso:** Configuração de alertas automáticos por e-mail caso o gasto projetado ultrapasse o limite definido pelo departamento financeiro, evitando surpresas na fatura mensal.

## Conclusão
A implementação dessas ferramentas na Abstergo Industries trará uma redução de custos operacionais e maior previsibilidade financeira. Além disso, a adoção de tecnologias serverless e armazenamento gerenciado aumenta a segurança e a escalabilidade do ambiente.

## Anexos
- Documentação oficial da AWS sobre S3 Tiering.
- Guia de boas práticas de segurança para AWS Lambda.

**Assinatura:**
Gustavo Araujo
