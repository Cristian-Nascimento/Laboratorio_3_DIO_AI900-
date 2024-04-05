# Laboratorio_3_DIO_AI900

- Passo a passo de experimento utilizando **Language Studio** para análise de texto com análise de sentimentos e opiniões. 
- Realizado como desafio de projeto no Bootcamp **Microsoft Azure AI Fundamentals** da [Dio.me](https://dio.me)
- Documentação: [https://aka.ms/ai900-text-analysis](https://aka.ms/ai900-text-analysis)
- [Análise de Inputs Adicionais](#análise-de-inputs)

<br/>

## Passo 1
- Abrir a página do Portal [https://portal.azure.com/#home](https://portal.azure.com/#home) e clicar para criar um recurso.
- Buscar por "Análise de Texto" e clicar em "create"

## Passo 2
- Com as funcionalidades adicionadas, basta clicar em "continue to create your resource"

![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto1.png)

## Passo 3
- Preencher as informações do recurso conforme imagem abaixo.
- Escolha um resource group, um nome (que deve ser único), e o Pricing Tier deve ser Free F0.
- Não esquecer de marcar a caixa com a observação de Responsabilidade AI.
- E então clique em Review + create para a validação das informações

![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto2.png)

## Passo 4
- Depois da validação anterior, sua tela deve se parecer com esta.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/e16d155a-ebc5-4071-9c9f-8c19ecf4a93d)

- Agora sim, você clica em Create.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/d90e8777-f774-4f91-b262-a69138d48ba6)

## Passo 5
- Esta é a tela de finalização da criação do recurso.
- Clique em "Ir para o grupo de recursos"

![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto4.png)


## Passo 6
- Abra a página do Language Studio (https://language.cognitive.azure.com/)[https://language.cognitive.azure.com/] com seu usuário logado.
- Automaticamente é aberta uma modal com as informações a preencher conforme imagem abaixo. Informe a Azure Subscription, o Resource Type e o resource group que você criou, e clique em "Done".

![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto5.png)

## Passo 7
- Ainda no Language Studio, selecione a aba "Classify Text", e o card "Analyse Sentiment and mine opinions"

![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto6.png)

## Passo 8
- Selecione o idioma do texto a ser utilizado (English).
- Copie o texto, fornecido pela documentação, na caixa de texto. Ver abaixo:

```
 DevOps orchestration, agile scrum master sprint retrospective. Kubernetes cluster, dockerized applications in microservices architecture. AI algorithms machine learning deep learning neural networks. Big data analytics, real-time processing, ETL pipelines, and data lakes in cloud storage solutions.
```

- Marque o box informativo
- Clique em "Run"
  
![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto7.png)

## Passo 9
- Resultados
- Ele traz o sentimento geral do texto
- Traz também a análise de cada uma das frases
- Ex.: Sentence 1 (basta clicar na aba da frase para abrir ou fechar)

![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto8.png)

- Ex.: Análise da Sentence 2
  
![image](https://github.com/Cristian-Nascimento/Laboratorio_3_DIO_AI900-/blob/main/assets/foto9.png)

##
<div align="center">
<p>by Cristian Nascimento.</p>
  <p>
    <a href="https://www.linkedin.com/in/cristian-rosa-nascimento/" target="_blank" >
      <img align="center" height="35" src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="Cristian Nascimento Linkedin" />
    </a>
    <a href="https://www.instagram.com/cristian._nascimento" target="_blank" >
      <img align="center" height="35" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/1200px-Instagram_icon.png" alt="Cristian Nascimento Instagram" />
    </a>
  </p>
</div>
