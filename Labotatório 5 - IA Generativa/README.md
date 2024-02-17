# ia-generativa-microsoft-azure
- Gerando Imagens com o Microsoft Copilot [https://copilot.microsoft.com/](https://copilot.microsoft.com/).
- Input 1:
  
![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/985e2b69-4b47-4db6-b670-c8ba4a047819)

- Output 1:

![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/55c82185-574b-4848-86a1-e166115dbfee)

- Input 2:

![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/d7efe751-238f-422d-a37a-d53202534597)

- Output 2:

![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/433fea75-6cd8-4362-b2a3-ba9bb59e987f)


#


# Reconhecimento de Texto a partir de imagens

- Passo a passo de experimento utilizando Vision Studio/ **Azure AI Vision** para extrair texto de imagens sem a utilização de código, com tecnologia OCR (Optical Character Recognition).

<br/>

## Passo 1
- Acessar [portal.azure.com](portal.azure.com) e clicar em "create a resource"

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/8a505e91-cc1b-446a-9e09-6fedf3b2dda8)

## Passo 2
- Buscar por "Ai azure services" e clicar em "create"

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/1440bff9-db85-4e4c-add5-723ae2b1978d)

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/9e018f9f-0c57-43b8-8627-d3c7b8df9c37)

## Passo 3
- Preencher as informações mostradas abaixo. O resource group pode ser novo ou existente. Escolhi um que eu já havia criado anteriormente. Depois disso, basta clicar em "review + create", e depois "create", e aguardar a finalização do deploy.

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/cc3d884b-29c9-4214-b857-a89566573358)
![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/4e02b437-2eb4-45ff-8f6c-5e67c253b191)
![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/78da3b04-368f-4009-93d2-77002712900b)

- Esta é a tela depois da finalização do deploy

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/df1bb43a-b25e-4b8d-8bf9-e3bb118ac11d)

## Passo 4
- Conectar o resource com o Vision Studio.
- Em outro navegador, ir para [https://portal.vision.cognitive.azure.com/?azure-portal=true](https://portal.vision.cognitive.azure.com/?azure-portal=true) e clicar em "View All Resources"

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/b2f300c4-363a-4619-a9eb-39df4adfbcc3)

- Clicar em "refresh" para que a lista seja carregada com o resource criado anteriormente, clicar para selecionar o mesmo, e depois clicar em "Select as default resource"

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/98557f0d-abe1-4d07-95ff-35108bd11dba)

## Passo 5
- Em outro navegador, abrir novamente a landing page [https://portal.vision.cognitive.azure.com/](https://portal.vision.cognitive.azure.com/), ir até a aba "Optical Character Vision" e clicar em "Extract text from images"

![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/d44d01fc-6add-48a3-9a6d-336c8c704b0a)

## Passo 6
- Marcar a opção conforme imagem abaixo
  
![image](https://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/b9925fc8-c5b6-420a-9242-8bf68c6b189f)

## Passo 7
- No portal, selecione "browse for a file" e selecione uma imagem com texto, e depois clique em abrir.
- A coluna da esquerda mostra a imagem fornecida, e a da direita, o resultado do texto extraído.

![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/7aac6ee3-8fd7-4b19-a2d0-689018fef0cf)

- Teste com a imagem 2

![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/6a2c93c9-8677-4cc7-8660-1e90bc24dbad)

- Teste com a imagem 3

![image](https://github.com/giselle-ferreira/ia-generativa-microsoft-azure/assets/84051263/4e103f4c-186a-4e59-bf0a-c6b27d66790e)


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
