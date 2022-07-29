---
layout: article
titles:
  # @start locale config
  en      : &EN       About
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : &ZH_HANS  关于
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : &ZH_HANT  關於
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : &KO       소개
  ko-KR   : *KO
  fr      : &FR       À propos
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-about
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tw-elements/dist/css/index.min.css" />
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          sans: ['Inter', 'sans-serif'],
        },
      }
    }
  }
</script>
<script src="https://cdn.jsdelivr.net/npm/tw-elements/dist/js/index.min.js"></script>

<!-- <script src="https://cdn.tailwindcss.com"></script> -->

<div
  class="p-12 text-center relative overflow-hidden bg-no-repeat bg-cover rounded-lg"
  style="
    background-image: url('https://user-images.githubusercontent.com/19698023/181514172-2568fc26-1711-47e0-b7d0-260f190e8834.jpeg');
    height: 400px;
  ">
  <div
    class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed"
    style="background-color: rgba(0, 0, 0, 0.6)">
    <div class="flex justify-center items-center h-full">
      <div class="text-white">
        <h2 class="font-semibold text-4xl mb-4" style="color: white">QBS185 Summer Capstone Projects</h2>
        <h4 class="font-semibold text-xl mb-6" style="color: white">Program Information</h4>
        <a
          class="inline-block px-7 py-3 mb-1 border-2 border-gray-200 text-gray-200 font-medium text-sm leading-snug uppercase rounded hover:bg-black hover:bg-opacity-5 focus:outline-none focus:ring-0 transition duration-150 ease-in-out"
          href="/presenters"
          role="button"
          data-mdb-ripple="true"
          data-mdb-ripple-color="light">Listen to our presenters</a>
      </div>
    </div>
  </div>
</div>

<br>
<div class="grid grid-cols-2 gap-4">
  <div class="accordion" id="accordionExample">
    <div class="accordion-item bg-white border border-gray-200">
      <h2 class="accordion-header mb-0" id="headingOne">
        <button class="
          accordion-button
          relative
          flex
          items-center
          w-full
          py-4
          px-5
          text-base text-gray-800 text-left
          bg-white
          border-0
          rounded-none
          transition
          focus:outline-none
        " type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true"
          aria-controls="collapseOne">
          Capstone Goals
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
        data-bs-parent="#accordionExample">
        <div class="accordion-body py-4 px-5">
          The <strong>goal of the capstone</strong> is to enable students to refine their skill set as they work on a research or applied data science, epidemiology or medical informatics project. The capstone also provides training in critical professional skills including scientific writing, presentation skills, and translating the findings of a research or applied project to key stakeholders who may not have expertise in the domain. Preparation for the capstone project begins in August of the first year and culminates in a written white paper and presentation at the end of the summer term.
        </div>
      </div>
    </div>
    <div class="accordion-item bg-white border border-gray-200">
      <h2 class="accordion-header mb-0" id="headingTwo">
        <button class="
          accordion-button
          collapsed
          relative
          flex
          items-center
          w-full
          py-4
          px-5
          text-base text-gray-800 text-left
          bg-white
          border-0
          rounded-none
          transition
          focus:outline-none
        " type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false"
          aria-controls="collapseTwo">
          What kind of projects have students worked on this Summer?
        </button>
      </h2>
      <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
        data-bs-parent="#accordionExample">
        <div class="accordion-body py-4 px-5">
          Students will work on one of the <strong>following three types of projects</strong>:
          <ul class="list-disc">
            <li>Individual project with Dartmouth PI</li>
            <li>Individual project based external experience (e.g., internship)</li>
            <li>Collaborative group project</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="accordion-item bg-white border border-gray-200">
      <h2 class="accordion-header mb-0" id="headingThree">
        <button class="
          accordion-button
          collapsed
          relative
          flex
          items-center
          w-full
          py-4
          px-5
          text-base text-gray-800 text-left
          bg-white
          border-0
          rounded-none
          transition
          focus:outline-none
        " type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false"
          aria-controls="collapseThree">
          What is the Program in Quantitative Biomedical Sciences?
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
        data-bs-parent="#accordionExample">
        <div class="accordion-body py-4 px-5">
          The <strong>Graduate Program in Quantitative Biomedical Sciences (QBS)</strong> provides training for Master's and PhD students in Biostatistics, Bioinformatics, Epidemiology, Health Data Science and Medical Informatics, including the development and application of artificial intelligence technologies. Graduating students are well positioned for jobs in industry and academia. QBS Master's students have enrolled in the following program tracks: 1) Epidemiology, 2) Health Data Science, and 3) Medical Informatics. More information on QBS can be found <a href="https://geiselmed.dartmouth.edu/qbs/">here</a>.
        </div>
      </div>
    </div>
  </div>

  <div id="carouselExampleCaptions" class="carousel slide relative" data-bs-ride="carousel">
    <div class="p-6 shadow-lg rounded-lg bg-white text-grey-700">
      <h2 class="font-semibold text-3xl mb-5">Featured Projects</h2>
      <p>
        Our Master's students have put together some absolutely incredible projects that we are excited to share program faculty.
      </p>
      <hr class="my-6 border-gray-300" />
      <p>
        Here are a few featured projects from some of our many all-stars!
      </p>
    </div>
    <div>
      <br>
    </div>
    <div class="carousel-indicators absolute right-0 bottom-0 left-0 flex justify-center p-0 mt-0 mb-2 py-2">
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner relative w-full overflow-hidden">
      <div class="carousel-item active relative float-left w-full">
        <img
          src="https://user-images.githubusercontent.com/19698023/181658028-55c8907e-f750-4d69-8ba7-14f4ca3f4f35.jpeg"
          class="block w-full"
          alt="..."
        />
        <div class="carousel-caption hidden md:block absolute text-center">
          <h5 class="text-xl text-white">Placeholder- Levy Lab</h5>
          <p>Placeholder- Apply to the <a href="https://levylab.host.dartmouth.edu/">Levy Lab</a> for opportunities in machine learning and health informatics.</p>
        </div>
      </div>
      <div class="carousel-item relative float-left w-full">
        <img
          src="https://user-images.githubusercontent.com/19698023/181657550-f9c375e1-7413-4046-9292-387731a3c8d8.jpeg"
          class="block w-full"
          alt="..."
        />
        <div class="carousel-caption hidden md:block absolute text-center">
          <h5 class="text-xl text-white">Placeholder- Previous Master's student Christian Haudenschild</h5>
          <p>Former QBS Master's student has cat named ChaCha and publishes <a href="/presenter_articles/1_Joshua_Levy.html">multimodal deep learning EHR research</a> under mentorship of Dr. Levy.</p>
        </div>
      </div>
      <div class="carousel-item relative float-left w-full">
        <img
          src="https://user-images.githubusercontent.com/19698023/181657854-47a08806-2d36-40b2-b86d-2d67fd36d1e3.jpeg"
          class="block w-full"
          alt="..."
        />
        <div class="carousel-caption hidden md:block absolute text-center">
          <h5 class="text-xl text-white">Placeholder- Dr. Carly Bobak</h5>
          <p>Placeholder- Learn about Dr. Carly Bobak's innovative work on her <a href="">website</a>.</p>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="prev">
      <span class="carousel-control-prev-icon inline-block bg-no-repeat" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="next">
      <span class="carousel-control-next-icon inline-block bg-no-repeat" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</div>
