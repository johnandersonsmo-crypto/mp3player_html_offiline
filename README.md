# 🎵 Player MP3 Web

Player de músicas que funciona diretamente no navegador (celular ou computador). Suas músicas ficam armazenadas no próprio aparelho, permitindo editar capas e metadados e gravar as alterações diretamente nos arquivos MP3.

## ✨ Funcionalidades

### 📚 Biblioteca
- Importação de uma pasta inteira.
- Compatibilidade com MP3, WAV, OGG, FLAC e M4A.
- Biblioteca salva no aparelho por meio do IndexedDB.
- Leitura automática das tags ID3: título, artista, álbum, ano, gênero, faixa e capa.
- Quando não há tags, utiliza o nome do arquivo no formato `Artista - Título`.
- Lista de artistas com pesquisa e opção de recolher no celular.
- Pesquisa por título, artista ou álbum.
- Carregamento progressivo de 200 músicas por vez.
- Botão **Limpar Tudo**, que remove músicas, favoritos, playlists e pendências.

### ▶️ Reprodução
- Play/Pause, música anterior e próxima.
- Reprodução aleatória (Shuffle).
- Repetição da música atual (Loop).
- Barra de progresso e controle de volume.
- Atalhos de teclado:
  - Espaço: Play/Pause.
  - Setas ← →: voltar ou avançar 5 segundos.
- Controles na tela de bloqueio e nas notificações do celular (Media Session).

### ❤️ Favoritos e Playlists
- Favoritar músicas pelo coração na lista ou no player.
- Criar playlists personalizadas.
- Adicionar músicas às playlists pelo menu de três pontinhos.
- Menu de playlists com:
  - Favoritos (coração vermelho).
  - Playlists criadas pelo usuário.
  - Contagem de músicas.
  - Opção para excluir playlists.
- Aba Playlists em destaque, exibindo o nome da playlist aberta.

### ⋮ Menu da música (três pontinhos)
- Adicionar à playlist.
- Criar playlist.
- Editar metadados.
- Enviar documento: compartilha o MP3 (por exemplo, pelo WhatsApp) ou baixa o arquivo quando o compartilhamento não estiver disponível.

### 🏷️ Editor de Metadados e Capas
- Edição de título, artista, álbum, ano, gênero e número da faixa.
- Capa:
  - Enviar imagem do aparelho.
  - Buscar imagem na internet.
  - Remover capa.
- Preenchimento automático pela internet usando MusicBrainz.
- Busca de capas no Cover Art Archive, iTunes e Deezer.
- Opção de pesquisar somente pelo nome da banda.
- Redimensionamento e compressão automática das imagens (máximo de 500 px).

### 🔔 Aba Pendentes
Toda alteração de capa ou metadados aparece na aba Pendentes.

- Identificação das alterações com os selos:
  - Capa.
  - Metadados.
  - Capa + Metadados.
- Miniatura da imagem e identificação da origem.
- Exibição das alterações no formato antes → depois para cada campo.
- Botão Editar para reabrir a música no editor.
- Opção **Substituir arquivo local**, que grava as tags ID3v2.4 e a capa dentro do MP3.
- A capa é aplicada a todas as músicas do mesmo artista e álbum, preservando os dados individuais de cada faixa.
- Somente as pendências efetivamente aplicadas são removidas da lista.

### 🔎 Busca de Capas em Lote
- Botão **Buscar capas faltantes** na aba Pendentes.
- Pesquisa automática no iTunes e Deezer.
- Agrupamento das músicas por artista e álbum.
- Aceita somente resultados em que artista e álbum correspondem.
- Permite selecionar as capas desejadas para adicioná-las à aba Pendentes.

## 🚀 Como Usar

1. Abra a página no navegador.
2. Clique em **Carregar Pasta** e selecione a pasta com suas músicas.
3. Clique em uma música para reproduzi-la.
4. Utilize o menu de três pontinhos para editar, adicionar às playlists ou compartilhar.
5. Revise as alterações na aba Pendentes.
6. Clique em **Substituir arquivo local** para gravar as alterações no MP3.

## 📝 Observações importantes

- As músicas ficam armazenadas somente no próprio aparelho. Nenhum arquivo é enviado para servidores.
- A internet é utilizada apenas para carregar as bibliotecas da página (Tailwind, jsmediatags e fonte Inter) e realizar pesquisas de metadados e capas (MusicBrainz, Cover Art Archive, iTunes e Deezer).
- A edição de metadados e a substituição de arquivos funcionam somente com arquivos MP3.
- Favoritos e playlists ficam armazenados no localStorage.
- A biblioteca e as pendências ficam armazenadas no IndexedDB.
- Limpar os dados do site apaga todas as informações armazenadas.
- Ao substituir um arquivo, a cópia salva no navegador é atualizada. O arquivo original na pasta do aparelho não é alterado.
- Para obter a versão editada, é necessário compartilhar ou baixar o MP3 atualizado.

## 🔧 Tecnologias utilizadas

- HTML5 Audio.
- Media Session API.
- JavaScript puro.
- Tailwind CSS (CDN).
- jsmediatags para leitura de ID3.
- IndexedDB.
- localStorage.
- Web Share API.
- MusicBrainz.
- Cover Art Archive.
- iTunes API.
- Deezer API.

## 📄 Licença
Projeto livre para uso pessoal e educacional.
