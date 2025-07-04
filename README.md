# 🎼 Amostras Geradas: Desenvolvimento de um Sistema Gerador de Música Simbólica para Jogos Eletrônicos do Gênero RPG

Este repositório contém as amostras musicais geradas como resultado do Trabalho de Conclusão de Curso. O projeto utiliza redes neurais recorrentes (LSTM) para gerar sequências musicais em formato MIDI, incluindo uma opção para representação sonora, com base em padrões aprendidos a partir da base de dados NES-MDB, rotulada com diferentes emoções.

## 🧠 Sobre o projeto

O modelo foi treinado com exemplos musicais rotulados com as seguintes emoções:

- Ação: Músicas que evocam movimento, com um rítmo acelerado.
- Aventura: Músicas que descrevem cenários, que podem evocar um sentimento de inspiração, jornada.
- Batalha: Músicas com rítmos acelerados e intensos, evocam um sentimento de conflito, perigo.
- Castelo: Músicas com ritmos calmos, exaltando sentimentos de nobreza.
- Cômico: Músicas que evocam um sentimento cômico, eventos que causam humor.
- Heroico: Músicas que exaltam heroísmo, glória, protagonismo.
- Melancólico: Músicas com temática triste, com rítmos lentos e poucas notas na melodia.
- Mistério: Músicas com rítmos lentos, que evocam o sentimento de medo, suspense.
- Tranquilidade: Músicas calmas e alegres, evocam um sentimento de paz, de estar em um ambiente familiar, calmo.

Cada pasta deste repositório contém as amostras sonoras geradas para uma dessas emoções. Cada diretório contém arquivos `.wav` representando as melodias geradas com base nas características emocionais aprendidas pelo modelo.

## 📁 Organização

output/

├── action_tense/

├── adventure/

├── battle/

├── castle/

├── comedic/

├── creepy_mystery/

├── heroic/

├── melancholic/

└── peaceful/
