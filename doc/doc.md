# Levantamento de requisitos da plataforma ArmazeneJá

> v1.0 - MVP
> | Esta primeira versão (MVP) busca validar a ideia central, oferecendo apenas funcionalidades essenciais.

## 1. Introdução

A plataforma **ArmazeneJá** tem como objetivo conectar clientes que desejam alugar espaços de armazenamento temporário com donos de armazéns que possuem disponibilidade.

## 2. Objetivos do Sistema
- Permitir que clientes pesquisem e reservem armazéns de acordo com localização e preço.
- Facilitar o anuncio para a monetização de armazéns por parte dos donos.
- Registrar reservas e disponibilizar histórico para ambas as partes.
- Possibilitar a personalização via metro cubico para à armazenagem do usuário.

## 3. Escopo MVP
Funcionalidades presentes nesta primeira versão:
- Cadastro e login de usuários.
- Cadastro de armazéns (com dados básicos: endereço, preço, tamanho, disponibilidade).
- Pesquisa de armazéns por filtros simples (localização, preço.)
- Calculadora de cubagem.
- Reserva de armazéns.
- Listagem de reservas feitas pelo cliente.
- Painel de controle para donos gerenciarem suas reservas.

Funcionalidades *fora do escopo do MVP* (Em planejamento):
- Planos de destaques para anunciantes.
- Integração com transportes parceiros.
- Gateways de pagamento online.
- Avaliação e feedbacks.

## 4. Usúarios de Sistema
- **Cliente:** pessoa que busca e reserva um armazém.  
- **Dono do Armazém:** pessoa que cadastra um espaço disponível. 

## 5. Requisitos Funcionais (RF)
1. O sistema deve permitir cadastro e autenticação de usuários.
2. O sistema deve permitir cadastro de armazéns.
3. O sistema deve listar armazéns com disponibilidade e filtros básicos.
4. O sistema deve permitir que clientes reservem armazéns.
5. O sistema deve exibir para o cliente todas as suas reservas realizadas.
6. O sistema deve exibir para o dono do armazém todas as reservas recebedias.

## 6. Requisitos Não Funcionais (RNF)
1. O sistema deve estar disponivel via navegador web.
2. O sistema deve ser responsivo (acessivel em dispositivos móveis).
3. O sistema deve possuir autenticação básica com com login e senha.
4. O sistema deve possuir recurso para recuperação de autenticação, via confirmação de dados cadastrados.
5. O sistema deve utilizar banco de dados relacioal para persitencia dos dados.

## 7. Histórias de Usuário
- **Cliente:**
    - Como cliente, quero me cadastrar no sistema, para poder reservar armazéns.
    - Como cliente, quero buscar armazéns por localização e preço, para encontrar a melhor opção.
    - Como cliente, quero reservar um armazém, para utilizá-lo no periodo escolhido.
    - Como cliente, quero calcular o metro cubico para a minha carga.
- **Dono do Armazém:**
    - Como dono, quero cadastrar meu armazém, para que clientes possam encontrá-lo.
    - Como dono, quero visualizar reservas feitas em meu armazém, para controlar disponibilidade.

## 8. Fluxo Básico do Sistema
1. Usuário acessa a plataforma e realiza login/cadastro.
2. Cliente pesquisa por armazéns.
3. Cliente reserva um armazém disponivel.
4. Dono recebe notificação de reserva.
5. Ambos podem visualizar histórico de reservas.

## 9. Conclusão
Este documento apresenta o levantamento inicial de requisitos da plataforma **ArmazeneJá**, servindo como referencia para o desenvolvimento do MVP.

A partir desta base, novas funcionalidades poderão ser adicionadas em versões futuras conforme validação do mercado.


> Autores: Fernanda Santos | Mateus Barbosa