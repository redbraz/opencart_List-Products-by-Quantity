# [brazil] Opencart - List Products by Quantity
Put the products with the largest inventory in first and products sold out at the end of the display list.

Compatibility: oc 3xxx
Modified pages: categories and promotions
	
  This xml will be available for free for future queries and improvements, thanks! :)
	We are changing the query to bring the products with the highest number quantity first in the general list
	See that you can change the query to bring products with stock based on the condition $sql .= " ORDER BY (p.quantity > 0) DESC, ";
  
  ---
  Este xml estará disponível gratuitamente para futuras consultas e melhorias, obrigado! :)..
  		Estamos mudando a consulta para trazer os produtos com o maior número em estoque primeiro na lista geral e na listagem de produtos promocionais.
  		Veja que você pode alterar a consulta para trazer produtos com estoque com base na condição $sql. = "ORDER BY (p.quantity > 0) DESC,";
  "Esse segunda condição traz os itens sem o parametro de maior quantidade, e sim envia os itens esgotados para o fim da lista."
  
  Note que testamos essa condição baseando-se em uma versão limpa do pacote 3.0.3.2, 
  note tambem que se você tiver outras modificações que afetem diretamnete o model do produto, sugerimos que você verifique isso antes de correr esse xml.
  
  Abaixo, caso você ainda não tenha experiência com o motor de modificações, execute o passo-a-passo conforme sugerido!
	
    1- Click on extensions > install > select the file you downloaded
    2- then extensions > modifications "click update on the blue button in the upper right corner"
    3- In the panel home > click on the gear in the upper right corner and select "update thema"
    4- Enjoy, this should increase your sales!!!
   
