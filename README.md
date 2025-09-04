# Diagrama-AWS

Diagrama de fluxo da AWS usando EC2, EBS e RDS.

Visão Geral da Arquitetura:

Este projeto utiliza uma arquitetura baseada na Amazon Web Services (AWS) para hospedar e gerenciar uma aplicação web. O diagrama de arquitetura ilustra a interação entre os principais serviços da AWS e o fluxo de dados na aplicação.

Componentes da Arquitetura:

AWS Cloud: Representa o ambiente da Amazon Web Services onde toda a infraestrutura está hospedada.

EC2 (Elastic Compute Cloud): Uma instância do EC2 serve como o servidor de aplicação. É onde o código da aplicação é executado.

RDS (Relational Database Service): Este serviço hospeda o banco de dados relacional da aplicação, garantindo alta disponibilidade e escalabilidade.

EBS (Elastic Block Store): São volumes de armazenamento de bloco que podem ser anexados a instâncias EC2, proporcionando armazenamento persistente para dados. O diagrama mostra dois volumes EBS (rotulados como "D - EBS" e "E - EBS").

Fluxo de Dados: A aplicação, representada por um componente de interface web, envia arquivos para um volume EBS ("D - EBS"). A instância EC2 se comunica com os volumes EBS para acessar os dados e também interage com o banco de dados RDS para gerenciar informações.




Como o Diagrama Foi Criado:
O diagrama de arquitetura foi criado usando a ferramenta draw.io (também conhecida como diagrams.net).
