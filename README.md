# conversor_andre_conforti

Descrição. 
O pacote conversor_unidades é utilizado para realizar conversões simples entre diferentes unidades de medida. 
Ele oferece funções para converter:
	- Temperatura: Celsius para Fahrenheit e vice-versa.    
	- Comprimento: Metros para centímetros e vice-versa.

## Instalação

Utilize o gerenciador de pacotes [pip](https://pip.pypa.io/en/stable/) para instalar o conversor_unidades:

```bash
pip install conversor-andre-conforti
```

## Uso

```python
from conversor_unidades.temperatura import celsius_para_fahrenheit
from conversor_unidades.comprimento import metros_para_centimetros

# Convertendo temperatura
temperatura_celsius = 25
temperatura_fahrenheit = celsius_para_fahrenheit(temperatura_celsius)
print(f"{temperatura_celsius}°C equivalem a {temperatura_fahrenheit:.2f}°F")

# Convertendo comprimento
comprimento_metros = 1.5
comprimento_centimetros = metros_para_centimetros(comprimento_metros)
print(f"{comprimento_metros}m equivalem a {comprimento_centimetros}cm")
```

## Author
André Conforti

## Versão
0.0.2

## License
[MIT](https://choosealicense.com/licenses/mit/)
