<h1>Ciclo de vida Bancos</h1>
<p>Proyecto de ciclo de vida de clientes de bancos del 12 de Agosto de 2016</p>
<div class="container">
  <p>Datos:
  <ul>
    <li>datos.rds son los resultados de la encuesta (i.e. la base de datos)</li>
    <li>bateria.rds son los resultasod de la segmentación</li>
  </ul>
  La segmentación se mantiene en un archivo aparte para respetar el raw.data lo más posible. En el script "reportev2.r" están los pasos con los que se junta la segmentación a la base original
  </p>
</div>
<p>Para reproducibilidad:</p>
<ul>
  <li>factoresv2.r tiene los pasos con los que se creo la segmentación</li>
  <li>Reportev2.r tiene todos los pasos para obtener las frecuencias</li>
  <li>reporteSegundaParteV1.r tiene la segunda parte de los pasos para obtener las frecuencias</li>
  <li>abiertas.r Son los pasos con que se consiguió reportar (y limpiar) las preguntas abiertas</li>
</ul>
