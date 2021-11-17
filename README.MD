# Exemplificando a Implantação utilizando o Heroku

## Fabrício Galende M. de Carvalho

Para testar e implantar esse sistema:

I. Teste de execução local:

1. Clonar o repositório
2. Criar um ambiente virtual
```console
virtualenv env
```
3. Ativar o ambiente virtual (no windows o arquivo é o .bat):
```console
env/Scripts/activate.bat
```
4. Instalar as dependências:
```console
pip install -r requirements.txt
```
5. Executar a aplicação (na pasta src/)
```console
python application.py
```

II. Implantar no Heroku (supondo que já tenha a conta na plataforma)

