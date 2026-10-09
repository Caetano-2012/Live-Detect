<h1 align="center">👤 Detector de Faces</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge" alt="Status Badge">
</p>

<p align="center">
  <i>Detecção de rostos em tempo real utilizando a webcam e OpenCV.</i><br>
  <b>Autor:</b> Caetano Bordin
</p>

---

## 🧩 Sobre o Projeto

Este projeto utiliza a biblioteca **OpenCV** para detectar rostos através da webcam do computador. Ao identificar uma face, o programa desenha um retângulo ao redor dela na imagem exibida em tempo real.

---

## 🧰 Tecnologias Utilizadas

* **Python**
* **OpenCV (cv2)**
* **Haar Cascade** — modelo utilizado para detecção de faces.

---

## ⚙️ Funcionalidades

* 📷 Captura de vídeo pela webcam;
* ⚫ Conversão dos frames para escala de cinza;
* 🔍 Detecção de rostos;
* 🟦 Desenho de retângulos ao redor das faces detectadas;
* ⏹️ Encerramento do programa ao pressionar a barra de espaço.

---

## 📚 Aprendizados

* Captura de vídeo com `cv2.VideoCapture()`;
* Processamento de imagens em tempo real;
* Utilização do classificador Haar Cascade;
* Detecção de objetos com `detectMultiScale()`;
* Desenho de formas em imagens com `cv2.rectangle()`.

---

## 🕹️ Como Executar

1. Instale o OpenCV:

```bash
pip install opencv-python
```

2. Coloque o arquivo `haarcascade_frontalface_default.xml` na mesma pasta do programa.

3. Execute o arquivo Python:

```bash
python main.py
```

4. Para encerrar, pressione a **barra de espaço**.

---

## 📜 Licença

O código pode ser usado somente para **fins educacionais**.

É permitida a modificação e redistribuição, desde que os autores sejam citados e a licença original seja mantida.

O software é fornecido **"como está"**, sem garantias de qualquer tipo. Os autores não são responsáveis por danos decorrentes de seu uso.

---

## 👨‍💻 Autor

**Caetano Bordin**

🔗 [@Caetano-2012](https://www.github.com/Caetano-2012)

---
