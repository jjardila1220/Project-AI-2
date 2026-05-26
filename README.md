
## 🧠 Clasificación de materiales del Dataset MINC 2500: 

**Autores:**  
Juan José Ardila, Roger Fuentes 

<img width="1228" height="397" alt="deep learning" src="https://github.com/user-attachments/assets/fcb91d8b-5e8e-4a7f-87ab-8570212e95b9" />

---

### 🎯 Objetivo del Proyecto

Desarrollar un sistema de clasificación de 23 materiales que compare el desempeño de ResNet-50, EfficientNet-B0 y Swin-Transformer mediante métricas de generalización, con el fin de determinar la capacidad analítica de cada arquitectura frente a categorías visualmente similares.

### 📊 Dataset Utilizado

- **Nombre:** MINC 2500
- **Fuente:** [Repo - Paper: Material Recognition in the Wild with the Materials in Context Database ](http://opensurfaces.cs.cornell.edu/publications/minc/)  
- **Descripción:**  
Presenta 57 500 imágenes en representación de parches de diferentes materiales:
  - 23 clases de materiales
  - 2500 imágenes por clase
  - tamaño ≈ 2.3 GB
  - Se encuentra dividido en: Entrenamiento, validación y prueba. 


---

### 🤖 Modelos Implementados

1. **ResNet - 50:**  
Introduce conexiones residuales o de "atajo" que permiten entrenar redes muy profundas omitiendo capas para mitigar el problema del desvanecimiento del gradiente.

2. **EfficientNet-B0:**  
Optimiza la eficiencia y el rendimiento escalando simultáneamente el ancho, la profundidad y la resolución de la red de manera equilibrada a través de un método de escalado compuesto.

3. **Swin Transformer:**  
Adapta el mecanismo de atención de los Transformers al análisis visual mediante ventanas desplazadas no superpuestas, lo que le permite procesar imágenes de forma jerárquica y con una eficiencia computacional lineal respecto al tamaño de la imagen.


---

### ⚙️ Tecnologías Utilizadas

- PyTorch
- Torchvision
- Scikit-Learn
- Pillow (PIL)
- Matplotlib / Seaborn


