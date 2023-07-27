# PruebaDP

Cambio 1: Se le dió mejor formato al archivo Respuesta1.json

Cambio 2: En la linea 46 del archivo api.php se le asignó el valor al objeto que se estaba retornando, ya que no estaba trayendo información venía como $Valor = []

Cambio 3: En la linea 62 del archivo api.php se le hizo el mismo cambio a la función de exportar() que hicimos en la función de MetodoGet() para que asignara el valor del objeto retornado (a pesar de que esa función para exportar no se usa, ya que se utiliza en el call el MetodoGet)

Cambio 4: En la linea 29 del archivo valida.php se agregó response en la función ObtenerResponse(), ya que esta función se utiliza en el MetodoGet que mencionamos anteriormente para devolver la respuesta, no estaba trayendo nada aunque usaramos el MetodoGet porque no estaba devolviendo el response desde valida.php



PruebaDP
