<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">"Catálogo interactivo de códigos HTTP"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="35" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"> </h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNjdzem16djBobHlpMDFkdnZrMXIwaXRlNWZ2bDh0andmdTRpcTFxMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/eCFAF0F7fQfqHeliiE/giphy.gif"/>
</p>

<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExeGNpcXkya3F1NGF3NWNxdDI2bzg0c3NzMmhuZWFlMHNsOGI3YmoycSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/P4sS7sU2ufXz183cfy/giphy.gif" width = 75px>  </picture> Catálogo interactivo de códigos HTTP

<br>

 **Catálogo web interactivo de códigos HTTP para bug bounty/pentesting. Incluye 1xx–5xx oficiales + “extra” no oficiales (Cloudflare, Nginx, etc.), búsqueda instantánea por número/texto, favoritos  y notas  con modal, categorías coloreadas, header/buscador fijo y encabezados de tabla sticky para navegar sin perder contexto. Todo persiste en localStorage y permite importar/exportar preferencias en JSON. Licencia MIT,<a href="https://youtu.be/EzWE7fqrCVo" target="_blank" rel="noopener">Youtube</a>.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/demo_codigos_http.gif"/>
</p>

<br>

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExczVrcnhwNDAzajJmMWhrN3p3OGg2b3B0emRoOGFlMnNlNm04Y2I3dCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/nndsQSOMEUToRELiAE/giphy.gif" width = 80px>  </picture> Resumen rápido
<br><br>

Catálogo web interactivo de códigos HTTP para bug bounty/pentesting. Incluye todos los oficiales 1xx–5xx (con 425 Too Early) + ~20 “extra” no oficiales (Cloudflare).<br>


• Formato: interfaz web local (HTML/JS), toda la data se guarda en localStorage por defecto (offline, en tu máquina).<br><br>

• Pasos a seguir:<br>
1. Descarga el repositorio.<br>
2. Abra el archivo Estados_servidor.html en con su navegador preferido.<br>
3. Introduzca el código de estado (ej.: 429) o presione Ctrl + F y busque "429".<br>

<br>

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExOXB5c2oxYnBwdGJpc3hhejl1c3Jzc3cyZTlzOWQ4a2N4dGx4eWdjbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/vYBtBiaNcZF3F3Iaip/giphy.gif" width = 80px>  </picture> Características
<br><br>


• Iniciar / Parar con botones y atajos (S = iniciar, P = parar).

• Buscador por categoría y texto: filtra códigos por categoría (1xx, 2xx, 3xx, 4xx, 5xx y extra).

• Persistencia local (sin backend) vía localStorage.

• Ctrl + F (búsqueda rápida): si presionás Ctrl+F e ingresás un código (ej.: 302), el navegador te lleva a la sección/parte donde se describe ese código.

• Buscador interno: el campo de búsqueda de la app permite encontrar por número, nombre o descripción y navegar directamente al resultado.

• Notas por código: cada código HTTP tiene su panel de notas editable (guardar, editar, eliminar); se muestra la última modificación.

• Ocultar/mostrar categorías: podés ocultar categorías completas; recomendado no ocultarlas porque Ctrl+F del navegador no buscará dentro de secciones colapsadas — sí podés usar el buscador interno.

• Favoritos: agrega códigos a “Mis favoritos” para filtrar ruido visual y quedarte solo con lo que te interesa.

• Importar / Exportar: exportá e importá preferencias, favoritos y notas en un JSON (ej.: importa.json).

• Cobertura: incluye todos los códigos HTTP oficiales (1xx–5xx, incluyendo 425 Too Early) y ~20 códigos extra/no oficiales (Cloudflare, Nginx, cPanel, frameworks, etc.) que se usan en la vida real.

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGdlNnJtczFndjRkZXczMXR0MmRvMHJteXJmMG5hOWN3djdzcmhqYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/DY4GxWN6Ml3oVexySy/giphy.gif" width = 80px>  </picture> Uso
<br><br>


• Búsqueda de códigos HTTP: primero ingrese el código HTTP que le devolvió el servidor (ej.: 429) en el buscador interno, o use Ctrl + F para que el navegador lo lleve a la sección donde se describe ese código.

• Uso simple y minimalista: diseñado para que cualquiera lo pueda usar sin complicaciones.
 
 <br>

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> "Buscar rápido: escribe el código HTTP (ej.: 429) en el buscador para saltar instantáneamente a su descripción completa — incluye todos los códigos (oficiales y no oficiales, incluso los menos conocidos) en un único lugar."
<br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
