---
layout: default-cobertura
title: Jetty | ¿Cuándo y dónde funciona Jetty?
description: Consulta nuestra cobertura y nuestros horarios de operaciones en la Zona Metropolitana del Valle de México.
id: cobertura
---

<div class="container cobertura">
  <div class="row">
    <div class="col-md-8 col-md-offset-2 text-center">

      <h2>Para reservar tu viaje, descarga la app:</h2>
        <a href="https://itunes.apple.com/us/app/jetty-soluciona-tu-transporte/id1276413293?l=es&ls=1&mt=8" target="_blank" class="download-app hvr-shadow" target="_blank" class="download-app hvr-shadow">
          <img src="img/jetty-iOS.png" alt="Jetty Descargar iOS">
        </a>

        <a href="https://play.google.com/store/apps/details?id=mx.jetty.jetty" target="_blank" class="download-app hvr-shadow">
          <img src="img/jetty-android.png" alt="Jetty Descargar Android">
        </a>
    </div>

    <embed src="mapa/mapa.html" class="mapaCobertura">

    <div class="clearfix"></div>

    <div class="col-md-12 text-center dondevas">
      <h3>¿Te interesa tener un Jetty cerca de ti?</h3>
      <p>Ingresa aquí tu origen y destino deseado y lo tomaremos en cuenta:</p>
      <a href="solicitud" class="btn btn-default btn-lg btn-green btn-header">¿A dónde te llevamos?</a>
    </div>

  </div>
</div>

<!-- /// MODAL 1 /// -->
<div class="modal fade" id="ruta1" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Cuautitlán/Perinorte <img src="img/arrowGreen-cobertura-2.png" class="arrow-cobertura"> Polanco/Reforma <img src="img/icon-expressGreen.svg" width="50" ></h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_2" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 2 /// -->
<div class="modal fade" id="ruta2" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Cuautitlán/Perinorte <img src="img/arrowGreen-cobertura-2.png" class="arrow-cobertura"> Santa Fe <img src="img/icon-expressGreen.svg" width="50" ></h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_7" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 3 /// -->
<div class="modal fade" id="ruta3" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Zona Norte <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Polanco</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 4 /// -->
<div class="modal fade" id="ruta4" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Reforma <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_3" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 5 /// -->
<div class="modal fade" id="ruta5" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Zona Norte <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_4" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 6 /// -->
<div class="modal fade" id="ruta6" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Aragón <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_5" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 7 /// -->
<div class="modal fade" id="ruta7" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Parque de los venados/Del Valle <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_6" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 8 /// -->
<div class="modal fade" id="ruta8" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Polanco <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_8" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 9 /// -->
<div class="modal fade" id="ruta9" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">M. Chabacano/Condesa <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_9" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 10 /// -->
<div class="modal fade" id="ruta10" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Las Alamedas/Atizapán <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_10" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 11 /// -->
<div class="modal fade" id="ruta11" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Azcapotzalco/Polanco <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_11" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 12 /// -->
<div class="modal fade" id="ruta12" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Coacalco/Satélite <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Polanco/Reforma</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_12" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 13 /// -->
<div class="modal fade" id="ruta13" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Las Águilas <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_13" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 1 SVBus /// -->
<div class="modal fade" id="rutaSVBus1" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Acoxpa <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus1" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 2 SVBus /// -->
<div class="modal fade" id="rutaSVBus2" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Acoxpa <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Auditorio</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus2" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 3 SVBus /// -->
<div class="modal fade" id="rutaSVBus3" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Toreo <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus3" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 4 SVBus /// -->
<div class="modal fade" id="rutaSVBus4" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Costco Coapa <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus4" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 5 SVBus /// -->
<div class="modal fade" id="rutaSVBus5" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Costco Coapa <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Centro Comercial Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus5" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 6 SVBus /// -->
<div class="modal fade" id="rutaSVBus6" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Costco Coapa <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Auditorio</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus6" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 7 SVBus /// -->
<div class="modal fade" id="rutaSVBus7" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Auditorio <img src="img/arrowPurple-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_SVBus7" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>

<!-- /// MODAL 1 RutasUnidas /// -->
<div class="modal fade" id="rutaUnidas1" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Viveros/Miguel Ángel de Quevedo /San Jerónimo <img src="img/arrowGreen-cobertura-1.png" class="arrow-cobertura"> Santa Fe</h4>
      </div>
      <div class="modal-body">
        <div id="map_canvas_Rutas1" class="map_canvas"></div>
      </div>
      <div class="modal-footer">
        <p><b>Ascenso <img src="img/icon-ascenso.png" width="22" style="margin-right: 40px;"> Descenso <img src="img/icon-descenso.png" width="22"></b></p>
      </div>
    </div>
  </div>
</div>