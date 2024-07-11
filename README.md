# Prédicteur de Diagnostic du Cancer du Sein

## Aperçu

L'application de diagnostic du cancer est un outil alimenté par l'apprentissage automatique conçu pour aider les professionnels de la santé à diagnostiquer le cancer du sein. En utilisant un ensemble de mesures, l'application prédit si une masse mammaire est bénigne ou maligne. Elle fournit une représentation visuelle des données d'entrée à l'aide d'un graphique radar et affiche le diagnostic prédit ainsi que la probabilité d'être bénigne ou maligne. L'application peut être utilisée en saisissant manuellement les mesures ou en se connectant à un laboratoire de cytologie pour obtenir les données directement à partir d'une machine. La connexion à la machine de laboratoire ne fait pas partie de l'application elle-même.

L'application a été développée à partir du jeu de données public (https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). Notez que ce jeu de données peut ne pas être fiable.


## Installation

### Étapes
1. Clonez le dépôt :
    ```bash
    git clone https://github.com/chrfsa/cancer_predict_with_ml.git
    cd cancer_predict_with_ml.git
    ```

2. Créez un environnement virtuel et activez-le :
    ```bash
    python -m venv venv
    # Sous Windows
    .\venv\Scripts\activate
    # Sous macOS et Linux
    source venv/bin/activate
    ```

3. Installez les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## Usage
    ```bash
    streamlit run app/main.py
    ```
