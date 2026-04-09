Focus – ADHD Medication Management (Backend)

O Focus é o backend de uma aplicação mobile desenvolvida para auxiliar pessoas com TDAH no gerenciamento de medicações e monitoramento de sintomas.

Este repositório foca na implementação da API robusta desenvolvida em C# .NET, utilizando os princípios da Clean Architecture para garantir escalabilidade, testabilidade e independência de frameworks.
🚀 Minha Contribuição Principal

Diferente da versão inicial em Flask, reestruturei e desenvolvi o core do backend focando em padrões de mercado:

    Arquitetura: Implementação de Clean Architecture (Domain, Application, Infrastructure e WebAPI).

    Linguagem/Framework: C# com .NET 8 (ou sua versão atual).

    Persistência: Migração e modelagem do banco de dados relacional para MySQL.

🏗️ Arquitetura do Sistema

O projeto foi construído seguindo os princípios da Arquitetura Limpa, dividindo as responsabilidades em camadas:

    Domain: Entidades, interfaces e regras de negócio puras.

    Application: Casos de uso (Use Cases), DTOs e serviços de aplicação.

    Infrastructure: Implementação do Entity Framework Core, repositórios e integração com AWS RDS.

    API: Controllers e configurações de injeção de dependência.

🛠️ Tech Stack (Backend)

    .NET Core / C# (Linguagem e Framework principal)

    Entity Framework Core (ORM para mapeamento objeto-relacional)

    MySQL (Banco de dados na nuvem via AWS )

    LINQ (Para consultas otimizadas no banco)

    Swagger/OpenAPI (Documentação e testes da API)

📊 Design do Banco de Dados

Como responsável pela arquitetura de dados, projetei um esquema relacional focado em consistência e integridade, suportando:

    Gestão de medicamentos e agendamento de doses.

    Log de sintomas com histórico temporal.

    Sincronização eficiente para o modelo Offline-first do mobile.

🧠 Conceitos de Engenharia Aplicados

    SOLID: Aplicação rigorosa dos princípios para evitar acoplamento.

    Repository Pattern: Para abstrair a lógica de acesso a dados.

    Injeção de Dependência: Nativa do .NET para facilitar a manutenção e testes.
