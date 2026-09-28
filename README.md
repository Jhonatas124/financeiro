# Financeiro de Bolso

Web app pessoal (PWA) de finanças para iPhone e Mac: contas fixas do mês, extrato de todas as contas e cartões,
faturas e parcelas, desejos com "Posso comprar?", relatórios e pendências de extrato.

- Sem servidor e sem conta: os dados ficam no aparelho (IndexedDB) e, se ligado, num cofre criptografado
  (AES-256-GCM, chave derivada da senha com PBKDF2) num repositório **privado** do GitHub do dono.
- Este repositório tem **só o código**. Nenhum dado financeiro fica aqui.
- Importa OFX e CSV de banco direto no app; PDF passa por fora e vira um arquivo .json.

Publicação: GitHub Pages, branch `main`, pasta raiz. No iPhone: Safari › Compartilhar › Adicionar à Tela de Início.
