# As Cr&#244;nicas do V&#233;u Partido - Cartas

Um conjunto de 18 cartas originais para um jogo de aventura e tesouro no universo
fantasia medieval sombria de "As Cr&#244;nicas do V&#233;u Partido".

## Estrutura de Pastas

cartas/
├── index.html                       # P&#225;gina da galeria principal
├── README.md                        # Este arquivo
├── assets/
│   ├── css/
│   │   └── style.css               # Estilos globais do tema sombrio
│   └── js/
│       └── main.js                 # Scripts globais (se houver)
├── cartas/
│   ├── M001_O_Cobrador_de_Almas.html    # Carta 1: Masmorra (monstro)
│   ├── M002_Draco_Penhorista.html       # Carta 2: Masmorra (monstro)
│   ├── M003_Galeria_que_Não_Termina.html # Carta 3: Masmorra (maldição)
│   ├── M004_Baú_de_Tragédia.html        # Carta 4: Masmorra (monstro)
│   ├── M005_Espirro_da_Bruxa_Cinzenta.html # Carta 5: Masmorra (maldição)
│   ├── M006_Cavaleiro_do_Sino_Oco.html  # Carta 6: Masmorra (monstro)
│   ├── M007_Pacto_das_Trash_Velas.html  # Carta 7: Masmorra (maldição)
│   ├── M008_Ogro_Gourmet.html           # Carta 8: Masmorra (monstro)
│   ├── T001_Grevas_do_Salto_Imprudente.html # Carta 9: Tesouro (equipamento)
│   ├── T002_Cutelo_do_Sol_Afogado.html  # Carta 10: Tesouro (equipamento)
│   ├── T003_Selo_de_Convocação_Emergencial.html # Carta 11: Tesouro (uso único)
│   ├── T004_Bolsa_do_Fundo_Improvável.html  # Carta 12: Tesouro (uso único)
│   ├── T005_Elmo_Contra_Profecias.html  # Carta 13: Tesouro (equipamento)
│   ├── T006_Anel_da_Última_Palavra.html # Carta 14: Tesouro (equipamento)
│   ├── T007_Poção_do_Segundo_Flégio.html # Carta 15: Tesouro (uso único)
│   ├── T008_Manto_da_Porta_Errada.html  # Carta 16: Tesouro (equipamento)
│   ├── T009_Moeda_do_Rei_Esquecido.html # Carta 17: Tesouro (item)
│   └── T010_Chave_do_Sepulcro_Sem_Dono.html # Carta 18: Tesouro (item)
└── imagens/                         # Aqui v&#227;o as ilustra&#231;&#245;es geradas por IA

## Como Acessar

1. Abra o arquivo `index.html` em um navegador de internet
2. Clique em qualquer carta para ver os detalhes completos
3. Para cada carta, substitua o `<img>` pela imagem gerada (veja abaixo)

## Como Adicionar Ilustra&#231;&#245;es

1. Gere as imagens usando ComfyUI ou outro gerador de IA
2. Coloque-as na pasta `imagens/`
3. Atualize o HTML de cada carta substituindo o `<img>` pela imagem real

### Exemplo de estrutura de imagens

```
imagens/
├── M001_Cobrador_de_Almas.png
├── M002_Draco_Penhorista.png
├── T001_Grevas_do_Salto_Imprudente.png
└── ...
```

### Atualizando uma carta

No arquivo `cartas/M001_O_Cobrador_de_Almas.html`, substitua:

```html
<img src="../imagens/M001_Cobrador_de_Almas.png" alt="Ilustra&#231;&#227;o" style="width:100%; height:100%; object-fit:cover;">
```

## Caracter&#237;sticas do Tema

- **Estilo:** Fantasia medieval sombria
- **Ilustra&#231;&#245;es:** Pintura &#224; m&#227;o com textura de &#211;leo e pergaminho
- **Ilumina&#231;&#227;o:** Dram&#225;tica de tochas, luar e magia arcana
- **Tom:** Armaduras gastas, s&#237;mbolos arcanos, ru&#237;nas antigas
- **Humor:** Negro sutil e express&#245;es exageradas

## Nota Legal

Conte&#250;do original. As cartas abaixo preservam categorias e mec&#226;nicas gerais de
jogos de aventura e tesouro, mas n&#227;o reproduzem cartas oficiais de Munchkin
nem personagens, locais ou textos de Baldur's Gate.
