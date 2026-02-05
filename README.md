# 🎵 NWamp - Next Web Audio Visualizer

> Uma homenagem moderna aos visualizadores clássicos dos anos 2000 (Winamp, WMP), construída com tecnologias web de ponta.

![Badge Status](https://img.shields.io/badge/Status-Stable-green)
![Three.js](https://img.shields.io/badge/Three.js-WebGL-black)
![Web Audio API](https://img.shields.io/badge/API-Web_Audio-yellow)

## 📖 Sobre o Projeto

O **NWamp** é um player de música e visualizador de áudio baseado em navegador. Ele combina a nostalgia dos efeitos visuais psicodélicos com a performance do **WebGL**.

Diferente de visualizadores comuns, o NWamp possui uma **Engine de Áudio Híbrida**: ele pode tocar seus arquivos locais (`.mp3`, `.wav`, etc.) ou **capturar o áudio do sistema** (YouTube, Spotify, Soundcloud) através da API de *Display Media*, permitindo que você visualize qualquer som que esteja tocando no seu computador.

## ✨ Funcionalidades

### 🎧 Reprodução e Streaming
- **Arquivos Locais:** Drag & Drop ou seleção de arquivos do dispositivo.
- **Modo Streaming (BETA):** Captura áudio de outras abas (YouTube, Spotify) para reagir aos visuais em tempo real.
- **Roteamento Inteligente:** Evita eco/feedback ao alternar entre arquivo local e streaming.

### 👁️ Visuais 3D Imersivos
10 modos de visualização reativos às frequências (Graves, Médios e Agudos):
- **Túnel Hiperespacial:** Um wormhole que acelera com o BPM.
- **Planeta Pulsante:** Uma esfera que se deforma com as batidas graves (Bass).
- **Vortex Neon:** Anéis geométricos de alta velocidade.
- **Terreno Retrô:** Estilo "Tron", onde montanhas surgem da música.
- **Galáxia Espiral:** Partículas que dançam e expandem.
- E mais (Cubo de Luzes, Ondas, Barras, etc.).

### 🎛️ Controle Total
- **Equalizador de 5 Bandas:** Com presets (Rock, Pop, Bass Boost, etc.).
- **Interativo:** Clique e arraste para girar a câmera 3D em torno dos efeitos.
- **Seekbar (Scrubbing):** Avance ou retroceda a música clicando ou arrastando a barra de progresso (Mobile friendly).
- **Temas:** Troque as paletas de cores (Cyberpunk, Matrix, Sunset, Ice).

## 🚀 Tecnologias Utilizadas

- **HTML5 & CSS3** (TailwindCSS para UI).
- **JavaScript (ES6+)**.
- **Three.js:** Para renderização 3D de alta performance.
- **Web Audio API:** Para análise de espectro (FFT) e filtros de equalização.
- **Simplex Noise:** Para geração de movimentos orgânicos e terrenos.
- **MediaStream API:** Para captura de áudio do sistema.

## 🛠️ Como Rodar Localmente

Este projeto não necessita de build (como Webpack ou Vite) para funcionar em sua versão básica, pois utiliza CDNs.

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/nwamp.git](https://github.com/SEU-USUARIO/nwamp.git)

2. **Abra o arquivo: Basta abrir o index.html em qualquer navegador moderno (Chrome, Edge, Firefox).**

Nota: Para o funcionamento correto do carregamento de arquivos locais (CORS) e melhor performance, recomenda-se usar uma extensão como "Live Server" no VSCode ou rodar um servidor simples Python: python -m http.server

🎮 **Como Usar o Modo Streaming (YouTube/Spotify)**
Abra o NWamp.

1. Clique no botão "CAPTURAR ÁUDIO (YOUTUBE/SPOTIFY)" na barra lateral.
2. O navegador abrirá uma janela de permissão.
3. Vá na aba "Guia do Navegador" (Chrome/Edge).
4. Selecione a aba onde a música está tocando (ex: YouTube).
5. IMPORTANTE: Marque a caixinha "Compartilhar áudio da guia" no canto inferior.
6. Clique em "Compartilhar".

📱 **Mobile**
O projeto é responsivo e suporta gestos de toque:
Toque e arraste no visualizador para girar a câmera.
Toque e arraste na barra de progresso para avançar/voltar a música.

**🤝 Contribuição**
Contribuições são bem-vindas! Sinta-se à vontade para abrir Issues ou Pull Requests com novos efeitos visuais ou melhorias de performance.

**📄 Licença**
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Feito com 💜 e muita música.

**Projeto criado para portfólio**

**🛠️ DESENVOLVIDO POR:**[pythonbasspy]

[https://www.linkedin.com/in/elias-rodrigues-de-oliveira-filho-43503123/]
