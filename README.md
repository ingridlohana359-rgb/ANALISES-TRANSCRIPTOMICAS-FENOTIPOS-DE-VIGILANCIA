<div align="center">

# Análise Transcriptômica em Silico
### Modulação da Neuroplasticidade e Neuroinflamação por Psilocibina na Depressão Maior

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-RNA--Seq-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

</div>

## Visão Geral do Projeto
Este projeto apresenta um pipeline de bioinformática voltado à análise de expressão gênica diferencial (RNA-Seq/Microarray) em tecido cerebral. O objetivo é comparar o perfil molecular entre estados de **Controle**, **Depressão Maior** e **Pós-Tratamento com Psilocibina**.

---

## Visualização dos Resultados (Clustermap)

> Agrupamento hierárquico (*Hierarchical Clustering*) demonstrando a normalização por Z-Score dos 25 genes mais variáveis e a separação dos perfis fenotípicos.

<div align="center">

![Heatmap Hierárquico](<imagem projeto 2.png>)

</div>

---

## Principais Achados Biológicos

* **Plasticidade Sináptica ($\text{Log}_2\text{FC} = +5.04$):** Forte ativação de marcadores de remodelação neural (*BDNF*, *ARC*).
* **Supressão da Neuroinflamação ($\text{Log}_2\text{FC} = -4.16$):** Atenuamento expressivo de citocinas pró-inflamatórias (*IL6*, *TNF*).
* **Via Serotoninérgica ($\text{Log}_2\text{FC} = +1.63$):** Modulação positiva de receptores específicos (*HTR2A*).

---

## Tecnologias Utilizadas

| Categoria | Tecnologias / Bibliotecas |
| :--- | :--- |
| **Linguagem** | Python 3 |
| **Análise Estatística** | `Pandas`, `NumPy`, `SciPy` |
| **Visualização Científica** | `Seaborn` (`clustermap`), `Matplotlib` |
| **Plataforma** | Google Colab / GitHub |
