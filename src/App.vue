<template>
  <div id="app">
    <!-- TITLE -->
    <p>The emoji piano</p>
    <div id="container">
      <!-- EMOJI -->
      <img id="emoji" />
      <img id="next" class="hidden" />
    </div>
    <!-- PIANO -->
    <svg
      width="691"
      height="448"
      viewBox="0 0 691 448"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <g filter="url(#filter0_d)">
        <rect x="80" y="68" width="531" height="276" rx="10" fill="black" />
        <path
          d="M115.608 396C116.114 395.933 116.641 395.893 117.188 395.88C117.748 395.853 118.221 395.84 118.608 395.84C119.821 395.84 120.834 396.013 121.648 396.36C122.474 396.707 123.134 397.193 123.628 397.82C124.134 398.433 124.494 399.173 124.708 400.04C124.934 400.907 125.048 401.86 125.048 402.9C125.048 403.847 124.948 404.76 124.748 405.64C124.548 406.507 124.201 407.28 123.708 407.96C123.214 408.627 122.548 409.167 121.708 409.58C120.881 409.98 119.841 410.18 118.588 410.18C118.414 410.18 118.188 410.173 117.908 410.16C117.628 410.16 117.341 410.147 117.048 410.12C116.754 410.107 116.474 410.093 116.208 410.08C115.941 410.067 115.741 410.047 115.608 410.02V396ZM118.688 397.32C118.501 397.32 118.261 397.327 117.968 397.34C117.688 397.353 117.454 397.38 117.268 397.42V408.62C117.334 408.633 117.428 408.647 117.548 408.66C117.681 408.66 117.814 408.667 117.948 408.68C118.081 408.68 118.208 408.687 118.328 408.7C118.461 408.7 118.568 408.7 118.648 408.7C119.621 408.7 120.408 408.54 121.008 408.22C121.621 407.9 122.094 407.473 122.428 406.94C122.761 406.393 122.988 405.773 123.108 405.08C123.228 404.373 123.288 403.647 123.288 402.9C123.288 402.247 123.234 401.593 123.128 400.94C123.021 400.273 122.801 399.673 122.468 399.14C122.148 398.607 121.681 398.173 121.068 397.84C120.468 397.493 119.674 397.32 118.688 397.32ZM126.96 403C126.96 400.68 127.367 398.893 128.18 397.64C129.007 396.387 130.273 395.76 131.98 395.76C132.913 395.76 133.7 395.933 134.34 396.28C134.993 396.627 135.52 397.12 135.92 397.76C136.32 398.387 136.607 399.147 136.78 400.04C136.953 400.92 137.04 401.907 137.04 403C137.04 405.32 136.627 407.107 135.8 408.36C134.987 409.613 133.713 410.24 131.98 410.24C131.06 410.24 130.28 410.067 129.64 409.72C129 409.373 128.48 408.887 128.08 408.26C127.68 407.62 127.393 406.86 127.22 405.98C127.047 405.087 126.96 404.093 126.96 403ZM128.72 403C128.72 403.773 128.767 404.507 128.86 405.2C128.967 405.893 129.147 406.507 129.4 407.04C129.653 407.56 129.987 407.98 130.4 408.3C130.813 408.607 131.34 408.76 131.98 408.76C133.127 408.76 133.96 408.293 134.48 407.36C135.013 406.427 135.28 404.973 135.28 403C135.28 402.24 135.227 401.513 135.12 400.82C135.027 400.113 134.853 399.5 134.6 398.98C134.347 398.447 134.007 398.027 133.58 397.72C133.153 397.4 132.62 397.24 131.98 397.24C130.847 397.24 130.02 397.713 129.5 398.66C128.98 399.593 128.72 401.04 128.72 403Z"
          fill="white"
          fill-opacity="0.4"
          id="letterDo"
          class="letter"
        />
        <path
          d="M188.008 396.14C188.514 396.047 189.094 395.973 189.748 395.92C190.414 395.867 191.021 395.84 191.568 395.84C192.181 395.84 192.761 395.907 193.308 396.04C193.868 396.173 194.354 396.393 194.768 396.7C195.194 397.007 195.534 397.407 195.788 397.9C196.041 398.393 196.168 398.993 196.168 399.7C196.168 400.247 196.074 400.733 195.888 401.16C195.714 401.573 195.494 401.933 195.228 402.24C194.974 402.533 194.708 402.773 194.428 402.96C194.148 403.147 193.908 403.28 193.708 403.36L197.408 410H195.468L192.168 403.84H189.668V410H188.008V396.14ZM191.608 397.28C191.434 397.28 191.254 397.28 191.068 397.28C190.881 397.28 190.701 397.287 190.528 397.3C190.354 397.313 190.188 397.327 190.028 397.34C189.881 397.353 189.761 397.373 189.668 397.4V402.56H191.228C192.148 402.56 192.908 402.333 193.508 401.88C194.108 401.427 194.408 400.72 194.408 399.76C194.408 399.04 194.161 398.447 193.668 397.98C193.174 397.513 192.488 397.28 191.608 397.28ZM200.14 396H208.36V397.48H201.8V402.06H207.86V403.54H201.8V408.52H208.46V410H200.14V396ZM205.04 392.6H207.32V393.02L204.06 394.96H202.68L205.04 392.6Z"
          fill="white"
          fill-opacity="0.4"
          id="letterRe"
          class="letter"
        />
        <path
          d="M269.148 400.7L269.348 398.8H269.248L268.288 400.52L266.248 403.94H265.748L263.608 400.5L262.688 398.8H262.588L262.828 400.68V410H261.208V396H262.748L266.068 401.32H266.108L269.308 396H270.808V410H269.148V400.7ZM273.2 396H282.8V397.48H278.82V408.52H282.8V410H273.2V408.52H277.16V397.48H273.2V396Z"
          fill="white"
          fill-opacity="0.4"
          id="letterMi"
          class="letter"
        />
        <path
          d="M336.348 396H344.368V397.48H338.008V402.26H343.968V403.74H338.008V410H336.348V396ZM354.62 406.12H349.24L347.96 410H346.32L351 396H352.96L357.68 410H355.94L354.62 406.12ZM349.76 404.68H354.16L352.1 398.1H351.86L349.76 404.68Z"
          fill="white"
          fill-opacity="0.4"
          id="letterFa"
          class="letter"
        />
        <path
          d="M404.012 408.02C404.412 408.233 404.858 408.413 405.352 408.56C405.858 408.693 406.365 408.76 406.872 408.76C407.312 408.76 407.725 408.72 408.112 408.64C408.498 408.547 408.832 408.407 409.112 408.22C409.405 408.02 409.632 407.773 409.792 407.48C409.965 407.187 410.052 406.84 410.052 406.44C410.052 405.893 409.865 405.447 409.492 405.1C409.132 404.753 408.678 404.447 408.132 404.18C407.585 403.913 406.992 403.653 406.352 403.4C405.712 403.147 405.118 402.847 404.572 402.5C404.025 402.153 403.565 401.733 403.192 401.24C402.832 400.733 402.652 400.093 402.652 399.32C402.652 398.773 402.758 398.28 402.972 397.84C403.198 397.4 403.512 397.027 403.912 396.72C404.312 396.413 404.792 396.18 405.352 396.02C405.925 395.847 406.558 395.76 407.252 395.76C408.052 395.76 408.778 395.82 409.432 395.94C410.085 396.047 410.605 396.193 410.992 396.38L411.032 396.36V396.4H411.052L411.032 396.46V399.66H409.552V397.52C409.218 397.44 408.852 397.373 408.452 397.32C408.052 397.267 407.625 397.24 407.172 397.24C406.732 397.24 406.332 397.293 405.972 397.4C405.625 397.507 405.325 397.653 405.072 397.84C404.832 398.013 404.645 398.22 404.512 398.46C404.378 398.7 404.312 398.953 404.312 399.22C404.312 399.74 404.492 400.173 404.852 400.52C405.225 400.867 405.685 401.18 406.232 401.46C406.778 401.727 407.372 401.993 408.012 402.26C408.652 402.527 409.245 402.84 409.792 403.2C410.338 403.547 410.792 403.967 411.152 404.46C411.525 404.953 411.712 405.567 411.712 406.3C411.712 406.9 411.598 407.44 411.372 407.92C411.158 408.4 410.845 408.813 410.432 409.16C410.032 409.507 409.532 409.773 408.932 409.96C408.345 410.147 407.678 410.24 406.932 410.24C406.425 410.24 405.945 410.2 405.492 410.12C405.038 410.04 404.618 409.94 404.232 409.82C403.858 409.7 403.518 409.573 403.212 409.44C402.918 409.307 402.685 409.193 402.512 409.1L402.532 409.04V405.8H404.012V408.02ZM413.964 403C413.964 400.68 414.371 398.893 415.184 397.64C416.011 396.387 417.277 395.76 418.984 395.76C419.917 395.76 420.704 395.933 421.344 396.28C421.997 396.627 422.524 397.12 422.924 397.76C423.324 398.387 423.611 399.147 423.784 400.04C423.957 400.92 424.044 401.907 424.044 403C424.044 405.32 423.631 407.107 422.804 408.36C421.991 409.613 420.717 410.24 418.984 410.24C418.064 410.24 417.284 410.067 416.644 409.72C416.004 409.373 415.484 408.887 415.084 408.26C414.684 407.62 414.397 406.86 414.224 405.98C414.051 405.087 413.964 404.093 413.964 403ZM415.724 403C415.724 403.773 415.771 404.507 415.864 405.2C415.971 405.893 416.151 406.507 416.404 407.04C416.657 407.56 416.991 407.98 417.404 408.3C417.817 408.607 418.344 408.76 418.984 408.76C420.131 408.76 420.964 408.293 421.484 407.36C422.017 406.427 422.284 404.973 422.284 403C422.284 402.24 422.231 401.513 422.124 400.82C422.031 400.113 421.857 399.5 421.604 398.98C421.351 398.447 421.011 398.027 420.584 397.72C420.157 397.4 419.624 397.24 418.984 397.24C417.851 397.24 417.024 397.713 416.504 398.66C415.984 399.593 415.724 401.04 415.724 403ZM426.796 396H428.456V408.52H434.116V405.04H435.596V410H426.796V396Z"
          fill="white"
          fill-opacity="0.4"
          id="letterSol"
          class="letter"
        />
        <path
          d="M481.808 396H483.468V408.52H489.128V405.04H490.608V410H481.808V396ZM500.62 406.12H495.24L493.96 410H492.32L497 396H498.96L503.68 410H501.94L500.62 406.12ZM495.76 404.68H500.16L498.1 398.1H497.86L495.76 404.68Z"
          fill="white"
          fill-opacity="0.4"
          id="letterLa"
          class="letter"
        />
        <path
          d="M555.008 408.02C555.408 408.233 555.854 408.413 556.348 408.56C556.854 408.693 557.361 408.76 557.868 408.76C558.308 408.76 558.721 408.72 559.108 408.64C559.494 408.547 559.828 408.407 560.108 408.22C560.401 408.02 560.628 407.773 560.788 407.48C560.961 407.187 561.048 406.84 561.048 406.44C561.048 405.893 560.861 405.447 560.488 405.1C560.128 404.753 559.674 404.447 559.128 404.18C558.581 403.913 557.988 403.653 557.348 403.4C556.708 403.147 556.114 402.847 555.568 402.5C555.021 402.153 554.561 401.733 554.188 401.24C553.828 400.733 553.648 400.093 553.648 399.32C553.648 398.773 553.754 398.28 553.968 397.84C554.194 397.4 554.508 397.027 554.908 396.72C555.308 396.413 555.788 396.18 556.348 396.02C556.921 395.847 557.554 395.76 558.248 395.76C559.048 395.76 559.774 395.82 560.428 395.94C561.081 396.047 561.601 396.193 561.988 396.38L562.028 396.36V396.4H562.048L562.028 396.46V399.66H560.548V397.52C560.214 397.44 559.848 397.373 559.448 397.32C559.048 397.267 558.621 397.24 558.168 397.24C557.728 397.24 557.328 397.293 556.968 397.4C556.621 397.507 556.321 397.653 556.068 397.84C555.828 398.013 555.641 398.22 555.508 398.46C555.374 398.7 555.308 398.953 555.308 399.22C555.308 399.74 555.488 400.173 555.848 400.52C556.221 400.867 556.681 401.18 557.228 401.46C557.774 401.727 558.368 401.993 559.008 402.26C559.648 402.527 560.241 402.84 560.788 403.2C561.334 403.547 561.788 403.967 562.148 404.46C562.521 404.953 562.708 405.567 562.708 406.3C562.708 406.9 562.594 407.44 562.368 407.92C562.154 408.4 561.841 408.813 561.428 409.16C561.028 409.507 560.528 409.773 559.928 409.96C559.341 410.147 558.674 410.24 557.928 410.24C557.421 410.24 556.941 410.2 556.488 410.12C556.034 410.04 555.614 409.94 555.228 409.82C554.854 409.7 554.514 409.573 554.208 409.44C553.914 409.307 553.681 409.193 553.508 409.1L553.528 409.04V405.8H555.008V408.02ZM565.2 396H574.8V397.48H570.82V408.52H574.8V410H565.2V408.52H569.16V397.48H565.2V396Z"
          fill="white"
          fill-opacity="0.4"
          id="letterSi"
          class="letter"
        />
        <path
          d="M92 85C92 82.2386 94.2386 80 97 80H161V332H97C94.2386 332 92 329.761 92 327V85Z"
          fill="white"
          class="note"
          id="do"
          v-on:click="color"
          v-on:keyup.q="color"
        />
        <rect
          x="165"
          y="80"
          width="69"
          height="252"
          fill="white"
          class="note"
          id="re"
          v-on:click="color"
          v-on:keyup.s="color"
        />
        <rect
          x="238"
          y="80"
          width="69"
          height="252"
          fill="white"
          class="note"
          id="mi"
          v-on:click="color"
          v-on:keyup.d="color"
        />
        <rect
          x="311"
          y="80"
          width="69"
          height="252"
          fill="white"
          class="note"
          id="fa"
          v-on:click="color"
          v-on:keyup.f="color"
        />
        <rect
          x="384"
          y="80"
          width="69"
          height="252"
          fill="white"
          id="sol"
          class="note"
          v-on:click="color"
          v-on:keyup.g="color"
        />
        <rect
          x="457"
          y="80"
          width="69"
          height="252"
          fill="white"
          id="la"
          class="note"
          v-on:click="color"
          v-on:keyup.h="color"
        />
        <path
          d="M530 80H594C596.761 80 599 82.2386 599 85V327C599 329.761 596.761 332 594 332H530V80Z"
          fill="white"
          class="note"
          id="si"
          v-on:click="color"
          v-on:keyup.j="color"
        />
        <path
          d="M148 80H178V259C178 261.761 175.761 264 173 264H153C150.239 264 148 261.761 148 259V80Z"
          fill="black"
          class="note"
          id="doD"
          v-on:click="color"
          v-on:keyup.z="color"
        />
        <path
          d="M221 80H251V259C251 261.761 248.761 264 246 264H226C223.239 264 221 261.761 221 259V80Z"
          fill="black"
          class="note"
          id="reD"
          v-on:click="color"
          v-on:keyup.e="color"
        />
        <path
          d="M367 80H397V259C397 261.761 394.761 264 392 264H372C369.239 264 367 261.761 367 259V80Z"
          fill="black"
          class="note"
          id="faD"
          v-on:click="color"
        />
        <path
          d="M440 80H470V259C470 261.761 467.761 264 465 264H445C442.239 264 440 261.761 440 259V80Z"
          fill="black"
          class="note"
          id="solD"
          v-on:click="color"
        />
        <path
          d="M513 80H543V259C543 261.761 540.761 264 538 264H518C515.239 264 513 261.761 513 259V80Z"
          fill="black"
          class="note"
          id="laD"
          v-on:click="color"
        />
      </g>
      <defs>
        <filter
          id="filter0_d"
          x="0"
          y="0"
          width="691"
          height="502.24"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          />
          <feOffset dy="12" />
          <feGaussianBlur stdDeviation="40" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.3 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow"
            result="shape"
          />
        </filter>
      </defs>
    </svg>
  </div>
</template>

<script>
import { GiphyFetch } from "@giphy/js-fetch-api";
export default {
  name: "App",
  components: {},
  data: function () {
    return {
      gifs: [],
    };
  },
  async asyncData() {},
  mounted() {
    this.asyncData();
    window.addEventListener("keypress", this.color);
  },
  methods: {
    async asyncData() {
      const gf = new GiphyFetch("hoc7Xw81iwUP2iewXhekupQznVmYDlHK");
      this.gifs = await gf.emoji({
        limit: 97,
      });
      console.log(this.gifs)
      const random = Math.floor(Math.random() * 97);
      const next = document.getElementById("next");
      next.src = this.gifs.data[random].images.fixed_width.webp;
    },
    color(e) {
      this.notes = this.$el.querySelectorAll(".note");
      this.notes.forEach((note) => {
        if (
          note.id == "doD" ||
          note.id == "reD" ||
          note.id == "faD" ||
          note.id == "solD" ||
          note.id == "laD"
        )
          note.setAttribute("fill", "#000000");
        else note.setAttribute("fill", "#FFFFFF");
      });
      this.letters = this.$el.querySelectorAll(".letter");
      this.letters.forEach((letter) => {
        letter.setAttribute("fill-opacity", "0.4");
      });
      let id;
      if (e.key) {
        switch (e.key) {
          case "q":
            id = "do";
            break;
          case "s":
            id = "re";
            break;
          case "d":
            id = "mi";
            break;
          case "f":
            id = "fa";
            break;
          case "g":
            id = "sol";
            break;
          case "h":
            id = "la";
            break;
          case "j":
            id = "si";
            break;
          case "z":
            id = "doD";
            break;
          case "e":
            id = "reD";
            break;
          case "t":
            id = "faD";
            break;
          case "y":
            id = "solD";
            break;
          case "u":
            id = "laD";
            break;
          default:
            return console.log("touche de clavier qui ne marche pas");
        }
      } else {
        id = e.target.id;
      }
      let note = document.getElementById(id);
      // console.log(note);
      let color;
      let piste;
      let letter;
      switch (id) {
        case "do":
          piste = "./assets/sounds/C.mp3";
          letter = document.getElementById("letterDo");
          color = "#FFD12D";
          break;
        case "doD":
          piste = "./assets/sounds/C%23.mp3";
          letter = document.getElementById("letterDo");
          color = "#E5016F";
          break;
        case "re":
          piste = "./assets/sounds/D.mp3";
          letter = document.getElementById("letterRe");
          color = "#FFD12D";
          break;

        case "reD":
          piste = "./assets/sounds/D%23.mp3";
          letter = document.getElementById("letterRe");
          color = "#E5016F";
          break;
        case "mi":
          piste = "./assets/sounds/E.mp3";
          letter = document.getElementById("letterMi");
          color = "#FFD12D";
          break;
        case "fa":
          piste = "./assets/sounds/F.mp3";
          letter = document.getElementById("letterFa");
          color = "#FFD12D";
          break;
        case "faD":
          piste = "./assets/sounds/F%23.mp3";
          letter = document.getElementById("letterFa");
          color = "#E5016F";
          break;
        case "sol":
          piste = "./assets/sounds/G.mp3";
          letter = document.getElementById("letterSol");
          color = "#FFD12D";
          break;
        case "solD":
          piste = "./assets/sounds/G%23.mp3";
          letter = document.getElementById("letterSol");
          color = "#E5016F";
          break;
        case "la":
          piste = "./assets/sounds/A.mp3";
          letter = document.getElementById("letterLa");
          color = "#FFD12D";
          break;
        case "laD":
          piste = "./assets/sounds/A%23.mp3";
          letter = document.getElementById("letterLa");
          color = "#E5016F";
          break;
        case "si":
          piste = "./assets/sounds/B.mp3";
          letter = document.getElementById("letterSi");
          color = "#FFD12D";
          break;
      }
      note.setAttribute("fill", color);
      letter.setAttribute("fill-opacity", "1");
      const audio = document.createElement("audio");
      // console.log("piste", piste);
      audio.src = piste;
      audio.play();
      const random = Math.floor(Math.random() * 97);
      const current = document.getElementById("emoji");
      const next = document.getElementById("next");
      current.src = next.src;
      next.src = this.gifs.data[random].images.fixed_width.webp;
    },
  },
};
</script>
<style scoped>
#app {
  width: 100%;
  height: 100%;
  position: absolute;
}
p {
  font-family: "PT Mono", monospace;
  color: white;
  background-color: #111111;
  border-radius: 10px;
  width: 380px;
  font-weight: normal;
  font-size: 30px;
  line-height: 34px;
  text-align: center;
  margin: auto;
  padding: 10px;
  margin-top: 3%;
  margin-bottom: 3%;
}

svg {
  margin: auto;
  height: 45%;
}

#container {
  margin: auto;
  min-height: 37%;
  position: relative;
  justify-content: center;
  display: flex;

  vertical-align: middle;
}
#emoji {
  margin: auto;
  height: 100%;
  position: absolute;
}
@media all and (max-width: 520px) {
  p {
    width: 95%;
    margin-top: 5%;
    margin-bottom: 5%;
  }
  svg {
    width: 100%;
    height: auto;
    margin-top: 18%;
  }
  #emoji {
    margin: auto;
    height: 80%;
    position: absolute;
    margin-top: 40%;
  }
}
</style>