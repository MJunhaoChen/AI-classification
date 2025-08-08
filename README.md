# AI Classification Project

## Overzicht

Dit project bevat een selectie van code en resultaten uit een breder onderzoek naar classificatiemodellen met behulp van neural networks. De notebooks richten zich op twee toepassingen: handgeschreven cijfers (MNIST) en bonenbladziekten (Angular Leaf Spot, Bean Rust, Gezond).

## Bestanden

* **[AI-results.pdf](./AI-results.pdf)** – Een presentatie met enkele voorbeeldresultaten van de modellen.  
* **[NN_Beans.ipynb](./NN_Beans.ipynb)** – Jupyter-notebook voor classificatie van bonenbladziekten.  
* **[NN_MNIST.ipynb](./NN_MNIST.ipynb)** – Jupyter-notebook voor herkenning van handgeschreven cijfers (MNIST).

## Benodigdheden

* Python 3.x
* TensorFlow
* Matplotlib (Pyplot)
* Seaborn
* Numpy
* Google Colab (optioneel, aanbevolen voor notebooks)

## Installatie

```bash
git clone <repository-url>
pip install tensorflow matplotlib seaborn numpy
```

Je kunt de notebooks lokaal openen via Jupyter, of via Google Colab.

## Gebruik

* **NN\_MNIST.ipynb** – Voer dit notebook uit voor het classificeren van cijfers.
* **NN\_Beans.ipynb** – Voer dit notebook uit voor het classificeren van bonenziekten.
* Bekijk de presentatie in **AI-results.pptx** voor een greep uit de resultaten.

## Resultaten

* **Cijfers (0–9)**: Vertrouwensscores tussen 0.8289 en 0.9785. De verwarringsmatrix laat sterke prestaties zien (afkomstig uit een bredere reeks testen).
* **Bonenziekten**: Na 35 epochs werd een accuraatheid van 0.7500 behaald, met stabiele training door verschillende testfasen heen.

## Uitdagingen

* Het vinden van het juiste aantal neuronen vroeg om veel finetuning, zeker in de beginfase.
* Tijdens het testen in Google Colab kwamen er wat cacheproblemen naar voren bij het herhaaldelijk draaien van notebooks.
