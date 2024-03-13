# STACI - Sistema de Transporte Aéreo de Cargas Industriais

O STACI é um sistema desenvolvido para gerenciar as operações de uma transportadora aérea de cargas industriais, com o objetivo de melhorar a eficiência e o controle sobre as atividades da empresa. Este documento descreve as funcionalidades do sistema, seus requisitos funcionais e não funcionais, bem como as regras de negócio que devem ser consideradas no desenvolvimento.

## Funcionalidades

O STACI possui os seguintes subsistemas e funcionalidades principais:

- **Gerenciar informações de aviões:** Cadastro, listagem e manutenção de informações sobre os aviões da frota da transportadora, incluindo dados sobre voos, fabricantes e manutenções.
- **Gerenciar informações de empregados:** Cadastro e listagem de informações sobre os empregados da empresa.
- **Gerenciar informações de pilotos:** Cadastro, listagem e exclusão de informações sobre pilotos e modelos de aviões autorizados.

## Requisitos Funcionais

O sistema deve atender aos seguintes requisitos funcionais:

- Cadastro e listagem de aviões, voos, fabricantes e manutenções.
- Cadastro e listagem de empregados.
- Cadastro, listagem e exclusão de pilotos e modelos de aviões autorizados.

## Requisitos Não Funcionais

Os requisitos não funcionais do sistema são:

- Utilização do SGBD MySQL, versão 8.0 ou superior.
- Desenvolvimento em linguagem Java.
- Controle de acesso por usuário/subsistema para garantir a segurança das informações.

## Requisitos de Negócio

Algumas regras de negócio que devem ser consideradas no desenvolvimento são:

- Manutenção única: Cada avião só pode ser mantido por uma equipe de manutenção por vez.
- Carga máxima: Os aviões de carga só podem decolar se estiverem carregados até a sua capacidade máxima.
- Manutenção preventiva: Todos os aviões devem passar por uma checagem preventiva mensalmente.

## Contribuição

Contribuições são bem-vindas! Para contribuir com o projeto, siga os passos abaixo:

1. Faça um fork do repositório
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`)
3. Faça commit das suas alterações (`git commit -am 'Adicionando nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Crie um novo Pull Request

## Contato

Para mais informações, entre em contato com [Gbriel Garcia Hintze](mailto:gabrielandgarcia@gmail.com).

