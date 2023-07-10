<template>
    <div class="w-side">
        <nav class="navbar bg-body-tertiary d-flex border-right collapsed">
            <form class="container-fluid justify-content-start d-flex flex-column p-0 lh-1">
              <button class="btn font m-1 p-0 button" type="button">
                <b-icon icon="wallet-fill" font-scale="1.5"></b-icon><br>
                Empleos</button>
              <button class="btn font m-1 p-0 button lh-1" type="button">
                <b-icon icon="file-earmark-check" font-scale="1.5"></b-icon><br>
                Postulaciones</button>
              <button class="btn font m-1 p-0 button" type="button">
                <b-icon icon="controller" font-scale="1.5"></b-icon><br>
                Cursos</button>
              <button class="btn font m-1 p-0 button" type="button">
                <b-icon icon="chat-left-text" font-scale="1.5"></b-icon><br>
                Preguntas</button>
              <button class="btn font m-1 p-0 button" type="button">
                <b-icon icon="braces" font-scale="1.5"></b-icon><br>
                Bootcamp</button>
              <button class="btn font m-1 p-0 button" type="button">
                <b-icon icon="gem" font-scale="1.5"></b-icon><br>
                Premios</button>
              <button class="btn font m-1 p-0 button" type="button">
                <b-icon icon="person-badge" font-scale="1.5"></b-icon><br>
                Tu CV</button>
            

        
            </form>
          </nav>

    </div>
</template>

<script>
export default{
    name: 'SideBar'
}

</script>

<style scoped>
.w-side{
    max-width: 8rem;
}
.button{
    width: 4rem;
    height: 4rem;
    font-size: 12px;
    letter-spacing: -1px
}
.button:hover{
    background-color: #B2E3FF;
}

</style>