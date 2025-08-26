# Análisis de un Modelo Matemático para la Fase de Inducción de la Anestesia basado en Redes Neuronales Informadas por la Física

El modelado farmacocinético y farmacodinámico es esencial para controlar de forma precisa la administración de fármacos como el propofol, ampliamente usado en procedimientos anestésicos. Su correcta dosificación permite inducir y mantener
el estado de inconciencia de manera segura y eficaz. Sin embargo, la variabilidad interindividual y el ruido presente en los datos dificultan la estimación de parámetros, lo que limita la personalización del tratamiento.

Este trabajo se centra en la planificación de la inducción anestésica con propofol, una etapa crítica del proceso. En este contexto, se presenta un modelo Farmacocinético-Farmacodinámico de cuatro compartimentos que describe la evolución del paciente desde la consciencia hasta la inconsciencia durante la administración del fármaco. El modelo considera como entrada la perfusión del fármaco y
emplea el Índice Biespectral como medida clínica del nivel de conciencia.

Para validar este modelo, se generan datos sintéticos que incorporan ruido gaussiano con el objetivo de simular la variabilidad interindividual habitual entre pacientes reales. Sobre esta base, se aplican Redes Neuronales Informadas por la Física para simular la dinámica farmacológica del sistema y estimar parámetros
desconocidos del modelo. La robustez y precisión de esta red se evalúan en una población sintética.

Los resultados obtenidos demuestran que las Redes Neuronales Informadas por la Física son capaces de simular con fidelidad la dinámica y cinética farmacológica, así como de estimar parámetros desconocidos en el modelo del propofol. Esto
abre las puertas a su aplicación en otros contextos biomédicos donde el acceso a datos es limitado o está sujeto a incertidumbre.

Todo el modelado y análisis se ha implementado en Python, haciendo uso de las librerías SciP y, Matplotlib y PyTorch.
