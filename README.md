🎵 Player MP3 Web

Player de músicas que roda no navegador (celular ou computador). Suas músicas ficam salvas no próprio aparelho, e você pode editar capas e metadados e gravar as mudanças de volta nos arquivos MP3.

✨ Funcionalidades
📚 Biblioteca
📁 Importação de uma pasta inteira (MP3, WAV, OGG, FLAC e M4A)
💾 Biblioteca salva no aparelho (IndexedDB), então as músicas continuam lá ao reabrir a página
🏷️ Leitura automática das tags ID3: título, artista, álbum, ano, gênero, faixa e capa
🔄 Quando não há tags, usa o nome do arquivo (formato Artista - Título)
🎤 Lista de artistas com busca, recolhível no celular
🔍 Pesquisa por título, artista ou álbum
⚡ Lista com carregamento progressivo (200 músicas por vez) para bibliotecas grandes
🗑️ Botão "Limpar Tudo" para remover músicas, favoritos, playlists e pendências
▶️ Reprodução
⏯️ Play/pause, anterior e próxima
🔀 Aleatório (shuffle) e 🔁 repetir música (loop)
📊 Barra de progresso e 🔊 controle de volume
⌨️ Atalhos de teclado: Espaço (play/pause) e setas ← → (volta/avança 5 s)
📱 Controles na tela de bloqueio e nas notificações do celular (Media Session)
❤️ Favoritos e Playlists
❤️ Favoritar pelo coração na lista ou no player
📝 Playlists criadas por você, com a música adicionada pelo menu de 3 pontinhos
📂 Menu Playlists com Favoritos (coração vermelho) e suas playlists, com a contagem de músicas e exclusão
✅ A aba Playlists fica em destaque e mostra o nome da playlist aberta
⋮ Menu da música (3 pontinhos)
➕ Adicionar à playlist
🆕 Criar playlist
✏️ Editar metadados
📤 Enviar documento: compartilha o MP3 (por exemplo, pelo WhatsApp) ou baixa o arquivo se o compartilhamento não for suportado
🏷️ Editor de Metadados e Capas
✏️ Edição de título, artista, álbum, ano, gênero e número da faixa
🖼️ Capa: enviar imagem do aparelho, buscar na internet ou remover
🌐 Preenchimento automático pela internet (MusicBrainz), que também busca a capa no Cover Art Archive, iTunes e Deezer
🎯 Opção de pesquisar só pelo nome da banda
📐 As imagens são redimensionadas e comprimidas automaticamente (máx. 500 px)
🔔 Aba Pendentes
🏷️ Toda alteração de capa ou metadados aparece aqui, com o selo Capa, Metadados ou Capa + Metadados
👀 Mostra a miniatura, a origem da imagem e o antes → depois de cada campo
✏️ Editar reabre a música no editor
💽 Substituir arquivo local grava as tags ID3v2.4 e a capa dentro do MP3
💿 A capa é aplicada a todas as músicas do mesmo artista e álbum. Os dados de cada música são mantidos
🧹 Só as pendências aplicadas saem da lista
🔎 Busca de Capas em Lote
🖼️ Botão "Buscar capas faltantes" nas Pendentes
🌐 Procura capas no iTunes e no Deezer para as músicas sem imagem, agrupadas por artista e álbum
✅ Aceita apenas resultados em que artista e álbum conferem
☑️ Você seleciona as capas desejadas e elas vão para a aba Pendentes
🚀 Como Usar
🌐 Abra a página no navegador
📁 Toque em Carregar Pasta e escolha a pasta com suas músicas
▶️ Toque em uma música para tocar
⋮ Use o menu de 3 pontinhos para editar, adicionar a playlists ou compartilhar
🔔 Revise as mudanças na aba Pendentes e toque em Substituir arquivo local para gravá-las no MP3
📝 Observações
🔒 As músicas ficam apenas no seu aparelho e nenhum arquivo é enviado para servidores
🌐 A internet é usada só para carregar as bibliotecas da página (Tailwind, jsmediatags e fonte Inter) e para as buscas de metadados e capas (MusicBrainz, Cover Art Archive, iTunes e Deezer)
🎧 Editar metadados e substituir arquivo funcionam apenas com arquivos .mp3
💾 Favoritos e playlists ficam no localStorage, e a biblioteca e as pendências ficam no IndexedDB. Limpar os dados do site apaga tudo
📥 Ao substituir o arquivo, a cópia salva no navegador é atualizada. O arquivo original na pasta do aparelho não é alterado, então compartilhe ou baixe o MP3 para obter a versão editada
🔧 Tecnologias
HTML5 Audio e Media Session API
JavaScript puro
Tailwind CSS (CDN)
jsmediatags para leitura de ID3
IndexedDB e localStorage
Web Share API
APIs de busca: MusicBrainz, Cover Art Archive, iTunes e Deezer
📄 Licença

Projeto livre para uso pessoal e educacional.
