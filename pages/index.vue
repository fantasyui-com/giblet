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


.container, .row {
  padding-top: 1rem;
}

</style>

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


           <em slot="footer"><i class="text-muted">Describe your song properties</i></em>
        </b-card>

          <b-card title="Song Preview" header-tag="header" footer-tag="footer">
            <h6 slot="header" class="mb-0">Song Preview</h6>
            <b-card-text>Header and footers using slots.</b-card-text>


            <b-button href="#" variant="primary">Preview Song</b-button>
            <em slot="footer"><i class="text-muted">Footer Slotdd</i></em>
          </b-card>

        </b-card-group>

      </div>

    </b-col>
  </b-row>









  <b-row>
    <b-col>


      <div>

        <b-card-group deck>


        <b-card title="Samples" header-tag="header" footer-tag="footer">
          <h6 slot="header" class="mb-0">Song Properties</h6>
          <b-card-text>Header and footers using slots.</b-card-text>


          <song-properties />


          <b-button href="#" variant="primary">Go somewhere</b-button>
          <em slot="footer"><i class="text-muted">Describe your song properties</i></em>
        </b-card>


        </b-card-group>

      </div>

    </b-col>
  </b-row>








    <b-row>
      <b-col>


        <div>

          <b-card-group deck>


            <b-card no-body header="Card with flush list group">
              <b-list-group flush>
                <b-list-group-item href="#">Intro</b-list-group-item>
                <b-list-group-item href="#">Solo</b-list-group-item>
                <b-list-group-item href="#">Choir</b-list-group-item>
                <b-list-group-item href="#">Drums</b-list-group-item>
                <b-list-group-item href="#">Ending</b-list-group-item>
                <b-list-group-item href="#">Outro</b-list-group-item>
              </b-list-group>

              <b-card-body>
                Quis magna Lorem anim amet ipsum do mollit sit cillum voluptate ex nulla tempor.
              </b-card-body>
            </b-card>


          <b-card title="Structure" header-tag="header" footer-tag="footer">
            <h6 slot="header" class="mb-0">Song Properties</h6>
            <b-card-text>Header and footers using slots.</b-card-text>


            <song-properties />


            <b-button href="#" variant="primary">Go somewhere</b-button>
            <em slot="footer"><i class="text-muted">Describe your song properties</i></em>
          </b-card>


          </b-card-group>

        </div>

      </b-col>
    </b-row>















</b-container>

</template>
