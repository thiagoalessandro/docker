# Docker

#Logstash

##Arquivos de configurações
Os arquivos de configurações também podem ser fornecidos através de montagens de ligação. O Logstash espera encontrá-los em /usr/share/logstash/config/.

##Configuração de logeditar
Em Docker, os logs do Logstash vão para a saída padrão por padrão. Para alterar esse comportamento, use qualquer uma das técnicas acima para substituir o arquivo em /usr/share/logstash/config/log4j2.properties.
