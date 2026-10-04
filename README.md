# MMO-NigrumStar-Binaries

Binários públicos do Nigrum Star na fase de desenvolvimento: o Instalador e os arquivos que ele baixa.
Este repositório **não tem código**; tudo fica nas [releases](../../releases).

| Arquivo da release | Para quê |
|---|---|
| `NigrumStarInstaller.exe` / `NigrumStarInstaller.x86_64` | O Instalador (Windows / Linux). Baixe, abra e clique em Jogar. |
| `manifest.json`, `manifest.json.sig` | Lista assinada dos arquivos do jogo; o Instalador a confere antes de instalar. |
| `news.json`, `news.json.sig` | Novidades de atualizações e de manutenção dos servidores, mostradas no Instalador. |
| demais arquivos | Arquivos do jogo, baixados e conferidos pelo Instalador. |

O Instalador cria a pasta `game/` ao lado dele e mantém o jogo atualizado a cada abertura.
