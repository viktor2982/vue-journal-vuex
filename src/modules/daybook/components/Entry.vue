<template>
  <div
    class="entry-container mb-3 p-2"
    role="button"
    @click="$router.push({ name: 'entry', params: { id: 10 } })">

        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">20</span>
            <span class="mx-1 fs-5">Febrero</span>
            <span class="mx-2 fw-light">2022, Domingo</span>
        </div>
        <div class="entry-description">
            Elit id amet eiusmod sunt cillum culpa. Deserunt minim sint quis non ipsum minim ad. Esse fugiat minim laboris irure mollit tempor labore elit incididunt minim ut amet dolore. Velit nulla exercitation labore excepteur. In commodo veniam adipisicing non nisi nisi non reprehenderit. Ad nulla eiusmod sunt dolor et excepteur consequat. Aliquip enim consectetur eu aliquip nisi eiusmod ullamco officia do reprehenderit adipisicing fugiat anim reprehenderit.
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

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}

</style>