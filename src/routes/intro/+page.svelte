<script>
    import Post from '../../routes/post/+page.svelte'
</script>
<div class="shadow">
    <div class="relative h-96 rounded-b flex justify-center max-[450px]:w-[900px] max-[850px]:w-[1200px] max-[450px]:m-auto ">
        <img
        src="src/OIP.jpg"
        class="object-cover w-full h-full rounded-b "
        alt="cover"
      />
      <div class="absolute -bottom-6">
        <img
          src="src/pro.jpg"
          class="object-cover border-4 border-white w-40 h-40 rounded-full"
          alt="cover"
        />
      </div>
    
    </div>
    <div class="text-center mt-6 text-3xl font-bold  max-[850px]:w-full text-fBlack max-[450px]:hidden max-[750px]:justify-center max-[750px]:ml-36  ">
        Salma Anika
      </div>
<Post/>
      </div>

      