<script >
export default{
    data(){
        return{
            alumnos:[
                {id:1, nombre:"Oliverio", gustos:["Cocinar", "Programar"]},
                {id:2, nombre:"Luis", gustos:["Cocinar", "Programar"]},
                {id:3, nombre:"Juan", gustos:["Cocinar", "Programar"]},
            ]
        }
    }
}


</script>

<template>
    <div class="container">
        <h1 class = "titulo">Lista de alumnos</h1>
        <ul>
        <li v-for = "alumno in alumnos" :key="alumno.id">
            <strong>{{ alumno.id }} </strong>
            <strong>{{ alumno.nombre }} </strong>
            <strong>{{ alumno.gustos }}</strong>
        </li>
    </ul>
    </div>
    
</template>

<style scoped>
.container{
    align-items: center;
    height: 100vh;
}
.titulo{
    background-color: rgb(194, 169, 57);
    border-radius: 20px;
    margin: 5px;
    padding: 15px;
    color: white;
}
ul{
    list-style: none;
}
li{
    background-color: rgb(57, 194, 132);
    border-radius: 20px;
    margin: 5px;
    padding: 15px;
    color: white;
}
</style>
