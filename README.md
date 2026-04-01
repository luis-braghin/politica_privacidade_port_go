# Politica de Privacidade - Port Go

Paginas legais estaticas do aplicativo **Port Go** (Portaria Go). Contém a politica de privacidade, termos de uso e instrucoes para exclusao de conta, exigidos pelas lojas de aplicativos (App Store / Google Play).

## Stack

- HTML estatico (sem frameworks, sem build)
- CSS inline
- Deploy via Vercel

## Pre-requisitos

Nenhum. Os arquivos sao HTML puro e podem ser abertos diretamente no navegador.

Para deploy na Vercel, e necessario ter uma conta configurada e o CLI da Vercel instalado (opcional).

## Como rodar localmente

Basta abrir o arquivo `index.html` no navegador:

```bash
# Ou usar qualquer servidor HTTP local
npx serve .
```

## Como fazer deploy

O projeto esta configurado para deploy automatico na Vercel. O arquivo `vercel.json` (quando presente) controla as configuracoes de roteamento.

```bash
vercel --prod
```

## Estrutura de pastas

```
politica_privacidade_port_go/
├── index.html          # Pagina principal (Politica de Privacidade)
└── .git/
```

> **Nota:** De acordo com a especificacao do projeto, as paginas `privacidade.html`, `termos.html` e `exclusao-de-conta.html` podem estar consolidadas em `index.html` ou serem adicionadas futuramente.

## Status

**Producao** -- Paginas publicadas e acessiveis via Vercel.
