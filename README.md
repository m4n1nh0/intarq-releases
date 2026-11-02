# INTARQ — AI Assistant

Aplicativo de assistente pessoal desktop com backend em FastAPI, interface em Flutter, memória vetorial, automações locais, integração com calendários, voz, notificações, modo educação com gravação de aulas e múltiplos provedores de LLM.

## Visão geral

O INTARQ foi pensado para rodar localmente, com dados e credenciais sensíveis fora do repositório. A aplicação combina processamento de linguagem, automações no ambiente do usuário e integração com serviços externos para atuar como assistente pessoal inteligente.

## Arquitetura

- Backend: FastAPI
- Frontend: Flutter
- Memória: vetorial
- Automação: local, integrada ao fluxo de trabalho do usuário
- Integrações: calendários, notificações, voz e provedores de LLM
- Modo educação: gravação de aulas para contexto e aprendizado

## Segurança e configuração

O projeto foi estruturado para manter informações sensíveis fora do código-fonte e fora do repositório. O arquivo `backend/.env.example` documenta apenas as variáveis de infraestrutura e provedores que continuam vindo do ambiente.

As configurações de notificação e as autorizações das contas de calendário são persistidas no banco pela própria aplicação. Segredos de aplicações OAuth, como o App Registration Microsoft multitenant, permanecem no ambiente do backend.

## Observação

Este repositório concentra os artefatos de release e distribuição do projeto, enquanto parte da configuração operacional e dos segredos permanece no ambiente local do usuário.
