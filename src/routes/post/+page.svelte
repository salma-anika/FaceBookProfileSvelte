<script>
    import DownArrow from '../../icons/downArrow.svelte';
import Phone from '../../icons/phone.svelte';
import Friend from '../../icons/friend.svelte';
import More from '../../icons/more.svelte';
</script>
<div class="border border-fGrey mt-6 border-opacity-10 w-full max-[850px]:w-full" />
<div class="flex justify-between px-8">
  <div class="flex items-center">
    <div class="px-4 py-5 text-fBlue border-b-4 border-fBlue">
      Posts
    </div>
    <div class="px-4 py-5 text-fGrey">
      About 
    </div>
    <div class="px-4 py-5 text-fGrey">
      Friends 
    </div>
    <div class="px-4 py-5 text-fGrey">Photos</div>
    <div class="px-4 py-5 text-fGrey">Videos</div>
    <div class="px-4 py-5 text-fGrey">Check-Ins</div>
    <div class="px-4 flex items-center py-5 text-fGrey">
      More
      <span class="ml-1">
        <DownArrow />
      </span>
    </div>
  
    </div>
    <div class="flex items-center space-x-2 max-[450px]:hidden">
        <button class="w-12 h-9 bg-fButton rounded flex items-center justify-center focus:outline-none">
          <Phone />
        </button>
        <button class="w-12 h-9 bg-fButton rounded flex items-center justify-center focus:outline-none">
          <Friend />
        </button>
        <button class="w-12 h-9 bg-fButton rounded flex items-center justify-center focus:outline-none">
          <More />
        </button>
      </div>
    </div>
