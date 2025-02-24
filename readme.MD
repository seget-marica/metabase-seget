# Serviço de Docker Compose - Metabase e PostgreSQL

Este repositório contém a configuração do serviço Docker Compose para a implantação do Metabase e do PostgreSQL, desenvolvido para a **Secretaria de Gestão Tributária e Fiscal de Maricá**.

## 📌 Descrição

O objetivo deste projeto é facilitar a instalação e configuração do Metabase, uma plataforma de análise de dados open-source, integrada a um banco de dados PostgreSQL. Essa configuração permite consultas eficientes, geração de relatórios e visualização de dados para auxiliar na gestão tributária e fiscal do município de Maricá.

## 🛠 Tecnologias Utilizadas

- **Docker**: Para a criação e gerenciamento dos containers.
- **Docker Compose**: Para orquestração dos serviços.
- **Metabase**: Ferramenta de BI para visualização e análise de dados.
- **PostgreSQL**: Banco de dados relacional para armazenar os dados da aplicação.

## 🚀 Como Utilizar

1. Clone este repositório:
   ```sh
   git clone https://github.com/seget-marica/metabase-seget.git
   ```

2. Acesse a pasta do projeto:
   ```sh
   cd metabase-seget
   ```

3. Crie um arquivo `.env` baseado no modelo `.env.example` e configure suas credenciais. O metabase está na porta 3000. Caso sinta 
   necessidade de alterar a porta, do serviço do metabase, você deverá alterar no arquivo docker-compose.yaml.

4. Suba os containers com o Docker Compose:
   ```sh
   docker-compose up -d
   ```

5. Acesse o Metabase via navegador:
   ```
   http://localhost:3000
   ```
   
## 📌 Estrutura do Repositório

```
/
├── docker-compose.yml  # Configuração dos serviços Docker
├── .env.example        # Exemplo de arquivo de variáveis de ambiente
└── README.md           # Documentação do projeto
```

## 📄 Licença

Este projeto é mantido pela **Subsecretaria de modernização** e segue as diretrizes internas de uso. Para mais informações, entre em contato com a equipe responsável.

---
📧 Para dúvidas e suporte, entre em contato com a equipe de dados da Subsecretaria de modernização.

## Links
**How to run Metabase in production**: https://www.metabase.com/blog/how-to-run-metabase-in-production

**Running Metabase on docker**: https://www.metabase.com/docs/latest/installation-and-operation/running-metabase-on-docker



