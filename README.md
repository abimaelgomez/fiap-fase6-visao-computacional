# FarmTech Solutions — Visão Computacional (FIAP · Fase 6)

Detector de **animais peçonhentos** (**cobras** e **aranhas**) para a segurança de trabalhadores rurais, construído com YOLOv5 e comparado com outras duas abordagens de visão computacional.

## Integrantes

| Nome | RM |
|---|---|
| Abimael Gomes | RM573528 |
| Élton Longaray | RM_____ |
| Natália Gimenez | RM_____ |

## Vídeo demonstrativo

▶️ [Assista no YouTube (não listado)](LINK_DO_VIDEO)

## Notebooks

| Entrega | Conteúdo | Abrir |
|---|---|---|
| **1** | Dataset (200 + 200 imagens, 160/20/20), rotulação (Open Images + pacote de revisão no Make Sense), YOLOv5 customizado com 30 × 60 épocas, validação, teste e conclusões | [`AbimaelGomes_rm573528_pbl_fase6.ipynb`](AbimaelGomes_rm573528_pbl_fase6.ipynb) · [Colab](https://colab.research.google.com/github/abimaelgomez/fiap-fase6-visao-computacional/blob/main/AbimaelGomes_rm573528_pbl_fase6.ipynb) |
| **2** | YOLOv5 customizado × YOLOv5 padrão (COCO) × CNN treinada do zero: precisão, facilidade de uso, tempo de treino e de inferência | [`AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb`](AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb) · [Colab](https://colab.research.google.com/github/abimaelgomez/fiap-fase6-visao-computacional/blob/main/AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb) |

O passo a passo completo, os resultados e a análise crítica estão nos notebooks.

## Estrutura

```
.
├── README.md
├── AbimaelGomes_rm573528_pbl_fase6.ipynb            # Entrega 1
├── AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb   # Entrega 2
└── assets/                                          # prints das detecções no conjunto de teste
```

No Google Drive (`MyDrive/FarmTech_Fase6`) ficam o dataset, os rótulos do Make Sense, os pesos treinados e os resultados (`runs/`).

## Como executar

1. Abra o notebook da Entrega 1 no Colab com GPU (**Ambiente de execução → Alterar tipo → T4 GPU**) e execute todas as células. Ele monta o Drive, cria o dataset, treina e salva os resultados.
2. Em seguida, execute o notebook da Entrega 2. Ele reutiliza o dataset e o `best.pt` salvos no Drive.

## Tecnologias

Python · YOLOv5 (Ultralytics, PyTorch) · TensorFlow/Keras · Make Sense AI · Open Images V7 · Google Colab/Drive
