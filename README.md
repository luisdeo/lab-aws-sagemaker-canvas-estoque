
Dataset usado:
[dataset_vendas.csv](https://github.com/user-attachments/files/16504130/dataset_vendas.csv)

Estrutura dos Dados para Previsão:

Criado um DataSet com Quantidade de Itens Vendidos como target usando Data de Venda como Data Stamp.


  Quantidade de Itens Vendidos:  Quantidade da vendas dos items.
  Data: Time Stamp das datas de venda.
  ID: Número do Produto


  Resultados das Métricas de Avaliação:
   
![Captura de tela 2024-08-05 223122](https://github.com/user-attachments/assets/7e3fae51-dd11-4ed9-ab61-2f011b03dc36)

  Avg. wQL:
  
		Valor: 0.522
		O que é: Mede o erro de previsão, levando em conta diferentes percentuais.
	
 MAPE: 
 
		Valor: 1.170
		O que é: Mostra o quão errado o modelo está, como uma porcentagem dos valores reais.
	
 WAPE:
 
		Valor: 0.667
		O que é: Pondera os erros de acordo com a importância dos dados.
	
 RMSE:
 
   	        Valor: 18.248
            O que é: Mostra a magnitude dos erros.
	
 MASE:
 
            Valor: 0.761
   	        O que é: Compara o erro do modelo com um método simples. Se o valor for menor que 1, o modelo é melhor que a média.


Pode se dizer que o Dataset usado é um modelo OK que poderia ser mais refinado para os processamentos de Machine Learning.


Usaremos o Item 3, para a predição.
![Captura de tela 2024-08-05 222213](https://github.com/user-attachments/assets/d685100d-ea92-4eb5-932c-23f39386c38c)

E segundo os resultados usaremos o forecast quantile do P50 pois é uma predição não otimista e não muito pessimista.
Aonde não saímos de perto da média geral de quantidade vendidas.
