# Aula 7: HyperFrames com Terminal

O jeito com mais controle: a pasta do projeto no seu computador, blocos prontos e legenda palavra por palavra.

## Links

- [Guia do Terminal (oficial)](https://code.claude.com/docs/en/terminal-guide) · Como abrir e colar.
- [Node.js](https://nodejs.org)
- [FFmpeg](https://ffmpeg.org)
- [Homebrew (brew)](https://brew.sh) · Instalador de programas do Mac.
- [Claude Code: instalar](https://code.claude.com/docs/en/setup) · Conta Pro ou maior.
- [HyperFrames: documentação](https://hyperframes.heygen.com)
- [HyperFrames: página do projeto](https://github.com/heygen-com/hyperframes)

## Para copiar e colar


**Mac: instalar Node e FFmpeg**

```
brew install node ffmpeg
```

**Windows: instalar o Node**

```
winget install OpenJS.NodeJS
```

**Windows: instalar o FFmpeg**

```
winget install Gyan.FFmpeg
```

**Conferir se está tudo pronto**

```
npx hyperframes doctor
```

**Mac: instalar o Claude Code**

```
curl -fsSL https://claude.ai/install.sh | bash
```

**Windows (PowerShell): instalar o Claude Code**

```
irm https://claude.ai/install.ps1 | iex
```

**Plugin do HyperFrames no Claude Code, passo 1**

```
claude plugin marketplace add heygen-com/hyperframes
```

**Plugin do HyperFrames no Claude Code, passo 2**

```
claude plugin install hyperframes@hyperframes
```

**Criar o projeto**

```
npx hyperframes init meu-video
```

**Entrar na pasta e abrir o Claude Code**

```
cd meu-video
```
```
claude
```

**Pedido do exemplo (dentro do Claude Code)**

```
Usando hyperframes, faz uma abertura de cinco segundos, com três camadas. Um fundo escuro, o bloco glass-hero com o título MOTION, e o bloco lt-dark-card com o nome Paulo.
```

**Conferir erros (em uma aba nova do Terminal, dentro da pasta)**

```
npm run check
```

**Ver ao vivo no estúdio**

```
npm run dev
```

**Gerar o MP4**

```
npm run render
```

**Achar um bloco pronto**

```
npx hyperframes catalog glass
```

**Instalar um bloco**

```
npx hyperframes add glass-hero
```

**Tempo de cada palavra (legenda)**

```
npx hyperframes transcribe clipe.mp4
```

## Dicas

- Abrir o Terminal no Mac: Comando + barra de espaço, digite Terminal, Enter. No Windows: tecla Windows, digite PowerShell, Enter.
- No Mac, cole com Comando V. No Windows, com Control V.
- Errou uma letra? Não acontece nada de ruim: o computador só diz que não entendeu.
- O Claude Code ocupa a janela. Abra uma aba nova do Terminal para o check, o dev e o render, e entre na pasta com cd meu-video.
- Os vermelhos do doctor (Docker, voz local, música local) são opcionais.

[Voltar para a Central de Ferramentas](README.md)
