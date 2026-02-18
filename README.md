# Custos_em_Farmacias_com_AWS
Redução dos Custos em Farmácias com os serviços da AWS

Data: 17/02/2026
Empresa: Farmácia Democrática S.A.
Responsável: Roberto da Conceição Santos
________________________________________
Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Farmácia Democrática S.A., realizado por Roberto da Conceição Santos.
O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, promovendo maior controle financeiro, otimização de recursos computacionais e melhor governança do ambiente em nuvem.
________________________________________
Descrição do Projeto
O projeto de implementação foi dividido em 3 etapas estratégicas, priorizando ganhos financeiros de curto prazo, sem comprometer disponibilidade e performance.
________________________________________
Etapa 1:
•	Nome da ferramenta: AWS Cost Explorer
•	Foco da ferramenta: Análise e otimização de custos
•	Descrição de caso de uso:
Foi realizada a ativação e configuração do AWS Cost Explorer para análise detalhada dos custos por serviço, região, conta e tag de projeto.
Identificou-se:
•	Recursos ociosos em instâncias EC2
•	Volumes EBS não utilizados
•	Ambientes de homologação ativos fora do horário comercial
Com base nos dados extraídos:
•	Foram desativados recursos não produtivos
•	Aplicadas políticas de desligamento automático (shutdown scheduling)
•	Reorganizadas tags para melhor rastreabilidade financeira
Resultado estimado: redução imediata de 18% nos custos mensais.

________________________________________
Etapa 2:
•	Nome da ferramenta: Amazon EC2 Auto Scaling
•	Foco da ferramenta: Otimização de capacidade computacional
•	Descrição de caso de uso:
Foi implementado Auto Scaling Groups para aplicações web hospedadas em instâncias EC2.
Antes da implementação:
•	6 instâncias fixas 24/7
•	Baixa utilização fora do horário comercial
Após implementação:
•	Mínimo: 2 instâncias
•	Máximo: 6 instâncias
•	Escalonamento baseado em CPU > 60%
Resultado:
•	Redução de desperdício computacional
•	Economia média mensal estimada de 25% em workloads variáveis
•	Melhor performance sob pico de demanda

________________________________________
Etapa 3:
•	Nome da ferramenta: Amazon S3 Intelligent-Tiering
•	Foco da ferramenta: Otimização de armazenamento
•	Descrição de caso de uso:
Análise demonstrou que grande parte dos dados armazenados no Amazon S3 eram acessados esporadicamente.
Foi aplicada a política S3 Intelligent-Tiering, permitindo migração automática entre camadas de armazenamento conforme padrão de acesso.
Benefícios obtidos:
•	Redução de custo de armazenamento de até 30%
•	Manutenção automática sem necessidade de intervenção manual
•	Otimização contínua baseada em comportamento real de uso
________________________________________
Conclusão
A implementação das ferramentas na empresa Farmácia Democrática S.A. tem como esperado:
•	Redução média consolidada de custos entre 20% e 30%
•	Melhor governança financeira (FinOps)
•	Eliminação de recursos ociosos
•	Escalabilidade sob demanda
•	Otimização automática de armazenamento
Essas ações aumentam a eficiência operacional, melhoram a previsibilidade orçamentária e elevam o nível de maturidade em gestão de ambientes Cloud.
Recomenda-se:
•	Implantação futura de políticas de Reserved Instances ou Savings Plans
•	Adoção de cultura FinOps
•	Monitoramento contínuo com dashboards executivos






Anexos
1.	Diagrama arquitetural do ambiente pós-implementação

 

2.	Tabela comparativa de custos antes e depois da otimização

 
________________________________________
Assinatura do Responsável pelo Projeto:
Roberto da Conceição Santos
