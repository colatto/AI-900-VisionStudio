
# AI-900 | Lendo texto em imagens

![Img](prints/azureAI.png)

Repositório do passo a passo criado para o desafio **Reconhecimento Facial e transformação de imagens em Dados no Azure ML**, durante o bootcamp [*Microsoft Azure AI Fundamentals*](https://www.dio.me/bootcamp/microsoft-azure-ai-fundamentals).

O objetido aqui é obter textos de imagens de forma rápida e eficiente sem a necessidade de programação, aproveitando os recursos tecnológicos disponíveis para reconhecer e extrair textos de qualquer imagem, em qualquer idioma, em questão de segundos.

Na busca por atingir esse objetivo farei uso da visão computacional do Azure AI para detectar e interpretar textos incorporados em 3 diferentes tipos de imagens. Esse metodo é conhecido como [Reconhecimento Óptico de Caracteres (OCR)](https://learn.microsoft.com/pt-br/azure/azure-video-indexer/ocr). 

Esse processo usará recurso de Inteligencia Artificial do Azure, que inclui os serviços do Azure Vision Studio para testar as possibilidades com OCR.

<br>

🔹 *A documentação usada no desenvolvimento desse material está referenciada no [rodapé](#final) dessa página*.

<br>

## 🔧 Preparando o ambiente

Para executar esse desafio é necessário ter uma conta devidamente configurada no portal Azure. (*Configure seu primeiro acesso gratuitamente [clicando aqui](https://azure.microsoft.com/pt-br/free/)*.)

![Img](prints/loading.png)

<br>

## 🔧 Acessando o portal Azure

Ao acessar o portal de serviços do Azure você verá uma interface web que permite gerenciar e pesquisar recursos de forma fácil e intuitiva. 

O painel sugere as informações mais relevantes inicialmente, podendo ser personalizado para o seu cenário. Também é possível navegar pelos menus laterais para explorar os diferentes serviços, como computação, armazenamento, rede, banco de dados, inteligência artificial, entre outros. 

O portal de serviços do Azure é uma ferramenta poderosa e flexível que facilita o uso da nuvem da Microsoft. 🌐

<br>

## 🧩 Configurando recurso

Irei iniciar criando um novo recurso necessário, a configuração correta de recursos no Azure é essencial para garantir o seu funcionamento adequado, segurança, escalabilidade e otimização de custos.

Cada recurso do Azure possui uma série de configurações que podem ser ajustadas de acordo com necessidades e objetivos de cada negócio. 

Para isso basta clicar em `Criar um recurso`, como mostra a imagem:

![img](prints/print00.png)

Em seguida navegue pelo menu esquerdo selecionando a opção `IA + Machine Learning` e clique em `Criar` na opção **Serviços Cognitivos**.

![img](prints/print01.png)

Feito isso a página **Criar Serviços Cognitivos** será carregada e as opções de configuração usadas para atender essa necessidade foram:

![img](prints/print02.png)

 *Lembre que é importante configurar corretamente um recurso para aproveitar ao máximo os benefícios da nuvem*. ☁️

 <br>

## 🗺️ Acessando o Vision Studio


- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com)


```
git init
```
<a id="final"></a>

## 📚 Referência:

- Microsoft Azure - [*Soluções*](https://azure.microsoft.com/pt-br/#solutions)

- Read text in Vision Studio - [*Microsoft Learn*](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

- (OCR) Reconhecimento Óptico de Caracteres - [*Microsoft Learn*](https://learn.microsoft.com/pt-br/azure/azure-video-indexer/ocr) 