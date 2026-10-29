# Bolso Claro

Controle de finanças com receitas, despesas, saldo e gráfico por categoria.

## Executar

Requer Node.js 22 ou superior. Sem dependências npm externas.

```bash
npm test
npm start
```

Acesse http://localhost:3000. Para mudar a porta: `PORT=3100 npm start` (PowerShell: `$env:PORT=3100; npm start`).

## Arquitetura

- Front-end: HTML semântico, CSS responsivo e JavaScript nativo.
- Back-end: servidor HTTP Node.js e API REST em `/api/records`.
- Persistência: `data/records.json` local, não versionado.
- Rotas: GET/POST `/api/records`, PUT/DELETE `/api/records/:id`, GET `/api/health`.
- Testes: `node --test`, CRUD, validação e arquivos estáticos.

## Acessibilidade e responsividade

Skip link, foco visível, labels, botões com nomes acessíveis, diálogos nativos, regiões de status e suporte a `prefers-reduced-motion`. Breakpoints em 600 e 900 px.

## Limitações

Protótipo funcional para estudo/portfólio, não serviço de produção. Não possui autenticação, autorização, banco relacional nem pagamentos reais. A sacola da loja é salva no navegador e o checkout é simulado. Não declare conformidade WCAG sem auditoria manual e automatizada.

## Design

Identidade visual própria para este domínio, com ilustrações SVG locais estáticas.
