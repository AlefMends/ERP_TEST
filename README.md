# Technical Test 2023
NEXER-BRA Technical Test 2023<br>

 LISTA DE REQUERIMENTOS<br><br>
▪ Task 1 – Ajustar problema ao cadastrar Caminhão;<br>
▪ Task 2 – Implementar novo transporte Avião;<br>
▪ Task 3 – Implementar cadastro de combustível nos veículos;<br>
▪ Task 4 – Implementar função para cálculo de frete.<br><br><br>


DETALHAMENTO FUNCIONAL<br><br>
3.1 AJUSTAR PROBLEMA AO CADASTRAR CAMINHÃO<br><br>
Ao adicionar um novo veículo do tipo Caminhão, o sistema cadastra de forma errada um <br>
novo veículo do tipo Carro. Ajuste para que ao adicionar um novo veículo, o sistema faça <br>
o registro correto do tipo informado pelo usuário<br>
![image](https://github.com/AlefMends/ERP_TEST/assets/95005787/11b999ba-c709-4a48-bb77-a5a87598465d)<br>
![image](https://github.com/AlefMends/ERP_TEST/assets/95005787/5e72d649-dbe6-4e5f-b3d6-1b7c587add38)<br>
Resultado esperado:<br>
Deverá ser possível cadastrar veículos do tipo Caminhão<br><br><br>

3.2 IMPLEMENTAR NOVO TRANSPORTE AVIÃO<br><br>
A empresa busca expandir sua área de atuação e pretende adquirir alguns aviões. <br>
Implemente a possibilidade de cadastrar o tipo Avião na frota dentro do sistema.<br>
Resultado esperado:<br>
Deverá ser possível cadastrar o novo tipo Avião dentro da tela Adicionar Veículo e <br>
visualizá-los na tela Veículos Cadastrados.<br><br><br>

3.3 IMPLEMENTAR CADASTRO DE COMBUSTÍVEL NOS VEÍCULOS<br><br>
Implemente o campo Combustível no cadastro Adicionar Veículos, cada veículo da <br>
companhia tem apenas 1 tipo de combustível.<br>
O campo Combustível será uma lista pré-definida de valores, como na tela Tabela de <br>
Combustível.<br>
Resultado esperado:<br>
Deverá ser possível associar um combustível a um veículo na tela Adicionar Veículo e <br>
visualizar o campo Combustível de cada veículo na tela Veículos Cadastrados.<br><br><br>

3.4 IMPLEMENTAR FUNÇÃO PARA CÁLCULO DE FRETE><br>><br>
Implemente uma nova função na tela Cálculo de Frete que exiba o veículo ideal para o ><br>
frete e o custo do frete para a entrega. ><br>
A função deve considerar tanto a distância da entrega quanto o peso da carga para ><br>
determinar qual veículo é o mais adequado levando em consideração a autonomia ><br>
(quilômetros por litro) e o preço do combustível cadastrados para cada veículo.><br>
Para ilustrar, considere um exemplo onde a entrega possui um peso de 30 kg e está a ><br>
uma distância de 5 km. Suponha que um veículo suporte até 10 kg e tenha autonomia de ><br>
8 km/litro, com um preço de combustível de R$ 4 por litro. ><br>
6
Nesse cenário, o veículo precisaria realizar 3 viagens para concluir a entrega. O custo 
total do frete calculado seria R$ 7,50.<br>
![image](https://github.com/AlefMends/ERP_TEST/assets/95005787/f8e0dde1-c0b2-4315-9798-e077557cf0a0)<br><br>

Resultado esperado:<br>
Na tela Verificar Autonomia, ao clicar no botão Calcular o sistema deverá verificar a <br>
frota de veículos cadastrados e exibir na tela as informações Tipo de Veículo, Marca, <br>
Modelo e Custo do frete do veículo que puder fazer a entrega no menor custo possível, <br>
considerando os valores inseridos nos campos Distância (KM) e Peso da Carga (KG) da <br>
tela<br><br><br>

(infelizmente não consegui fazer o 3.4)

