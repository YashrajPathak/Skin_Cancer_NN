{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Untitled0.ipynb",
      "provenance": [],
      "authorship_tag": "ABX9TyNXqCkclxRLpgz1ZZVj5Sc2",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/YashrajPathak/Skin_Cancer_NN/blob/main/README.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "# Skin Cancer CNN\n",
        "> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.\n",
        "\n",
        "\n",
        "## Table of Contents\n",
        "* [General Info](#general-information)\n",
        "* [Technologies Used](#technologies-used)\n",
        "* [Conclusions](#conclusions)\n",
        "* [Acknowledgements](#acknowledgements)\n",
        "\n",
        "<!-- You can include any other section that is pertinent to your problem -->\n",
        "\n",
        "## General Information\n",
        "- The project is built using tensorflow CNN\n",
        "- The Project dataset include 9 types of different skin diseases. CNN Model is used to detect Melanoma\n",
        "\n",
        "<!-- You don't have to answer all the questions - just the ones relevant to your project. -->\n",
        "\n",
        "## Conclusions\n",
        "- We built 3 Different Model\n",
        "- First Model was a overfit with Training Accuracy of 0.95 and validation of around 0.55\n",
        "- We fixed this Model overfit, we added additional neural network and dropout layers, which handled overfitting.\n",
        "- Since the data was skewed for number samples to train on was limited and hence we agumented data and achived a accuracy: 0.8027 and val_accuracy: 0.7988\n",
        "\n",
        "<!-- You don't have to answer all the questions - just the ones relevant to your project. -->\n",
        "\n",
        "\n",
        "## Technologies Used\n",
        "- Tensorflow - version 2.8.0\n",
        "\n",
        "<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->\n",
        "\n",
        "<!-- ## Acknowledgements\n",
        "Give credit here.\n",
        "\n",
        "\n",
        "- This project was based on [this tutorial](https://www.example.com). -->\n",
        "\n",
        "\n",
        "## Contact\n",
        "Created by [@Yashraj_Pathak] - feel free to contact me!\n",
        "\n",
        "\n",
        "<!-- Optional -->\n",
        "<!-- ## License -->\n",
        "<!-- This project is open source and available under the [... License](). -->\n",
        "\n",
        "<!-- You don't have to include all sections - just the one's relevant to your project -->"
      ],
      "metadata": {
        "id": "RgiKrr_xA4d4"
      }
    }
  ]
}