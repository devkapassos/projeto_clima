# projeto_clima
Este é um projeto de previsão do tempo, que permite ao usuário consultar as condições climáticas em uma cidade específica, incluindo temperatura, umidade e velocidade do vento. Ele utiliza a Weather API para fornecer dados climáticos em tempo real.

## Funcionalidades
- Busca por Cidade: O usuário insere o nome de uma cidade para ver as condições climáticas.
- Exibição de Dados Climatológicos: Inclui a temperatura atual, umidade, velocidade do vento e a condição climática.
- Ícone da Condição Climática: Exibe um ícone relacionado ao estado atual do clima (ex.: ensolarado, chuvoso).


## Tecnologias Utilizadas
- HTML5 e CSS3: Estrutura e estilo da aplicação.
- JavaScript: Manipulação da DOM e integração com a Weather API.
- Weather API: API de terceiros usada para obter informações sobre o clima em tempo real.


## Estrutura do Código
- HTML: A interface contém uma área de busca e duas seções para exibir informações:
  - Seção Principal: Mostra a cidade, temperatura e condição climática.
  - Seção Secundária: Exibe informações de umidade e velocidade do vento.
- CSS: Estiliza a página, com uma interface centralizada e uma combinação de cores atraente para a exibição de dados climáticos.
- JavaScript:
  - buscarDadosDaCidade(cidade): Faz a chamada para a API, usando a cidade fornecida.
  - preencherDadosNaTela(dados, cidade): Insere as informações do clima na página, como temperatura e umidade, e atualiza o ícone da condição climática.

## Como Executar
***Pré-requisitos***
- Navegador atualizado com suporte a JavaScript
- Chave de API da Weather API (você pode obter uma gratuitamente em WeatherAPI.com)
***Passo a Passo***
1. Clone este repositório e navegue até o diretório do projeto.
2. No arquivo index.js, substitua o valor da variável chaveDaApi pela sua chave da Weather API:
    ```bash
    const chaveDaApi = "sua-chave-aqui";
3. Abra o arquivo index.html no navegador para ver a aplicação em funcionamento.

## Exemplo de Fluxo de Uso
1. Busca: Insira o nome de uma cidade no campo de busca e clique no ícone de lupa.
2. Visualização dos Dados: As informações de temperatura, condição climática, umidade e velocidade do vento são exibidas na interface.

## Personalização e Estilo
A interface foi projetada para ser simples e intuitiva, com um esquema de cores escuro e ícones que representam as condições climáticas. A fonte principal utilizada é Red Hat Display, trazendo um visual moderno.
