# Projeto Scuba Cat
Descrição:

Este repositório contém o código-fonte do projeto Scuba Cat, cujo objetivo é, por meio da identificação de gestos, exibir um GIF animado.

Nota importante sobre a versão do Python
O projeto deve ser executado utilizando Python 3.10, pois existem incompatibilidades e exceções em bibliotecas essenciais ao utilizar versões diferentes.

Requisitos do Python:
Python 3.10.x (obrigatório)
Não há garantia de compatibilidade com:
Python 3.11+
Python 3.9 ou versões anteriores

# Motivo
Algumas das bibliotecas utilizadas no projeto possuem dependências que ainda não são compatíveis, ou geram exceções de execução fora do Python 3.10. Por esse motivo, a branch main está validada e suportada apenas no Python 3.10.

# Exemplo de uso:
Utilizando o gerenciador de projetos uv:
# Instalar o Python 3.10 caso ainda não esteja instalado
uv python install 3.10
# Criar ambiente virtual com essa versão
uv venv --python 3.10
# Ativar o ambiente
source .venv/bin/activate # Linux
.venv\Scripts\activate    # Windows Powershell
# Instalar dependências
uv pip install opencv-python mediapipe==0.10.21 imageio

# Executar
uv run main.py
