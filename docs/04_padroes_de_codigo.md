# 💡 Padrões de Código

## Convenções Gerais
- Seguir a **PEP8** para código Python.
- Utilizar **docstrings** no formato Google Style.
- Nomear arquivos e diretórios em **snake_case**.
- Usar comentários curtos e objetivos.
- Organizar imports por tipo (padrão, terceiros, internos).

## Estrutura de Arquivos

```
src/
    ├── main.py
    ├── models/
    ├── views/
    ├── controllers/
    └── utils/
``` 

## Estilo de Código
```python
def calcular_total(itens: list[float]) -> float:
    """Calcula o total da soma de itens.

    Args:
        itens (list[float]): Lista de valores.

    Returns:
        float: Soma total.
    """
    return sum(itens)
```

## Boas Práticas
- Funções pequenas e de propósito único.
- Mensagens de commit claras e no imperativo:
- Exemplo: add função de cálculo total
- Sempre documentar decisões no código ou em docs/decisoes.md.