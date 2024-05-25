<template>
    <div class="row">
        <div v-for="work of array_works.slice().reverse()" :key="work.image" class="col-12 col-sm-6 col-md-4 col-lg-3 mb-4">
            <div class="card">
                <img :src="work.image" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">{{work.title}}</h5>
                    <p class="card-text">{{work.description}}</p>
                </div>
                <div class="card-footer text-end">
                    <a :href="work.url" v-if="work.url!=''" class="btn btn-danger" target="blank">VIEW</a>
                </div>    
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'Works',
    computed: {
        visibleWorks() {
        return this.array_works.slice(0, this.worksVisible)
        }
    },
    data(){
        return {
            array_works: [
                {
                    image: require('../assets/works-img/Caperucita2.jpg'),
                    title:"Caperucita",
                    description: "Fotomontaje Photoshop",
                    url: require('../assets/works-img/Caperucita2.jpg')
                },
                {
                    image: require('../assets/works-img/IMG-20171120-WA0001.jpg'),
                    title:"Libro mágico",
                    description: "Fotomontaje Photoshop",
                    url: require('../assets/works-img/IMG-20171120-WA0001.jpg')
                },
                {
                    image: require('../assets/works-img/Proyecto.jpg'),
                    title:"Apocalipsis",
                    description: "Matte Painting creado en Photoshop",
                    url: require('../assets/works-img/Proyecto.jpg')
                },
                {
                    image: require('../assets/works-img/IMG_1347.jpg'),
                    title:"Wonderland",
                    description: "HDR editado en Photoshop. 1r premio en el concurso de Fotografía Digital de Sant Sadurní (2009)",
                    url: require('../assets/works-img/IMG_1347.jpg')
                },
                {
                    image: require('../assets/works-img/sprint1.jpg'),
                    title:"Maquetación HTML y CSS",
                    description: "Práctica de IT Academy de maquetación responsive mediante HTML y CSS",
                    url: "https://maquetacionsprint1.netlify.app/"
                },
                {
                    image: require('../assets/works-img/sprint2.jpg'),
                    title:"Maquetación Bootstrap",
                    description: "Práctica de IT Academy de maquetación responsive mediante Bootstrap",
                    url: "https://bootstrapsprint2.netlify.app/"
                },
                {
                    image: require('../assets/works-img/sprint3.jpg'),
                    title:"Maquetación Tienda Online",
                    description: "Práctica de IT Academy de maquetación responsive de una tienda virtual mediante Bootstrap",
                    url: "https://shopsprint3.netlify.app/"
                },
                {
                    image: require('../assets/works-img/sprint5.jpg'),
                    title:"Aplación de chistes",
                    description: "Práctica de IT Academy dónde se recogen datos de varias APIs y se muestran aleatoriamente en pantalla",
                    url: "https://apisprint5.netlify.app/"
                },
                {
                    image: require('../assets/works-img/sprint7.jpg'),
                    title:"Presupuesto Web",
                    description: "Práctica de IT Academy para la gestión de presupuestos Web mediante VUE",
                    url: "https://vuesprint7.netlify.app/"
                },
                {
                    image: require('../assets/works-img/sprint8.jpg'),
                    title:"StarWars",
                    description: "Práctica de IT Academy sobre la película StarWars dónde se leen datos de una API usando VUE",
                    url: "https://apistarwarsvuex.netlify.app/"
                },
                {
                    image: require('../assets/works-img/sprint9.jpg'),
                    title:"Mealvelous",
                    description: "Proyecto final de IT Academy que muestra recetas de una API usando VUE",
                    url: "https://mealvelous.netlify.app/"
                },
                
            ]
        }
    }
}
</script>

<style>
/* .card-body {
    min-height: 15em;
} */

.card-img-top {
    width: 100%;
    height: 10em;
    object-fit: cover;
}

@media (min-width: 580px) {
  .card {
    min-height: 400px;
  }  
}
</style>