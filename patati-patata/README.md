# Patati Patata

Patati Patata é um chatbot de ficheiro único: uma página HTML autónoma com duas vozes, revelação rítmica do texto e percussão sintetizada. Podes conversar com diferentes modelos de linguagem, ajustar o som e guardar preferências neste browser.

## Como usar

1. Abre [`index.html`](./index.html) num browser recente. Não é necessário instalar dependências nem iniciar um servidor. A fonte Google Fonts é opcional e tem alternativas de sistema.
2. Na primeira visita, percorre ou salta a apresentação. Abre as definições pela engrenagem e escolhe um fornecedor.
3. Introduz **a tua própria chave API**, seleciona ou escreve um modelo e guarda as definições. Em alternativa, liga a um servidor local compatível, como Ollama ou LM Studio.
4. Escreve uma mensagem e carrega em Enter para enviar; Shift+Enter insere uma linha. Usa as definições para ajustar o áudio, os perfis e a privacidade.

## Chaves API e privacidade

Cada pessoa tem de obter e usar a sua própria chave no fornecedor escolhido. **Não coloques uma chave no código, neste repositório, num screenshot ou numa publicação.** A utilização pode ter custos e está sujeita aos limites e às políticas do fornecedor.

A chave é enviada para o endpoint do fornecedor selecionado. Conforme a opção «Lembrar chave neste browser», fica guardada no armazenamento local do browser ou apenas durante a sessão. As conversas permanecem na página e não são guardadas pelo projeto; o fornecedor pode tratar ou conservar os pedidos de acordo com a sua própria política. As definições incluem opções para apagar a conversa, a memória das personagens ou todos os dados locais.

## Inspirações e identidade

As referências de tom e de estilo incluem **Calvin & Hobbes** e **Patapon**, mencionadas apenas por palavras. Patati Patata, as suas personagens, textos, ilustrações e sons são originais: este projeto não reproduz personagens, imagens, logótipos, música ou outros elementos dessas obras e não é afiliado aos respetivos titulares.

## Licença

Este repositório não inclui atualmente um ficheiro `LICENSE`. Sem uma licença, não se deve presumir que o código pode ser reutilizado, modificado ou redistribuído. Se quiseres permitir essa reutilização, escolhe uma licença e acrescenta o respetivo ficheiro.
