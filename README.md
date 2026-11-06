# Editor de Livros — instaladores

Este repositório guarda só as versões do **Editor de Livros** para Windows. O código fica em outro repositório, privado.

## O que o app faz

- Escrever com uma barra de formatação no estilo do Word.
- Ver o livro paginado e em 3D.
- Montar capa, contracapa e lombada.
- Exportar o PDF do livro e a capa para a gráfica.

## Baixar

Abra **[Releases](https://github.com/murilosgodoy/editor-livros-releases/releases/latest)** e baixe o arquivo `Editor-de-Livros-Setup-X.Y.Z.exe` da versão mais recente.

Na primeira instalação, o Windows pode mostrar um aviso do SmartScreen, porque o instalador não tem assinatura digital. Clique em **Mais informações > Executar assim mesmo**.

## Novidades

As mudanças de cada versão estão nas notas da **[versão mais recente](https://github.com/murilosgodoy/editor-livros-releases/releases/latest)**. A lista de todas as versões fica na página de [Releases](https://github.com/murilosgodoy/editor-livros-releases/releases).

## Atualizações

Depois de instalado, o app procura versões novas sozinho, baixa em segundo plano e avisa quando estiver pronta para instalar. Não é preciso baixar de novo por aqui.

Para entrar, use a conta criada pelo administrador.

## Antivírus

O Windows Defender pode marcar por engano o arquivo `ffmpeg.dll`. Ele é um componente padrão do Electron, a base do app, e serve para áudio e vídeo. O arquivo foi conferido e é idêntico ao oficial.

O motivo é o mesmo do aviso do SmartScreen: o instalador ainda não tem assinatura digital.

Se acontecer, abra **Segurança do Windows > Proteção contra vírus e ameaças > Histórico de proteção** e restaure o arquivo. Se quiser, envie um relato em microsoft.com/wdsi/filesubmission.
