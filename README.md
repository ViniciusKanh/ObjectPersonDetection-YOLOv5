<h1 align="center">Detecção de Objetos e Pessoas com YOLOv5</h1>

<p align="center">
  <img src="https://github.com/ViniciusKanh/ObjectPersonDetection-YOLOv5/assets/cover.png" alt="Imagem de Capa">
</p>

<p align="center">
  <a href="#sobre-o-projeto">Sobre o Projeto</a> •
  <a href="#demonstração">Demonstração</a> •
  <a href="#instalação">Instalação</a> •
  <a href="#utilização">Utilização</a> •
  <a href="#contribuições">Contribuições</a> •
  <a href="#licença">Licença</a>
</p>

---

## Sobre o Projeto 🚀

Bem-vindo ao projeto de Detecção de Objetos e Pessoas com YOLOv5. Este projeto utiliza o poderoso YOLOv5 para detectar objetos e pessoas em imagens e vídeos em tempo real. Combinando precisão e velocidade, esta aplicação tem aplicações em várias áreas, desde segurança até automação.

---

## Demonstração 📷

### Detecção em Tempo Real

![GIF de Detecção em Tempo Real](https://github.com/ViniciusKanh/ObjectPersonDetection-YOLOv5/assets/demo.gif)

### Detecção em Imagens

![Imagem de Detecção em Imagem](https://github.com/ViniciusKanh/ObjectPersonDetection-YOLOv5/assets/image.png)

---

## Instalação 🛠️

Para usar este projeto, siga as etapas abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/ViniciusKanh/ObjectPersonDetection-YOLOv5.git
    ```
2. Instale as dependências:
   ```bash
    pip install -r requirements.txt
   ```
3. Execute o projeto
   ```bash
    python DetecObjPeople-WebCam.py
    ```
# Utilização 📦
* Carregue uma imagem ou vídeo para iniciar a detecção.
* Visualize as detecções em tempo real ou nas imagens.
* Explore as informações detalhadas dos objetos e pessoas detectadas.
  
     ```Python
  # Exemplo de código para usar a detecção de objetos
  from deteccao_objetos import DetectorObjetos
  
  detector = DetectorObjetos()
  imagem = "caminho/para/sua/imagem.jpg"
  resultados = detector.detectar(imagem)
  print(resultados)
     ```
# Contribuições 🤝
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar solicitações de pull (pull requests) para melhorar este projeto. Juntos, podemos torná-lo ainda mais incrível.

