# teste-analista-integracao

Teste para vaga de analista de integação - magazord


# Teste para vaga de Analista de Integração

1. Verificando a documentação de api da Magazord, é possível observar a necessidade de inclusão de um token e senha utilizando Basic Auth. Com base no retorno da requisição, uma possibilidade é que o cliente não tenha informado tais credenciais corretamente (não é uma certeza porque a mensagem difere do que consta na documentação). Para confirmar tal teoria, seria necessária validação com o cliente.

2. Verificando na documentação, o tipo do arquivo aparenta estar correto. Em uma análise inicial, validaria com o cliente as informações colocadas na requisição (especialmente o midiaFile, pois não parece estar codificado corretamente em base64). Caso estejam realmente corretas, solicitaria ao cliente que realizasse o mesmo procedimento com outro arquivo, considerando que a resposta sugere erro no conteúdo do arquivo (garantindo a funcionalidade correta da integração). 