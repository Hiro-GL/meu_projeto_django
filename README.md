Como Rodar o Projeto Localmente
Siga estes passos para configurar e executar este projeto Django em sua máquina local.

Pré-requisitos
Certifique-se de ter o seguinte instalado:

Python 3 (versão 3.8 ou superior recomendada)
pip (gerenciador de pacotes do Python)
Git (para clonar o repositório)
1. Clonar o Repositório
Primeiro, clone o repositório para sua máquina local usando o Git:

Bash

git clone https://github.com/Hiro-GL/meu_projeto_django.git
Em seguida, navegue até o diretório do projeto:

Bash

cd meu_projeto_django
2. Configurar o Ambiente Virtual

Ative o ambiente virtual:

Windows (Prompt de Comando - cmd.exe):

Bash

.\venv\Scripts\activate.bat
(Ou simplesmente .\venv\Scripts\activate)

Você saberá que o ambiente está ativado quando (venv) aparecer no início da linha de comando do seu terminal.

3. Instalar as Dependências do Projeto

Bash

pip install Django

5. Rodar o Servidor de Desenvolvimento
Finalmente, inicie o servidor de desenvolvimento do Django:

Bash

python manage.py runserver
Após executar este comando, o projeto estará acessível em seu navegador através do endereço:

http://127.0.0.1:8000/

Extra. Como rodar no Replit

1. Abra uma aba Shell

2. Coloque o codigo python manage.py runserver 0.0.0.0:8000

3. Enter, e pronto.
