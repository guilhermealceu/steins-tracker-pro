# Steins;Tracker

Steins;Tracker e um aplicativo desktop para Windows que monitora o tempo de jogo 100% localmente e exibe tudo em um dashboard visual e interativo. Foco em privacidade, desempenho e simplicidade.

Gratis: https://github.com/guilhermealceu/steins-tracker-pro/releases
Comprar (DLCs/Pro): https://pagbuypix.discloud.app/

## Principais recursos

- Deteccao automatica de jogos em segundo plano
- Painel de estatisticas
  - Tempo total por jogo
  - Medias diarias e historico por periodo
  - Sessoes, streaks e metas
  - Heatmap anual e graficos radiais
- Visao por jogo
  - Tempo total, numero de sessoes, ultima jogada
  - Adicao manual ou por pasta
  - Nomes amigaveis e icones personalizados
- Exportacao de logs (CSV)
- Interface personalizavel
  - Wallpapers por pagina
  - Temas, blur, opacidade e modo escuro
  - Ocultar elementos de UI
- Wizard de boas-vindas com deteccao automatica de idioma
- Importacao de visuais e configuracoes via JSON
- Monitoramento de sistema
  - CPU, RAM, GPU
  - Temperaturas (CPU/GPU)
  - Rede, ping e FPS
- Acesso via celular (LAN)
  - QR Code para abrir o dashboard na rede local
  - Uso automatico do IP local
- Dados locais apenas (privacidade)
- Instalador tudo-em-um (servidor local e monitor embutidos; nao precisa Node.js)
- Atualizacoes automaticas via GitHub Releases
- Suporte a versao Pro/DLCs por token

## Instalacao

1. Baixe o instalador .exe mais recente em Releases.
2. Execute o instalador e siga o assistente.
3. Opcional: inicializar com o Windows.

Compatibilidade: Windows 10/11 64-bit.

## Tecnologias

- Electron
- Node.js (embutido)
- Express, Chart.js, systeminformation, ping
- HTML5 + CSS3 + JavaScript (vanilla)

## Privacidade

Todos os dados ficam salvos localmente na pasta de Documentos do usuario. Nada e enviado para servidores externos sem acao explicita.

Desenvolvido por Guilherme Dill (https://github.com/guilhermealceu)
Repositorio: https://github.com/guilhermealceu/steins-tracker-pro
