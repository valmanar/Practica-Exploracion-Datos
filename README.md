# Practica-Exploracion-Datos José Alberto Sánchez Nieto
1.- Se adjuntan los dos ficheros .twbx
  a) PracticaExploracionDatosJoseAlbertoSanchezNieto
    Este fichero contiene los 3 primeros objetivos de la práctica
  b) PracticaCriptoPricesJoseAlbertoSanchezNieto
    Contiene el objetivo 4 de la práctica que a continuación se detalla funcionamiento:
    Un dashboard que consta de 4 vistas y analiza el volumen de N criptomonedas.
    - Contiene un parámetro para seleccionar el número de criptomonedas a visualizar, siempre ordenadas por mayor volumen
    - Contiene un parámetro para seleccionar los años a analizar
    - Las vistas:
      1) Top N por mayor volumen:
        N criptomonedas de mayor volumen seleccionadas por parámetro y ordenadas de mayor a menor, también muestra
        su volumen en los años seleccinados
      2) Máximas aperturas y valor:
        Sobre la criptomoneda seleccionada en la vista anterior y teniendo en cuenta el parámetro de los años se muestra
        el máximo valor con que abrió el mercado, el máximo valor que alcanzó la moneda, así cómo el mínimo valor que alcanzó
        la moneda y su mínimo cierre. En el título se muestra la criptomoneda seleccionada
      3) Distribución porcentual del volumen:
        Mostramos cómo se han ditribuido en porcentaje las distintas criptomonedas tomando en cuenta el parámetro de los años,
        pero NO se tiene en cuenta en esta vista el parámetro de criptomoneda seleccionada ya que lo que queremos es contrastar
        siempre entre todas ellas de mayor volumen a menor y por años.
      4) Diferencia entre Máximo y Mínimo que alcanzó la criptomoneda y su relación con el volumen:
        Con un campo calculado hayamos la diferencia entre el máximo valor y mínimo que alcanzó la criptomoneda seleccionada en la vista
        número 1, las ordenamos por la mayor diferencia y la relacionamos con el volumen que tuvo esa criptomoneda, también se tiene
        en cuenta el parámetro de años y el de criptomoneda seleccionada, el nombre también aparece en el editor.
