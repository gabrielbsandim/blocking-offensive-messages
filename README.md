# Bloqueio de Mensagens Ofensivas

Este script utiliza o modelo de linguagem grande (LLM) da Google AI, Gemini, para analisar e bloquear mensagens ofensivas. Ele é ideal para aplicações que recebem input de usuários, como comentários em redes sociais, fóruns ou chats.

## Funcionalidades:
* Analisa mensagens de texto em tempo real.
* Classifica mensagens como ofensivas ou não ofensivas.
* Bloqueia mensagens ofensivas de serem exibidas ou processadas.
* Utiliza configurações de segurança para personalizar o nível de bloqueio.

## Configuração

1. Instale as dependências: `pip install -q -U google-generativeai`
1. Obtenha uma chave de API do Google.
1. Cole a chave de API no arquivo de configuração.

## Como Usar
1. Execute o arquivo `BlockingOffensiveMessages.ipynb` no [Google Colab](colab.new/).
2. Insira o texto que deseja testar quando solicitado.
3. Aguarde o veredito sobre a ofensividade.

> Para finalizar a execução do programa, digite `finish` no input.

## Exemplos de Resultados
> [Mensagem não ofensiva](https://drive.google.com/file/d/1LTL9Ezb6a2vfj82TMAcGoQP6_8f_v68A/view?usp=sharing)

> [Mensagem ofensiva](https://drive.google.com/file/d/1S9M0EnGSoix3cXWwA7q6R4pCWzMKjMWl/view?usp=sharing)

## Próximos Passos
* Melhorar a precisão do modelo com mais dados de treinamento e técnicas de aprendizado de máquina.
* Criar API Rest que recebe o texto a ser analisado e responde com a análise realizada.


## Licença

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo LICENSE.md para obter detalhes.

---
