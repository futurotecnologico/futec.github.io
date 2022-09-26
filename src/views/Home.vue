<template>
  <div class="home">
    <div class="orange-box">
      <v-container>
        <v-row
          justify="center"
          align="center"
        >
          <v-col
            sm="12"
            md="6"
            lg="3"
          >
            <v-img src="../assets/logosimbolo_slogan_blanco@2x.png"></v-img>
          </v-col>
        </v-row>
      </v-container>
    </div>
    <div class="wite-box">
      <v-row
        justify="center"
        align="center"
      >
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <div
            :class="[`text-h4 mb-normal orange-text`]"
            v-text="'Outsourcing IT'"
          ></div>
          <p class="text-justify size">
            Realizamos reclutamiento de profesionales para integrarse como parte de nuestro
            equipo. Trabajamos bajo buenas prácticas y estándares de selección, ayudando en el
            momento de selección de perfiles que cuenten tanto con las habilidades como con las
            capacidades técnicas necesarias para el desarrollo de los proyectos.
          </p>
        </v-col>
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <v-img
            class="filtered"
            src="https://sachg.cl/wp-content/uploads/elementor/thumbs/recluting-p0vxrx6ldn36p6mbahbqin401zac57ucjo19mfhu7k.png"
          ></v-img>
        </v-col>
      </v-row>
    </div>
    <div class="orange-box">
      <v-row
        justify="center"
        align="center"
      >
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <v-img
            class="filtered"
            src="https://sachg.cl/wp-content/uploads/elementor/thumbs/recluting-p0vxrx6ldn36p6mbahbqin401zac57ucjo19mfhu7k.png"
          ></v-img>
        </v-col>
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <div
            :class="[`text-h4 mb-normal`]"
            v-text="'Desarrollo'"
          ></div>
          <p class="text-justify size">
            Contamos con equipos Full Stack para el desarrollo de front-end, back-end, data, apis,
            micro servicios, y open-stack. Ofrecemos una alta flexibilidad y capacidad de adaptación a
            demandas variables, entornos tecnológicos especializados, y un ecosistema de desarrollo
            propio.
          </p>
        </v-col>
      </v-row>
    </div>
    <div class="wite-box">
      <v-row
        justify="center"
        align="center"
      >
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <div
            :class="[`text-h4 mb-normal orange-text`]"
            v-text="'UX/UI'"
          ></div>
          <p class="text-justify size">
            Ofrecemos la mejor Experiencia de Usuario (UX), haciendo que el sitio sea amigable para el usuario y fácil de entender.
          </p>
        </v-col>
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <v-img
            class="filtered"
            src="https://sachg.cl/wp-content/uploads/elementor/thumbs/recluting-p0vxrx6ldn36p6mbahbqin401zac57ucjo19mfhu7k.png"
          ></v-img>
        </v-col>
      </v-row>
    </div>
    <div class="orange-box">
      <v-row
        justify="center"
        align="center"
      >
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <v-img
            class="filtered"
            src="https://sachg.cl/wp-content/uploads/elementor/thumbs/recluting-p0vxrx6ldn36p6mbahbqin401zac57ucjo19mfhu7k.png"
          ></v-img>
        </v-col>
        <v-col
          sm="12"
          md="6"
          lg="6"
        >
          <div
            :class="[`text-h4 mb-normal`]"
            v-text="'Seguimiento de tareas'"
          ></div>
          <p class="text-justify size">
            Adoptamos como metodología de trabajo Agile y Scrum cumpliendo con cada una de las ceremonias y artefactos. Generando valor en cada sprint con un prototipo funcional.
          </p>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>
<style>
.orange-box {
  background-color: #f96138;
  width: 100%;
  padding: 10rem 3rem;
  color: #fff;
}
.wite-box {
  background-color: #fff;
  width: 100%;
  padding: 10rem 3rem;
}
.orange-text {
  color: #f96138;
}
.size {
  font-size: large;
}
.filtered {
  -webkit-filter: grayscale(100%);
  filter: grayscale(100%);
}
</style>