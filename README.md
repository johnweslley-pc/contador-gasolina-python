# contador-gasolina-python

Projeto simples em Python criado durante meus estudos para calcular o custo de completar o tanque de combustível.

## Código

```python
tanque_capacidade = 50
tanque_atual = 20
preco_gasolina = 5.80

gasolina_faltando = tanque_capacidade - tanque_atual
custo_para_encher = gasolina_faltando * preco_gasolina

print("Capacidade do tanque:", tanque_capacidade, "litros")
print("Gasolina atual:", tanque_atual, "litros")
print("Faltam", gasolina_faltando, "litros para completar")
print("Custo para encher: R$", custo_para_encher)
```
