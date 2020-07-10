<template>
  <div class="container px-4 lg:px-6 xl:px-10 mx-auto justify-center">
    <section>
      <div class="flex flex-col lg:flex-row justify-between items-center">
        <div class>
          <div class="mt-10 md:mt-20">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight max-w-2xl">
              Looking for
              <span class="underline">CTO</span>
              for your Startup you are at right place
            </h1>
          </div>
          <div
            class="md:text-2xl mt-4 md:mt-5 font-semibold text-gray-600 dark:text-gray-500 uppercase tracking-wide"
          >
            <span>CTO & Project Manager at</span>
            <span class="underline hover:text-gray-900 dark:hover:text-gray-100">
              <a href="https://hkbyte.com" target="_blank">HKBYTE</a>
            </span>
          </div>
          <div class="my-4 md:my-5">
            <a href="#work">
              <Button
                class="bg-gray-300 dark:bg-gray-800 text-gray-900 dark:text-gray-100 hover:bg-gray-400 dark:hover:bg-gray-700 mr-1"
              >Check Work</Button>
            </a>
            <a href="#contact">
              <Button class="bg-blue-500 text-blue-100 hover:bg-blue-600 ml-1">Contact Now</Button>
            </a>
          </div>
        </div>
        <div class="pt-10">
          <img
            class="h-64 rounded-lg lg:rounded-full shadow-lg"
            src="https://kunalgosrani.com/img/profile.jpg"
            alt="Kunal Gosrani Profile Picture"
          />
        </div>
      </div>
    </section>

    <section class="pt-20" id="about">
      <h1 class="text-3xl font-bold">About Me</h1>
      <div class="font-bold text-gray-600 dark:text-gray-500 uppercase tracking-wide">
        <span>BCA Graduate</span>
        &bull;
        <span>Jamnagar, India</span>
      </div>
      <p
        class="text-lg max-w-2xl"
      >I enjoy programming, designing, solving complex problems, learning new programming languages. Love to play Cricket, Badminton & Table Tennis. Also like to invest time and money on right place for prosperous and peacefull future.</p>
    </section>

    <section class="pt-20" id="work">
      <h1 class="text-3xl font-bold">Work</h1>
      <p
        class="text-lg max-w-2xl"
      >I have maintained, developed and launched multiple projects from scratch, carrying the development and monitoring of its' back-end and front-end codebases and UI/UX designing..</p>

      <br />
      <h1 class="text-xl md:text-2xl font-bold mb-1">Repositories</h1>
      <div class="grid grid-cols-12 gap-3">
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Github"
          href="https://github.com/kunalgosrani"
          subTitle="kunalgosrani"
        >
          <svg width="2em" height="2em" data-icon="github" viewBox="0 0 496 512" class="icon">
            <path
              fill="currentColor"
              d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"
              class
            />
          </svg>
        </ContactCard>
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Gitlab"
          href="https://gitlab.com/kunalgosrani"
          subTitle="kunalgosrani"
        >
          <svg width="2em" height="2em" data-icon="gitlab" viewBox="0 0 512 512" class="icon">
            <path
              fill="currentColor"
              d="M105.2 24.9c-3.1-8.9-15.7-8.9-18.9 0L29.8 199.7h132c-.1 0-56.6-174.8-56.6-174.8zM.9 287.7c-2.6 8 .3 16.9 7.1 22l247.9 184-226.2-294zm160.8-88l94.3 294 94.3-294zm349.4 88l-28.8-88-226.3 294 247.9-184c6.9-5.1 9.7-14 7.2-22zM425.7 24.9c-3.1-8.9-15.7-8.9-18.9 0l-56.6 174.8h132z"
              class
            />
          </svg>
        </ContactCard>
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="NPM"
          href="https://www.npmjs.com/~iamkunalgosrani"
          subTitle="iamkunalgosrani"
        >
          <svg width="2em" height="2em" data-icon="npm" viewBox="0 0 576 512" class="icon">
            <path
              fill="currentColor"
              d="M288 288h-32v-64h32v64zm288-128v192H288v32H160v-32H0V160h576zm-416 32H32v128h64v-96h32v96h32V192zm160 0H192v160h64v-32h64V192zm224 0H352v128h64v-96h32v96h32v-96h32v96h32V192z"
              class
            />
          </svg>
        </ContactCard>
      </div>

      <br />
      <h1 class="text-xl md:text-2xl font-bold mb-1">Projects</h1>
      <div class="grid grid-cols-12 gap-3">
        <ProjectCard
          title="HVO Cricket"
          subtitle="Project Manager, Backend"
          class="col-span-12 md:col-span-6 xl:col-span-4"
          imageUrl="images/projects/hvo-cricket.jpg"
          link="https://osu.hkbyte.com"
        />
        <ProjectCard
          title="Image Light"
          subtitle="Project Manager, Backend"
          class="col-span-12 md:col-span-6 xl:col-span-4"
          imageUrl="images/projects/image-light.jpg"
          link="https://play.google.com/store/apps/details?id=com.hkbyte.imagelight"
        />
        <ProjectCard
          title="Govardhan Caterers"
          subtitle="Project Manager, Backend"
          class="col-span-12 md:col-span-6 xl:col-span-4"
          imageUrl="images/projects/govardhan-caterers.jpg"
          link="https://govardhancaterers.com"
        />
        <ProjectCard
          title="Deep Consultancy"
          subtitle="UX/UI, Frontend"
          class="col-span-12 md:col-span-6 xl:col-span-4"
          imageUrl="images/projects/deep-consultancy.jpg"
          link="https://deepconsultancy.in"
        />
        <ProjectCard
          title="Edufinger"
          subtitle="Project Manager, Backend"
          class="col-span-12 md:col-span-6 xl:col-span-4"
          imageUrl="images/projects/edufinger.png"
          link="https://play.google.com/store/apps/details?id=com.hkbyte.edufinger"
        />
      </div>
    </section>

    <section class="pt-20" id="contact">
      <h1 class="text-3xl font-bold">Contact</h1>
      <p>Feel free to say hello!</p>
      <br />

      <h1 class="text-xl md:text-2xl font-bold mb-1">Lets Chat</h1>
      <div class="grid grid-cols-12 gap-3">
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Skype"
          href="skype:live:iamkunalgosrani?chat"
          subTitle="iamkunalgosrani"
        >
          <svg width="2em" height="2em" data-icon="skype" viewBox="0 0 448 512" class="icon">
            <path
              fill="currentColor"
              d="M424.7 299.8c2.9-14 4.7-28.9 4.7-43.8 0-113.5-91.9-205.3-205.3-205.3-14.9 0-29.7 1.7-43.8 4.7C161.3 40.7 137.7 32 112 32 50.2 32 0 82.2 0 144c0 25.7 8.7 49.3 23.3 68.2-2.9 14-4.7 28.9-4.7 43.8 0 113.5 91.9 205.3 205.3 205.3 14.9 0 29.7-1.7 43.8-4.7 19 14.6 42.6 23.3 68.2 23.3 61.8 0 112-50.2 112-112 .1-25.6-8.6-49.2-23.2-68.1zm-194.6 91.5c-65.6 0-120.5-29.2-120.5-65 0-16 9-30.6 29.5-30.6 31.2 0 34.1 44.9 88.1 44.9 25.7 0 42.3-11.4 42.3-26.3 0-18.7-16-21.6-42-28-62.5-15.4-117.8-22-117.8-87.2 0-59.2 58.6-81.1 109.1-81.1 55.1 0 110.8 21.9 110.8 55.4 0 16.9-11.4 31.8-30.3 31.8-28.3 0-29.2-33.5-75-33.5-25.7 0-42 7-42 22.5 0 19.8 20.8 21.8 69.1 33 41.4 9.3 90.7 26.8 90.7 77.6 0 59.1-57.1 86.5-112 86.5z"
              class
            />
          </svg>
        </ContactCard>
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Facebook Messenger"
          href="https://m.me/iamkunalgosrani"
          subTitle="iamkunalgosrani"
        >
          <svg
            width="2em"
            height="2em"
            data-icon="facebook-messenger"
            viewBox="0 0 512 512"
            class="icon"
          >
            <path
              fill="currentColor"
              d="M256.55 8C116.52 8 8 110.34 8 248.57c0 72.3 29.71 134.78 78.07 177.94 8.35 7.51 6.63 11.86 8.05 58.23A19.92 19.92 0 0 0 122 502.31c52.91-23.3 53.59-25.14 62.56-22.7C337.85 521.8 504 423.7 504 248.57 504 110.34 396.59 8 256.55 8zm149.24 185.13l-73 115.57a37.37 37.37 0 0 1-53.91 9.93l-58.08-43.47a15 15 0 0 0-18 0l-78.37 59.44c-10.46 7.93-24.16-4.6-17.11-15.67l73-115.57a37.36 37.36 0 0 1 53.91-9.93l58.06 43.46a15 15 0 0 0 18 0l78.41-59.38c10.44-7.98 24.14 4.54 17.09 15.62z"
              class
            />
          </svg>
        </ContactCard>
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="WhatsApp"
          href="https://wa.me/919870097361"
          subTitle="+91 9870097361"
        >
          <svg width="2em" height="2em" data-icon="whatsapp" viewBox="0 0 448 512" class="icon">
            <path
              fill="currentColor"
              d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"
              class
            />
          </svg>
        </ContactCard>
      </div>
      <br />
      <h1 class="text-xl md:text-2xl font-bold mb-1">Connect</h1>
      <div class="grid grid-cols-12 gap-3">
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Phone Call"
          href="tel:+919870097361"
          subTitle="+91 9870097361"
        >
          <svg width="2em" height="2em" fill="currentColor" viewBox="0 0 16 16">
            <path
              fill-rule="evenodd"
              d="M3.925 1.745a.636.636 0 0 0-.951-.059l-.97.97c-.453.453-.62 1.095-.421 1.658A16.47 16.47 0 0 0 5.49 10.51a16.471 16.471 0 0 0 6.196 3.907c.563.198 1.205.032 1.658-.421l.97-.97a.636.636 0 0 0-.06-.951l-2.162-1.682a.636.636 0 0 0-.544-.115l-2.052.513a1.636 1.636 0 0 1-1.554-.43L5.64 8.058a1.636 1.636 0 0 1-.43-1.554l.513-2.052a.636.636 0 0 0-.115-.544L3.925 1.745zM2.267.98a1.636 1.636 0 0 1 2.448.153l1.681 2.162c.309.396.418.913.296 1.4l-.513 2.053a.636.636 0 0 0 .167.604L8.65 9.654a.636.636 0 0 0 .604.167l2.052-.513a1.636 1.636 0 0 1 1.401.296l2.162 1.681c.777.604.849 1.753.153 2.448l-.97.97c-.693.693-1.73.998-2.697.658a17.47 17.47 0 0 1-6.571-4.144A17.47 17.47 0 0 1 .639 4.646c-.34-.967-.035-2.004.658-2.698l.97-.969z"
            />
          </svg>
        </ContactCard>
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Email"
          href="mailto:me@kunalgosrani.com"
          subTitle="me@kunalgosrani.com"
        >
          <svg width="2em" height="2em" fill="currentColor" viewBox="0 0 16 16">
            <path
              fill-rule="evenodd"
              d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2zm13 2.383l-4.758 2.855L15 11.114v-5.73zm-.034 6.878L9.271 8.82 8 9.583 6.728 8.82l-5.694 3.44A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.739zM1 11.114l4.758-2.876L1 5.383v5.73z"
            />
          </svg>
        </ContactCard>
      </div>
      <br />
      <h1 class="text-xl md:text-2xl font-bold mb-1">Social Network</h1>
      <div class="grid grid-cols-12 gap-3">
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Linkedin"
          href="https://www.linkedin.com/in/iamkunalgosrani/"
          subTitle="iamkunalgosrani"
        >
          <svg class="icon" data-icon="linkedin-in" viewBox="0 0 448 512" width="2em" height="2em">
            <path
              fill="currentColor"
              d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"
              class
            />
          </svg>
        </ContactCard>
        <ContactCard
          class="col-span-12 md:col-span-6 lg:col-span-4 xl:col-span-3"
          title="Instagram"
          href="https://instagram.com/kunal_gosrani"
          subTitle="kunal_gosrani"
        >
          <svg width="2em" height="2em" data-icon="instagram" viewBox="0 0 448 512">
            <path
              fill="currentColor"
              d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"
              class
            />
          </svg>
        </ContactCard>
      </div>
    </section>

    <hr class="mt-10 opacity-75" />

    <footer class="w-full text-center my-5">
      <div>
        <b>Kunal Gosrani</b>
        &copy; 2020
      </div>
      <div>
        <small>
          <!-- <a class="text-light" href="#">Privacy Policy</a> -->
        </small>
      </div>
    </footer>
  </div>
</template>

<script>
import Button from "../components/Button";
import ContactCard from "../components/ContactCard";
import ProjectCard from "../components/ProjectCard";

export default {
  components: {
    Button,
    ContactCard
  },
  head() {
    return {
      title: "Kunal Gosrani | Project Manager | Backend Developer",
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          name: "keywords",
          content:
            "Kunal Gosrani, Gosrani, Kunal Hitesh Gosrani, Kunal, Kunal Jamnagar, Kunal Gosrani Jamnagar, Kunal Gosrani Coder, Kunal Gosrani Developer, Kunal Gosrani CTO, Kunal Gosrani India, Kunal Gosrani Thane"
        },
        {
          hid: "description",
          name: "description",
          content:
            "I am Kunal Gosrani, CTO, Backend Developer and Project Manager at HKByte. Lives in Jamnagar, Gujarat, India. Graduated in BCA from Saurashtra University"
        }
      ]
    };
  }
};
</script>

<style>
</style>
