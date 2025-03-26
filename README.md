# IA_DIO_Project

Passos que Segui:

1️⃣ Criação do Repositório: Comecei criando um repositório no GitHub chamado azure-ai-language e organizei os arquivos necessários.

2️⃣ Definição do Input: Preparei um arquivo sentences.txt na pasta inputs, onde escrevi algumas frases para teste de análise de sentimentos e compreensão de linguagem coloquial.

3️⃣ Testes no Azure AI Language Studio:

Enviei as frases para o serviço de Análise de Sentimentos.

Recebi um retorno com a classificação de cada uma como positiva, negativa ou neutra.

Também testei a compreensão de linguagem coloquial no Language Studio.

4️⃣ Experimentação com o Azure Bot Service:

Configurei um chatbot simples para responder a perguntas baseadas nas frases analisadas.

O bot usou os serviços de IA para interpretar o contexto e gerar respostas.

5️⃣ Observações sobre os Resultados:

A IA conseguiu identificar sentimentos de forma bastante precisa.

Algumas respostas do bot não foram tão naturais e precisaram de ajustes para interpretar frases mais complexas.


🔍 O que Aprendi com Isso
✅ A análise de sentimentos pode ser muito útil para redes sociais e suporte ao cliente.
✅ O Azure Bot Service permite criar assistentes virtuais que realmente entendem o que está sendo dito.
✅ O Speech Studio é interessante para transformar texto em fala e melhorar a acessibilidade.
✅ Para obter melhores resultados, o ideal é treinar um modelo personalizado com mais exemplos.


Tarefa extração de texto de uma imagem.

Passos para Configuração
Instalar Bibliotecas

Para usar o Tesseract OCR, é necessário instalar as bibliotecas pytesseract e Pillow. Você pode instalar as bibliotecas usando o comando pip install pytesseract pillow.

Importar as Bibliotecas

Após a instalação, importe as bibliotecas necessárias no seu código Python.

Carregar e Exibir a Imagem

Carregue a imagem que você deseja processar. Use um código para abrir e exibir a imagem.

Extrair Texto da Imagem

Para extrair o texto da imagem, utilize a função apropriada do Tesseract, que irá mostrar o texto extraído da imagem.

Resultado Esperado

Ao processar a imagem, o texto extraído será mostrado no seu terminal ou saída. O texto extraído pode ser algo como: "Exemplo de texto da imagem processada".

Insights e Possibilidades
Precisão: O Tesseract funciona melhor com imagens nítidas e boa qualidade de contraste. Quanto melhor a imagem, maior a precisão na extração de texto.

Aplicações:

Digitalização de documentos para transformá-los em formato digital pesquisável.

Extração de texto de recibos ou faturas para organizar dados de forma automática.

Ferramenta útil para melhorar a acessibilidade de conteúdos visuais, ajudando pessoas com deficiências visuais.

