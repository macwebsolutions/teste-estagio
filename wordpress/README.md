# Teste Estagiário MacWeb

## Exercício Nivelamento - Wordpress

**Objetivo desse exercício**: mesmo que não tenha um nível intermediário em Wordpress no tocante a desenvolvimento de tema o candidato poderá ter um momento para aprender ao mesmo tempo que nos possibilitará conhecer o nível Wordpress informado ao se candidatar para a vaga.

### Ambiente para fazer o exercício:

Para esse exercício você deverá ter o Wordpress instalado em sua máquina para desenvolvimento.

Você poderá:

1. Em ambiente Windows você pode utilizar o [WAMP](http://www.wampserver.com/en/#download-wrapper) em sua máquina para instalar o servidor web Apache + MySQL + PHP para então instalar o Wordpress localmente
2. Instalar o [Docker](https://www.docker.com/get-started) e usar o Docker Compose - [arquivo docker-compose preparado aqui](https://github.com/macwebsolutions/teste-estagio/blob/master/wordpress/docker-compose.yml) - para subir uma instância do Wordpress em sua máquina.

**Caso escolha item 2. Docker**

Após instalar o Docker:

1. [Baixar o docker-compose.yml](https://github.com/macwebsolutions/teste-estagio/blob/master/wordpress/docker-compose.yml) e salvar em uma pasta
2. Acessar a pasta via terminal e rodar `docker-compose up -d`
3. Aguarde até o Docker subir a instância, após basta acessar `http://localhost` em seu navegador para iniciar a instalação do Wordpress

### Tarefa

Você deverá criar um tema simples, não será necessário estilizar telas ou criar detalhes de UI, o tema deverá apresentar a capacidade de lidar com

1. Página de Blog (lista de artigos) (blog archive)
2. Página de Artigo do blog (blog single)
3. Página de lista de resultado de pesquisa

Você tem a liberdade de consultar os materiais web do [Codex Wordpress](https://codex.wordpress.org/Theme_Development) para aprender/entender como um tema é desenvolvido.

### Prazo

Você terá até 01/09/2018 às 23 h 59 min para encaminhar o exercício conforme informado abaixo.

### Enviando o exercício

Você deverá retornar para webmaster@macweb.com.br o seu tema em formato zip (zipar a pasta do tema criado).

Nós iremos rodar a instalação do tema em nosso ambiente de teste e testar os itens citados.