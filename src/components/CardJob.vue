
<template>
    <!-- aca comence -->

    <div   
        class="card job-card mb-3 border m-2 icon-link icon-link-hover cardh">
        <div  class="card-body p-2 p-md-3 ">
            <div class="row align-items-center">
                <div class="justify-content-center align-items-center col-md-1 col-3"><img
                        :src= url
                        alt="Logo empresa" width="70" height="70" class="rounded">
                </div>
                <div class="col-md-11 col-9 text-truncate col">
                    <div class="row align-items-center">
                        <div class="mb-2 col">
                            <a href="/es/empleos/10406"
                                class="text-dark stretched-link d-inline d-md-inline-flex text-truncate" itemprop="url" target="_self">
                                <h2 itemprop="title" class="job-title bold pl-md-2 pr-md-2 mb-0 pb-0">
                                    {{ title }}
                                    
                                </h2>
                                <section itemprop="skills"
                                    class="btn pl-md-2 d-inline d-md-inline-flex align-items-center text-truncate gap-1">
                                    <div role="button"
                                        class=" btn rounded-pill text-truncate border border-dark text-decoration-none"
                                        style="font-size: 0.8em; margin-bottom: 0px !important;"><span></span>
                                        negotiation skills
                                    </div>
                                    <div role="button"
                                        class=" btn rounded-pill text-truncate border border-dark text-decoration-none"
                                        style="font-size: 0.8em; margin-bottom: 0px !important;"><span></span>
                                        B2B sales
                                    </div>
                                    <div role="button"
                                        class=" btn rounded-pill text-truncate border border-dark text-decoration-none"
                                        style="font-size: 0.8em; margin-bottom: 0px !important;"><span></span>
                                        cold prospecting
                                    </div>

                                </section> <!----> <!---->
                            </a>
                        </div>
                    </div>
                    <div class="row pl-md-2 mt-1 flex-column flex-md-row" style="font-size: 0.9em;">
                            <div itemprop="hiringOrganization" itemscope="itemscope" itemtype="http://schema.org/Organization"
                                class="text-truncate text-capitalize col">
                                    <span itemprop="name">
                                    <b-icon icon="Building" font-scale="1"></b-icon>
                                    {{ company}}
                                    </span>
                            </div>
                        <div itemprop="jobLocation" itemscope="itemscope" itemtype="http://schema.org/Place"
                            class="text-truncate col"><span itemprop="name address">
                                <b-icon icon="geo-alt" font-scale="1"></b-icon>
                                {{location}}
                            </span>
                        </div>
                        <div itemprop="estimatedSalary baseSalary" class="text-truncate col">
                             <span>
                                <b-icon icon="cash" font-scale="1"></b-icon>
                                $ 3M - 4M COP + Stock options $ 20M - 50M COP
                            </span>
                        </div>
                        <div class="d-none d-md-inline-block col">
                            <b-icon icon="people" font-scale="1"></b-icon>
                            1
                            Vacante
                        </div>
                        <div class="text-truncate col"><b-icon icon="calendar" font-scale="1"></b-icon> <!----> <span itemprop="datePosted validThrough" class="sr-only">
                                2023-07-07T16:31:02.451Z
                            </span> <time datetime="2023-07-07T16:31:52.299Z">about 11 hours ago</time></div>

                        <!-- ICONS -->
                        <div class="text-truncate col">
                            <div role="button" title="Cursos de inglés"
                                class="btn skill-tag custom-skill-tag text-truncate border border-dark text-dark m-1">
                                <b-icon icon="globe" font-scale="1"></b-icon>

                            </div>
                            <div role="button" title="Trabajo remoto"
                                class="btn skill-tag custom-skill-tag text-truncate border border-dark text-dark m-1">
                                <b-icon icon="geo-alt" font-scale="1"></b-icon>
                            </div>
                            <div role="button" title="Horario flexible"
                                class="btn skill-tag custom-skill-tag text-truncate border border-dark text-dark m-1">
                                <b-icon icon="watch" font-scale="1"></b-icon>
                            </div><!---->

                            <div role="button" title="Celebración de días especiales"
                                class="btn skill-tag custom-skill-tag text-truncate border border-dark text-dark m-1">
                                <b-icon icon="emoji-smile" font-scale="1"></b-icon>
                            </div>

                            <div role="button" title="Juegos online"
                                class="btn skill-tag custom-skill-tag text-truncate border border-dark text-dark m-1">
                                <b-icon icon="controller" font-scale="1"></b-icon>
                            </div>

                            <!-- icon people -->
                            <div class="btn skill-tag custom-skill-tag text-truncate border border-dark text-dark m-1">
                                <b-icon icon="globe" font-scale="1"></b-icon>
                            </div>
                        </div>
                    </div>
                </div>
                <div>

                </div>
            </div>

        </div>
        <!-- fin -->
    </div>
</template>

<script>
export default {
    name: 'CardJob',
    props: {
        title : String,
        url: String,
        company: String,
        location: String,
    }

}

</script>
<style scoped>
.card:hover{
    box-shadow: 0 10px 20px rgba(0,0,0,.12), 0 4px 8px rgba(0,0,0,.06);
}


</style>

