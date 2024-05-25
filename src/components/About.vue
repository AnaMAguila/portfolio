<template>
  <div class="row">
    <div class="col-3">
      <img
        src="../assets/img/AnaAguila.jpg"
        alt="Foto perfil"
        class="img-fluid rounded-circle"
      />
    </div>
    <div class="col-9">
      <div class="accordion accordion-flush" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#flush-collapseOne"
              aria-expanded="false"
              aria-controls="flush-collapseOne"
            >
              <strong>Experiencia Laboral</strong>
            </button>
          </h2>
          <div
            id="flush-collapseOne"
            class="accordion-collapse collapse"
            aria-labelledby="flush-headingOne"
            data-bs-parent="#accordionFlushExample"
          >
            <div class="accordion-body">
              <strong>AJUNTAMENT DE MATARÓ (2023-2024)</strong>
              <ul>
                <li>Técnico especialista de soporte web </li>
              </ul>
              <strong>FREELANCE (2013-2021)</strong>
              <ul>
                <li>Diseño, gestión y mantenimiento web</li>
              </ul>
              <strong>TELIC GROUP (2012-2013)</strong>
              <ul>
                <li>Diseño web</li>
                <li>Gestión de Bases de datos</li>
              </ul>
              <strong>GESTION INTEGRAL SL (2011-2012)</strong>
              <ul>
                <li>Diseño web y mantenimiento</li>
                <li>Diseño gráfico</li>
              </ul>
              <strong>ENTRAMOS GROUP (2009-2011)</strong>
              <ul>
                <li>Diseño web y mantenimiento</li>
                <li>Diseño gráfico</li>
              </ul>
              <strong>ALTEN TIC (2008)</strong>
              <ul>
                <li>Creación de consultas PL/MySQL</li>
              </ul>
              <strong>VIA 21 (2007)</strong>
              <ul>
                <li>Full stack developer</li>
                <li>Diseño gráfico</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseTwo"
              aria-expanded="false"
              aria-controls="panelsStayOpen-collapseTwo"
            >
              <strong>Formación</strong>
            </button>
          </h2>
          <div
            id="panelsStayOpen-collapseTwo"
            class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingTwo"
          >
            <div class="accordion-body">
              <strong>Bootcamp IT ACADEMY (2023)</strong>
              <ul>
                <li>Especialización Front-End Vue</li>
              </ul>
              <strong>IES Carles Vallbona (2006)</strong>
              <ul>
                <li>
                  Ciclo Formativo grado superior Desarrollo de Aplicaciones
                  Informáticas
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingThree">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseThree"
              aria-expanded="false"
              aria-controls="panelsStayOpen-collapseThree"
            >
              <strong>Skills Técnicos</strong>
            </button>
          </h2>
          <div
            id="panelsStayOpen-collapseThree"
            class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingThree"
          >
            <div class="accordion-body">
              <ul class="three-cols">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Vue</li>
                <li>Bootstrap</li>
                <li>GitHub</li>
                <li>TypeScript</li>
                <li>MySQL</li>
                <li>Photoshop</li>
                <li>Sass</li>
                <li>WordPress</li>
                <li>Joomla</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingFour">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseFour"
              aria-expanded="false"
              aria-controls="panelsStayOpen-collapseFour"
            >
              <strong>Soft Skills</strong>
            </button>
          </h2>
          <div
            id="panelsStayOpen-collapseFour"
            class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingFour"
          >
            <div class="accordion-body">
              <ul>
                <li>Trabajo en equipo</li>
                <li>Aprendizaje constante e independiente</li>
                <li>Creatividad</li>
                <li>Compromiso</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingFive">
            <button
              class="accordion-button collapsed"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseFive"
              aria-expanded="false"
              aria-controls="panelsStayOpen-collapseFive"
            >
              <strong>Idiomas</strong>
            </button>
          </h2>
          <div
            id="panelsStayOpen-collapseFive"
            class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingFive"
          >
            <div class="accordion-body">
              <ul>
                <li>Español</li>
                <li>Catalán</li>
                <li>Inglés</li>
              </ul>
            </div>
          </div>
        </div>


      </div>
    </div>
  </div>
</template>

<style>

.three-cols {
  columns: 1;
}

@media (min-width: 500px) {
  .three-cols {
    columns: 3;
  }  
}
</style>
