<script>
    import { fade } from 'svelte/transition';
    import { inview } from 'svelte-inview';  
    let isInView;
  </script>
  
  <div
    class="wrapper"
    use:inview={{ unobserveOnEnter: true, rootMargin: '-20%' }}
    on:change={({ detail }) => {
      isInView = detail.inView;
    }}
  >
    {#if isInView}
      <div in:fade>
          <h2>Claws in your leg</h2>
          <p>Cat ipsum dolor sit amet, velitesse exercitationem quae. Consequat nemo and nostrum so veritatis architecto natus or minima. Quia laborum cillum, yet aliquip so elit deserunt or tempora. Commodo dolores, but irure and accusantium. Reprehenderit. Ullamco totam consequatur or nisi deserunt iure. Ratione enim. Aute iure. Occaecat. Quisquam iure so dolores quia so nostrud. Aut sint and ullam or dolore or anim qui incidunt. Ex occaecat for sit lorem ut yet autem for velitesse. Sequi. Natus. Culpa. Cupidatat est and iste.</p>
          <p>
              Consectetur error for modi for quisquam cupidatat. Fugiat consectetur, or ipsam lorem. Accusantium mollit and veritatis. Fugit architecto vel exercitation. Ratione do iure and quaerat. Esse id or nemo for fugit and vitae. Illum sint or aut or doloremque so aperiam eaque sequi. Tempor qui ratione or inventore modi but aliqua or veniam. Adipisicing. Si aliqua excepteur for occaecat so ipsam. Exercitationem occaecat iure dolores nequeporro for dolores.
          
          </p>
          <p>
              Pariatur quisquam. Sunt mollit. Dicta vitae, vel ullamco or molestiae quae dolore. Unde laborum or occaecat. Dolor. Ipsum sequi consequatur ab incididunt. Exercitationem aliquip. Officia commodo, but deserunt. Molestiae amet. Nemo magnam totam so aperiam yet aliqua.
          </p>
      </div>
    {/if}
  </div>
  
  <style>
    h2 {
        font-family: 'Montserrat Subrayada', sans-serif;
        text-align: left;
    }
    p {
        font-family: 'Libre Baskerville', serif;
    }
  </style>