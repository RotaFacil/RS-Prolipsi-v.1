# Documentação do RS-Prolipsi v.1

Bem-vindo à documentação do sistema RS-Prolipsi versão 1.0.0.

## Índice

1. [Visão Geral](#visão-geral)
2. [Arquitetura](#arquitetura)
3. [Configuração do Supabase](#configuração-do-supabase)
4. [Configuração do WeWeb](#configuração-do-weweb)
5. [Guia de Uso](#guia-de-uso)

## Visão Geral

O RS-Prolipsi é um sistema desenvolvido utilizando a abordagem no-code/low-code, combinando o poder do Supabase como backend e WeWeb como frontend.

### Objetivos da Versão 1.0.0

- Estabelecer a estrutura base do sistema
- Implementar funcionalidades essenciais
- Garantir integração entre Supabase e WeWeb
- Fornecer uma base sólida para futuras expansões

## Arquitetura

### Backend - Supabase

O Supabase fornece:
- **Banco de Dados**: PostgreSQL hospedado e gerenciado
- **Autenticação**: Sistema completo de auth com múltiplos provedores
- **API**: RESTful API gerada automaticamente
- **Realtime**: Subscriptions em tempo real
- **Storage**: Armazenamento de arquivos

### Frontend - WeWeb

O WeWeb oferece:
- **Editor Visual**: Construção de interfaces sem código
- **Componentes**: Biblioteca rica de componentes prontos
- **Responsividade**: Design adaptável a diferentes dispositivos
- **Integrações**: Conexão nativa com Supabase e outras APIs

## Configuração do Supabase

### Passo 1: Criar Projeto
1. Acesse [supabase.com](https://supabase.com)
2. Crie uma nova organização ou use uma existente
3. Crie um novo projeto
4. Anote a URL e a chave anon do projeto

### Passo 2: Configurar Banco de Dados
1. Acesse o SQL Editor no painel do Supabase
2. Configure as tabelas necessárias
3. Configure as políticas de RLS (Row Level Security)

### Passo 3: Configurar Autenticação
1. Acesse Authentication no painel
2. Configure os provedores de autenticação desejados
3. Configure as URLs de redirecionamento

## Configuração do WeWeb

### Passo 1: Criar Projeto
1. Acesse [weweb.io](https://www.weweb.io)
2. Crie um novo projeto
3. Escolha um template ou comece do zero

### Passo 2: Conectar ao Supabase
1. Vá em Settings > Integrations
2. Adicione a integração Supabase
3. Insira a URL e chave anon do seu projeto Supabase
4. Teste a conexão

### Passo 3: Desenvolver Interface
1. Use o editor visual para criar páginas
2. Configure workflows e lógica de negócio
3. Conecte componentes aos dados do Supabase

## Guia de Uso

### Para Desenvolvedores

Esta versão estabelece a fundação do sistema. Para desenvolvimento futuro:

1. Mantenha a documentação atualizada
2. Registre mudanças no CHANGELOG.md
3. Incremente a versão no arquivo VERSION conforme necessário
4. Siga as convenções estabelecidas

### Para Usuários

(Esta seção será expandida conforme as funcionalidades forem implementadas)

## Suporte

Para questões ou suporte, entre em contato:
- Email: rsprolipsioficial@gmail.com

## Histórico de Versões

Consulte [CHANGELOG.md](../CHANGELOG.md) para histórico completo de versões.
