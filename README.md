# XNLM Lab @ LCL 2023 🔍

This repository contains materials for the lab *"Explaining Neural Language Models from Internal Representations to Model Predictions"* by [Alessio Miaschi](https://alemiaschi.github.io/) and [Gabriele Sarti](https://gsarti.com/) at the [AILC Lectures on Computational Linguistics 2023](https://www.ai-lc.it/en/lectures-2/lectures-2023/).

## Contents

The lab session is divided in two parts:

- Notebooks [1.1](notebooks/1.1_Transformer_Syntactic_Abilities.ipynb) and [1.2](notebooks/1.2_Probing.ipynb) introduce probing approaches for evaluating the linguistic knowledge of neural language models and shows how diagnostic classifiers can be used to study  models' internal representations.

- Notebook [2](notebooks/2_Attribution_Contrastive.ipynb) discusses feature attribution methods and their usage to identify biases and prediction errors in NLMs for classification and generation tasks.

You can find a notebook for each part in the [`notebooks`](notebooks/) folder.

## Tools and Frameworks

The lab sessions make use of the [Jupyter](https://jupyter.org/) environment. You can use the following links to get started:

- [Jupyter Notebook/Lab Installation](https://jupyter.org/install)
- [Jupyter Quickstart](https://docs.jupyter.org/en/latest/running.html)

Alternatively, it is possible to use the notebooks via the [Google Colab](https://colab.research.google.com/) web environment simply by clicking on the [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() button at the beginning of each notebook. If you’re running on Windows, we recommend following along using a Colab notebook. If you’re using a Linux distribution or macOS, you can use either approach described here. For an intro to the Colab environment, refer to:

- [Colab Quickstart](https://colab.research.google.com/notebooks/intro.ipynb)


The file `requirements.txt` in this repository contains the list of all the packages required to run the lab sessions. You can create a Python virtual environment (Python>=3.8.1) and install them using the following command:


```shell
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Make sure the virtual environment is activated before running Jupyter. If you are using Colab, simply run the cell at the beginning of each notebook to install the required packages. Refer to [Using a Python Virtual Environment](https://huggingface.co/course/chapter0/1#using-a-python-virtual-environment) for more details on how to create and activate a virtual environment.

## About us

<table>
  <tr>
    <td style="width:100px"><img src="https://www.ai-lc.it/wp-content/uploads/2023/03/Miaschi-200x200.jpg" alt="Arianna Bisazza" style="width:200px"/></td>
      <td>
        <a href="https://alemiaschi.github.io/"><b>Alessio Miaschi</b></a> is a Post Doctoral Researcher at the <a href="http://www.italianlp.it/">ItaliaNLP Lab</a> from the <a href="www.ilc.cnr.it/">Institute for Computational Linguistics “A. Zampolli”</a> (CNR-ILC, Pisa). He received his Ph.D. in Computer Science from the University of Pisa in 2022 with a thesis focused on the definition of techniques for interpreting and understanding the linguistic knowledge implicitly encoded in recent state-of-the-art Neural Language Models. His current research interest mainly focuses on the development and analysis of neural network models for language processing, as well as on the definition of NLP tools for educational applications.
      </td>
  </tr>
  <tr>
    <td style="width:100px"><img src="https://gsarti.com/authors/gsarti/avatar_hu02574c73d8d5cf0c41465216db38be2a_239118_250x250_fill_q90_lanczos_center.jpg" alt="Gabriele Sarti" style="width:800px"/></td>
    <td>
      <a href="https://gsarti.com"><b>Gabriele Sarti</b></a> is a PhD student at the <a href="https://www.rug.nl/research/clcg/research/cl/">Computational Linguistics Group</a> (GroNLP) of the University of Groningen. He is part of the Dutch consortium <a href="https://interpretingdl.github.io/">InDeep</a>, working on interpretability for language generation and neural machine translation. Previously, he worked as a research intern at Amazon Translate NYC, a research scientist at <a href="https://www.aindo.com/">Aindo</a>, and a research assistant at the ItaliaNLP Lab (CNR-ILC, Pisa). His research aims to improve our understanding of generative neural language models’ inner workings, with the ultimate goal of enhancing the controllability and robustness of these systems in human-AI interactions.
    </td>
  </tr>
</table>

## Join the Conversation on RiTA 🇮🇹

**[RiTA](https://github.com/RiTA-nlp)** (Risorse per la Lingua Italiana) is a new community aimed at bringing together enthusiasts and professionals of Italian computational linguistics and to create new collaborations for the construction of resources for the Italian language. If you are working on NLP-related topics and want to keep up with latest initiatives
from the Italian research community, you can join the conversation on the [RiTA Discord](https://discord.gg/NHRCVqjaDM) server. See you there! 🙂