<h1 align="center">🧪 Bruno Gebara</h1>

<p align="center"><b>📊 Lidero um time de dados · Experimentos com dados, Python e IA</b><br><i>I lead a data team · Experiments with data, Python and AI</i></p>

<p align="center"><b><i>Este GitHub é o meu laboratório: registro aqui cada avanço.</i></b><br>
<i>This GitHub is my lab: I log every step of progress here.</i></p>

---

## 📰 Novidades · What's new

<sub>As 3 últimas novidades, da mais recente para a mais antiga · The 3 latest updates, newest first</sub>

| Data · Date | Novidade · What's new |
|---|---|
| **27/10/2026** | 🏛️ **[Quem é meu deputado estadual (SP)](https://reset-hightide.github.io/quem-e-meu-deputado-estadual/)**: painel dos 94 deputados estaduais de São Paulo com projetos apresentados, quantos foram aprovados e presença nas comissões, em vermelho (esquerda), cinza (centro) e azul (direita), atualizado sozinho todos os dias<br><i>Dashboard of the 94 São Paulo state deputies: bills filed, how many passed and committee attendance, in red (left), gray (center) and blue (right), updated automatically every day</i> |
| **26/10/2026** | 🏛️ **[Quem é meu deputado](https://reset-hightide.github.io/quem-e-meu-deputado/)**: painel dos 513 deputados federais com presença nas sessões, projetos apresentados e quantos foram aprovados, em vermelho (esquerda), cinza (centro) e azul (direita), atualizado sozinho todos os dias<br><i>Dashboard of Brazil's 513 federal deputies: attendance, bills filed and how many passed, in red (left), gray (center) and blue (right), updated automatically every day</i> |
| **26/10/2026** | 🗳️ **[Votos após as 17h no 2º turno de 2026](https://reset-hightide.github.io/votos-apos-17h-2t-2026/)**: quantos votos foram registrados depois das 17h, na prorrogação até as 19h, explicado em linguagem simples, com fontes e tom neutro; os logs de urna do TSE ainda não saíram, então uma segunda versão virá depois<br><i>How many votes were cast after 5 pm, during the extension to 7 pm, explained in plain language with sources and a neutral tone; the TSE ballot-box logs are not out yet, so a second version will follow</i> |

---

## 🛠️ Projetos · Projects

<sub>Cada projeto mostra o que é e o que me ensinou · Each project shows what it is and what it taught me</sub>

<h3 align="center">🤖 Automações com Claude · Claude automations</h3>

<p align="center"><b>🎬 <a href="https://github.com/reset-hightide/drive-video-sorter">Drive Video Sorter</a></b><br>
Automação que separa vídeos e fotos soltos da câmera: transcreve a fala, lê o horário de gravação e interpreta a imagem para entender o contexto, cria as pastas por assunto no Google Drive e organiza tudo por conteúdo. Pensada para quem grava muito material para redes sociais<br>
<b>💡 O que me ensinou:</b> transcrição de fala, leitura de metadados de vídeo, IA para interpretar imagens e a API do Google Drive para organizar tudo sozinho<br>
<i>Automation that sorts loose camera videos and photos: it transcribes speech, reads the recording time and interprets the image to understand context, then creates folders by topic in Google Drive and sorts everything by content. Built for anyone who shoots a lot of social media material</i><br>
<i><b>💡 What it taught me:</b> speech transcription, reading video metadata, AI to interpret images and the Google Drive API to organize everything on its own</i></p>

<p align="center"><b>🎞️ <a href="https://github.com/reset-hightide/course-backup-kit">Course Backup Kit</a></b><br>
Automação para guardar uma cópia dos cursos online que você comprou: baixa os vídeos e anexos de cada aula, mantém a mesma estrutura de módulos e aulas do site, gera catálogo e relatório e avisa o progresso (WhatsApp, Telegram...). Testado em um curso real: 190 vídeos e 316 anexos, 24 GB, sem erros<br>
<b>💡 O que me ensinou:</b> baixar vídeo em streaming (HLS) com ffmpeg, trabalhar com arquivos grandes sem perder nada (log e relatório) e avisar o progresso por WhatsApp, Telegram e ntfy<br>
<i>Automation to keep a copy of the online courses you bought: it downloads each lesson's videos and attachments, keeps the site's module and lesson structure, builds a catalog and report, and sends progress alerts (WhatsApp, Telegram...). Tested on a real course: 190 videos and 316 attachments, 24 GB, zero errors</i><br>
<i><b>💡 What it taught me:</b> downloading streaming video (HLS) with ffmpeg, handling large files without losing anything (log and report) and sending progress alerts through WhatsApp, Telegram and ntfy</i></p>

<h3 align="center">📊 Dados · Data</h3>

<p align="center"><b>📊 <a href="https://github.com/reset-hightide/-brasil-por-governo">Brasil por Governo</a></b><br>
33 indicadores do Brasil, de 1979 a 2025, por governo<br>
<b>💡 O que me ensinou:</b> consumir APIs públicas, organizar séries históricas de décadas e transformar muitos indicadores em um painel que qualquer pessoa entende<br>
<i>33 indicators of Brazil, 1979 to 2025, by administration</i><br>
<i><b>💡 What it taught me:</b> using public APIs, organizing decades of historical series and turning many indicators into a dashboard anyone can understand</i></p>

<p align="center"><b>🏛️ <a href="https://github.com/reset-hightide/quem-e-meu-deputado-estadual">Quem é meu deputado estadual (SP)</a></b><br>
Painel dos 94 deputados estaduais de São Paulo: quantos projetos cada um apresentou, quantos foram aprovados e como é a presença nas reuniões das comissões. A Alesp não divulga presença em plenário, por isso a medida é a de comissões, e o painel avisa isso. Os deputados aparecem em vermelho (esquerda), cinza (centro) e azul (direita). Os dados são oficiais, da Alesp, e um robô no GitHub Actions atualiza tudo sozinho todos os dias e avisa no celular se der certo ou errado. <a href="https://reset-hightide.github.io/quem-e-meu-deputado-estadual/">Abrir o painel</a><br>
<b>💡 O que me ensinou:</b> lidar com dados abertos incompletos (sem presença em plenário), ler arquivos XML de centenas de MB, validar os dados antes de publicar e ser transparente sobre o que a fonte não entrega<br>
<i>Dashboard of the 94 São Paulo state deputies: how many bills each filed, how many passed and committee-meeting attendance. The Assembly does not publish plenary attendance, so the measure is committee attendance, and the dashboard says so. Deputies appear in red (left), gray (center) and blue (right). The data is official, from Alesp, and a GitHub Actions robot refreshes everything on its own every day and sends a phone alert on success or failure. <a href="https://reset-hightide.github.io/quem-e-meu-deputado-estadual/">Open the dashboard</a></i><br>
<i><b>💡 What it taught me:</b> dealing with incomplete open data (no plenary attendance), reading XML files of hundreds of MB, validating data before publishing and being transparent about what the source does not provide</i></p>

<p align="center"><b>🏛️ <a href="https://github.com/reset-hightide/quem-e-meu-deputado">Quem é meu deputado</a></b><br>
Painel dos 513 deputados federais: quantas sessões cada um frequentou, quantos projetos apresentou e quantos foram aprovados. Os deputados aparecem pelo nome, em vermelho (esquerda), cinza (centro) e azul (direita), com rankings e ficha de cada um. Os dados são oficiais, da Câmara dos Deputados, e um robô no GitHub Actions atualiza tudo sozinho todos os dias e avisa no celular se der certo ou errado. <a href="https://reset-hightide.github.io/quem-e-meu-deputado/">Abrir o painel</a><br>
<b>💡 O que me ensinou:</b> usar a API e os arquivos em lote da Câmara, montar um robô em Python no GitHub Actions que roda sozinho todo dia e usar o ntfy para receber no celular o aviso de que deu certo ou errado<br>
<i>Dashboard of Brazil's 513 federal deputies: how many sessions each attended, how many bills they filed and how many passed. Deputies are listed by name in red (left), gray (center) and blue (right), with rankings and a profile for each. The data is official, from the Chamber of Deputies, and a GitHub Actions robot refreshes everything on its own every day and sends a phone alert on success or failure. <a href="https://reset-hightide.github.io/quem-e-meu-deputado/">Open the dashboard</a></i><br>
<i><b>💡 What it taught me:</b> using the Chamber's API and bulk files, building a Python robot on GitHub Actions that runs by itself every day and using ntfy to get a phone alert on success or failure</i></p>

<p align="center"><b>🗳️ <a href="https://github.com/reset-hightide/votos-apos-17h-2t-2026">Votos após as 17h no 2º turno de 2026</a></b><br>
Explica, em linguagem simples e com fontes, quantos votos foram registrados depois das 17h, quando o STF prorrogou a votação até as 19h. Os números vêm de reportagens com dados do TSE, e os logs de urna ainda não saíram, então haverá uma segunda versão. <a href="https://reset-hightide.github.io/votos-apos-17h-2t-2026/">Abrir o painel</a><br>
<b>💡 O que me ensinou:</b> explicar dados difíceis em linguagem simples, citar sempre as fontes, manter tom neutro em tema sensível e entender como funcionam os logs de urna do TSE<br>
<i>Explains, in plain language and with sources, how many votes were cast after 5 pm, when the Supreme Court extended voting to 7 pm. The numbers come from reports based on TSE data, and the ballot-box logs are not out yet, so a second version will follow. <a href="https://reset-hightide.github.io/votos-apos-17h-2t-2026/">Open the dashboard</a></i><br>
<i><b>💡 What it taught me:</b> explaining hard data in plain language, always citing sources, keeping a neutral tone on a sensitive topic and understanding how TSE ballot-box logs work</i></p>

<h3 align="center">🎨 Front-end</h3>

<p align="center"><b>🛡️ <a href="https://github.com/reset-hightide/heros-shield-artwork-hd">Hero's Shield Artwork HD</a></b><br>
Mod de arte HD para Zelda 64: Recompiled (Majora's Mask)<br>
<b>💡 O que me ensinou:</b> front-end temático, com visual inspirado no jogo, e modelagem 3D do escudo<br>
<i>HD artwork mod for Zelda 64: Recompiled (Majora's Mask)</i><br>
<i><b>💡 What it taught me:</b> themed front-end, with a look inspired by the game, and 3D modeling of the shield</i></p>

<h3 align="center">🎴 Magic</h3>

<p align="center"><b>🎴 <a href="https://github.com/reset-hightide/mtg-lands-calculator">Calculadora de Terrenos</a></b><br>
Quantos terrenos e quantas fontes de cada cor o seu deck precisa: cole a lista, leia a resposta e compre uma mão de teste. Baseada no meu TCC (regressão linear em 39 mil decks), com Scryfall, Archidekt e Excel<br>
<b>💡 O que me ensinou:</b> regressão linear aplicada a um problema real e o uso de APIs (Scryfall e Archidekt) junto com Excel<br>
<i>How many lands and sources of each color your deck needs: paste the list, read the answer and draw a test hand. Based on my thesis (linear regression on 39k decks), with Scryfall, Archidekt and Excel</i><br>
<i><b>💡 What it taught me:</b> linear regression applied to a real problem and using APIs (Scryfall and Archidekt) together with Excel</i></p>
