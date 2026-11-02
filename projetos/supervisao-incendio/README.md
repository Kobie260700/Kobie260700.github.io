# Automação e Supervisão de Sistemas de Pressurização e Combate a Incêndio

Solução de software voltada à supervisão de variáveis operacionais, ao acompanhamento de equipamentos e ao apoio a rotinas de teste em sistemas de pressurização e combate a incêndio.

## Contexto

O acompanhamento de sistemas de combate a incêndio envolve a verificação de condições como pressão hidráulica, nível de reservatório, disponibilidade de energia e estado dos equipamentos.

O projeto foi desenvolvido para centralizar informações de supervisão, registrar eventos e apoiar a execução de testes, oferecendo à equipe uma visão mais organizada da operação e de seu histórico.

A solução já funciona em várias empresas. Sua utilização depende das características de cada instalação e da atuação dos profissionais responsáveis pelo sistema.

## Visão geral da solução

A aplicação reúne interface web, backend, banco de dados e integração com uma camada de automação industrial. Entre suas funcionalidades estão:

- Acompanhamento de variáveis e estados operacionais;
- Visualização de condições e histórico de eventos;
- Apoio a rotinas de teste manual e agendado, conforme a configuração da instalação;
- Envio de comandos temporários necessários às rotinas de teste;
- Registro de eventos e alarmes;
- Geração de relatórios e apoio ao envio de notificações por e-mail.

A solução atua em conjunto com os equipamentos e procedimentos da instalação. Sua aplicação não substitui inspeções obrigatórias nem a atuação dos responsáveis técnicos.

## Minha contribuição

O trabalho que desenvolvi no projeto incluiu:

- Desenvolvimento de funcionalidades da aplicação de supervisão e da interface web;
- Implementação de serviços backend para leitura de variáveis e registro de informações;
- Desenvolvimento da integração entre a aplicação e a camada de automação industrial;
- Implementação de rotinas para acompanhamento e execução de testes;
- Criação de um simulador local para apoiar a validação da comunicação industrial;
- Preparação de documentação e participação nas atividades de validação técnica.

O projeto foi desenvolvido em conjunto com o projetista **Michael Richard**.

## Tecnologias

| Tecnologia | Aplicação no projeto |
| --- | --- |
| Java 17 e Spring Boot | Backend, regras de negócio e serviços web |
| PostgreSQL e Flyway | Persistência de dados e evolução do banco |
| HTML, CSS e JavaScript | Interface web |
| WebSocket | Atualização de informações operacionais na interface |
| Modbus TCP | Comunicação com a camada de automação industrial |
| Python e Tkinter | Simulador local |
| Gradle | Build e gerenciamento de dependências |
| SMTP | Notificações e envio de relatórios por e-mail |

## Arquitetura em alto nível

A solução integra informações da instalação industrial ao backend de supervisão. A aplicação disponibiliza informações na interface web e mantém registros para consulta e geração de relatórios. A separação entre a camada industrial e a aplicação permite organizar a integração de acordo com as características de cada instalação.

## Testes e validação

Em ambiente local, foram realizados:

- Compilação e execução do backend e da interface;
- Migrações do banco de dados em ambiente isolado;
- Validação da comunicação TCP com o simulador industrial;
- Uso do simulador para apoiar a avaliação de cenários operacionais e comandos de teste.

Os testes com simulador ajudam a verificar a comunicação e o comportamento da aplicação em laboratório. A integração com equipamentos reais deve ser avaliada de acordo com as condições e os procedimentos de cada instalação.

## Situação atual

A solução está em funcionamento em várias empresas e apoia atividades de acompanhamento e teste dos sistemas instalados.

O projeto proporcionou experiência prática em desenvolvimento backend, integração industrial, persistência de dados, testes e tradução de requisitos de engenharia em software.
