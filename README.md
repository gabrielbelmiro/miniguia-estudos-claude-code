🚀 Miniguia de estudo: Dominando o Claude Code

Um guia prático e estratégico para dominar o uso do Claude Code na
automação de desenvolvimento com IA.

📌 1. Contexto e Objetivo

Este repositório documenta um estudo estruturado sobre o Claude Code, um
assistente agêntico que opera diretamente no terminal e potencializa
fluxos de desenvolvimento com Inteligência Artificial.

O material foi construído com foco em aprendizado aplicado + engenharia
de prompts.

🎯 Objetivos de Estudo
Compreender o Loop Agêntico (Contexto → Ação → Verificação)
Dominar a gestão da Janela de Contexto
Configurar instruções persistentes com CLAUDE.md
Utilizar checkpoints e modos de permissão
Aplicar em refatoração, debug, code review e automação

📚 2. Curadoria de Fontes
Guia de Início Rápido
Como funciona
Melhores práticas
Fluxos de trabalho
Code review

🧠 3. Engenharia de Prompts
🔎 Exploração

Dê uma visão geral de alto nível do projeto

Exemplo de Exploração

Resultado:

Análise automática da estrutura do projeto
Identificação de padrões e organização

Insight:

Claude performa muito bem quando começa pela fase de contexto
🛠️ Refatoração

Use Plan Mode antes de executar mudanças

Exemplo de 🛠️ Refatoração

Problema inicial:

Prompt genérico → resultados inconsistentes

Solução:

Uso de Plan Mode antes da execução

Cicatriz aprendida 💡:

Sempre separar planejamento de execução em tarefas complexas
🐞 Debug

Sempre valide com testes (ex: npm test)

Exemplo de 🐞 Debug - Correção com Verificação

Corrija o erro de login e valide executando npm test

Dificuldade:

Sem testes → respostas “plausíveis”, porém não confiáveis

Dica de Ouro 🧠:

Sempre forneça uma forma de validação automática (testes, logs, etc.)
📘 4. Miniguia
🔁 Loop Agêntico

O Claude Code opera em 3 etapas:

Contexto → leitura de arquivos e entendimento
Ação → edição/criação de código
Verificação → execução de testes ou validações
Janela de Contexto

Recurso mais crítico do modelo acumula:

histórico da conversa
arquivos lidos
Possui auto-compactação, mas não é suficiente

💡 Boas práticas:

Usar /clear entre tarefas diferentes
Evitar misturar contextos
Segurança

Cada alteração gera um checkpoint

Possível desfazer com:
Esc (duas vezes)
/rewind
📖 5. Glossário
CLAUDE.md → instruções persistentes
Plan Mode → planejamento
Subagents → execução isolada
Severidade → classificação de bugs: Crítico / Médio / Baixo
🧪 6. Prompts
Revisão → identificar edge cases
Analise este arquivo e identifique edge cases que podem causar falhas
Testes → gerar scaffolding
Identifique código não testado e gere o scaffolding de testes
Integração → hook de lint
Crie um hook para rodar o linter automaticamente após cada edição
/btw → dúvida rápida
/btw [sua pergunta]
🏁 Conclusão

IA amplifica produtividade. Prompt bem feito = resultado melhor.

⭐ Roadmap
CI/CD
Automação
Prompts avançados
🎓 Formação

Escola: DIO – Digital Innovation One
🔗 https://web.dio.me/

Instrutor responsável pelos desafios:
Felipe Silva Aguiar – Desenvolvedor FullStack
🔗 https://www.linkedin.com/in/felipeaguiar-exe/

👨‍💻 Autor

Gabriel Belmiro
🔗 https://www.linkedin.com/in/gabriel-belmiro/

Desenvolvedor em constante evolução, com foco em fundamentos sólidos,
organização de código e crescimento progressivo em arquitetura e boas práticas.

✨ Repositório focado na consolidação de fundamentos e construção estratégica de portfólio.