# Exemplo CC — Claude Code

Projeto de exemplo para demonstrar o uso do **Claude Code**, a CLI oficial da Anthropic para interação com o modelo Claude diretamente no terminal e em ambientes de desenvolvimento.

## Sobre o projeto

Este repositório serve como ponto de partida para explorar as capacidades do Claude Code no fluxo de trabalho de desenvolvimento de software, incluindo:

- Geração e edição de código assistida por IA
- Automação de tarefas de desenvolvimento (commits, PRs, refatorações)
- Integração com ferramentas de desenvolvimento (VS Code, JetBrains, terminal)
- Uso de skills, hooks e servidores MCP personalizados

## Pré-requisitos

- [Node.js](https://nodejs.org/) 18+
- [Claude Code CLI](https://claude.ai/code) instalado globalmente
- Conta Anthropic com acesso à API

## Instalação do Claude Code

```bash
npm install -g @anthropic-ai/claude-code
```

## Como usar

1. Clone este repositório:

```bash
git clone https://github.com/hebinhopassamani/Exemplo_CC.git
cd Exemplo_CC
```

2. Inicie o Claude Code no diretório:

```bash
claude
```

3. Explore os comandos disponíveis:

```
/help        — Lista todos os comandos disponíveis
/init        — Inicializa o CLAUDE.md com documentação do projeto
/code-review — Revisa o código atual
/run         — Executa o projeto
```

## Servidores MCP configurados

| Servidor | Descrição |
|---|---|
| `github` | Integração com a API do GitHub via Copilot MCP |
| `context-mode` | Otimização de contexto e análise de código |
| `Google Calendar` | Integração com o Google Calendar |
| `Gamma` | Geração de apresentações com IA |

## Recursos úteis

- [Documentação oficial do Claude Code](https://docs.anthropic.com/claude-code)
- [Claude API Reference](https://docs.anthropic.com/en/api/getting-started)
- [Repositório de issues](https://github.com/anthropics/claude-code/issues)

## Licença

Este projeto está sob a licença MIT.
