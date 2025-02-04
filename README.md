# Azure Inteligência Artificial (IA) - Estúdio de visão computacional
Repositório para documentar experiência com o AI Vision Studio do Microsoft Azure. Esse é um estudo incentivado pelo bootcamp IA-900, patrocinado pela Microsoft e distribuído pela [DIO](https://web.dio.me/track/microsoft-fundamentos-de-ia).

![image](https://github.com/user-attachments/assets/8e2bc87c-b000-4bd3-9f85-5d4bbd72aee9)

### Links importantes:
- **Documetações oficiais:** [Detecção de faces](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html), [Análise de imagens](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html), [Leitura de textos](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html) <br>
O qual descrevem, passo a passo, como replicar os testes que fiz

- **Azure AI Visio Studio:** [portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com/gallery/featured) <br>
  Ferramente utilizada

## Passo a passo resumido:
1. O primeiro passo é criar um novo recurso, no [portal do Azure](https://portal.azure.com/?azure-portal=true), referente aos serviços de IA.
2. O próximo passo já é dentro do **AI VIsion Studio**, plataforma simples e intuitiva para fazer testes. Todos os serviços são livres e de fácil acesso, é só escolher um e utilizar.

## Detecção de imagens:
A IA de detectção facial do Azure é super precisa, detectando rapidamente cada ponto de rosto presente em uma imagem, a seguir alguns testes:

![image](https://github.com/user-attachments/assets/6be592e3-0424-4eb3-963d-e33b3476e983) <br>
***(Detecção simples)***

![image](https://github.com/user-attachments/assets/22b6b9b4-1242-468f-a99d-12cf4999bc88) <br>
***(Detecção com rosto escuro)***

![image](https://github.com/user-attachments/assets/e3d13ba7-40dd-4325-88ba-5ace38a43954) <br>
***(Detecção em foto antiga)***

![image](https://github.com/user-attachments/assets/1f6942ea-476a-4e31-96f5-a2d4fd4d5b9e) <br>
***(Detecção em um retrato artístico)***

![image](https://github.com/user-attachments/assets/1d640b78-79df-4fe5-97e0-0da89af67c33) <br>
***(Detecção em imagem com mais de 10 rostos)***

## Descrição de imagens
Recurso muito útil para questões de acessibiliadde. A IA experimental do Azure cumpre essa função, descrevendo as imagens de forma direta
<br>
<br>

![image](https://github.com/user-attachments/assets/5b98bd5b-fb0d-4fa0-b788-8d25c499b0b4)
``` 
a group of people in red and black striped shirts
(um grupo de pessoas em camisas listradas vermelhas e pretas)
```
<br>
<br>

![image](https://github.com/user-attachments/assets/bdc54704-73db-4789-a238-b92c0cf5306c)
``` 
a pixel art of a tree
(uma pixel art de uma árvore)
```


## Detecção de textos em imagens 
Recurso útil para digitaçização de cartas, notas fiscais e outros documentos no geral.

![image](https://github.com/user-attachments/assets/2e841d59-8ed9-459a-99e6-6bf20b100a0a)
```
IFE IS LIKE RIDING A BICYCLE
TO KEEP YOUR BALANCE YOU MUST KEEP MOVING
```
<br>
<br>

![image](https://github.com/user-attachments/assets/d5edb5dc-fbf5-480b-81bf-87025b917138)
```
CONSUMIDOR
CPF:000.000.000-00 NF-E EMITIDA EM AMBIENTE DE H
OMOLOGACAO - SEM VALOR FISCAL
Consulta via leitor de QRCode
Protocolo de Autorização:143150000144125
```
<br>
<br>

![image](https://github.com/user-attachments/assets/e11b49ce-cf02-4120-a474-dd94e3b50861)
```
Tulipa
ANTOFÁGICA
Finalmente encontrei sossego.Éum lugarzinho nos
confins da terra, mas no centro de tudo. Consigo
1805
imaginá-lá trotando por esses campos dourados, as
irinas ao vento... Não há sequer mosquitos para espantar. Mas não adianta
Pedir endereço. Não revela. antes foragido que ração de cães ferozes.
uma pena saber que deram pérolas aos porcos. Mas, pensandob em.
o ditado não diz nada sobre leite ou whisky, nãoé? Cuide-se
e tente enviar notícias
Bola de Neve.
```

## Considerações finais:
O Azure Vision Studio oferece uma IA ***competente e com potencial.*** Foi um exercício importante para se ter ***noção do poder atual das IA's de visão computacional e as áreas em que essa tecnologia pode ser útil.*** Lembrando que a implementação dessa tecnologia é outros sistemas é um serviço pago. Porém, a experimentação no Vision Studio é gratuita









