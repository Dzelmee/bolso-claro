# bolso.claro

A ideia do bolso.claro foi experimentar uma forma mais visual de acompanhar registros financeiros pessoais. Em vez de depender de uma planilha para tudo, organizei cadastro, consulta e indicadores em uma interface única.

## O que desenvolvi

- Inclusão, edição, pesquisa e exclusão de registros.
- Validação dos dados no servidor.
- Indicadores que acompanham as informações registradas.
- Layout adaptável, alternância entre temas claro e escuro e animações com opção de movimento reduzido.

## Como executar

```bash
npm test
npm start
```

O servidor inicia em `http://localhost:3000`. Para usar outra porta, configure `PORT`.

## Tecnologias e armazenamento

Usei HTML, CSS e JavaScript com ES Modules no front-end. O servidor é feito em Node.js, usando o módulo HTTP nativo. Os registros ficam em um arquivo JSON local.

## Limitações

Esta é uma aplicação de demonstração, não um serviço pronto para produção. Ainda não há autenticação, permissões por usuário nem banco de dados de produção. O armazenamento em JSON também não foi pensado para várias instâncias simultâneas.

## Imagens

Fotografias do [Unsplash](https://unsplash.com/license):
- https://images.unsplash.com/photo-1554224155-6726b3ff858f?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=1100&q=85
