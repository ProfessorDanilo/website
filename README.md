# website
Site desenvolvido durante o projeto integrador 1 da Univesp.

### 1. Clonando o repositório

No terminal, digite:
  ```bash 
  $ mkdir ~/git

  $ git clone https://github.com/univesp-projetointegrador1/website.git

  (digite seu login e senha do GitHub)

  $ cd ~/git/website
  ```

### Para criar um ambiente virtual:
  ```bash 
  
  virtualenv env

  source env/bin/activate
  ```

### Para instalar pacotes necessários:
  ```bash 
  
  pip install flask

  pip install sqlalchemy

  pip install flask-sqlalchemy
  ```

### Para atualizar o repositório:
  ```bash 
  git pull
  ```

### Antes de rodar exporte as seguintes variáveis de ambiente:
  ```bash
  export FLASK_APP=app
  export FLASK_ENV=development
  ```
### Para rodar o servidor:
  ```bash
  flask run
  ```
 Acessar o endereço 127.0.0.1:5000 de execução no navegador de internet.
 
 
