{
  "cells": [
    {
      "cell_type": "code",
      "source": [
        "import numpy as np\n",
        "import pandas as pd\n",
        "\n",
        "df = pd.DataFrame({'A': 1.,\n",
        "                   'B': pd.Timestamp('20130102'),\n",
        "                   'C': pd.Series(1, index=list(range(4)), dtype='float32'),\n",
        "                   'D': np.array([3] * 4, dtype='int32'),\n",
        "                   'E': pd.Categorical([\"test\", \"train\", \"test\", \"train\"]),\n",
        "                   'F': 'foo'})\n",
        "\n",
        "print(df)"
      ],
      "outputs": [],
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "jupyter": {
          "source_hidden": false,
          "outputs_hidden": false
        },
        "nteract": {
          "transient": {
            "deleting": false
          }
        }
      }
    }
  ],
  "metadata": {
    "kernelspec": {
      "argv": [
        "/usr/bin/python3",
        "-m",
        "ipykernel_launcher",
        "-f",
        "{connection_file}"
      ],
      "display_name": "Python 3",
      "language": "python",
      "name": "python3"
    }
  },
  "nbformat": 4,
  "nbformat_minor": 0
}