# SNN-Art

Localización del training y test set: https://drive.google.com/drive/folders/1TpxvFHPC9QXfQ2KHptS8luUqdUe5VKsI?usp=sharing

Los datos originales provienen de https://www.kaggle.com/datasets/ravidussilva/real-ai-art/data pero hemos modificado la
estructuración de las carpetas para que sea compatible con el código de los modelos de este proyecto.

## Instalar dependencias

Primero creamos el entorno virtual:

`python3 -m venv venvAIArt`

Accedemos a el entorno:

`source venvAIArt/bin/activate`

Instalamos las dependecias:

`python3 -m pip install -r requirements.txt`

## Estructura dentro de la carpeta:

```bash
SNN_Art/
├── Consumo/
│   ├── emissions_cnn.csv
│   ├── emissions_cnn+snn.csv
│   └── emissions_snn.csv
├── data_snn_flat/
│   ├── test/
│   │   ├── AI/
│   │   └── human/
│   └── train/
│       ├── AI/
│       └── human/
├── Graficas/
│   ├── CNN/
│   │   ├── accuracy_epoch.png
│   │   ├── test_loss_epoch.png
│   │   └── train_loss_epoch.png
│   ├── CNN+SNN/
│   │   ├── accuracy_epoch.png
│   │   ├── test_loss_epoch.png
│   │   └── train_loss_epoch.png
│   └── SNN/
│       ├── accuracy_epoch.png
│       ├── test_loss_epoch.png
│       └── train_loss_epoch.png
├── Modelos/
│   ├── Modelo_SNN_Puro.ipynb
│   ├── notebookCNN.ipynb
│   └── notebookCNN+SNN.ipynb
├── Modelos_Guardados/
│   ├── checkpoint_cnn.pth
│   ├── checkpoint_cnn+snn.pth
│   └── checkpoint_snn.pth
├── README.md
└── requirements.txt
```
