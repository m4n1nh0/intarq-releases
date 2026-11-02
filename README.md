# INTARQ Releases

Este repositório reúne as versões públicas, builds e artefatos de distribuição do projeto INTARQ.

O projeto principal da aplicação fica em outro repositório, enquanto este espaço é dedicado a releases, instaladores e materiais de publicação das versões estáveis do produto.

## Sobre o INTARQ

O INTARQ é um assistente pessoal desktop pensado para funcionar de forma local-first, com foco em produtividade, automação, memória contextual e integração com ferramentas do usuário.

Sua arquitetura combina:

- Backend em FastAPI
- Interface desktop em Flutter
- Memória vetorial para contexto e recuperação de informações
- Automações locais e execução de ações com confirmação do usuário
- Integração com calendários, notificações e voz
- Suporte a múltiplos provedores de IA
- Modo educação para gravação, transcrição e organização de aulas

## Objetivo deste repositório

- Centralizar releases do INTARQ
- Publicar instaladores e builds distribuíveis
- Organizar versões estáveis do produto
- Manter o repositório principal focado no desenvolvimento e na manutenção do código-fonte

## Segurança e configuração

O projeto foi pensado para rodar localmente, com dados e credenciais sensíveis fora do repositório. O arquivo `backend/.env.example` documenta apenas as variáveis de infraestrutura e provedores que continuam vindo do ambiente.

As configurações de notificação e as autorizações das contas de calendário são persistidas no banco pela própria aplicação. Segredos de aplicações OAuth, como o App Registration Microsoft multitenant, permanecem no ambiente do backend.

## Observação

Este repositório não substitui o projeto principal de desenvolvimento; ele serve como canal oficial de distribuição das versões do INTARQ.
