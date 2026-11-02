# Adega Summer

Sistema de gestão local desenvolvido para apoiar a operação de uma adega, reunindo vendas, estoque, controle de caixa e acompanhamento administrativo em uma única aplicação.

> Projeto preparado para instalação controlada. A operação definitiva em produção ainda não foi confirmada.

## Problema

A Adega Summer foi criada para organizar rotinas de vendas, estoque e controle de clientes e oferecer uma visão mais confiável da operação.

## Funcionalidades

- Registro de vendas e acompanhamento de caixa;
- Controle de estoque por produto, entradas e ajustes;
- Gestão de fiado, recebimentos, consumação e cancelamentos;
- Cadastro de produtos, categorias e marcas;
- Indicadores gerenciais, alertas e dashboard;
- Controle de acesso por perfil e auditoria de ações administrativas;
- Backup, restauração e diagnóstico operacional.

## Tecnologias

- **Backend:** Python e FastAPI
- **Frontend:** Next.js e TypeScript
- **Banco de dados:** PostgreSQL
- **Containerização:** Docker e Docker Compose
- **Testes de interface:** Playwright
- **Automação operacional:** PowerShell

## Desenvolvimento e qualidade

O desenvolvimento priorizou consistência de dados e segurança operacional em cenários com mais de um usuário. Foram realizadas validações de operações simultâneas, cancelamentos, idempotência, permissões, backup e restauração, recuperação de serviços, interface em desktop e mobile e carga com múltiplos usuários.

O estoque é centralizado por produto, com regras para evitar saldo negativo e inconsistências em vendas, consumação e cancelamentos.

## Status

A aplicação está tecnicamente preparada para instalação controlada em ambiente local. A operação definitiva depende da instalação no cliente e da validação prática da rede e dos dispositivos utilizados pela equipe.

Projeto de engenharia de software desenvolvido para atender às necessidades de um negócio real, com foco em consistência de dados, manutenção e confiabilidade operacional.
