<script>

import emailjs from '@emailjs/browser';

export default {
  methods: {
    sendEmail() {
      emailjs.sendForm('service_4ia4s9i', 'template_but8u3v', this.$refs.form, 'd0vOCDiHKgAlgjbLA')
        .then((result) => {
            alert("Something went wrong")
        }, (error) => {
            alert("Something went wrong")
        });
    }
  }
}

</script>

<template>
  <section
    id="contact"
    class="w-screen h-screen p-10 lg:p-20 overflow-hidden bg-[#000b2e] snap-start flex flex-col xl:flex-row items-center md:justify-between relative"
  >
    <div class="min-w-[370px]">
      <h1 class="text-5xl z-10 lg:text-7xl font-bold text-white">
        Contact Me <span class="text-white/50">//</span>
      </h1>
      <p
        class="font-mono z-10 mt-4 text-white/70 w-[370px] lg:w-[600px] text-center sm:text-left"
      >
        You can Contact me by email or by using the form on this page. You can
        expect a response within 48 hours. I hope to talk to you soon!
      </p>
      <p
        class="font-mono z-10 mt-4 text-white w-[370px] lg:w-[600px] text-center sm:text-left"
      >
        Email: matissjurevics@gmail.com
      </p>
      <p
        class="font-mono z-10 mt-4 text-white w-[370px] lg:w-[600px] text-center sm:text-left"
      >
        Phone: (+353) 83 043 3434
      </p>
    </div>
    <form
      ref="form"
      @submit.prevent="sendEmail"
      id="contactForm"
      class="min-w-[370px] w-1/3 h-fit md:mt-8 mb-16 md:mb-0rounded-3xl p-5"
    >
      <input
        type="text"
        name="name"
        placeholder="Your Name"
        class="border-pink-500/60 focus:border-pink-500/90 hover:border-pink-500/90 border-2 bg-transparent outline-none rounded-xl w-full py-2 px-3 text-white/70"
      />
      <input
        type="email"
        name="email"
        placeholder="Your Email"
        class="mt-4 border-pink-500/60 focus:border-pink-500/90 hover:border-pink-500/90 border-2 bg-transparent outline-none rounded-xl w-full py-2 px-3 text-white/70"
      />
      <input
        type="text"
        name="subject"
        placeholder="Subject"
        class="border-pink-500/60 mt-4 focus:border-pink-500/90 hover:border-pink-500/90 border-2 bg-transparent outline-none rounded-xl w-full py-2 px-3 text-white/70"
      />
      <Textarea
        name="message"
        placeholder="Your Message..."
        class="mt-4 h-32 border-pink-500/60 focus:border-pink-500/90 hover:border-pink-500/90 border-2 bg-transparent outline-none rounded-xl w-full py-2 px-3 text-white/70"
      ></Textarea>
      <button
        type="submit"
        class="mt-8 p-2 w-full bg-transparent border-2 border-pink-500/60 rounded-xl text-pink-500 hover:bg-pink-500 hover:text-white hover:shadow-lg hover:shadow-pink-500/30 transition duration-300"
      >
        See You Soon
      </button>
    </form>
    <div
      class="absolute bottom-0 left-0 bg-white/10 w-full h-fit py-6 text-white/60 flex flex-col items-center justify-center"
    >
      <p>Made By: Matiss Jurevics</p>
      <a href="https://github.com/SeatomGuy/Vue-Portfolio"
        ><span
          class="iconify"
          data-icon="ant-design:github-filled"
          data-width="30"
          data-height="30"
        ></span
      ></a>
    </div>
  </section>
</template>
