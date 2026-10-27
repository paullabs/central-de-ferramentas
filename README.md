# Central de Ferramentas

Todas as ferramentas do curso, com o link certo de cada uma. Os números (estrelas e licença) foram conferidos em 27/10/2026 e mudam toda semana.

> Link quebrado? Avise na comunidade. Aqui ele é arrumado num lugar só.

## Como usar

1. Ache a ferramenta na tabela abaixo e clique no link dela.
2. Antes de instalar, faça o teste dos 30 segundos da aula 1: estrelas, última atualização, dono e licença.
3. Siga o jeito de instalar da coluna **Como instalar** (aula 2).
4. No fim da página tem o material de cada aula, com os comandos para copiar.

## Ferramentas do curso

| Ferramenta | Para que serve | Como instalar | Licença | Estrelas | Aulas |
|---|---|---|---|---|---|
| **Voicebox** | Clona a sua voz e narra qualquer texto, no seu computador. É o ElevenLabs grátis. | Instalador | MIT | 58,7 mil | 1, 2 |
| **OpenCut** | Editor de vídeo grátis, parecido com o CapCut. Roda no navegador, sem instalar. | Navegador | MIT | 96,5 mil | 2, 4 |
| **Buzz** | Escuta o áudio de um vídeo e escreve o que foi falado, com o tempo de cada trecho. | Instalador | MIT | 22,2 mil | 5 |
| **HyperFrames** | Cria vídeo animado a partir de um pedido que você escreve. Abertura, título, legenda palavra por palavra. | Aplicativo (aula 6) ou Terminal (aula 7) | Apache-2.0 | 73,9 mil | 2, 6, 7 |
| **Pinokio** | Uma loja de ferramentas de IA. Você escolhe, e ele instala tudo que a ferramenta precisa. | Instalador | MIT | 8,3 mil | 2 |
| **ComfyUI** | Gera imagem e vídeo com IA, montando o caminho em blocos. | Pinokio | GPL-3.0 | 143,6 mil | 2 |
| **MoneyPrinterTurbo** | Cria um vídeo curto a partir de um tema ou palavra-chave. | Ainda não ensinado | MIT | 135,8 mil | 3 |

### Voicebox

Clona a sua voz e narra qualquer texto, no seu computador. É o ElevenLabs grátis.

- [Página do projeto](https://github.com/jamiepine/voicebox)
- [Baixar o instalador (Releases)](https://github.com/jamiepine/voicebox/releases)

> O programa é MIT, mas cada motor de voz dentro dele tem a licença própria. Antes de usar em trabalho pago, confira a do motor que você escolheu.

### OpenCut

Editor de vídeo grátis, parecido com o CapCut. Roda no navegador, sem instalar.

- [Abrir o editor](https://opencut.app)
- [Página do projeto](https://github.com/OpenCut-app/OpenCut)

> Está em beta e sendo reescrito. Hoje, o que funciona é o site opencut.app.

### Buzz

Escuta o áudio de um vídeo e escreve o que foi falado, com o tempo de cada trecho.

- [Página do projeto](https://github.com/chidiwilliams/buzz)
- [Baixar o instalador (Releases)](https://github.com/chidiwilliams/buzz/releases)

> Os arquivos para baixar ficam em Releases, na parte Assets. No Windows são três arquivos juntos.

### HyperFrames

Cria vídeo animado a partir de um pedido que você escreve. Abertura, título, legenda palavra por palavra.

- [Baixar o aplicativo Studio (Mac e Windows)](https://hyperframes.dev/studio)
- [Guia de início](https://hyperframes.heygen.com/quickstart)
- [Documentação](https://hyperframes.heygen.com)
- [Página do projeto](https://github.com/heygen-com/hyperframes)

> O aplicativo Studio pede uma conta grátis da HeyGen e usa o seu plano do Claude. O Claude Code exige conta Pro ou maior.

### Pinokio

Uma loja de ferramentas de IA. Você escolhe, e ele instala tudo que a ferramenta precisa.

- [Site e download](https://pinokio.co)
- [Página do projeto](https://github.com/pinokiocomputer/pinokio)

### ComfyUI

Gera imagem e vídeo com IA, montando o caminho em blocos.

- [Página do projeto](https://github.com/Comfy-Org/ComfyUI)

> Ocupa dezenas de giga com os modelos. Cada modelo de IA tem a sua própria licença. O projeto mudou de dono: o endereço certo hoje é Comfy-Org.

### MoneyPrinterTurbo

Cria um vídeo curto a partir de um tema ou palavra-chave.

- [Página do projeto](https://github.com/harry0703/MoneyPrinterTurbo)

> Foi só mostrado na aula 3, para ensinar a traduzir a página. Ainda não tem aula de instalação.

## Outros links úteis

- [Claude](https://claude.ai) · Assistente que lê o manual com você, instala e escreve os arquivos.
- [Claude Code](https://code.claude.com/docs/en/setup) · O Claude dentro do Terminal. Precisa de conta Pro ou maior. Guia de instalação oficial.
- [Guia do Terminal (oficial)](https://code.claude.com/docs/en/terminal-guide) · Como abrir o Terminal e colar um comando, passo a passo.
- [Node.js](https://nodejs.org) · Programa que roda o HyperFrames no Terminal (aula 7).
- [FFmpeg](https://ffmpeg.org) · Programa que junta as imagens num vídeo MP4 (aula 7).
- [Homebrew (brew)](https://brew.sh) · Instalador de programas do Mac, usado na aula 7.
- [HeyGen](https://www.heygen.com) · Conta grátis para entrar no aplicativo HyperFrames Studio (aula 6).
- [ElevenLabs](https://elevenlabs.io) · O serviço pago que o Voicebox substitui (aula 1).
- [Busca do GitHub](https://github.com/search) · Para achar projetos novos (aula 3).

## Skills e plugin do HyperFrames

O HyperFrames ensina o seu Claude Code a criar vídeo. Escolha UM método. Os dois valem para o computador todo, menos o último comando, que vale só para a pasta do projeto.

**Método 1: plugin (recomendado)**

```
claude plugin marketplace add heygen-com/hyperframes
claude plugin install hyperframes@hyperframes
```
Depois, abra uma conversa nova do Claude Code.

**Método 2: skills avulsas, para o computador todo**

```
npx hyperframes skills update
```

**Método 2b: skills avulsas, só dentro de uma pasta**

```
npx skills add heygen-com/hyperframes
```
Rode dentro da pasta do projeto.

## Material de cada aula

- [Aula 1: O que é o GitHub e como ler um projeto](aula-01.md)
- [Aula 2: Como instalar qualquer projeto](aula-02.md)
- [Aula 3: A Central de Ferramentas e como achar projetos](aula-03.md)
- [Aula 4: Editando um vídeo no OpenCut](aula-04.md)
- [Aula 5: Transcrevendo com o Buzz](aula-05.md)
- [Aula 6: HyperFrames sem Terminal](aula-06.md)
- [Aula 7: HyperFrames com Terminal](aula-07.md)
