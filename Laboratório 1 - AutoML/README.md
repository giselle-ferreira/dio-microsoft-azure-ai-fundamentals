# automl-microsoft-azure

- Passo a passo de experimento de Aprendizagem Automatizada, de Regressão, utilizando A **Azure Machine Learning**, realizado como desafio de projeto no Bootcamp **Microsoft Azure AI Fundamentals** da [Dio.me](https://dio.me)

<br/>

## Passo 1 
- Criar uma conta no [https://azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free)
- O cadastro é inicializado ao clicar no botão "Experimentar gratuitamente" (É necessário informar um número de cartão de crédito)

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/65ec85c8-0e65-4ec7-99ca-3dae6d5c70f5)

## Passo 2 
- Acessar a plataforma do Azure em [portal.azure.com](portal.azure.com)
- Buscar por "Azure Machine Learning" no campo de busca e selecionar o card referido.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/268bc950-6675-43f7-a7b0-f878ec8e5d26)

## Passo 3
- Clicar em "Criar", para criar um novo workspace

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/ee3f5e69-ca7e-481a-97c6-3e5b94239db7)


## Passo 4
- Criar um novo "resource group", criar um "nome", a "região", e clicar em "Examinar e criar"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/baa93339-7a6d-4103-9472-8642ea15471f)

- Aguardar até que a validação seja aprovada, e então clicar em "criar"
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/48f345fc-3c51-49d4-94e6-2d217c5e09be)

## Passo 5
- A implantação fica em andamento e pode ser acompanhada na tela que é aberta automaticamente

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/fe5f7747-7039-4525-b093-0d17a6149500)

- Esta é a tela de finalização do deploy. Agora podemos clicar em "ir para o recurso".
   
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/0bba7339-c866-4aa5-a254-2aa83120247b)

- Na tela do recurso, clicar em "Iniciar estúdio"
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/f163bd85-4275-481c-b771-b98972acc889)

## Passo 6
- O diretório do workspace é então aberto.
- Posso visualizar todos os workspaces existentes, clicando em "all workspaces"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/d0c313bc-288d-43ff-988e-a518deea160f)
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/70198982-b1cf-4e08-a81f-4bb4e2d7c469)

## Passo 7
- O workspace escolhido é aberto. Preciso agora entrar no ambiente "Automated ML" e clicar em criar um "new ML automated job"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/d36beebe-f666-4b4f-b811-962ac26daabe)

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/37bc5857-71d7-4550-b15e-15e358586003)

## Passo 7
- Preencher os dados do job com as informações (fornecidas pela documentação da Microsoft)

- 7.1 -> Preenchimento das informações básicas
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/03857d50-4b3a-4ad2-abbb-a531f2968a7a)

- 7.2 -> Escolha do tipo de tarefa (Regressão) e criação do dataset

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/44e58420-dd67-4c26-995b-adbcb0b235bf)


- 7.3 -> Preenchimento das informações do dataset

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/86b9b033-5042-4f21-9852-1f795e5332b8)

- 7.4 -> Escolha da fonte dos dados

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/06238e45-cca4-4825-a40c-ac363d057e3c)

- 7.5 -> Inclusão da url do dataset. A url passa por uma verificação e validação.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/fa37fc73-e064-4be5-8920-f1e1139f8f56)

- 7.6 -> Os dados devem estar com as seguintes configurações

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/3b2030c6-08b4-422d-8265-dd8bdbb2134c)

- 7.7 -> Ele traz uma visualização do schema. Não é necessário alterar nenhuma informação.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/c7cd6ac2-dcbd-40fb-9ca2-497b45c76120)

- 7.8 -> Por fim, ele traz todas informações para review, e clicamos em "criar", para criar o dataset.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/3dba151a-e6d4-4ac8-969d-8485f527a7e2)

- 7.9 -> Para avançar, selecionamos o dataset, e clicamos em "next"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/b615675d-30b7-4c53-8a33-284f2040c411)

- 7.10 -> Configurações da tarefa

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/c362fa19-26c8-4a5e-ad97-664085dcfaba)

- 7.11 -> Não é necessário setar nenhuma informação diferença da parte de Computação

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/31efafef-e201-4872-94d5-677eac379505)

- 7.12 -> As informações são trazidas e podemos enviar o trabalho de treinamento

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/e59c9084-09e2-47b7-86c8-146125f37356)

## Passo 8
- O modelo inicia o treinamento até a finalização
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/a788dc15-9ccc-42bb-ac97-eee69e4d54cd)

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/8a0edf91-aacf-4ddf-9db9-fcee526c5997)

## Passo 9
- Validar métricas

- 9.1 -> Acessar as informações do modelo conforme imagem abaixo
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/56d6b4e5-fdef-4851-ba1a-66353f5cfad1)

- 9.2 -> Acessar o job

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/644f1220-2b2a-4c77-a2cf-14a9c1e54d8a)

- 9.3 -> Acessar as métricas

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/09c1e784-88ef-4874-907c-7a69cad7da9a)

- As métricas trazem dois gráficos, o predicted_true e o residuals, que trazem informações de valores previstos comparados com os reais

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/5ec09914-fe37-453e-9468-290537921ad3)

## Passo 10
- Deploy e Teste do Modelo

- 10.1 -> De volta à página do modelo, escolhemos a opção de Deploy Web Service.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/7f2d36b0-3d97-4a05-a593-07406dd2dbc0)

- 10.2 -> Preencher com as informações fornecidas na documentação e clicar em "Deploy"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/36f2c66f-2322-4777-94a3-8900fb367750)

- 10.3 -> Receberemos a notificação de que o deploy está completo e, no menu esquerdo, vamos clicar na aba Endpoints.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/53696037-5733-47b6-af72-4c1b69ac0d0b)

- 10.4 -> Na tela de Endpoint, confirmamos o status "Succeed" do deploy, e clicamos na aba "Test"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/2b929571-c2b8-424c-bccb-d05c21b0c1ef)

- 10.4 -> Substituímos o json existente, pelo código fornecido pela documentação, e depois clicamos em "Test".

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/a5185136-afb5-4af4-a0b2-057d1ece66b1)

- 10.5 -> Resultado do Teste

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/60b1b3bc-8737-44d1-8cad-d28dabe853df)


## Códigos

<details>
<summary>Input (Clique para abrir)</summary>

```
 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }
```

</details>


<details>
<summary>Resultado (Clique para abrir)</summary>

```
{
  "Results": [
    331.839379193704
  ]
}
```

</details>

<details>
<summary>Swagger URI (Clique para abrir)</summary>

```
// 20240206030758
// http://ca6e07b7-d4a1-4ad1-8c57-489dfd4c6228.eastus.azurecontainer.io/swagger.json

{
  "swagger": "2.0",
  "info": {
    "title": "predict-rentals",
    "description": "API specification for the Azure Machine Learning service predict-rentals",
    "version": "1.0"
  },
  "schemes": [
    "https"
  ],
  "consumes": [
    "application/json"
  ],
  "produces": [
    "application/json"
  ],
  "securityDefinitions": {
    "Bearer": {
      "type": "apiKey",
      "name": "Authorization",
      "in": "header",
      "description": "For example: Bearer abc123"
    }
  },
  "paths": {
    "/": {
      "get": {
        "operationId": "ServiceHealthCheck",
        "description": "Simple health check endpoint to ensure the service is up at any given point.",
        "responses": {
          "200": {
            "description": "If service is up and running, this response will be returned with the content 'Healthy'",
            "schema": {
              "type": "string"
            },
            "examples": {
              "application/json": "Healthy"
            }
          },
          "default": {
            "description": "The service failed to execute due to an error.",
            "schema": {
              "$ref": "#/definitions/ErrorResponse"
            }
          }
        }
      }
    },
    "/score": {
      "post": {
        "operationId": "RunMLService",
        "description": "Run web service's model and get the prediction output",
        "security": [
          {
            "Bearer": [
              
            ]
          }
        ],
        "parameters": [
          {
            "name": "serviceInputPayload",
            "in": "body",
            "description": "The input payload for executing the real-time machine learning service.",
            "schema": {
              "$ref": "#/definitions/ServiceInput"
            }
          }
        ],
        "responses": {
          "200": {
            "description": "The service processed the input correctly and provided a result prediction, if applicable.",
            "schema": {
              "$ref": "#/definitions/ServiceOutput"
            }
          },
          "default": {
            "description": "The service failed to execute due to an error.",
            "schema": {
              "$ref": "#/definitions/ErrorResponse"
            }
          }
        }
      }
    },
    "/swagger.json": {
      "get": {
        "operationId": "GetSwaggerSpec",
        "description": "Get the Swagger specification.",
        "parameters": [
          {
            "name": "version",
            "in": "query",
            "required": false,
            "type": "integer",
            "enum": [
              2,
              3
            ]
          }
        ],
        "responses": {
          "200": {
            "description": "The Swagger specification.",
            "schema": {
              "type": "string"
            }
          },
          "default": {
            "description": "The service failed to execute due to an error.",
            "schema": {
              "$ref": "#/definitions/ErrorResponse"
            }
          }
        }
      }
    }
  },
  "definitions": {
    "ServiceInput": {
      "type": "object",
      "properties": {
        "Inputs": {
          "type": "object",
          "required": [
            "data"
          ],
          "properties": {
            "data": {
              "type": "array",
              "items": {
                "type": "object",
                "required": [
                  "day",
                  "mnth",
                  "year",
                  "season",
                  "holiday",
                  "weekday",
                  "workingday",
                  "weathersit",
                  "temp",
                  "atemp",
                  "hum",
                  "windspeed"
                ],
                "properties": {
                  "day": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "mnth": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "year": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "season": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "holiday": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "weekday": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "workingday": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "weathersit": {
                    "type": "integer",
                    "format": "int64"
                  },
                  "temp": {
                    "type": "number",
                    "format": "double"
                  },
                  "atemp": {
                    "type": "number",
                    "format": "double"
                  },
                  "hum": {
                    "type": "number",
                    "format": "double"
                  },
                  "windspeed": {
                    "type": "number",
                    "format": "double"
                  }
                }
              },
              "format": "pandas.DataFrame:records"
            }
          }
        },
        "GlobalParameters": {
          "type": "number",
          "format": "double"
        }
      },
      "example": {
        "Inputs": {
          "data": [
            {
              "day": 0,
              "mnth": 0,
              "year": 0,
              "season": 0,
              "holiday": 0,
              "weekday": 0,
              "workingday": 0,
              "weathersit": 0,
              "temp": 0.0,
              "atemp": 0.0,
              "hum": 0.0,
              "windspeed": 0.0
            }
          ]
        },
        "GlobalParameters": 1.0
      }
    },
    "ServiceOutput": {
      "type": "object",
      "required": [
        "Results"
      ],
      "properties": {
        "Results": {
          "type": "array",
          "items": {
            "type": "integer",
            "format": "int64"
          },
          "format": "numpy.ndarray"
        }
      },
      "example": {
        "Results": [
          0
        ]
      }
    },
    "ErrorResponse": {
      "type": "object",
      "properties": {
        "message": {
          "type": "string"
        }
      }
    }
  }
}
```

</details>

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
