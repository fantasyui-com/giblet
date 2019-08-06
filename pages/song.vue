<template>

<b-container class="bv-example-row">
  <b-row>
    <b-col>


      <div>

        <b-card-group deck>


        <b-card title="Song" header-tag="header" footer-tag="footer">
          <h6 slot="header" class="mb-0">Song Properties</h6>
          <b-card-text>Header and footers using slots.</b-card-text>


<song-properties />



          <b-button href="#" variant="primary">Go somewhere</b-button>
          <em slot="footer"><i class="text-muted">Describe your song properties</i></em>
        </b-card>

          <b-card title="Title" header-tag="header" footer-tag="footer">
            <h6 slot="header" class="mb-0">Header Slot</h6>
            <b-card-text>Header and footers using slots.</b-card-text>


            <b-button href="#" variant="primary">Preview Song</b-button>
            <em slot="footer"><i class="text-muted">Footer Slotdd</i></em>
          </b-card>

        </b-card-group>

      </div>

    </b-col>
  </b-row>
</b-container>

</template>

<script>
import Logo from '~/components/Logo.vue';
import SongProperties from '~/components/SongProperties.vue';

export default {
  components: {
    Logo,
    SongProperties
  }
}
</script>

<style>


.container {
  padding-top: 1rem;
}

</style>
