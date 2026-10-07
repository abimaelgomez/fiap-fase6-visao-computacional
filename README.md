<div align="center">

<img src="https://img.shields.io/badge/FIAP-ED1C24?style=for-the-badge&logoColor=white" alt="FIAP" height="40"/>

# FIAP - Faculdade de Informática e Administração Paulista

> **Fase 6 · Visão Computacional com YOLO** — detecção de animais peçonhentos (cobras e aranhas) para a segurança de trabalhadores rurais.
>
> ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
> ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
> ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
> ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
> ![Ano](https://img.shields.io/badge/ano-2026-ED1C24?style=flat-square)
>
> </div>

---

<p align="center">
  <a href="https://www.fiap.com.br/">
    <img src="https://raw.githubusercontent.com/agodoi/template/main/assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width="40%" height="40%">
  </a>
</p>

## 👨‍🎓 Integrantes

| RM | Nome | LinkedIn |
|---|---|---|
| RM573528 | Abimael Gomes Silva De Carvalho | [LinkedIn](https://www.linkedin.com/in/abimaelgomez/) |
| RM569623 | Élton de Oliveira Longaray | [LinkedIn](https://www.linkedin.com/in/eltonlongaray/) |
| RM572243 | Natália Gimenez Leite | [LinkedIn](https://www.linkedin.com/in/natalia-gimenez-leite/) |

## 👩‍🏫 Professores

#### Tutor(a)
- Sabrina Otoni

#### Coordenador(a)
- André Godoi

## 📜 Descrição

A **FarmTech Solutions** apresenta a um cliente do agronegócio um sistema de visão computacional capaz de reconhecer **cobras** e **aranhas** em imagens de câmeras instaladas em galpões, currais e áreas de colheita, para disparar alertas antes de um acidente.

O projeto treina um detector **YOLOv5** com um dataset próprio de **390 imagens** (312 de treino, 40 de validação e 38 de teste), montado a partir do Open Images e **rotulado com revisão no Make Sense AI**, compara duas durações de treinamento (**30 × 60 épocas**) e confronta o modelo com outras duas abordagens: o **YOLOv5 padrão (COCO)** e uma **CNN treinada do zero**.

> Toda a metodologia, o código executado, os resultados e a análise crítica estão nos notebooks abaixo. Este README apenas guia o leitor até eles.

## 🎥 Vídeo demonstrativo

▶️ [Assista no YouTube (não listado)](LINK_DO_VIDEO)

## 📓 Notebooks

| Entrega | Tema | Notebook | Abrir no Colab |
|---|---|---|---|
| **1** | Dataset, rotulação, treino com 30 e 60 épocas, validação, teste e conclusões | [`AbimaelGomes_rm573528_pbl_fase6.ipynb`](AbimaelGomes_rm573528_pbl_fase6.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abimaelgomez/fiap-fase6-visao-computacional/blob/main/AbimaelGomes_rm573528_pbl_fase6.ipynb) |
| **2** | YOLOv5 customizado × YOLOv5 padrão × CNN do zero: precisão, facilidade de uso, tempo de treino e de inferência | [`AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb`](AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb) | [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abimaelgomez/fiap-fase6-visao-computacional/blob/main/AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb) |

## ▶️ Como executar

1. Abra o notebook da **Entrega 1** pelo botão do Colab e selecione **Ambiente de execução → Alterar tipo → GPU (T4)**.
2. Execute todas as células (**Ambiente de execução → Executar tudo**) e autorize o acesso ao Google Drive, onde ficam dataset, pesos e resultados (`MyDrive/FarmTech_Fase6`). O tempo total é de cerca de 20 minutos.
3. Execute o notebook da **Entrega 2**, que reutiliza o dataset e o melhor modelo salvos no Drive pela Entrega 1.

## 📁 Estrutura do repositório

```
fiap-fase6-visao-computacional/
├── AbimaelGomes_rm573528_pbl_fase6.ipynb            ← Entrega 1: YOLOv5 customizado (30 × 60 épocas)
├── AbimaelGomes_rm573528_pbl_fase6_entrega2.ipynb   ← Entrega 2: comparação de três abordagens
├── makesense/
│   ├── exportado_yolo.zip                           ← rótulos revisados no Make Sense (formato YOLO)
│   └── assinaturas_treino.json                      ← verificação de que as imagens são as revisadas
└── README.md
```

## 📋 Licença

[MODELO GIT FIAP](https://github.com/agodoi/template) por [FIAP](https://fiap.com.br) está licenciado sobre [Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1).

© 2026 Grupo FarmTech Solutions · FIAP — Inteligência Artificial
