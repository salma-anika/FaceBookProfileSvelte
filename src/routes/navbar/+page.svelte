<script>
    import FacebookLogo from '../../icons/facebookLogo.svelte';
import SearchIcon from '../../icons/searchIcon.svelte';
import Plus from '../../icons/plus.svelte';
import Messenger from '../../icons/messenger.svelte';
import DownArrow from '../../icons/downArrow.svelte';
import Bell from '../../icons/bell.svelte';
import Home from '../../icons/home.svelte';
import Watch from '../../icons/watch.svelte';
import Groups from '../../icons/groups.svelte';
import Feed from '../../icons/feed.svelte';
</script>
<div>
    <div class="h-14 flex justify-between w-screen shadow-fb px-4 py-2">
      <div class="flex ">
        <FacebookLogo />
        <div class="h-10 w-64 ml-2 flex items-center rounded-full bg-fFill p-3">
          <SearchIcon />
          <input
            class="text-fGrey ml-2 bg-fFill focus:outline-none"
            placeholder="Search Facebook"
          />
        </div>
      </div>
      <div class="flex space-x-24 items-center">
        <button class="focus:outline-none">
          <Home />
        </button>
        <button class="focus:outline-none">
          <Watch />
        </button>
        <button class="focus:outline-none">
          <Groups />
        </button>
        <button class="focus:outline-none">
          <Feed />
        </button>
      </div>s
    </div>
</div>