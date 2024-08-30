# package_rodrigo


from imagem_processador_rodrigo import processador
imagem = processador.carregar_imagem("caminho/para/imagem.jpg")
imagem_cinza = processador.converter_para_escala_cinza(imagem)
processador.salvar_imagem(imagem_cinza, "imagem_cinza.jpg")

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install imagem_processador_rodrigo

```bash
pip install imagem_processador_rodrigo
```

## Usage

```python
from imagem_processador_rodrigo import processador.py
processador.py.my_function()
```

## Author
Rodrigo

## License
[MIT](https://choosealicense.com/licenses/mit/)