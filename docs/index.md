# Bem-vindo ao MkDocs

Para documentação completa visite [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Crie um novo projeto.
* `mkdocs serve` - Inicie o servidor de documentos.
* `mkdocs build` - Construa o site de documentação.
* `mkdocs -h` - Imprimir mensagem de ajuda e sair.

## Project layout

    mkdocs.yml    # O arquivo de configuração.
    docs/
        index.md  # A página inicial da documentação.
        ...       # Outras páginas de markdown, imagens e outros arquivos.
		
## superfances
``` {.py3 hl_lines="10 11" linenums="10" title="exemplo.py"}
def xpto():
	"""docstring."""
	return 'Olá, bb!'
```

## diagramas mermaid
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
