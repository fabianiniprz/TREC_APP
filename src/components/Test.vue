<template>
  <div>
    <nav>
      <label id="lbl_home">TREC APP</label>
      <Label class="normal">Equipo</Label>
      <label class="normal">TREC</label>
      <button id="btn_registrarse">Registrarse</button>
      <button id="btn_inciar_sesion">Iniciar sesion</button>
    </nav>

    <hr />

    <article>

        <section>
            <h1>T R E C</h1>
            <p class="black"> La terapia relacional emotiva conductual o por sus siglas TREC, se centra en mejorar tres ámbitos en nuestras vidas: la racional, el emotivo, y el conductual. Esto se logra enseñando a las personas a examinar sus propios pensamientos, creencias y acciones autp-derrotistas y cambiarlas por alternativas más productivas para su vida. <br>
            la TREC desarrolló a partir de las emociones y conductas son producto de las creencias de una persona o de la interpretación que haga de la realidad. De esta compresión se desprende el ABC de la TREC

            </p>
            <ol type="A">
                <li>Evento activador</li>
                <li>Creencias y lo que nos decimos</li>
                <li>Consecuencias</li>
            </ol>
        </section>


    </article>

    <footer>
      <section id="section1">
        <p  class="white">Accede para saber más de TREC y comenzar a practicar</p>
        <button id="btn_registrarse_down">Registrarse</button>
        <button id="btn_inciar_sesion_down">Iniciar sesion</button>
      </section>

      <section id="section2">
        <label class="white">Sobre nosotros</label>
        <label class="white">Investigación</label>
        <label class="white">Equipo</label>
        <label class="white">Contáctenos</label>
      </section>

      <section id="section3">
        <label class="white">Términos y privacidad</label>
        <label class="white">Terminos</label>
        <label class="white">privacidad</label>
      </section>
    </footer>
  </div>
</template>


<script>
export default {
  data() {
    return {};
  }
};
</script>


<style>
label {
  color: white;
}


#lbl_home {
  float: left;
}


footer {
  background: #000033;
}

.normal {
  font-weight: bold;
  color: black;
}

.white {
  color: white;
}

.black {
  color: black;
}

#lbl_home {
  color: #0099ff;
  font-family: verdana;
  font-weight: bold;
}

#btn_registrarse {
  color: white;
  background: #0099ff;
  border-radius: 20em;
}

#btn_inciar_sesion {
  color: #0099ff;
  background: white;
  border-radius: 20em;
}
#btn_registrarse_down {
  color: white;
  background: #0099ff;
  border-radius: 20em;
}

#btn_inciar_sesion_down {
   color: white;
  background: #0099ff;
  border-radius: 20em;
}

</style>
