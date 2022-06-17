<template>
  <main class="h-screen w-screen bg-slate-800">
    <Navbar />
    <section class="p-8">
      <h1
        class="w-fit text-4xl bg-gradient-to-br from-blue-400 to-green-400 bg-clip-text text-transparent font-bold"
      >
        Generate UI Components
      </h1>
      <div class="w-full h-[2px] bg-white/30 my-2"/>

      <div class="mt-6">
        <div class="card w-96 bg-base-100 drop-shadow-xl">
          <figure>
            <img
              src="https://api.lorem.space/image/shoes?w=400&h=225"
              alt="Shoes"
            />
          </figure>
          <div class="card-body">
            <h2 class="card-title">Shoes!</h2>
            <p>If a dog chews shoes whose shoes does he choose?</p>
            <div class="card-actions justify-end">
              <button class="btn btn-primary">Buy Now</button>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
