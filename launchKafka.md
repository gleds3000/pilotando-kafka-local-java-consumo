#Pilotando-kafka-local-java


##Para MAC 

primeiro install kafka do site apache kafka 

##Lançando os servicos
para cada comando uma aba de terminal 

cmd 1
 zookeeper-server-start.sh ~/kafka/config/zookeeper.properties
cmd 2 
 kafka-server-start.sh ~/kafka/config/server.properties 


##Validando o kafka 

kafka-topics.sh --bootstrap-server localhost:9092 --list  


##Criando um topico 


kafka-topics.sh --bootstrap-server localhost:9092 --create --topic piloto-msg   

##Para visualizar as msg geradas 
 Conduktor
app para windows linux e mac 
https://www.conduktor.io/download/
 basta configura para seu ambiente localhost:9092
 
 
 -----------
 <span style="color:blue"> Produto para fim educativo </span>
 ------------
 |versão|Autor|Criado em| Atualizado em |
 |---|---|---|---|
 |1.0|Gleds3000|05-03-21|-|
 