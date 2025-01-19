## Projeto Conceitual de Ordem de Serviço para Oficina
# OFICINA

   ### Esquema conceitual: 
       - Sistema de controle
       - Gerenciamento de execução de ordens de serviço em uma oficina mecânica
   
# Modelando Ordem de Serviço:
  ### Oficina:
	        - Oferece serviços de manutenção 
	        - Conserto ou revisões  periódicas
	
  ### Cliente:
	        - O cliente vai até a oficina em busca de uma avaliação para seu carro.
	        - Que após a avaliação do mecânico, poderá autorizar ou não a execução do serviço.
            - O valor do serviço irá determinar se o cliente vai autorizar o serviço. 

  ### Equipe de Mecânicos:
            - Os mecânicos possuem código, nome, endereço e especialidade.
	        - A oficina possue uma equipe de mecânicos especializados 
            - A mesma equipe avalia e executa os serviços.
	        - A equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.

  ### O.S de Serviço:
          - A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra  
	      - Cada O.S possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
          - O valor de cada peça também irá compor a O.S.
    
  ### Entidades: 
        - Cliente
        - Veiculo
        - Oficina
        - Mecâncico
        - Avaliação
        - O.S
        - Execução de Serviço

  ## Software usado para modelagem
**MySQL Workbench**
