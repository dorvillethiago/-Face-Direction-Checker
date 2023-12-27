## API que verifica qual a direção que a pessoa está olhando.

- Esta api utiliza OpenCV e MediaPipe para determinar para qual direção a pessoa está olhando.
- A conexão é realizada com FastAPI e WebSockets, o endpoint recebe um base64 que será convertido em imagem e processado para retornar uma direção.