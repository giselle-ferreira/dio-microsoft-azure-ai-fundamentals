# language-studio-microsoft-azure

- Passo a passo de experimento utilizando **Language Studio** para análise de texto com análise de sentimentos e opiniões. 
- Realizado como desafio de projeto no Bootcamp **Microsoft Azure AI Fundamentals** da [Dio.me](https://dio.me)
- Documentação: [https://aka.ms/ai900-text-analysis](https://aka.ms/ai900-text-analysis)
- [Análise de Inputs Adicionais](#análise-de-inputs)

<br/>

## Passo 1
- Abrir a página do Portal [https://portal.azure.com/#home](https://portal.azure.com/#home) e clicar para criar um recurso.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/6bc43467-d189-4de9-a81a-f7ab8e0db078)

## Passo 2
- Com as funcionalidades adicionadas, basta clicar em "continue to create your resource"

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/5bb2b5e1-e5eb-4bc1-9115-dc638ee4966a)

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/2038b430-4fa4-4c58-9b0d-4e58ff7411f6)


## Passo 3
- Preencher as informações do recurso conforme imagem abaixo.
- Escolha um resource group, um nome (que deve ser único), e o Pricing Tier deve ser Free F0.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/b58bf3bf-d582-4cdc-a328-ff8cf2153c76)

- Não esquecer de marcar a caixa com a observação de Responsabilidade AI.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/838936e6-eb49-46d1-8e5e-d1ae982dd573)

- E então clique em Review + create para a validação das informações

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/7d7c96dc-5421-430b-af34-560663ebb187)

## Passo 4
- Depois da validação anterior, sua tela deve se parecer com esta.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/e16d155a-ebc5-4071-9c9f-8c19ecf4a93d)

- Agora sim, você clica em Create.

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/d90e8777-f774-4f91-b262-a69138d48ba6)

## Passo 5
- Esta é a tela de finalização da criação do recurso.
- Clique em "Go to resource group"

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/c1d90271-0365-4ad7-88a9-6f689dfc2c43)

- Esta é a tela que deve abrir

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/95c2901b-1f4b-47b2-8a0a-091a407dab54)

## Passo 6
- Abra a página do Language Studio (https://language.cognitive.azure.com/)[https://language.cognitive.azure.com/] com seu usuário logado.
- Automaticamente é aberta uma modal com as informações a preencher conforme imagem abaixo. Informe a Azure Subscription, o Resource Type e o resource group que você criou, e clique em "Done".

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/2a83e87a-6915-4e15-8d70-e22be36f8107)

## Passo 7
- Ainda no Language Studio, selecione a aba "Classify Text", e o card "Analyse Sentiment and mine opinions"

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/4538cce7-c0c7-4d0e-b218-cf20fa58637a)

## Passo 8
- Selecione o idioma do texto a ser utilizado (English).
- Copie o texto, fornecido pela documentação, na caixa de texto. Ver abaixo:

```
 Tired hotel with poor service
 The Royal Hotel, London, United Kingdom
 5/6/2018
 This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.
```

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/b433b007-6ded-4a86-b71f-5f28f624d3b0)

- Marque o box informativo
- Clique em "Run"

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/04e4719f-40a8-42bc-bfe4-3585e129df80)

## Passo 9
- Resultados

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/ce157701-918c-41df-b865-40c2294916c1)

- Ele traz o sentimento geral do texto
  
![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/89785bcc-f34d-46d6-a0e8-68bf51852442)

- Traz também a análise de cada uma das frases
- Ex.: Sentence 1 (basta clicar na aba da frase para abrir ou fechar)

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/e84ca617-1666-46c6-8d38-1acc393c7dab)

- Ex.: Análise da Sentence 2
  
![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/6f4c0832-7914-4488-a051-badc791c9921)

##

# Análise de inputs
- Abaixo compartilho o resultado das frases que trouxe de exemplo em [inputs](https://github.com/giselle-ferreira/language-studio-microsoft-azure/blob/main/inputs/sentences.txt)

## Sentence 1
- Escolho o idioma, incluo a frase e inicio o teste:

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/36fe823d-8096-49ff-9180-f2e2ae0674d7)
![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/93544242-8fef-4467-9cf2-9143fe6140f3)

- Resultados:
   <details>
   <summary>Análise de Sentimento da Frase Completa</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/80f72209-863f-49eb-88ab-418ec338cfe9)

   </details>    

   <details>
   <summary>Análise Fragmento 1</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/af4a21b3-4590-4ffe-97e7-1e8a9e9d2142)

   </details>
   
   <details>
   <summary>Análise Fragmento 2</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/c18d6596-5354-4af0-b521-4919d59e2d51)

   </details>

   <details>
   <summary>Análise Fragmento 3</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/3eefad6a-d6a5-48bb-96d3-93c09a53be3e)

   </details>

   <details>
   <summary>Análise Fragmento 4</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/5300a216-aad8-413f-8e55-473dcbca0c31)

   </details>

## Sentence 2
- Escolho o idioma, incluo a frase e inicio o teste:

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/0a4d2aea-33e9-4273-8016-f1d3c6a71422)
![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/93544242-8fef-4467-9cf2-9143fe6140f3)

- Resultados:
   <details>
   <summary>Análise de Sentimento da Frase Completa</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/262e5723-d750-4a63-9bf3-c7809bff6c7c)

   </details>    

   <details>
   <summary>Análise Fragmento 1</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/456b01ec-d16e-464b-9c40-e428bf0624c5)

   </details>
   
   <details>
   <summary>Análise Fragmento 2</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/6f028c9b-ccad-4380-9ebf-1b2bf78b1624)

   </details>

   <details>
   <summary>Análise Fragmento 3</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/e79e856e-91e2-46bf-9657-1ccb23bd306c)

   </details>

## Sentence 3
- Escolho o idioma, incluo a frase e inicio o teste:

![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/eb11d136-0c71-468d-89b8-ce8cc00405ec)
![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/93544242-8fef-4467-9cf2-9143fe6140f3)

- Resultados:
   <details>
   <summary>Análise de Sentimento da Frase Completa</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/1191db56-c5b1-4f6b-af99-947f94e90f45)

   </details>    

   <details>
   <summary>Análise Fragmento 1</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/c095bd4e-d675-4ed4-ab9b-7f171daac016)

   </details>
   
   <details>
   <summary>Análise Fragmento 2</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/103dee01-90ed-41cd-a29d-e7a304f57be7)

   </details>

   <details>
   <summary>Análise Fragmento 3</summary>

   ![image](https://github.com/giselle-ferreira/language-studio-microsoft-azure/assets/84051263/a48fb6d7-52f1-499f-89ff-efa37b755e7c)

   </details>


## Comentários
Pude perceber que as análise são bem similares e satisfatórias, não importa o idioma que estamos trabalhando, seja inglês, português, espanhol ou francês, confome nos exemplos adicionais que eu trouxe aqui. Não encontrei discrepâncias, e percebi que realmente é uma ferramenta poderosa para empresas no quesito de análise de satisfação dos clientes. 


##

<div align="center">
<p>Made with ❤️ by Giselle Ferreira.</p>
  <p>
    <a href="https://linkedin.com/in/giselleferreiras" target="_blank" >
      <img align="center" height="35" src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="Giselle Ferreira Linkedin" />
    </a>
    <a href="https://instagram.com/giselletech" target="_blank" >
      <img align="center" height="35" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/1200px-Instagram_icon.png" alt="Giselle Ferreira Instagram" />
    </a>
  </p>
</div>
