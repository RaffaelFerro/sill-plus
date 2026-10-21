# Sill Plus

Versão modificada do **[Sill](https://github.com/Saffsanity/sill)**, de Noah Saffer, para iPhone.
**Não é o app oficial** e não tem ligação com o autor original. O Sill oficial é gratuito na
[App Store](https://apps.apple.com/app/id6816359860) e em [getsill.app](https://getsill.app).

O Sill Plus usa o **app Sill gratuito no Mac** (o oficial, [getsill.app](https://getsill.app)); só o
app do iPhone muda.

## Instalar

Adicione este source na sua loja de sideload (AltStore, SideStore, Feather e afins):

```
https://raw.githubusercontent.com/RaffaelFerro/sill-plus/main/source.json
```

Ou baixe o IPA direto em [Releases](https://github.com/RaffaelFerro/sill-plus/releases) e instale com
a sua ferramenta de sideload. O IPA vem sem assinatura; a ferramenta assina com a sua conta.

Requer iOS 17 ou mais novo.

## O que muda em relação ao Sill 0.5.1

No iPhone em pé:

- **Zoom na imagem** de 1× a 4×, só no iPhone, com o cursor do Mac sempre no centro: toque no **Aa**
  para ligar e desligar, segure e suba o dedo para escolher, ou dê dois toques com dois dedos. Cada
  janela lembra o seu zoom.
- **Tela cheia vertical** (botão no canto da imagem, ou em Settings › This iPhone): a área livre vira
  o "monitor" e a janela do Mac se encaixa nela, inclusive quando o teclado abre; alça com modo toque
  ou trackpad, recolher os controles e sair. O Desktop pode preencher a tela ou aparecer inteiro.
- **Aa automático** (padrão): escolhe sozinho o tamanho de texto em que a janela encaixa sem faixa
  preta.
- **Gaveta de atalhos** (botão Shortcuts): combinações de teclas, abrir um app, digitar um texto pronto
  (com Return) e ações do Sill; atalhos só para um app; editar, reordenar e apagar.
- **Janelas agrupadas por app**: um app com várias janelas vira uma pasta que abre por cima da fileira.
- **Desktop** fixo como primeira miniatura e no topo da gaveta Apps.
- **Manter a tela acesa** em Settings.

Arquivos do Sill alterados ou novos nesta versão: `iOSClient/PictureZoom.swift`, `QuickShortcuts.swift`, `HEVCDisplayView.swift`,
`InputOverlay.swift`, `PhonePortraitLayout.swift`, `PortraitStreamScreen.swift`, `StreamClient.swift`,
`StreamScreen.swift`, `TrackpadView.swift`, `HostSettingsPanel.swift` e `TourPolicy.swift`.

## Licença

O Sill é Copyright 2026 Noah Saffer, sob a [Apache License 2.0](LICENSE). Esta versão modificada é
distribuída sob a mesma licença. "Sill" é o nome do projeto original; o Sill Plus não é endossado por
ele.
