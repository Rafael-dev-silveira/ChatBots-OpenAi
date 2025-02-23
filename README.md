Chatbots que utilizam IA generativa como o chatGPT da OpenAI
=
Vamos entender como o chat GPT funciona, a diferença entre usar o front-end do chat GPT e a API da OpenAI, que tem um custo associado. 

Vamos utilizar a documentação e a API da OpenAI para interagir com o modelo GPT 3.5, e vamos usar a biblioteca Streamlit em Python para construir um front-end de forma simples. 

Vamos personalizar as instruções para o nosso chatbot agir conforme desejamos

Abordado o processo de criação de um arquivo Python para utilizar o Streamlit e a OpenAI. 

São mencionados a importação das bibliotecas necessárias, a inicialização da conexão com a OpenAI, a criação de um título para o projeto, a utilização do Secrets do Streamlit para armazenar a API Key de forma segura, e a localização da chave de API na plataforma da OpenAI. 

Também é destacada a importância de não subir a chave de API para o GitHub.

 São apresentados os métodos ChatMessage e ChatInput do Streamlit para construir uma interface de chat. 
 
 O ChatMessage exibe o histórico de mensagens, enquanto o ChatInput permite inserir novas mensagens. 
 
 São explicados parâmetros necessários para interagir com o modelo GPT da OpenAI, como o modelo a ser utilizado e a gestão de mensagens. 
 
 A estrutura do chat é detalhada, com roles de usuário e assistente. 
 
 A configuração do front-end é demonstrada com exemplos de mensagens e respostas.

 Como utilizar o método chat_input para enviar mensagens para o GPT
 =
 Primeiramente, é criada a caixa de input com a mensagem inicial. 
 
 Em seguida, são definidas as instruções para o GPT atuar de forma informal. Após o usuário pressionar o input, a mensagem é salva e exibida no histórico da conversa. 
 
 A resposta do assistente é obtida da OpenAI utilizando o método chat_completions, passando as mensagens e o modelo como parâmetros.

Conclusão :
=
Este projeto foi criado nos meus estudos na RocketSeat,no curso de inteligencia artificial para desenvolvedores.
 
 
