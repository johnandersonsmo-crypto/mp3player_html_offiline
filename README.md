🎵 PLAYER MP3 WEB
==============================

Player de músicas que funciona diretamente no navegador (celular ou computador). Suas músicas ficam armazenadas no próprio aparelho, permitindo editar capas, metadados e letras, além de gravar as alterações diretamente nos arquivos MP3 quando aplicável.

✨ FUNCIONALIDADES
==============================

📚 BIBLIOTECA
------------------------------

• Importação de uma pasta inteira.
• Compatibilidade com MP3, WAV, OGG, FLAC e M4A.
• Importação de arquivos LRC junto com os arquivos de áudio.
• Biblioteca salva no aparelho por meio do IndexedDB.
• Leitura automática das tags ID3: título, artista, álbum, ano, gênero, faixa e capa.
• Quando não há tags, utiliza o nome do arquivo no formato Artista - Título.
• Lista de artistas com pesquisa e opção de recolher no celular.
• Pesquisa por título, artista ou álbum.
• Carregamento progressivo de 200 músicas por vez.
• Botão "Limpar Tudo" para remover músicas, favoritos, playlists e pendências.

▶️ REPRODUÇÃO
------------------------------

• Play/Pause, música anterior e próxima.
• Reprodução aleatória (Shuffle).
• Repetição da música atual (Loop).
• Barra de progresso e controle de volume.
• Atalhos de teclado:
  - Espaço: Play/Pause.
  - Setas ← →: voltar ou avançar 5 segundos.
• Controles na tela de bloqueio e nas notificações do celular (Media Session).

❤️ FAVORITOS E PLAYLISTS
------------------------------

• Favoritar músicas pelo coração na lista ou no player.
• Criar playlists personalizadas.
• Adicionar músicas às playlists pelo menu de três pontinhos.
• Menu de playlists com:
  - Favoritos (coração vermelho).
  - Playlists criadas pelo usuário.
  - Contagem de músicas.
  - Opção para excluir playlists.
• Aba Playlists em destaque, exibindo o nome da playlist aberta.

⋮ MENU DA MÚSICA (TRÊS PONTINHOS)
------------------------------

• Adicionar à playlist.
• Criar playlist.
• Editar metadados.
• Ver letra.
• Enviar documento: compartilha o MP3 (por exemplo, pelo WhatsApp) ou baixa o arquivo quando o compartilhamento não estiver disponível.

🏷️ EDITOR DE METADADOS E CAPAS
------------------------------

• Edição de título, artista, álbum, ano, gênero e número da faixa.
• Capa:
  - Enviar imagem do aparelho.
  - Buscar imagem na internet.
  - Remover capa.
• Preenchimento automático pela internet usando MusicBrainz.
• Busca de capas no Cover Art Archive, iTunes e Deezer.
• Opção de pesquisar somente pelo nome da banda.
• Redimensionamento e compressão automática das imagens (máximo de 500 px).

🎤 LETRAS DAS MÚSICAS
------------------------------

• Nova aba dedicada à exibição de letras.
• Opção "Ver letra" disponível no menu de três pontinhos da lista de músicas e do player.
• Tela de letras com capa, título e artista.
• Reprodução da música mantida no player acima da letra.
• Suporte a letras sincronizadas no formato LRC.
• Destaque automático da linha correspondente ao momento atual da música.
• Rolagem automática para acompanhar a reprodução.
• Ao tocar em uma linha sincronizada, a reprodução avança diretamente para aquele trecho.
• A rolagem automática fica pausada por 4 segundos quando o usuário realiza uma rolagem manual.
• A letra é atualizada automaticamente quando a música muda, mesmo com a aba aberta.

BUSCA E ARMAZENAMENTO DE LETRAS
------------------------------

A busca por letras segue esta ordem de prioridade:

1. Letra previamente salva no aparelho.
2. Arquivo LRC importado ou associado à música.
3. Letra armazenada nas tags do MP3.
4. Pesquisa na internet pelo LRCLIB.

• Letras encontradas na internet são armazenadas em um banco próprio no IndexedDB.
• Após serem salvas, ficam disponíveis para consulta offline.
• Botão para pesquisar letras diretamente na internet.
• Opção para colar letras manualmente, aceitando texto comum ou formato LRC.
• Importação de arquivos LRC diretamente do aparelho.
• Importação de pastas com arquivos de áudio e letras LRC.
• Quando não existe letra disponível ou não há conexão com a internet, exibe "Letra não encontrada".
• A ausência de letras não interfere na reprodução das músicas.

🔔 ABA PENDENTES
------------------------------

Toda alteração de capa ou metadados aparece na aba Pendentes.

• Identificação das alterações com os selos:
  - Capa.
  - Metadados.
  - Capa + Metadados.
• Miniatura da imagem e identificação da origem.
• Exibição das alterações no formato antes → depois para cada campo.
• Botão Editar para reabrir a música no editor.
• Opção "Substituir arquivo local", que grava as tags ID3v2.4 e a capa dentro do MP3.
• A capa é aplicada a todas as músicas do mesmo artista e álbum, preservando os dados individuais de cada faixa.
• Somente as pendências efetivamente aplicadas são removidas da lista.

🔎 BUSCA DE CAPAS EM LOTE
------------------------------

• Botão "Buscar capas faltantes" na aba Pendentes.
• Pesquisa automática no iTunes e Deezer.
• Agrupamento das músicas por artista e álbum.
• Aceita somente resultados em que artista e álbum correspondem.
• Permite selecionar as capas desejadas para adicioná-las à aba Pendentes.

🚀 COMO USAR
==============================

1. Abra a página no navegador.
2. Clique em "Carregar Pasta" e selecione a pasta com suas músicas.
3. Clique em uma música para reproduzi-la.
4. Utilize o menu de três pontinhos para editar, adicionar às playlists, compartilhar ou visualizar a letra.
5. Para visualizar uma letra, utilize a opção "Ver letra".
6. Se a letra não estiver disponível, utilize as opções de busca na internet, colagem de texto ou importação de arquivo LRC.
7. Revise as alterações de capas e metadados na aba Pendentes.
8. Clique em "Substituir arquivo local" para gravar as alterações no MP3.

📝 OBSERVAÇÕES IMPORTANTES
==============================

• As músicas ficam armazenadas somente no próprio aparelho. Nenhum arquivo de áudio é enviado para servidores.
• A internet é utilizada para carregar as bibliotecas da página (Tailwind, jsmediatags e fonte Inter) e realizar pesquisas de metadados, capas e letras.
• Serviços utilizados nas pesquisas: MusicBrainz, Cover Art Archive, iTunes, Deezer e LRCLIB.
• A edição de metadados e a substituição de arquivos funcionam somente com arquivos MP3.
• Arquivos LRC podem ser importados e utilizados para sincronização das letras.
• Favoritos e playlists ficam armazenados no localStorage.
• A biblioteca, as pendências e as letras armazenadas ficam no IndexedDB.
• Limpar os dados do site apaga as informações armazenadas no navegador.
• Ao substituir um arquivo, a cópia salva no navegador é atualizada. O arquivo original na pasta do aparelho não é alterado.
• Para obter a versão editada, é necessário compartilhar ou baixar o MP3 atualizado.
• A disponibilidade de letras sincronizadas depende da existência de marcações de tempo no conteúdo encontrado ou importado.
• Quando não há conexão com a internet e nenhuma letra está salva localmente, a reprodução continua normalmente.

🔧 TECNOLOGIAS UTILIZADAS
==============================

• HTML5 Audio.
• Media Session API.
• JavaScript puro.
• Tailwind CSS (CDN).
• jsmediatags para leitura de ID3.
• IndexedDB.
• localStorage.
• Web Share API.
• MusicBrainz.
• Cover Art Archive.
• iTunes API.
• Deezer API.
• LRCLIB para pesquisa de letras.
• Formato LRC para sincronização de letras.

📄 LICENÇA
==============================
Projeto livre para uso pessoal e educacional.
