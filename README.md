# UyA: Práctica 1

## Analizar

[Gobierno de Canarias](http://www.gobiernodecanarias.org/istac/api/) 
<br>
[XML correspondiente](https://www3.gobiernodecanarias.org/istac/api/operations/v1.0/operations?limit=5)

## Cuestiones
### Peticiones desencadenadas por la consulta con su tipo de  de petición y el código de status devuelto.
  <table>
  <thead>
    <tr>
      <th>Petición</th>
      <th>Tipo</th>
      <th>Código de status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>api/</td>
      <td>GET</td>
      <td>304 (Not Modified)</td>
    </tr>
        <tr>
      <td>istac.css</td>
      <td>GET</td>
      <td>302 (Found)</td>
    </tr>
            <tr>
      <td>logo_istac.jpg</td>
      <td>GET</td>
      <td>302 (Found)</td>
    </tr>
                        <tr>
      <td>logo_edatos.jpg</td>
      <td>GET</td>
      <td>302 (Found)</td>
    </tr>
                <tr>
      <td>istac.css</td>
      <td>GET</td>
      <td>200 (OK)</td>
    </tr>
                        <tr>
      <td>font_awesome.min.css</td>
      <td>GET</td>
      <td>200 (OK)</td>
    </tr>
                           <tr>
      <td>logo_istac.jpg</td>
      <td>GET</td>
      <td>200 (OK)</td>
    </tr>
                               <tr>
      <td>logo_edatos.jpg</td>
      <td>GET</td>
      <td>200 (OK)</td>
    </tr>
  </tbody>
  </table>
   

### ¿Qué DNS tiene el servidor?
    SETI.GOBIERNODECANARIAS.ORG - 93.188.137.34
### ¿Qué IP tiene tiene el servidor?
    93.188.136.129
### ¿La página tiene alguna cookie?, ¿Cuáles?.
    _cfduid --> .cloudfare.com
### ¿Qué idioma acepta?.
    es-ES,es;q=0.9 --> español
### Alguna línea de código JavaScript
    for (let key in PATCHES)
    {
      const {isMatching, apply, description, applyOnDOMReady} = PATCHES[key];
      if (isMatching()) {
        const run = () => {
          apply();
          log(`${key}, ${description}`);
        };

        if (applyOnDOMReady) {
          addEventListener(document, 'DOMContentLoaded', run, false);
        } else {
          run();
        }
      }
    }

### Alguna línea de código CSS que se aplique
    @import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css";
    .top {
      /* width: 100%; */
      border-bottom: 2px solid rgb(214, 214, 214);
      padding: 0px 4px 8px 0px !important;
      margin-left: auto;
      margin-right: auto;
    }

### Alguna línea de código HTML que se aplique.
	<head>
		<title>ISTAC | API | eDatos</title>
		<link href="/istac/resources/css/istac.css" media='screen' rel='stylesheet' type='text/css' />
	</head>




<hr>
<div class="footer">
    &copy; 2019 Diego Vázquez Campos<br>
      &copy; 2019 Brian Santana Mon<br>
      &copy; 2019 Gerardo de Delás Cuesta
</div>
