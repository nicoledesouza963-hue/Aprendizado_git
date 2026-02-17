Diferenças entre Git e GitHub

1. Git
- É um sistema de controle de versão.
- Funciona localmente no computador.
- Permite criar, salvar e gerenciar versões do código.
- Não precisa de internet para ser usado.
- Comandos comuns: git init, git add, git commit, git merge.

2. GitHub
- É uma plataforma online que hospeda repositórios Git.
- Facilita colaboração e compartilhamento de projetos.
- Precisa de internet para acessar e sincronizar.
- Oferece recursos extras: pull requests, issues, forks, interface web.
- É focado em comunidade e colaboração.

Resumo:
- Git = ferramenta para versionar código.
- GitHub = serviço online que usa Git para conectar pessoas e projetos.

Comandos comuns do Git

1. git init
- Cria um novo repositório Git no diretório atual.
- Inicializa o controle de versão, permitindo começar a registrar mudanças.
- Exemplo: git init

2. git add
- Adiciona arquivos ao "staging area" (área de preparação).
- É o passo antes de confirmar as mudanças com commit.
- Exemplo: git add arquivo.txt
- Para adicionar todos os arquivos: git add .

3. git commit
- Registra as mudanças adicionadas com git add no histórico do repositório.
- Cria um ponto de versão (snapshot) com uma mensagem descritiva.
- Exemplo: git commit -m "Adiciona nova funcionalidade"

4. git merge
- Junta o histórico de um branch com outro.
- Usado para integrar alterações de diferentes linhas de desenvolvimento.
- Exemplo: git merge nome-do-branch
