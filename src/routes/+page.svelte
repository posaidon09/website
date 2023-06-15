<script>
  let show = false
  async function Show() {
    show = !show
  }
</script>
<body class="min-h-screen bg-[#111118]">
  <div class="z-0 md:h-20 fixed bg-gray-900 w-full p-1">
    <div class=" ml-5 rounded items-center flex"><button on:click={Show} class="w-6 p-1 h-6 bg-gray-900"><img alt="menu" src="https://cdn.discordapp.com/attachments/1054855781268332636/1113213212435955772/ymrpd0S.png"></div>
    {#if show}
    <div class="ml-5 mr-20 flex flex-col gap-3 bg-gray-900 bg-cover h-80 w-40 rounded-3xl mt-3">
      <div><a href="./commands"><button class="bg-zinc-700 w-28 p-3 rounded-2xl  ml-3 text-gray-300">Commands</button></a></div>
      <div><a href="./report"><button class="bg-zinc-700 w-28 p-3 rounded-2xl mt-5 ml-3 text-gray-300">Report bug</button></a></div>
      <div><a href="./report"><button class="bg-zinc-700 w-28 p-3 rounded-2xl mt-5 ml-3 text-gray-300">Invite</button></a></div>
      <div><a href="./report"><button class="bg-zinc-700 w-28 p-3 rounded-2xl mt-5 ml-3 text-gray-300">Support</button></a></div>
    </div>
    {/if}
  </div>
  
  <div class="grid grid-flow-col grid-rows-1  mx-10 justify-center items-center z-10 md:mt-20">
    <div class="mt-8">
  <h1 class="text-gray-300 font-bold text-2xl md:text-6xl mt-7 text-center">BoredomBot</h1>
  </div>
  <div>
    <img alt="BoredomBot" src="https://cdn.discordapp.com/attachments/1105582960310226974/1112099086611529861/1lyKfYY.png" class="h-24 w-24 block mx-auto mt-10 ml-6 md:h-60 md:w-60"></div>
  </div>
  
  
  <div class="flex flex-col ml-10 mt-16 mr-3 gap-6 md:gap-20">
   <div><h3 class="text-gray-300 font-bold text-2xl md:text-6xl">The multi-purpose bot for your server</h3>
    <p class="text-gray-400 md:text-5xl">Introducing BoredomBot! a multi-purpose discord bot to help you manage your members and give them more control over their experience in your server.</p></div>
    <div><h3 class="text-gray-300 font-bold text-2xl md:text-6xl">Moderation</h3>
    <p class="text-gray-400 md:text-5xl">BoredomBot has a bunch of moderation commands to help you manage your server.</p></div>
    <div><h3 class="text-gray-300 font-bold text-2xl md:text-6xl">Utility</h3>
    <p class="text-gray-400 md:text-5xl">Not only does the bot offer features for the moderators but it also includes tools for the members to use to spice up their experience in the server.</p></div>
  </div>
  
  <div class="mt-10 ml-10 md:mt-20 mb-28">
    <h3 class="font-bold text-gray-300 text-2xl md:text-6xl text-center">Developers</h3>
    <div class="mt-6 md:mt-16 flex flex-col gap-10">
    <div class="bg-zinc-900 rounded-2xl flex flex-row gap-8 w-[75%] p-3 md:p-8">
     <img alt="posaidon#7497" src="https://cdn.discordapp.com/attachments/1112382531044642897/1112436713084698634/844f924b99bb85eace6c8dbcb88d2ca2.png" class="border-gray-600 border-2 h-14 w-14 md:h-28 md:w-28 rounded-full">
     <h4 class="text-gray-200 md:mt-10 mt-[6%] md:text-4xl">posaidon#7497</h4>
     </div>
     <div class="bg-zinc-900 rounded-2xl flex flex-row gap-8 w-[75%] p-3 md:p-8">
     <img alt="𝐊𝐞𝐭 𝐋𝐗𝐗#0001" src="https://cdn.discordapp.com/avatars/757016233471246346/85b06de289af9bd2ee059a6010aa14a2.png?size=4096" class="border-gray-600 border-2 h-14 w-14 md:h-28 md:w-28 rounded-full">
       <h4 class="text-gray-200 md:mt-10 mt-[6%] md:text-4xl">𝐊𝐞𝐭 𝐋𝐗𝐗#0001</h4>
     </div>
     <div class="bg-zinc-900 rounded-2xl flex flex-row gap-8 w-[75%] p-3 md:p-8">
     <img alt="IronKerman#0001" src="https://cdn.discordapp.com/avatars/759004876838535188/2897acd995506cb208b817fc776616b2.png?size=4096" class="border-gray-600 border-2 h-14 w-14 md:h-28 md:w-28 rounded-full">
       <h4 class="text-gray-200 md:mt-10 mt-[6%] md:text-4xl">IronKerman#0001</h4>
     </div>
    </div>
  </div>
</body>