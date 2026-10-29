# App_Invest — Minha Carteira

App de celular para acompanhar a carteira de investimentos em um só lugar: importa a posição e as movimentações da B3 (Excel) e extratos da Nubank e da Nomad (CSV), e mostra patrimônio, evolução, alocação por classe e instituição, proventos e resultado.

Os dados ficam salvos só no navegador do seu aparelho. Nada é enviado a servidor.

## Baixar tudo

[Baixar o projeto completo (ZIP)](https://github.com/PedroAllison/App_Invest/archive/refs/heads/main.zip)

## Usar no celular (mais fácil)

1. No repositório, vá em Settings > Pages, escolha Deploy from a branch, branch `main`, pasta `/ (root)` e salve.
2. Abra o endereço que o GitHub mostrar (algo como `https://pedroallison.github.io/App_Invest/`) no Chrome (Android) ou Safari (iPhone).
3. Adicione à tela inicial: Chrome em "Instalar app"; Safari em Compartilhar > "Adicionar à Tela de Início".

Depois da primeira abertura o app funciona também sem internet.

## Usar no computador

Extraia o ZIP e abra `index.html` no navegador. A leitura de arquivos Excel precisa de internet na primeira vez.

## Importar os dados

- B3: Canal do Investidor > Extratos > baixe Posição e Movimentação em Excel e importe com origem B3.
- Nubank e Nomad: CSV nos modelos que aparecem na aba Importar, ou cadastro manual do ativo.

## Arquivos

- `index.html` o app inteiro
- `manifest.webmanifest`, `icon-*.png` instalação como app
- `sw.js` funcionamento offline
