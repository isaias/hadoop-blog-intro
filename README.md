hadoop-blog-intro
=================

Contém um código de um MapReduce simples que recebe registros a partir de arquivos texto e gera um arquivo de saída contendo
cada código de doença e o número de ocorrência.

Formato de entrada:

cod_paciente;data_atendimento;cod_doenca

Formato de saída:

cod_doenca <espaco> número de ocorrências

Arquivos de exemplo estao localizados em hadoop-blog-intro/src/main/resources/input e hadoop-blog-intro/src/main/resources/output

#Referências para executar o MapReduce

Configurando o Hadoop: http://hadoop.apache.org/common/docs/r1.0.3/single_node_setup.html