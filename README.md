# Pareamento do Codex no Windows com celular Android

Registro da solução encontrada em 8 de outubro de 2026.

## Sintoma

O aplicativo no celular oferecia a opção de pareamento e abria a câmera, mas o QR code não havia sido localizado no aplicativo Windows.

Segundo o relato do usuário, a opção **Conexões** passou a aparecer nas Configurações depois de acessar **foto do perfil no canto inferior esquerdo > Ajuda > Configurar remoto**.

## Solução encontrada

1. Clicar na **foto do perfil**, no canto inferior esquerdo do aplicativo Windows.
2. Acessar **Ajuda > Configurar remoto**.
3. Abrir as **Configurações**. Após utilizar o caminho acima, a opção **Conexões** apareceu nessa tela.
4. Na lista lateral, localizar **Conexões** na seção **Programação** e selecioná-la.
5. Seguir o fluxo de controle deste PC para gerar o código e concluir o pareamento no celular.

Na instalação observada, depois de acessar **Ajuda > Configurar remoto**, **Conexões** apareceu na parte inferior da lista lateral de Configurações. O usuário confirmou que conseguiu concluir o pareamento.

Essa sequência foi observada pelo usuário nessa instalação; não foi confirmado qual mecanismo interno fez a opção aparecer.

## Ambiente observado

- Aplicativo Windows: **26.1002.52244**, build **13536**, canal **prod**.
- Sistema: **Windows 10 Pro 22H2**, 64 bits.
- Celular: **Samsung Galaxy S23** com Android.

Este registro descreve a solução observada nessa instalação. A posição e os nomes dos controles podem mudar entre versões.

Referência: [documentação oficial de conexões remotas](https://learn.chatgpt.com/docs/remote-connections).
