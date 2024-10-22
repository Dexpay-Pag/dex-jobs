
# Desafio Dex - CRUD de Carteira Digital

## Contexto
Esse desafio é uma réplica do nosso dia a dia. Ele consiste em construir um CRUD para gerenciar uma carteira digital.

## Stack Dex
- **Backend**: MongoDB, Kotlin, C#
- **Frontend**: React, Kotlin, Styled-components, AntD, Storybook, Vite

## Tema do Desafio - Carteira Digital
O tema é criar uma carteira digital onde seja possível:
- **Criar uma carteira**: Toda carteira é associada a um usuário específico.
- **Criar uma operação**: O usuário poderá realizar operações de crédito e débito na conta.
- **Realizar transferências**: Transferir valores entre carteiras de usuários.
- **Sacar valores**: O usuário poderá realizar saques da sua carteira.
- **Consultar extrato**: Gerar o extrato de operações realizadas.
- **Consultar saldo**: Consultar o saldo atual da carteira.

## Como começar?
- Se você está aplicando para **fullstack**, deve implementar tanto o backend quanto o frontend.
- Se está aplicando para **backend**, foque na implementação do backend.
- Se está aplicando para **frontend**, implemente o frontend.

### Backend
O backend deve ser uma API REST que manipula todas as funcionalidades listadas.  
**Stack**: a critério do candidato  
**Plus (opcional)**: Utilizar a nossa stack descrita no início do desafio.

#### Estrutura do banco de dados:
- **Carteira**: Representa uma carteira digital associada a um usuário.
- **Operação**: Contém registros de transações (crédito, débito, transferência) realizadas em uma carteira.

### Frontend
O frontend deve permitir a criação e o gerenciamento de carteiras de forma intuitiva.  
**Stack**: a critério do candidato  
**Plus (opcional)**: Utilizar a nossa stack descrita no início do desafio.

#### Entregáveis
- Deve ser possível criar uma nova conta de carteira com contas padrão.
- Adicionar botões de ação para transferir dinheiro entre contas.
- Exibir o saldo e o extrato de uma carteira.

### Artefatos que devem ser produzidos:
- Documentação da API
- Arquivo JSON do Postman para realizar chamadas à API

## Arquitetura Sênior
Caso deseje se aventurar em um escopo mais avançado, sugerimos o design de uma arquitetura para lidar com funcionalidades futuras da carteira.

## Submissão do desafio
Exemplo: 
Candidato: Vinícius Torres  
Criar uma pasta `vinicius_torres` com o projeto dentro da pasta challenges e abrir um Pull Request nesse repositório.

## Finalização
Após abrir o Pull Request, envie um e-mail para `ti@dexpay.com.br` ou `vinicius.torres@dexpay.com.br`
