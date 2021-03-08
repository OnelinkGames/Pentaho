
# ETL Robots Logs
O proposito deste ETL é servir como ferramenta de automação para as atividades de separar os logs em pastas, excluir logs grandes e excluir pastas de logs antigos.

# Pré-requisitos
1. É necessário ter o Java 1.8 instalado na maquina para rodar o Pentaho.
3. É necessário ter o Pentaho versão 9.0 instalado na maquina e rodando.

# Instalação
1. Clonar o repositório e abrir o arquivo desejado com o Pentaho 9.0, o arquivo do projeto principal é o **main_job.kjb**
2. Abrir o arquivo **config.properties** e alterar a variável **files-path** para o caminho onde está os arquivos de log.

# Desenvolvimento
A documentação de desenvolvimento deste projeto se encontra no próprio projeto, bastando selecionar o step desejado, clicar com o botão direito sobre ele e ir na opção **Editar a descrição de entrada deste (job ou transformação)**

# Utilização
Abrir o ETL com as configurações já realizadas e rodar o job, ele irá organizar os arquivos em pastas e excluir pastas antigas ao final do processo, além de excluir qualquer log que tenha mais de 1GB de tamanho.
