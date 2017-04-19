## 19-04-2017-SO
### Jesús Alberto Ramírez Otálvaro
### Código: 1422554

### Ejercicio 1
  echo $(ps -A | wc -l)

#### Otra manera más exacta sería:
#### export var1=$(ps -A | wc -l)
#### echo $((var1 - 1))

### Ejercicio 2
#### export cuadrado=$((2**4))
#### echo $cuadrado

