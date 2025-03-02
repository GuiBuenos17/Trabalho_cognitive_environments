📊 Análise Facial e OCR com AWS Rekognition e Textract

📖 Sobre

Este projeto utiliza os serviços AWS Rekognition e Textract para realizar reconhecimento facial, detecção de atributos faciais e extração de texto a partir de imagens armazenadas no Amazon S3. O objetivo é verificar similaridade entre rostos e processar documentos automaticamente.

⚙️ Como funciona?

O sistema analisa imagens para identificar rostos e seus atributos, como olhos abertos, uso de óculos escuros e rostos parcialmente ocultos. Caso a face seja compatível, ele realiza a comparação entre duas imagens. Além disso, um modelo OCR extrai texto de documentos para análise posterior. A implementação inclui chamadas aos serviços da AWS e exibição dos resultados.

💡 Objetivo

O projeto busca desenvolver uma solução para reconhecimento facial e extração de informações de documentos de forma automática, podendo ser utilizada em autenticação, verificação de identidade e digitalização de registros físicos.

💻 Tecnologias Utilizadas

O projeto foi desenvolvido em Python e utiliza as seguintes bibliotecas:

Boto3 – Para integração com os serviços da AWS

Pillow – Para manipulação e exibição de imagens

AWS Rekognition – Para análise facial e comparação de imagens

AWS Textract – Para extração de texto de documentos
