<template>
  <header class="mx-auto">
    <div
      class="h-[0.3125rem] bg-gradient-to-r from-[#319795] to-[#3182CE]"
    ></div>
    <nav
      class="rounded-b-xl shadow-[0_6px_12px_rgba(0,0,0,0.29)] sticky text-right"
    >
      <li class="list-none p-[1.25rem]">
        <a href="#" class="text-[#319795] hover:underline-offset-1">Login</a>
      </li>
    </nav>
  </header>
  <section
    class="flex flex-col justify-center align-center bg-[#E6FFFA] mx-auto"
  >
    <h1 class="text-center text-4xl text-[#2D3748] p-4">
      Deine Job <br />website
    </h1>
    <div class="flex justify-center align-center">
      <img src="/assets/images/undraw_agreement_aajr.svg" alt="Agreement" />
    </div>
  </section>

  <section class="mx-auto">
    <h2 class="text-[#4A5568] text-center text-2xl p-4">
      Drei einfache Schritte <br />
      deinem neuen Job
    </h2>
    <ul>
      <li class="my-6">
        <div class="flex justify-center">
          <img
            src="/assets/images/undraw_profile_data.svg"
            alt="Profile Data"
          />
        </div>
        <div class="flex justify-around align-center">
          <span class="text-[#718096] text-[7.6rem]">1.</span>
          <p class="flex self-end mb-10 text-[#718096]">
            Erstellen dein Lebenslauf
          </p>
        </div>
      </li>
      <li
        class="my-6 bg-[url('/assets/images/blob1.svg')] bg-no-repeat bg-cover"
      >
        <div class="flex justify-around align-center px-2">
          <span class="text-[#718096] text-[7.6rem]">2.</span>
          <p class="flex self-end mb-10 text-[#718096]">
            Erstellen dein Lebenslauf
          </p>
        </div>
        <div class="flex justify-center">
          <img src="/assets/images/undraw_task.svg" alt="Profile Data" />
        </div>
      </li>
      <li
        class="my-6 bg-[url('/assets/images/blob2.svg')] bg-no-repeat bg-cover"
      >
        <div class="flex justify-center">
          <img src="/assets/images/undraw_personal.svg" alt="Profile Data" />
        </div>

        <div class="flex justify-around align-center px-2">
          <span class="text-[#718096] text-[7.6rem]">3.</span>
          <p class="flex self-end mb-10 text-[#718096]">
            Mit nur einem Klick bewerben
          </p>
        </div>
      </li>
    </ul>
  </section>

  <footer
    class="mx-auto rounded-b-xl shadow-[0_-6px_12px_rgba(0,0,0,0.29)] sticky p-4 text-center"
  >
    <button
      class="bg-gradient-to-r from-[#319795] to-[#3182CE] text-[0.9rem] text-[#E6FFFA] py-[0.7rem] px-[5.5rem] rounded-[0.6rem]"
    >
      Kostenlos Registrieren
    </button>
  </footer>
</template>
