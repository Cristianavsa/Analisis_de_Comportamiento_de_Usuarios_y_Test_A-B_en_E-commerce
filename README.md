<!-- ====== TÍTULO DEL PROYECTO ====== -->
<h1 style="font-family: Arial, sans-serif; color:#1A73E8; margin-bottom: 5px;">
  Análisis del Embudo de Conversión y Test A/B
</h1>
<p style="font-family: Arial, sans-serif; color:#555; margin-top: 0;">
  Tienda de Productos Alimenticios ·
</p>

<hr style="border: 0; border-top: 2px solid #1A73E8; margin: 20px 0;">


<!-- ====== CONTEXTO ====== -->
<h2 style="font-family: Arial, sans-serif; color:#1A73E8;">Contexto</h2>
<p style="font-family: Arial, sans-serif; color:#333;">
  Una tienda de productos alimenticios busca optimizar la experiencia de sus usuarios dentro de la aplicación 
  y mejorar su tasa de conversión. Para ello se analizó el comportamiento de los usuarios a lo largo del embudo 
  de ventas y se evaluó, mediante una prueba A/B, si un nuevo diseño de la página web podría influir positivamente 
  en su avance hacia la compra.
</p>


<!-- ====== OBJETIVO ====== -->
<h2 style="font-family: Arial, sans-serif; color:#1A73E8;">Objetivo</h2>
<ul style="font-family: Arial, sans-serif; color:#333;">
  <li>Analizar cómo los usuarios progresan por cada etapa del embudo de ventas.</li>
  <li>Identificar los puntos críticos donde se produce la mayor pérdida de usuarios.</li>
  <li>Ejecutar una prueba A/B para determinar si un nuevo diseño de interfaz mejora la experiencia del usuario y la tasa de conversión.</li>
</ul>


<!-- ====== ANÁLISIS ====== -->
<h2 style="font-family: Arial, sans-serif; color:#1A73E8;">Análisis</h2>
<p style="font-family: Arial, sans-serif; color:#333;">
  Para el estudio se utilizaron herramientas de análisis de datos y estadística, incluyendo 
  <strong>pandas, NumPy, Seaborn, Matplotlib, SciPy, datetime, Stats y statsmodels</strong>.
</p>
<ul style="font-family: Arial, sans-serif; color:#333;">
  <li>Exploración del embudo de conversión y cálculo de porcentajes de avance entre pantallas.</li>
  <li>Comparación estadística entre los grupos experimentales (246, 247 y 248).</li>
  <li>Pruebas de hipótesis para evaluar diferencias significativas en las medias de conversión.</li>
  <li>Evaluación del nivel de significancia y del riesgo de error tipo II.</li>
</ul>


<!-- ====== HALLAZGOS ====== -->
<h2 style="font-family: Arial, sans-serif; color:#1A73E8;">Hallazgos</h2>
<ul style="font-family: Arial, sans-serif; color:#333;">
  <li>
    La mayor pérdida de usuarios ocurre entre <strong>MainScreenAppear</strong> y 
    <strong>OffersScreenAppear</strong>, con una caída del <strong>40%</strong> 
    (de 7,419 a 4,482 usuarios).
  </li>
  <li>Solo el <strong>46.22%</strong> de los usuarios completa el embudo completo.</li>
  <li>
    Las pruebas estadísticas entre los grupos <strong>246/248</strong> y <strong>247/248</strong> 
    no permitieron rechazar la hipótesis nula.
  </li>
  <li>No se encontraron diferencias significativas atribuibles al nuevo diseño.</li>
  <li>El tamaño de muestra actual es insuficiente para detectar efectos pequeños o moderados con alta confianza.</li>
</ul>


<!-- ====== CONCLUSIONES ====== -->
<h2 style="font-family: Arial, sans-serif; color:#1A73E8;">Conclusiones</h2>
<ul style="font-family: Arial, sans-serif; color:#333;">
  <li>
    El embudo presenta un punto crítico claro en la transición hacia la pantalla de ofertas, 
    lo que sugiere una oportunidad de optimización en esa etapa.
  </li>
  <li>
    Mantener un nivel de significancia de <strong>0.05</strong> o incluso <strong>0.01</strong> 
    ayuda a reducir el riesgo de error tipo II, pero con el tamaño de muestra actual no es posible 
    obtener conclusiones sólidas.
  </li>
  <li>
    Para mejorar la potencia estadística sería necesario extender el experimento y recopilar más datos, 
    aunque esto no garantiza un cambio significativo.
  </li>
  <li>
    Con la información disponible, el nuevo diseño aplicado al grupo <strong>248</strong> muestra 
    baja probabilidad de generar un impacto significativo en la tasa de conversión.
  </li>
</ul>
