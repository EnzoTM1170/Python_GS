# Planeta Azul
## Membros:
##### RM Enzo Teles 553899 
##### RM Nicolas Ribeiro 553273

## Descrição do Projeto:
Planeta Azul é uma iniciativa pioneira dedicada ao monitoramento da poluição nos oceanos. Utilizando tecnologia de ponta, empregamos sensores avançados para avaliar não apenas o pH da água, mas também sua turbidez e o nível de poluição (em uma escala de 0 a 10), registrando ainda a localização e a data das medições. O pH da água é um indicador crucial da saúde do ecossistema marinho, sendo qualquer alteração nesses níveis um possível sinal de presença de poluentes.

Para ampliar a eficácia do monitoramento, criamos o site Planeta Azul, onde todos os dados coletados são armazenados e analisados. Caso seja detectada poluição excessiva em uma determinada região, o site emitirá um alerta imediato, indicando que aquela área está em perigo. Além disso, na aba de denúncias do site, você pode reportar casos de descarte ilegal de lixo, contribuindo diretamente para a preservação do meio ambiente.

## Instruções de Uso:

### Execução do Programa:
Certifique-se de ter o Python instalado em sua máquina.
Execute o script Python fornecido para iniciar a interface gráfica (GUI).

### Interface Gráfica:
pH: Insira o valor do pH da água.
Turbidez: Insira o valor da turbidez da água.
Poluição: Insira o nível de poluição (0 a 10).
Área: Insira a área onde a medição foi feita.
Data: Insira a data da medição no formato dd/mm/aaaa.
Clique no botão "Registrar Dados" para salvar os dados e enviar para o serviço web.

### Resultados:
A mensagem de resultado será exibida na parte inferior da interface, indicando se os dados foram registrados com sucesso ou se houve algum erro.

## Requisitos:
Python 3.x
Biblioteca tkinter (inclusa no Python padrão)
Biblioteca requests (instalar via pip install requests)
Biblioteca csv (inclusa no Python padrão)

## Dependências:
requests: Utilizada para enviar os dados para um serviço web.

## Estrutura do Projeto:
Código Principal: Script Python que implementa a interface gráfica e a lógica de registro de dados.
Arquivo CSV: dados_oceanos.csv para armazenar localmente os dados coletados.




















