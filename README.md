# Lab Project 03 - Análise de Sentimentos com Language Studio no Azure AI  

![Status](https://img.shields.io/badge/Status_Projeto:-Concluído_(10/Mar/2025)-green)  

![Inteligência Artificial](https://img.shields.io/badge/Inteligência_Artificial_(IA)-blue)  
![NLP](https://img.shields.io/badge/NLP-blue)  
![Speech Recognition](https://img.shields.io/badge/Speech_Recognition-blue)  
![Sentiment Mining](https://img.shields.io/badge/Sentiment_Mining-blue)  
![Opinion Mining](https://img.shields.io/badge/Opinion_Mining-blue)  
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-blue)  
![Azure Language Studio](https://img.shields.io/badge/Azure_Language_Studio-blue)  

---

## Introdução  

O **Sentiment and Opinion Mining** é uma solução do **Azure Language Studio** que permite identificar **sentimentos positivos, negativos e neutros** em textos. Este repositório apresenta testes realizados na plataforma como parte do **Bootcamp Microsoft Azure AI Fundamentals, da DIO**.  

A análise de sentimentos e opiniões é amplamente utilizada para automatizar a compreensão de feedbacks de clientes, avaliações de produtos e interações em redes sociais. Essa tecnologia permite extrair informações relevantes e gerar insights valiosos para empresas.  

📌 **Para mais informações, acesse:**  
[Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html).  

---

## 📌 Índice  
1. [Procedimento](#procedimento)  
2. [Resultados](#resultados)  
3. [Conclusão e Insights](#conclusão-e-insights)  

---

## 🛠️ Procedimento  

### **Criando um Recurso no Azure Language Service**  

Para utilizar o **Language Studio**, é necessário criar um recurso **Language Service** no **Azure**.  

1. Acesse o portal do Azure: [https://portal.azure.com](https://portal.azure.com)  
2. No menu principal, clique em **Criar um Recurso** e procure por **Language Service**.  
3. Configure os detalhes do recurso e aguarde a conclusão do deploy.  


### **Selecionando o Recurso no Language Studio**  

Após a criação do serviço, conecte-o ao **Language Studio**:  

1. Acesse o [Language Studio](https://language.cognitive.azure.com/home).  
2. No menu inicial, clique em **Selecionar um Recurso**.  
3. Escolha o recurso criado e confirme a seleção.  


### **Selecionando e Testando o Serviço**  

Após a conexão, é possível visualizar a lista de serviços disponíveis. Neste experimento, foi utilizado o recurso **"Analyze sentiment and mine opinions"**, na aba **"Classify text"**.  


---

## 📊 Resultados  

O **Language Studio** permite carregar um texto para análise, selecionar o idioma e ativar a funcionalidade de **opinion mining**.  

Para o experimento, foi utilizado um capítulo do **livro de Mateus, da Bíblia**.  

O gráfico abaixo mostra os resultados da análise de sentimentos do texto completo. Segundo os dados, **65% do conteúdo foi classificado como negativo**, embora a confiança na análise seja de **apenas 25%**.  


Curiosamente, algumas sentenças apresentaram **alta confiança** na análise, enquanto outras foram classificadas como **100% negativas**, mas com **baixa confiabilidade**.  

Além disso, a funcionalidade de **opinion mining** foi testada para destacar termos-chave dentro do texto.  
 

---

## 📝 Conclusão e Insights  

A análise automatizada de sentimentos e opiniões pode ser extremamente útil para entender feedbacks de clientes e avaliações de produtos.  

💡 **Principais aprendizados deste experimento:**  
✅ **Alta eficiência em textos curtos** como avaliações de produtos e comentários.  
✅ **Dificuldade em analisar textos longos**, onde o contexto global pode ser ignorado.  
✅ **Baixa precisão em textos neutros ou ambíguos**, exigindo refinamentos no modelo.  
✅ **O uso combinado de análise de sentimentos e opinion mining** pode fornecer insights mais precisos.  

Embora a ferramenta seja poderosa, ela **analisa frases individualmente**, sem levar em conta o contexto geral do documento. Um modelo que consiga estabelecer conexões entre sentenças pode oferecer resultados mais robustos.   

---

## 🔗 Links Úteis  

- [Guia Oficial: Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)  
- [Introdução ao Azure Cognitive Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-cognitive-services.html)  
- [Tutorial: Criando um Recurso no Azure Language Service](https://portal.azure.com)  
