# Slink.io

Jogo casual de navegador com interface colorida, arena animada e sistemas de progressão.

## Executar localmente

1. Baixe ou clone este repositório.
2. Abra `index.html` em um navegador moderno.

Não é necessário instalar dependências nem executar um servidor para testar a versão atual.

## Publicar com GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos desta pasta para a raiz do repositório.
2. No repositório, acesse **Settings → Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch principal (normalmente `main`) e a pasta `/ (root)`; salve.
5. Aguarde a publicação. O GitHub exibirá o endereço do site na seção **Pages**.

## Estrutura

```text
slink-io/
├── index.html   # jogo e estilos/scripts da versão atual
├── README.md    # documentação e instruções de publicação
├── .gitignore   # arquivos locais que não devem ser enviados
└── .nojekyll    # evita processamento Jekyll no GitHub Pages
```

## Observações

- A versão atual é um site estático, sem etapa de build.
- A fonte Baloo 2 é carregada do Google Fonts; a conexão com a internet permite carregá-la. Se indisponível, o navegador usa fontes alternativas.
- Publicar no GitHub Pages hospeda o site, mas não cria por si só multiplayer online, contas, backend ou armazenamento remoto.
- Revise e confirme os direitos de uso de todo conteúdo de terceiros antes de distribuir publicamente.
