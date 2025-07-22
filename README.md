# aws-farmacia-project
Desafio DIO GFT  -  Redução dos Custos em Farmácias com AWS

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 22/07/2025  
Empresa: FarmaCloud Solutions  
Responsável: Andressa Rodrigues

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa FarmaCloud Solutions, realizado por Andressa Rodrigues.  
O objetivo do projeto foi *elencar 3 serviços AWS*, com a finalidade de *realizar diminuição de custos imediatos* e garantir *escalabilidade e segurança* para uma plataforma virtual de farmácia.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1:
- **Nome da ferramenta**: Amazon S3  
- **Foco da ferramenta**: Armazenamento de arquivos e imagens dos produtos  
- **Descrição de caso de uso**: Utilizamos o Amazon S3 para hospedar imagens e documentos da farmácia, como fotos de medicamentos, prescrições digitalizadas e arquivos de catálogo. Isso possibilitou alta disponibilidade e baixo custo.

### Etapa 2:
- **Nome da ferramenta**: Amazon RDS (MySQL)  
- **Foco da ferramenta**: Gerenciamento dos dados transacionais da farmácia  
- **Descrição de caso de uso**: O RDS foi usado para hospedar o banco de dados relacional da aplicação, permitindo o controle de pedidos, cadastro de clientes e histórico de compras com segurança e backups automáticos.

### Etapa 3:
- **Nome da ferramenta**: AWS CloudFront  
- **Foco da ferramenta**: Otimização de performance e entrega de conteúdo  
- **Descrição de caso de uso**: O CloudFront foi usado como CDN para entregar os conteúdos da plataforma (como imagens e páginas estáticas) com mais velocidade, garantindo uma melhor experiência para o usuário final.

---

## Anexos

- [Template Figma da Plataforma](https://www.figma.com/your-template-link)
- [Script de Banco de Dados](./database/farmacia.sql)
- [Documentação de Referência AWS](https://docs.aws.amazon.com/)
