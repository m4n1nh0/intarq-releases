# INTARQ Releases

Este repositório é dedicado às versões e artefatos de release do projeto INTARQ.

O código principal da aplicação fica em outro repositório público/privado, conforme a estratégia de manutenção do projeto. Aqui são publicados os builds, instaladores e materiais relacionados à distribuição e disponibilização das versões estáveis do sistema.

## Objetivo

- Centralizar as releases do INTARQ
- Disponibilizar instaladores e pacotes de distribuição
- Registrar versões publicadas do produto
- Manter o repositório principal focado no desenvolvimento e na manutenção do código-fonte

## Segurança e configuração

O projeto principal foi pensado para rodar localmente, com dados e credenciais sensíveis fora do repositório. O arquivo `backend/.env.example` documenta apenas as variáveis de infraestrutura e provedores que continuam vindo do ambiente.

As configurações de notificação e as autorizações das contas de calendário são persistidas no banco pela própria aplicação. Segredos de aplicações OAuth, como o App Registration Microsoft multitenant, permanecem no ambiente do backend.

## Observação

Este repositório não substitui o projeto principal de desenvolvimento; ele serve como canal de distribuição das versões do INTARQ.
