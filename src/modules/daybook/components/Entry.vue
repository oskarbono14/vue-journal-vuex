<template>

    <div
        class="entry-container  mb-3 pointer p-2"
        @click="$router.push({name:'entry', params:{id:10}})"
    >
        <div class="entry-title d-flex">
            <span class="text-sucess fs-5 fw-bold">17</span>
            <span class="mx-1 fs-5">Junio</span>
            <span class="mx-1 fw-light">2023</span>


        </div>

        <div class="entry-description">
            Pariatur velit nostrud excepteur ullamco. Cupidatat anim in pariatur qui qui tempor mollit. Nisi culpa sunt irure incididunt ad aliqua est. Adipisicing labore excepteur sint nulla eu Lorem. Velit mollit pariatur sit ipsum cillum ex quis Lorem.

        </div>
    </div>
   
</template>

<script>
export default {

}

</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hoover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description{
        font-size: 12px;
}
}


</style>