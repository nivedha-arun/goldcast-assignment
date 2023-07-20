<template>
  <div>
    <div>
        <div class="hero">
          <Header/>
          <div class="container">
            <div class="pt-[132px] pb-8 sm:pb-16 xl:py-[132px] 3xl:py-32">
              <div class="relative z-10 rounded-r-full flex flex-col py-8 sm:pl-8 pr-20 lg:p-20 mr-auto hero-bg max-w-fit">
                <div class="max-w-[132px] xl:max-w-[212px] mb-10 revealUp">
                  <svg width="100%" height="100%" viewBox="0 0 96 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path d="M27.0215 11.7047H33.3004L33.122 19.0503H31.6412L31.4241 16.6812C30.6082 18.4851 29.055 19.3859 26.7645 19.3859C24.6449 19.3859 22.957 18.6648 21.6995 17.2239C20.442 15.783 19.8145 14.0414 19.8145 12.0017C19.8145 10.6718 20.0877 9.45792 20.6341 8.35884C21.1805 7.25975 22.0089 6.36152 23.1217 5.6629C24.2332 4.96552 25.5407 4.61621 27.0415 4.61621C28.7269 4.61621 30.0892 5.04786 31.1284 5.90991C32.1676 6.77196 32.8725 7.88103 33.2418 9.23711H30.8328C30.2664 7.49928 29.0026 6.63099 27.0415 6.63099C25.5145 6.63099 24.3268 7.14747 23.4772 8.18044C22.6289 9.2134 22.2035 10.4871 22.2035 12.0017C22.2035 13.5162 22.6214 14.7887 23.4573 15.8229C24.2931 16.8558 25.4484 17.3736 26.923 17.3736C28.1081 17.3736 29.1049 17.0417 29.9146 16.3768C30.7242 15.7118 31.1808 14.7675 31.2869 13.5436L27.0215 13.5636V11.7047Z" fill="black"/>
                      <path d="M43.3291 17.8349C42.3423 18.8292 41.0848 19.3257 39.5578 19.3257C38.0308 19.3257 36.7733 18.8292 35.7865 17.8349C34.7997 16.8419 34.3057 15.5482 34.3057 13.9551C34.3057 12.362 34.7997 11.0658 35.7865 10.0652C36.7733 9.06472 38.0308 8.56445 39.5578 8.56445C41.0848 8.56445 42.3423 9.06472 43.3291 10.0652C44.3159 11.0658 44.81 12.362 44.81 13.9551C44.81 15.5482 44.3159 16.8419 43.3291 17.8349ZM37.4345 16.4826C37.9934 17.1413 38.7008 17.4694 39.5566 17.4694C40.4124 17.4694 41.1197 17.1401 41.6786 16.4826C42.2375 15.8239 42.5182 14.9818 42.5182 13.9551C42.5182 12.9284 42.2388 12.0863 41.6786 11.4276C41.1185 10.7689 40.4111 10.4408 39.5566 10.4408C38.7145 10.4408 38.0096 10.7701 37.4432 11.4276C36.8768 12.0863 36.5937 12.9284 36.5937 13.9551C36.5937 14.9818 36.8744 15.8251 37.4345 16.4826Z" fill="black"/>
                      <path d="M45.874 4.95215H48.1645V19.0506H45.874V4.95215Z" fill="black"/>
                      <path d="M57.2162 4.95215H59.5853V19.0506H57.2162V17.1943H57.1962C56.9717 17.8393 56.5774 18.3595 56.011 18.7537C55.4447 19.1492 54.741 19.3463 53.8977 19.3463C52.5416 19.3463 51.4288 18.8398 50.5605 17.8255C49.6922 16.8125 49.2568 15.5088 49.2568 13.9157C49.2568 12.3363 49.6872 11.0501 50.5505 10.0558C51.4126 9.06155 52.5279 8.56503 53.8977 8.56503C54.7273 8.56503 55.4384 8.77212 56.0298 9.18755C56.6223 9.60174 57.0166 10.1057 57.2149 10.6983V4.95215H57.2162ZM54.4716 17.4513C55.4322 17.4513 56.157 17.1257 56.6436 16.4744C57.1301 15.8232 57.3746 14.9712 57.3746 13.917V13.7985C57.3484 12.8117 57.0752 12.0045 56.555 11.3795C56.0348 10.7545 55.3411 10.4413 54.4716 10.4413C53.5896 10.4413 52.8822 10.7744 52.3495 11.4381C51.8168 12.1031 51.5498 12.9289 51.5498 13.9157C51.5498 14.93 51.8131 15.7721 52.3395 16.4433C52.866 17.1157 53.5758 17.4513 54.4716 17.4513Z" fill="black"/>
                      <path d="M70.5834 15.7535C70.3463 16.8987 69.8161 17.7808 68.994 18.3995C68.1719 19.0183 67.1414 19.3277 65.9039 19.3277C64.3507 19.3277 63.067 18.8312 62.054 17.8369C61.0397 16.8439 60.5332 15.5501 60.5332 13.957C60.5332 12.3377 61.0397 11.0353 62.054 10.0472C63.067 9.06043 64.3507 8.56641 65.9039 8.56641C67.1539 8.56641 68.1906 8.88578 69.014 9.52452C69.8361 10.1633 70.3463 11.0153 70.5447 12.082H68.3528C67.9448 10.9505 67.1152 10.3841 65.8652 10.3841C64.9832 10.3841 64.2496 10.7097 63.6633 11.3609C63.0769 12.0121 62.785 12.8779 62.785 13.957C62.785 15.0237 63.0782 15.882 63.6633 16.5345C64.2484 17.1857 64.9832 17.5113 65.8652 17.5113C67.1951 17.5113 68.0371 16.9262 68.3927 15.7535H70.5834V15.7535Z" fill="black"/>
                      <path d="M80.1241 16.7001C80.1241 17.8191 80.1902 18.6026 80.3212 19.0505H77.9908C77.9247 18.7086 77.8922 18.2545 77.8922 17.6882V17.3925H77.8723C77.6614 17.9327 77.2922 18.3868 76.767 18.7548C76.2405 19.1228 75.5294 19.3075 74.6349 19.3075C73.5296 19.3075 72.6538 19.0118 72.0088 18.4192C71.3639 17.8266 71.042 17.1093 71.042 16.2672C71.042 15.9117 71.0944 15.586 71.2004 15.2904C71.3052 14.9947 71.4375 14.744 71.5959 14.5394C71.7543 14.336 71.9639 14.1514 72.2272 13.9867C72.4904 13.822 72.7337 13.6935 72.9582 13.6012C73.1815 13.5089 73.4585 13.4241 73.7878 13.3442C74.1172 13.2656 74.3829 13.2132 74.5875 13.1858C74.7909 13.1596 75.0478 13.1234 75.3572 13.0772C75.6666 13.0311 75.8737 13.0024 75.9798 12.9887C76.7033 12.8701 77.2011 12.7317 77.4706 12.5745C77.74 12.416 77.8748 12.1341 77.8748 11.7249C77.8748 11.2908 77.7001 10.9489 77.3521 10.6982C77.0027 10.4487 76.5199 10.3227 75.9012 10.3227C75.3348 10.3227 74.8744 10.4674 74.5189 10.7568C74.1633 11.0462 73.9725 11.448 73.9463 11.9607H71.7144C71.7668 11.0388 72.1523 10.2391 72.8696 9.56167C73.587 8.88425 74.5838 8.54492 75.8612 8.54492C78.7044 8.54492 80.1266 9.9534 80.1266 12.7703V16.7001H80.1241ZM77.9322 14.351V13.2843C77.7999 13.6137 77.5504 13.8894 77.1824 14.1139C76.8131 14.3385 76.2343 14.5219 75.4446 14.6666C74.7073 14.7988 74.1671 14.9822 73.8253 15.2193C73.4822 15.4563 73.3113 15.7919 73.3113 16.226C73.3113 16.634 73.4822 16.9696 73.8253 17.2328C74.1671 17.496 74.6274 17.6283 75.2075 17.6283C75.971 17.6283 76.616 17.3488 77.1425 16.7887C77.6689 16.2298 77.9322 15.4164 77.9322 14.351Z" fill="black"/>
                      <path d="M87.1084 11.9019C87.0298 11.3754 86.8053 10.9775 86.4373 10.7068C86.068 10.4373 85.6338 10.3025 85.1336 10.3025C84.6857 10.3025 84.2977 10.4248 83.9684 10.6681C83.639 10.9113 83.4744 11.2108 83.4744 11.5663C83.4744 11.8033 83.5367 12.0079 83.6615 12.1789C83.7862 12.3498 84.0033 12.502 84.3127 12.633C84.6221 12.7652 84.9053 12.8638 85.1623 12.9286C85.4193 12.9947 85.8235 13.0933 86.3761 13.2243C88.4421 13.6859 89.4763 14.6465 89.4763 16.1074C89.4763 17.0942 89.0683 17.8776 88.2524 18.4565C87.4365 19.0366 86.4423 19.3248 85.2708 19.3248C84.1256 19.3248 83.1487 19.0453 82.3391 18.4852C81.5294 17.9263 81.0716 17.073 80.9668 15.9277H83.2373C83.4344 17.0206 84.1256 17.567 85.3107 17.567C85.8372 17.567 86.2813 17.4547 86.6431 17.2314C87.0049 17.0081 87.1858 16.6725 87.1858 16.2246C87.1858 15.803 87.0149 15.5011 86.6718 15.3164C86.3287 15.1318 85.7374 14.9409 84.8941 14.7438C84.7356 14.7039 84.6171 14.6777 84.5385 14.6652C82.3528 14.1649 81.2612 13.1644 81.2612 11.6636C81.2612 10.7554 81.643 10.0119 82.4065 9.43177C83.17 8.85291 84.0919 8.56348 85.171 8.56348C86.3163 8.56348 87.2569 8.84916 87.9942 9.42178C88.7315 9.99441 89.1594 10.8203 89.2779 11.8994H87.1084V11.9019Z" fill="black"/>
                      <path d="M95.3477 10.6198H93.3528V15.5364C93.3528 16.7078 93.7408 17.2942 94.5181 17.2942H95.1306V19.052H94.044C92.0691 19.052 91.0823 17.9728 91.0823 15.8134V10.6198H89.5029V8.84209H91.0823V6.55161L93.2742 5.44629H93.3528V8.84209H95.3477V10.6198Z" fill="black"/>
                      <path fill-rule="evenodd" clip-rule="evenodd" d="M10.339 12.0004C10.339 6.28999 5.7104 1.66139 0 1.66139V0.185547C6.52549 0.185547 11.8148 5.4749 11.8148 12.0004C11.8148 18.5259 6.52549 23.8152 0 23.8152V22.3394C5.7104 22.3394 10.339 17.7108 10.339 12.0004Z" fill="#FF4200"/>
                      <path fill-rule="evenodd" clip-rule="evenodd" d="M5.90773 12.0008C5.90773 8.73804 3.26272 6.09303 0 6.09303V4.61719C4.07781 4.61719 7.38357 7.92295 7.38357 12.0008C7.38357 16.0784 4.07799 19.3856 0 19.3856V17.9097C3.26254 17.9097 5.90773 15.2637 5.90773 12.0008Z" fill="#FF4200"/>
                  </svg>
                </div>
                <div class="flex flex-col gap-y-5 max-w-[866px] mb-7 revealUp">
                  <h1 class="text-4xl lg:text-5xl xl:text-7xl font-black">Content <span class="text-primary">Studio</span></h1>
                  <p class="text-lg xl:text-[36px] max-w-lg xl:max-w-5xl leading-[1.5]">The first <span class="font-bold">AI-powered</span> studio to turn your events into a multi-channel content strategy</p>
                </div>
                <div class="flex flex-col sm:flex-row gap-x-4 gap-y-2 revealUp">
                  <div class="input-container">
                    <input class="px-6 rounded-full email-input" type="text" id="email" name="email" placeholder="Enter your email">
                  </div>
                  <a href="/" class="primary-button px-9 py-2.5">Join Waitlist</a>
                </div>
              </div>
            </div>
            <div class="hidden xl:flex justify-center pb-9">
              <a href="#join-the-waitlist" class="flex flex-col items-center w-fit">
                <i class="gg-arrow-long-down mb-11"></i>
                <div class="primary-button px-9 py-2.5 w-fit h-fit">Join Waitlist</div>
              </a>
            </div>
          </div>
        </div>
        <div class="second-fold">
          <div class="container">
            <div class="pt-16 pb-32 3xl:pb-40">
              <div class="mb-8 lg:mb-16 revealUp">
                <h4 class="text-lg xl:text-4xl font-bold max-w-xl xl:max-w-6xl sm:text-center mx-auto">B2B brands know events are where authentic moments 🤌 happen. But they are lost in archives after the event is over.</h4>
              </div>
              <img class="max-w-full mx-auto revealUp" src="@/static/assets/b2b-brands.svg" alt="">
            </div>
            <div class="mb-5 lg:mb-14">
                <h2 class="text-3xl xl:text-6xl font-black sm:text-center mb-4 lg:mb-8 revealUp">Meet your  <span class="text-primary">Content Studio</span></h2>
                <h4 class="text-lg xl:text-4xl font-bold max-w-xl xl:max-w-6xl sm:text-center mx-auto revealUp">Get more out of your events by creating always-on easily consumable content - in minutes, not weeks</h4>
            </div>
            <div class="pb-8 xl:pb-20 hidden md:block revealUp">
              <div class="tabs flex text-black text-md xl:text-2xl font-bold justify-between px-20 max-w-6xl mx-auto py-4">
                <div class="">Event Marketer</div>
                <div class="">Demand Gen Marketer</div>
                <div class="">Content Marketer</div>
              </div>
            </div>
            <div class="flex sm:justify-center pb-7 lg:mb-0 revealUp">
              <a href="/" class="primary-button px-9 py-2.5 w-fit h-fit">Join Waitlist</a>
            </div>
          </div>
        </div>
        <div class="third-fold bg-body-bg">
          <div class="container">
            <div class="flex flex-col xl:flex-row items-center justify-center gap-x-9 max-w-7xl mx-auto">
              <div class="py-7 xl:py-20 min-w-[260px] xl:min-w-[340px] xl:min-h-[460px] h-full max-w-sm revealUp">
                <div class="bg-white p-8 rounded-bl-2xl flex flex-col justify-between h-[280px] md:h-[300px] rounded-br-2xl rounded-tr-2xl">
                  <div>
                    <div class="flex justify-between mb-5">
                      <img src="@/static/assets/quote.svg" alt="">
                      <img src="@/static/assets/logo/drift.svg" alt="">
                    </div>
                    <div class="text-base 2xl:text-lg font-semibold mb-11">
                      Without you showing me anything else, I would like to buy this.
                    </div>
                  </div>
                  <div class="flex gap-x-4">
                    <div class="max-w-[55px]">
                      <img src="@/static/assets/testimonial/justin-keller.png" alt="">
                    </div>
                    <div class="flex flex-col text-sm gap-y-0.5">
                      <div class="text-sm lg:text-base">Justin Keller</div>
                      <div class="text-sm lg:text-base">SVP, Marketing</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="py-7 xl:py-20 min-w-[260px] h-full max-w-sm revealUp">
                <div class="bg-white p-8 rounded-bl-2xl flex flex-col justify-between h-[280px] md:h-[300px] rounded-br-2xl rounded-tr-2xl">
                  <div>
                    <div class="flex justify-between mb-5">
                      <img src="@/static/assets/quote.svg" alt="">
                      <img src="@/static/assets/logo/cognism.svg" alt="">
                    </div>
                    <div class="text-base 2xl:text-lg font-semibold mb-11">
                      This is going to save atleast 8 hours every week for our video and content teams.
                    </div>
                  </div>
                  <div class="flex gap-x-4">
                    <div class="max-w-[55px]">
                      <img src="@/static/assets/testimonial/ashleigh-frank.png" alt="">
                    </div>
                    <div class="flex flex-col text-sm gap-y-0.5">
                      <div class="text-sm lg:text-base">Ashleigh Frank</div>
                      <div class="text-sm lg:text-base">Senior Demand Gen Executive</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="py-7 xl:py-20 min-w-[260px] h-full max-w-sm revealUp">
                <div class="bg-white p-8 rounded-bl-2xl flex flex-col justify-between h-[280px] md:h-[300px] rounded-br-2xl rounded-tr-2xl">
                  <div>
                    <div class="flex justify-between mb-5">
                      <img src="@/static/assets/quote.svg" alt="">
                      <img src="@/static/assets/logo/snaplogic.svg" alt="">
                    </div>
                    <div class="text-base 2xl:text-lg font-semibold mb-11">
                      We are so excited about this, especially streamlining all the post event activities.
                    </div>
                  </div>
                  <div class="flex gap-x-4">
                    <div class="max-w-[55px]">
                      <img src="@/static/assets/testimonial/davi-schmidt.png" alt="">
                    </div>
                    <div class="flex flex-col text-sm gap-y-0.5">
                      <div class="text-sm lg:text-base">Davi Schmidt</div>
                      <div class="text-sm lg:text-base">Director, Demand Generation</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="relative">
          <div class="fourth-fold"></div>
          <div class="container relative">
            <div class="pt-24 xl:pt-10 pb-32 revealUp">
              <div class="flex flex-col lg:items-center justify-center gap-y-4 lg:gap-y-8 xl:gap-y-4 mb-4 lg:mb-14 xl:mb-10">
                <h3 class="sm:text-center text-primary text-3xl font-bold"> AI suggested video clips</h3>
                <p class="max-w-2xl sm:text-center text-lg">Instantaneous video highlights maximized for social sharing, without having to rewatch the whole event</p>
              </div>
              <div class="flex sm:justify-center">
                <video autoplay width="998" class="max-w-[270px] sm:max-w-lg xl:max-w-4xl rounded-3xl border-[10px] xl:border-[24px] border-[rgba(255,255,255,0.5)] bg-[rgba(255,255,255,0.5)] object-cover">
                    <source src="https://content-lab.goldcast.io/videos/vid-ai.mp4" type="video/mp4">
                </video>         
              </div>
            </div>
            <div class="pb-32 revealUp">
              <div class="flex flex-col lg:items-center justify-center gap-y-4 lg:gap-y-8 xl:gap-y-4 mb-4 lg:mb-14 xl:mb-10">
                <h3 class="sm:text-center text-primary text-3xl font-bold">Video Clip Editor</h3>
                <p class="max-w-2xl sm:text-center text-lg">Clip interesting moments that follow your brand guidelines all in your browser. As easy as editing a document.</p>
              </div>
              <div class="flex sm:justify-center">
                <video src="https://content-lab.goldcast.io/videos/vid-editor.mp4" width="998" class="max-w-[270px] sm:max-w-lg xl:max-w-4xl rounded-3xl border-[10px] xl:border-[24px] border-[rgba(255,255,255,0.5)] bg-[rgba(255,255,255,0.5)] object-cover"></video>
              </div>
            </div>
            <div class="pb-32 revealUp">
              <div class="flex flex-col lg:items-center justify-center gap-y-4 lg:gap-y-8 xl:gap-y-4 mb-4 lg:mb-14 xl:mb-10">
                <h3 class="sm:text-center text-primary text-3xl font-bold">Insightful SEO-rich blog posts</h3>
                <p class="max-w-2xl sm:text-center text-lg">Boost organic traffic by easily extracting and summarizing event takeaways into a digestible blog post.</p>
              </div>
              <div class="flex sm:justify-center">
                <video src="https://content-lab.goldcast.io/videos/vid-blog.mp4" width="998" class="max-w-[270px] sm:max-w-lg xl:max-w-4xl rounded-3xl border-[10px] xl:border-[24px] border-[rgba(255,255,255,0.5)] bg-[rgba(255,255,255,0.5)] object-cover"></video>
              </div>
            </div>
            <div class="revealUp">
              <div class="flex flex-col lg:items-center justify-center gap-y-4 lg:gap-y-8 xl:gap-y-4 mb-4 lg:mb-14 xl:mb-10">
                <h3 class="sm:text-center text-primary text-3xl font-bold">On-demand embeddable player</h3>
                <p class="max-w-2xl sm:text-center text-lg">Auto-generate key event moments and make them available on-demand through our embeddable video player.</p>
              </div>
              <div class="flex sm:justify-center">
                <video src="https://content-lab.goldcast.io/videos/vid-player.mp4" width="960" class="max-w-[270px] sm:max-w-lg xl:max-w-4xl rounded-3xl border-[10px] xl:border-[24px] border-[rgba(255,255,255,0.5)] bg-[rgba(255,255,255,0.5)] object-cover"></video>
              </div>
            </div>
          </div>
        </div>
        <div class="fifth-fold pt-32">
          <div class="container">
            <div class="flex justify-center mb-9 xl:mb-8 revealUp">
              <h3 class="text-black text-3xl font-bold">And many more..</h3>
            </div>
            <div>
              <div class="pb-28">
                <div class="flex flex-col lg:flex-row gap-y-8 xl:gap-x-12 sm:items-center justify-center">
                  <div class="revealUp max-w-sm sm:max-w-xs 2xl:max-w-[23rem] 3xl:max-w-sm rounded-[2.5rem] xl:rounded-3xl 2xl:rounded-[3.5rem] flex justify-center">
                    <div class="flex flex-col items-center relative">
                      <svg id="eMlTuqQS9eP1" class="w-72 h-60 md:h-60 lg:h-56 xl:h-64 2xl:w-96 2xl:h-80" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 361 317" shape-rendering="geometricPrecision" text-rendering="geometricPrecision"><defs><linearGradient id="eMlTuqQS9eP6-fill" x1="224.17" y1="52.1299" x2="224.17" y2="157.02" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP6-fill-0" offset="0%" stop-color="#ff7c68"/><stop id="eMlTuqQS9eP6-fill-1" offset="61%" stop-color="#e43c64"/><stop id="eMlTuqQS9eP6-fill-2" offset="91%" stop-color="#da2363"/></linearGradient><linearGradient id="eMlTuqQS9eP10-fill" x1="199.64" y1="59.2999" x2="199.64" y2="164.19" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP10-fill-0" offset="0%" stop-color="rgba(255,255,255,0.81)"/><stop id="eMlTuqQS9eP10-fill-1" offset="21%" stop-color="rgba(255,255,255,0.81)"/><stop id="eMlTuqQS9eP10-fill-2" offset="40%" stop-color="rgba(255,255,255,0.72)"/><stop id="eMlTuqQS9eP10-fill-3" offset="59%" stop-color="rgba(255,255,255,0.51)"/><stop id="eMlTuqQS9eP10-fill-4" offset="77%" stop-color="rgba(255,255,255,0.12)"/><stop id="eMlTuqQS9eP10-fill-5" offset="93%" stop-color="rgba(255,255,255,0)"/></linearGradient><linearGradient id="eMlTuqQS9eP11-stroke" x1="199.64" y1="61.7799" x2="199.64" y2="138.53" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP11-stroke-0" offset="0%" stop-color="rgba(255,255,255,0.45)"/><stop id="eMlTuqQS9eP11-stroke-1" offset="2%" stop-color="rgba(255,255,255,0.42)"/><stop id="eMlTuqQS9eP11-stroke-2" offset="9%" stop-color="rgba(255,255,255,0.31)"/><stop id="eMlTuqQS9eP11-stroke-3" offset="17%" stop-color="rgba(255,255,255,0.23)"/><stop id="eMlTuqQS9eP11-stroke-4" offset="26%" stop-color="rgba(255,255,255,0.16)"/><stop id="eMlTuqQS9eP11-stroke-5" offset="38%" stop-color="rgba(255,255,255,0.11)"/><stop id="eMlTuqQS9eP11-stroke-6" offset="54%" stop-color="rgba(255,255,255,0.09)"/><stop id="eMlTuqQS9eP11-stroke-7" offset="100%" stop-color="rgba(255,255,255,0.08)"/></linearGradient><radialGradient id="eMlTuqQS9eP12-fill" cx="0" cy="0" r="1" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="matrix(-20.8419 0.352881 -0.031071 -1.83514 212.792 107.551)"><stop id="eMlTuqQS9eP12-fill-0" offset="0%" stop-color="#b1b1b0"/><stop id="eMlTuqQS9eP12-fill-1" offset="15%" stop-color="rgba(152,152,151,0.81)"/><stop id="eMlTuqQS9eP12-fill-2" offset="44%" stop-color="rgba(106,106,105,0.47)"/><stop id="eMlTuqQS9eP12-fill-3" offset="69%" stop-color="rgba(73,73,72,0.21)"/><stop id="eMlTuqQS9eP12-fill-4" offset="89%" stop-color="rgba(52,52,51,0.06)"/><stop id="eMlTuqQS9eP12-fill-5" offset="100%" stop-color="rgba(45,45,44,0)"/></radialGradient><radialGradient id="eMlTuqQS9eP13-fill" cx="0" cy="0" r="1" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="matrix(-20.8419 0.352881 -0.031071 -1.83514 192.126 57.2497)"><stop id="eMlTuqQS9eP13-fill-0" offset="0%" stop-color="#b1b1b0"/><stop id="eMlTuqQS9eP13-fill-1" offset="15%" stop-color="rgba(152,152,151,0.81)"/><stop id="eMlTuqQS9eP13-fill-2" offset="44%" stop-color="rgba(106,106,105,0.47)"/><stop id="eMlTuqQS9eP13-fill-3" offset="69%" stop-color="rgba(73,73,72,0.21)"/><stop id="eMlTuqQS9eP13-fill-4" offset="89%" stop-color="rgba(52,52,51,0.06)"/><stop id="eMlTuqQS9eP13-fill-5" offset="100%" stop-color="rgba(45,45,44,0)"/></radialGradient><linearGradient id="eMlTuqQS9eP15-fill" x1="2.137" y1="0" x2="2.137" y2="8.7549" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP15-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP15-fill-1" offset="36.9587%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP15-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="eMlTuqQS9eP16-fill" x1="2.136" y1="0" x2="2.136" y2="22.5126" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP16-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP16-fill-1" offset="36.9587%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP16-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="eMlTuqQS9eP17-fill" x1="2.137" y1="0" x2="2.137" y2="22.5126" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP17-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP17-fill-1" offset="36.9587%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP17-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="eMlTuqQS9eP18-fill" x1="2.136" y1="0" x2="2.136" y2="27.5154" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP18-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP18-fill-1" offset="36.9587%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP18-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="eMlTuqQS9eP19-fill" x1="2.136" y1="0" x2="2.136" y2="7.5042" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP19-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP19-fill-1" offset="36.9587%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP19-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="eMlTuqQS9eP20-fill" x1="2.136" y1="0" x2="2.136" y2="3.7521" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP20-fill-0" offset="0%" stop-color="#fd4507"/><stop id="eMlTuqQS9eP20-fill-1" offset="63.0413%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP20-fill-2" offset="100%" stop-color="rgba(253,69,7,0)"/></linearGradient><linearGradient id="eMlTuqQS9eP21-fill" x1="2.136" y1="0" x2="2.136" y2="47.526" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP21-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP21-fill-1" offset="36.9587%" stop-color="rgba(251,68,7,0.42)"/><stop id="eMlTuqQS9eP21-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="eMlTuqQS9eP22-fill" x1="2.136" y1="0" x2="2.136" y2="35.0192" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eMlTuqQS9eP22-fill-0" offset="0%" stop-color="rgba(253,69,7,0)"/><stop id="eMlTuqQS9eP22-fill-1" offset="36.9587%" stop-color="rgba(253,69,7,0.420354)"/><stop id="eMlTuqQS9eP22-fill-2" offset="100%" stop-color="#fd4507"/></linearGradient></defs><g><path d="M50.7302,0C23.116,0,0.730225,22.3858,0.730225,50v217c0,27.614,22.385775,50,49.999975,50h259.9998c27.614,0,50-22.386,50-50v-217c0-27.6142-22.386-50-50-50L50.7302,0ZM184.23,153c28.443,0,51.5-23.057,51.5-51.5c0-28.4427-23.057-51.5-51.5-51.5-28.442,0-51.5,23.0573-51.5,51.5c0,28.443,23.058,51.5,51.5,51.5Z" clip-rule="evenodd" fill="#fff" fill-opacity="0.6" fill-rule="evenodd"/></g><g transform="translate(0-.254163)" mask="url(#eMlTuqQS9eP7)"><g><path d="M203.79,55.1899h40.18c14.54,0,26.79,11.9,26.51,26.43-.27,14.09-11.77,25.4301-25.93,25.4301h-.48v22.74c0,.96-1.23,1.35-1.79.57l-16.45-23.3h-21.46c-14.54,0-26.79-11.9001-26.51-26.4301.27-14.09,11.77-25.43,25.93-25.43v-.01Z" fill="url(#eMlTuqQS9eP6-fill)"/></g><mask id="eMlTuqQS9eP7" mask-type="luminance" x="-150%" y="-150%" height="400%" width="400%"><path d="M243.97,55.1899h-40.18c-6.94,0-13.24,2.73-17.9,7.17h34.13c14.15,0,25.66,11.34,25.93,25.43.21,11-6.76,20.4801-16.46,24.4501l12.79,18.12c.55.78,1.79.39,1.79-.57v-22.74h.48c14.15,0,25.66-11.3401,25.93-25.4301.28-14.54-11.97-26.43-26.51-26.43Z" transform="translate(.000001 0)" fill="#fff"/></mask></g><g><path d="M220.03,62.3599h-40.18c-14.54,0-26.79,11.9-26.51,26.43.27,14.0901,11.77,25.4301,25.93,25.4301h.48v22.74c0,.96,1.23,1.35,1.79.57l16.45-23.3h21.46c14.54,0,26.79-11.9,26.51-26.4301-.27-14.09-11.77-25.43-25.93-25.43v-.01Z" fill="url(#eMlTuqQS9eP10-fill)"/><path d="M220.03,62.3599h-40.18c-14.54,0-26.79,11.9-26.51,26.43.27,14.0901,11.77,25.4301,25.93,25.4301h.48v22.74c0,.96,1.23,1.35,1.79.57l16.45-23.3h21.46c14.54,0,26.79-11.9,26.51-26.4301-.27-14.09-11.77-25.43-25.93-25.43v-.01Z" fill="none" stroke="url(#eMlTuqQS9eP11-stroke)" stroke-width="1.16" stroke-linecap="round" stroke-linejoin="round"/></g><path style="mix-blend-mode:color-dodge" d="M193.17,114.35c.02,1.01,9.13,1.68,20.35,1.49s20.31-1.17,20.29-2.18-9.13-1.68-20.35-1.49-20.31,1.17-20.29,2.18Z" fill="url(#eMlTuqQS9eP12-fill)"/><path style="mix-blend-mode:color-dodge" d="M172.47,62.7099c.02,1.01,9.13,1.68,20.35,1.49s20.31-1.17,20.29-2.18-9.13-1.68-20.35-1.49-20.31,1.17-20.29,2.18Z" fill="url(#eMlTuqQS9eP13-fill)"/><g transform="translate(.000001 0)"><rect id="eMlTuqQS9eP15" width="4.27273" height="7.92" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 175.73 98.2105)" fill="url(#eMlTuqQS9eP15-fill)"/><rect id="eMlTuqQS9eP16" width="4.27273" height="20.37" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 182.852 101.1842)" fill="url(#eMlTuqQS9eP16-fill)"/><rect id="eMlTuqQS9eP17" width="4.27273" height="20.37" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 211.353635 102.1842)" fill="url(#eMlTuqQS9eP17-fill)"/><rect id="eMlTuqQS9eP18" width="4.27273" height="25" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 189.973 102.078885)" fill="url(#eMlTuqQS9eP18-fill)"/><rect id="eMlTuqQS9eP19" width="4.27273" height="6.79" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 218.458 92.728628)" fill="url(#eMlTuqQS9eP19-fill)"/><rect id="eMlTuqQS9eP20" width="4.27273" height="3.39474" rx="1.69737" ry="1.69737" transform="translate(218.458 94.1578)" fill="url(#eMlTuqQS9eP20-fill)"/><rect id="eMlTuqQS9eP21" width="4.27273" height="43" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 197.513629 110)" fill="url(#eMlTuqQS9eP21-fill)"/><rect id="eMlTuqQS9eP22" width="4.27273" height="31.68" rx="2.13636" ry="2.13636" transform="matrix(1 0 0-1 204.215 104.0262)" fill="url(#eMlTuqQS9eP22-fill)"/></g></svg>
                      <div class="w-full absolute bottom-0">
                        <h3 class="w-full px-10 pb-8 2xl:px-14 2xl:pb-12 mx-auto text-center text-base 2xl:text-xl font-bold">AI transcripts in <span class="text-primary">50+ languages</span></h3>
                      </div>
                    </div>
                  </div>
                  <div class="revealUp max-w-sm sm:max-w-xs 2xl:max-w-[23rem] 3xl:max-w-sm rounded-[2.5rem] xl:rounded-3xl 2xl:rounded-[3.5rem] flex justify-center">
                    <div class="flex flex-col items-center relative">
                      <svg id="epbloRDC0mK1" class="w-72 h-60 md:h-60 lg:h-56 xl:h-64 2xl:w-96 2xl:h-80" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 361 318" shape-rendering="geometricPrecision" text-rendering="geometricPrecision"><defs><linearGradient id="epbloRDC0mK6-fill" x1="203.71" y1="107.689" x2="263.7" y2="49.8693" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK6-fill-0" offset="0%" stop-color="#ff7c68"/><stop id="epbloRDC0mK6-fill-1" offset="18%" stop-color="#f05966"/><stop id="epbloRDC0mK6-fill-2" offset="36%" stop-color="#e43b64"/><stop id="epbloRDC0mK6-fill-3" offset="52%" stop-color="#ff4c00"/><stop id="epbloRDC0mK6-fill-4" offset="63%" stop-color="#fd4507"/></linearGradient><linearGradient id="epbloRDC0mK10-fill" x1="202.66" y1="62.7794" x2="202.66" y2="159.499" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK10-fill-0" offset="0%" stop-color="rgba(255,255,255,0.35)"/><stop id="epbloRDC0mK10-fill-1" offset="21%" stop-color="rgba(255,255,255,0.88)"/><stop id="epbloRDC0mK10-fill-2" offset="40%" stop-color="rgba(255,255,255,0.63)"/><stop id="epbloRDC0mK10-fill-3" offset="59%" stop-color="rgba(255,255,255,0.69)"/><stop id="epbloRDC0mK10-fill-4" offset="77%" stop-color="rgba(255,255,255,0.55)"/><stop id="epbloRDC0mK10-fill-5" offset="93%" stop-color="rgba(255,255,255,0.72)"/></linearGradient><radialGradient id="epbloRDC0mK11-fill" cx="0" cy="0" r="1" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="matrix(-20.8419 0.352881 -0.031071 -1.83514 177.144 72.7996)"><stop id="epbloRDC0mK11-fill-0" offset="0%" stop-color="#b1b1b0"/><stop id="epbloRDC0mK11-fill-1" offset="15%" stop-color="rgba(152,152,151,0.81)"/><stop id="epbloRDC0mK11-fill-2" offset="44%" stop-color="rgba(106,106,105,0.47)"/><stop id="epbloRDC0mK11-fill-3" offset="69%" stop-color="rgba(73,73,72,0.21)"/><stop id="epbloRDC0mK11-fill-4" offset="89%" stop-color="rgba(52,52,51,0.06)"/><stop id="epbloRDC0mK11-fill-5" offset="100%" stop-color="rgba(45,45,44,0)"/></radialGradient><radialGradient id="epbloRDC0mK12-fill" cx="0" cy="0" r="1" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="matrix(-20.8419 0.352881 -0.031071 -1.83514 227.168 126.09)"><stop id="epbloRDC0mK12-fill-0" offset="0%" stop-color="#b1b1b0"/><stop id="epbloRDC0mK12-fill-1" offset="15%" stop-color="rgba(152,152,151,0.81)"/><stop id="epbloRDC0mK12-fill-2" offset="44%" stop-color="rgba(106,106,105,0.47)"/><stop id="epbloRDC0mK12-fill-3" offset="69%" stop-color="rgba(73,73,72,0.21)"/><stop id="epbloRDC0mK12-fill-4" offset="89%" stop-color="rgba(52,52,51,0.06)"/><stop id="epbloRDC0mK12-fill-5" offset="100%" stop-color="rgba(45,45,44,0)"/></radialGradient><linearGradient id="epbloRDC0mK13-fill" x1="202.66" y1="71.5193" x2="202.66" y2="124.099" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK13-fill-0" offset="0%" stop-color="#fff"/><stop id="epbloRDC0mK13-fill-1" offset="21%" stop-color="#fff"/><stop id="epbloRDC0mK13-fill-2" offset="40%" stop-color="rgba(255,255,255,0.45)"/><stop id="epbloRDC0mK13-fill-3" offset="59%" stop-color="rgba(255,255,255,0.41)"/><stop id="epbloRDC0mK13-fill-4" offset="77%" stop-color="rgba(255,255,255,0.08)"/><stop id="epbloRDC0mK13-fill-5" offset="93%" stop-color="rgba(255,255,255,0.02)"/></linearGradient><linearGradient id="epbloRDC0mK13-stroke" x1="202.66" y1="30.5693" x2="202.66" y2="124.789" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK13-stroke-0" offset="0%" stop-color="rgba(255,255,255,0.45)"/><stop id="epbloRDC0mK13-stroke-1" offset="2%" stop-color="rgba(255,255,255,0.42)"/><stop id="epbloRDC0mK13-stroke-2" offset="9%" stop-color="rgba(255,255,255,0.31)"/><stop id="epbloRDC0mK13-stroke-3" offset="17%" stop-color="rgba(255,255,255,0.23)"/><stop id="epbloRDC0mK13-stroke-4" offset="26%" stop-color="rgba(255,255,255,0.16)"/><stop id="epbloRDC0mK13-stroke-5" offset="38%" stop-color="rgba(255,255,255,0.11)"/><stop id="epbloRDC0mK13-stroke-6" offset="54%" stop-color="#fd4507"/><stop id="epbloRDC0mK13-stroke-7" offset="100%" stop-color="#fd4507"/></linearGradient><linearGradient id="epbloRDC0mK17-fill" x1="0" y1="0.5" x2="1" y2="0.5" spreadMethod="pad" gradientUnits="objectBoundingBox" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK17-fill-0" offset="0%" stop-color="#f34d15"/><stop id="epbloRDC0mK17-fill-1" offset="100%" stop-color="#fff"/></linearGradient><linearGradient id="epbloRDC0mK18-fill" x1="0" y1="0.5" x2="1" y2="0.5" spreadMethod="pad" gradientUnits="objectBoundingBox" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK18-fill-0" offset="0%" stop-color="#f34d15"/><stop id="epbloRDC0mK18-fill-1" offset="100%" stop-color="#fff"/></linearGradient><linearGradient id="epbloRDC0mK19-fill" x1="0.50148" y1="1.19491" x2="0.50148" y2="-0.21472" spreadMethod="pad" gradientUnits="objectBoundingBox" gradientTransform="translate(0 0)"><stop id="epbloRDC0mK19-fill-0" offset="0%" stop-color="#fff"/><stop id="epbloRDC0mK19-fill-1" offset="100%" stop-color="rgba(255,255,255,0)"/></linearGradient></defs><g><path d="M50.7302,0.709351C23.116,0.709351,0.730225,23.0951,0.730225,50.7094v216.9996c0,27.615,22.385775,50,49.999975,50h259.9998c27.614,0,50-22.385,50-50v-216.9996c0-27.6143-22.386-50.000049-50-50.000049h-259.9998ZM184.23,153.709c28.443,0,51.5-23.057,51.5-51.5c0-28.4423-23.057-51.4996-51.5-51.4996-28.442,0-51.5,23.0573-51.5,51.4996c0,28.443,23.058,51.5,51.5,51.5Z" clip-rule="evenodd" fill="#fff" fill-opacity="0.6" fill-rule="evenodd"/></g><g transform="translate(.140823 2.499997)" mask="url(#epbloRDC0mK7)"><g><path d="M256.72,66.7094h-77.78c-2.612,0-4.73,2.1176-4.73,4.73v45.2696c0,2.613,2.118,4.73,4.73,4.73h77.78c2.613,0,4.73-2.117,4.73-4.73v-45.2696c0-2.6124-2.117-4.73-4.73-4.73Z" fill="url(#epbloRDC0mK6-fill)" fill-opacity="0.9"/></g><mask id="epbloRDC0mK7" mask-type="luminance" x="-150%" y="-150%" height="400%" width="400%"><path d="M255.95,66.7094h-76.23c-3.04,0-5.51,2.46-5.51,5.51v5.87h66.57c3.04,0,5.51,2.46,5.51,5.5099v37.8397h9.67c3.04,0,5.51-2.46,5.51-5.51v-43.7096c0-3.04-2.46-5.51-5.51-5.51h-.01Z" fill="#fff"/></mask></g><g><path d="M241.55,78.0894h-77.78c-2.612,0-4.73,2.1176-4.73,4.73v45.2696c0,2.613,2.118,4.73,4.73,4.73h77.78c2.613,0,4.73-2.117,4.73-4.73v-45.2696c0-2.6124-2.117-4.73-4.73-4.73Z" fill="url(#epbloRDC0mK10-fill)" fill-opacity="0.5"/></g><path style="mix-blend-mode:color-dodge" d="M156.73,78.4393c.02,1.01,9.13,1.68,20.35,1.49s20.31-1.17,20.29-2.18-9.13-1.68-20.35-1.49-20.31,1.17-20.29,2.18Z" fill="url(#epbloRDC0mK11-fill)"/><path style="mix-blend-mode:color-dodge" d="M206.82,133.159c.02,1.01,9.13,1.68,20.35,1.49s20.31-1.17,20.29-2.18-9.13-1.68-20.35-1.49-20.31,1.17-20.29,2.18Z" fill="url(#epbloRDC0mK12-fill)"/><path id="epbloRDC0mK13" d="M202.66,123.939l42.860815-43.982191c-1-1.02-3.210815-1.877509-4.750815-1.877509h-76.22c-1.54,0-3.57127.493024-4.255357,1.357695L202.66,123.939Z" transform="matrix(1 0 0 1.000001 0.04525 0.083268)" fill="url(#epbloRDC0mK13-fill)" stroke="url(#epbloRDC0mK13-stroke)" stroke-width="1.16" stroke-opacity="0.4" stroke-linecap="round" stroke-linejoin="bevel" stroke-miterlimit="10"/><g transform="translate(.000001 0.000001)"><path id="epbloRDC0mK15" d="M170.990289,89.670233l15.869299,17.038616l16.704524,17.372707l16.704525-17.873843l16.370435-17.038617-65.648783.501137Z" transform="translate(-.610131-.028658)" opacity="0" fill="#fff" stroke-width="0.722"/><g id="epbloRDC0mK16" transform="translate(0-29.999999)" opacity="0"><rect width="52.058212" height="4.004478" rx="2" ry="2" transform="translate(177.125959 96.567586)" fill="url(#epbloRDC0mK17-fill)" stroke-width="0"/><rect width="52.058212" height="4.004478" rx="2" ry="2" transform="matrix(.804184 0 0 1 177.514123 104.735338)" fill="url(#epbloRDC0mK18-fill)" stroke-width="0"/></g></g><path d="M160.62,79.739303l42.04,44.199694L244.7,79.95681q1.58-.154388,1.58,7.021131c0,7.175519,0,37.7202,0,41.111059s-1.743802,4.380021-4.30374,4.72501-73.47626-.000001-78.20626-.000001-4.73-3.799277-4.73-7.591777-.000001-37.173055-.000001-41.327993q0-4.154938,1.580001-4.154936Z" transform="translate(.163831 0.000002)" fill="url(#epbloRDC0mK19-fill)" stroke-width="0.722"/></svg>
                      <div class="w-full absolute bottom-0">
                        <h3 class="w-full px-10 pb-8 2xl:px-14 2xl:pb-12 mx-auto text-center text-base 2xl:text-xl font-bold">Auto-generated post event <span class="text-primary">email</span></h3>
                      </div>
                  </div>
                  </div>
                  <div class="revealUp max-w-sm sm:max-w-xs 2xl:max-w-[23rem] 3xl:max-w-sm rounded-[2.5rem] xl:rounded-3xl 2xl:rounded-[3.5rem] flex justify-center">
                    <div class="flex flex-col items-center relative">
                      <svg id="eka9IbBxHS21" class="w-72 h-60 md:h-60 lg:h-56 xl:h-64 2xl:w-96 2xl:h-80" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 361 318" shape-rendering="geometricPrecision" text-rendering="geometricPrecision"><defs><linearGradient id="eka9IbBxHS26-fill" x1="204.71" y1="107.398" x2="264.7" y2="49.5785" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eka9IbBxHS26-fill-0" offset="0%" stop-color="#ff7c68"/><stop id="eka9IbBxHS26-fill-1" offset="18%" stop-color="#f05966"/><stop id="eka9IbBxHS26-fill-2" offset="36%" stop-color="#e43b64"/><stop id="eka9IbBxHS26-fill-3" offset="52%" stop-color="#ff4c00"/><stop id="eka9IbBxHS26-fill-4" offset="63%" stop-color="#fd4507"/></linearGradient><linearGradient id="eka9IbBxHS211-fill" x1="203.66" y1="62.4886" x2="203.66" y2="159.209" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eka9IbBxHS211-fill-0" offset="0%" stop-color="rgba(255,255,255,0.35)"/><stop id="eka9IbBxHS211-fill-1" offset="21%" stop-color="rgba(255,255,255,0.88)"/><stop id="eka9IbBxHS211-fill-2" offset="40%" stop-color="rgba(255,255,255,0.63)"/><stop id="eka9IbBxHS211-fill-3" offset="59%" stop-color="rgba(255,255,255,0.69)"/><stop id="eka9IbBxHS211-fill-4" offset="77%" stop-color="rgba(255,255,255,0.55)"/><stop id="eka9IbBxHS211-fill-5" offset="93%" stop-color="rgba(255,255,255,0.72)"/></linearGradient><radialGradient id="eka9IbBxHS212-fill" cx="0" cy="0" r="1" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="matrix(-20.8419 0.352881 -0.031071 -1.83514 178.144 72.5088)"><stop id="eka9IbBxHS212-fill-0" offset="0%" stop-color="#b1b1b0"/><stop id="eka9IbBxHS212-fill-1" offset="15%" stop-color="rgba(152,152,151,0.81)"/><stop id="eka9IbBxHS212-fill-2" offset="44%" stop-color="rgba(106,106,105,0.47)"/><stop id="eka9IbBxHS212-fill-3" offset="69%" stop-color="rgba(73,73,72,0.21)"/><stop id="eka9IbBxHS212-fill-4" offset="89%" stop-color="rgba(52,52,51,0.06)"/><stop id="eka9IbBxHS212-fill-5" offset="100%" stop-color="rgba(45,45,44,0)"/></radialGradient><radialGradient id="eka9IbBxHS213-fill" cx="0" cy="0" r="1" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="matrix(-20.8419 0.352881 -0.031071 -1.83514 228.168 125.799)"><stop id="eka9IbBxHS213-fill-0" offset="0%" stop-color="#b1b1b0"/><stop id="eka9IbBxHS213-fill-1" offset="15%" stop-color="rgba(152,152,151,0.81)"/><stop id="eka9IbBxHS213-fill-2" offset="44%" stop-color="rgba(106,106,105,0.47)"/><stop id="eka9IbBxHS213-fill-3" offset="69%" stop-color="rgba(73,73,72,0.21)"/><stop id="eka9IbBxHS213-fill-4" offset="89%" stop-color="rgba(52,52,51,0.06)"/><stop id="eka9IbBxHS213-fill-5" offset="100%" stop-color="rgba(45,45,44,0)"/></radialGradient><linearGradient id="eka9IbBxHS214-stroke" x1="176.73" y1="86.4185" x2="176.73" y2="106.418" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eka9IbBxHS214-stroke-0" offset="0%" stop-color="#fd4507"/><stop id="eka9IbBxHS214-stroke-1" offset="100%" stop-color="rgba(253,69,7,0)"/></linearGradient><linearGradient id="eka9IbBxHS215-stroke" x1="176.73" y1="111.418" x2="176.73" y2="131.418" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eka9IbBxHS215-stroke-0" offset="0%" stop-color="#fd4507"/><stop id="eka9IbBxHS215-stroke-1" offset="100%" stop-color="rgba(253,69,7,0)"/></linearGradient><linearGradient id="eka9IbBxHS216-fill" x1="0.331" y1="3.5" x2="40.382" y2="3.2808" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eka9IbBxHS216-fill-0" offset="0%" stop-color="#fd4507"/><stop id="eka9IbBxHS216-fill-1" offset="100%" stop-color="rgba(253,69,7,0)"/></linearGradient><linearGradient id="eka9IbBxHS217-fill" x1="0.331" y1="3.5" x2="40.382" y2="3.281" spreadMethod="pad" gradientUnits="userSpaceOnUse" gradientTransform="translate(0 0)"><stop id="eka9IbBxHS217-fill-0" offset="0%" stop-color="#fd4507"/><stop id="eka9IbBxHS217-fill-1" offset="100%" stop-color="rgba(253,69,7,0)"/></linearGradient></defs><g><path d="M50.7302,0.418457C23.116,0.418457,0.730225,22.8042,0.730225,50.4185v216.9995c0,27.615,22.385775,50,49.999975,50h259.9998c27.614,0,50-22.385,50-50v-216.9995c0-27.6143-22.386-50.000043-50-50.000043h-259.9998ZM184.23,153.418c28.443,0,51.5-23.057,51.5-51.5c0-28.4422-23.057-51.4995-51.5-51.4995-28.442,0-51.5,23.0573-51.5,51.4995c0,28.443,23.058,51.5,51.5,51.5Z" clip-rule="evenodd" fill="#fff" fill-opacity="0.6" fill-rule="evenodd"/></g><g mask="url(#eka9IbBxHS27)"><g><path d="M257.72,66.4185h-77.78c-2.612,0-4.73,2.1176-4.73,4.73v45.2695c0,2.613,2.118,4.73,4.73,4.73h77.78c2.613,0,4.73-2.117,4.73-4.73v-45.2695c0-2.6124-2.117-4.73-4.73-4.73Z" fill="url(#eka9IbBxHS26-fill)" fill-opacity="0.9"/></g><mask id="eka9IbBxHS27" mask-type="luminance" x="-150%" y="-150%" height="400%" width="400%"><path d="M256.95,66.4185h-76.23c-3.04,0-5.51,2.46-5.51,5.51v5.87h66.57c3.04,0,5.51,2.46,5.51,5.51v37.8395h9.67c3.04,0,5.51-2.46,5.51-5.51v-43.7095c0-3.04-2.46-5.51-5.51-5.51h-.01Z" fill="#fff"/></mask></g><g transform="translate(0 0.004899)"><g><path d="M242.55,77.7986h-77.78c-2.612,0-4.73,2.1177-4.73,4.73v45.2704c0,2.612,2.118,4.73,4.73,4.73h77.78c2.613,0,4.73-2.118,4.73-4.73v-45.2704c0-2.6123-2.117-4.73-4.73-4.73Z" fill="url(#eka9IbBxHS211-fill)" fill-opacity="0.72"/></g></g><path style="mix-blend-mode:color-dodge" d="M157.73,78.1485c.02,1.01,9.13,1.68,20.35,1.49s20.31-1.17,20.29-2.18-9.13-1.68-20.35-1.49-20.31,1.17-20.29,2.18Z" fill="url(#eka9IbBxHS212-fill)"/><path style="mix-blend-mode:color-dodge" d="M207.82,132.868c.02,1.01,9.13,1.68,20.35,1.49s20.31-1.17,20.29-2.18-9.13-1.68-20.35-1.49-20.31,1.17-20.29,2.18Z" fill="url(#eka9IbBxHS213-fill)"/><path id="eka9IbBxHS214" d="M168.73,93.0851l5.189,5.3334l10.811-12" fill="none" stroke="url(#eka9IbBxHS214-stroke)" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" stroke-dasharray="23.592871"/><path id="eka9IbBxHS215" d="M168.73,118.085l5.189,5.333l10.811-12" fill="none" stroke="url(#eka9IbBxHS215-stroke)" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" stroke-dasharray="23.592584"/><rect id="eka9IbBxHS216" width="47" height="5" rx="2.5" ry="2.5" transform="translate(194.73 93.4185)" fill="url(#eka9IbBxHS216-fill)"/><rect id="eka9IbBxHS217" width="47" height="5" rx="2.5" ry="2.5" transform="translate(194.73 112.418)" fill="url(#eka9IbBxHS217-fill)"/></svg>
                      <div class="w-full absolute bottom-0">
                        <h3 class="w-full px-10 pb-8 2xl:px-14 2xl:pb-12 mx-auto text-center text-base 2xl:text-xl font-bold">Auto-generated <span class="text-primary">summaries </span>for executives and sales teams</h3>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="fifth-fold py-20">
          <div id="join-the-waitlist" class="revealUp container">
            <div class="flex flex-col items-center gap-y-6 xl:gap-y-14">
              <div class="w-fit">
                <h3 class="text-center text-primary text-3xl font-bold w-fit">Join the Waitlist</h3>
              </div>
              <div class="w-fit">
                <img class="max-w-[270px] sm:max-w-[460px] xl:max-w-xl" src="@/static/assets/sample-form.png" alt="">
              </div>
            </div>
          </div>
        </div>
        <div class="sixth-fold py-20 xl:py-36">
          <div class="container">
            <div class="flex justify-center mb-8 revealUp">
              <h3 class="text-black text-3xl font-bold">Frequently Asked Questions</h3>
            </div>
            <div class="max-w-3xl mx-auto">
              <div class="revealUp">
                <button class="accordion cursor-pointer py-5 xl:p-5 w-full text-left outline-none transition-all text-lg font-bold capitalize active border-t border-t-gray-400 flex justify-between">
                  <span>When will the product be available in general availability?</span>
                  <span class="hidden md:block">
                    <svg width="12" height="13" viewBox="0 0 12 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path class="horizontal" d="M0 6.40332H12" stroke="#FF4200"/>
                      <path class="vertical" d="M6 0.40332V12.4033" stroke="#FF4200"/>
                    </svg>
                  </span>
                </button>
                <div class="panel active text-lg text-gray-500 xl:px-5 max-h-0 overflow-hidden transition-all" style="max-height: max-content;">
                  <p>The product is expected to be available for all customers in fall of 2023.</p>
                </div>
              </div>
              <div class="revealUp">
                <button class="accordion cursor-pointer py-5 xl:p-5 w-full text-left outline-none transition-all text-lg font-bold capitalize border-t border-t-gray-400 flex justify-between">
                  <span>Why is the waitlist there in the first place?</span>
                  <span class="hidden md:block">
                    <svg width="12" height="13" viewBox="0 0 12 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path class="horizontal" d="M0 6.40332H12" stroke="#FF4200"/>
                      <path class="vertical" d="M6 0.40332V12.4033" stroke="#FF4200"/>
                    </svg>
                  </span>
                </button>
                <div class="panel text-lg text-gray-500 xl:px-5 max-h-0 overflow-hidden transition-all">
                  <p>There are a lot of AI based products that don't generate useful output. We want to roll the product out slowly, at the right pace, and get enough feedback on the output quality before we release in general availability.</p>
                </div>
              </div>
              <div class="revealUp">
                <button class="accordion cursor-pointer py-5 xl:p-5 w-full text-left outline-none transition-all text-lg font-bold capitalize border-t border-t-gray-400 flex justify-between">
                  <span>What happens once I sign up for a waitlist?</span>
                  <span class="hidden md:block">
                    <svg width="12" height="13" viewBox="0 0 12 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path class="horizontal" d="M0 6.40332H12" stroke="#FF4200"/>
                      <path class="vertical" d="M6 0.40332V12.4033" stroke="#FF4200"/>
                    </svg>
                  </span>
                </button>
                <div class="panel text-lg text-gray-500 xl:px-5 max-h-0 overflow-hidden transition-all">
                  <p>Signing up for the waitlist grants you early access to our Content Studio. We’ll roll out out the invites slowly and onboard customers by batches.</p>
                </div>
              </div>
              <div class="xl:pl-5 pt-6 border-t border-t-gray-400 revealUp">
                <p class="mb-4 text-gray-500">More questions?</p>
                <a class="py-2 text-blue-700 font-semibold group flex items-center gap-x-2 transition-all" href="">
                  Visit Help Center 
                  <span>
                    <svg class="flex relative max-w-[16px] -left-1 group-hover:left-0 transition-all" width="100%" height="100%" viewBox="0 0 14 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path class="arrow -left-1 group-hover:block" d="M10.755 5.47889L6.86484 1.58877L7.771 0.682617L13.2079 6.11954L7.771 11.5565L6.86484 10.6503L10.755 6.76019L11.4747 6.11954L10.755 5.47889Z" fill="#1F43FD"/>
                      <path class="line hidden group-hover:block" d="M1.44999 5.47896L10.777 5.47896L11.4968 6.11961L10.777 6.76027L1.44999 6.76027L1.44999 5.47896Z" fill="#1F43FD"/>
                    </svg>
                  </span>
                </a>
              </div>
            </div>
          </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  mounted(){
    (function(s,i,u,o,c,w,d,t,n,x,e,p,a,b){(a=Array.from(d.querySelectorAll('svg#' + i.root)).filter(n=> !n.svgatorPlayer)[0]||{}).svgatorPlayer={ready:(function(a){b=[];return function(c){return c?(b.push(c),a.svgatorPlayer):b}})(a)};w[o]=w[o]||{};w[o][s]=w[o][s]||[];w[o][s].push(i);e=d.createElementNS(n,t);e.async=true;e.setAttributeNS(x,'href',[u,s,'.','j','s','?','v','=',c].join(''));e.setAttributeNS(null,'src',[u,s,'.','j','s','?','v','=',c].join(''));p=d.getElementsByTagName(t)[0];p.parentNode.insertBefore(e,p);})('91c80d77',{"root":"eMlTuqQS9eP1","version":"2022-05-04","animations":[{"elements":{"eMlTuqQS9eP15":{"#size":[{"t":100,"v":{"width":4.27273,"height":7.92}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":500,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":800,"v":{"width":4.27273,"height":9},"e":[0,0,0.58,1]},{"t":900,"v":{"width":4.27273,"height":7.92}}]},"eMlTuqQS9eP16":{"#size":[{"t":100,"v":{"width":4.27273,"height":20.37}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":400,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":800,"v":{"width":4.27273,"height":22},"e":[0,0,0.58,1]},{"t":900,"v":{"width":4.27273,"height":20.37}}]},"eMlTuqQS9eP17":{"#size":[{"t":100,"v":{"width":4.27273,"height":20.37}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":400,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":700,"v":{"width":4.27273,"height":23},"e":[0,0,0.58,1]},{"t":800,"v":{"width":4.27273,"height":20.37}}]},"eMlTuqQS9eP18":{"#size":[{"t":100,"v":{"width":4.27273,"height":25}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":300,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":700,"v":{"width":4.27273,"height":27},"e":[0,0,0.58,1]},{"t":800,"v":{"width":4.27273,"height":25}}]},"eMlTuqQS9eP19":{"#size":[{"t":100,"v":{"width":4.27273,"height":6.79}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":500,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":700,"v":{"width":4.27273,"height":7},"e":[0,0,0.58,1]},{"t":800,"v":{"width":4.27273,"height":6.79}}]},"eMlTuqQS9eP20":{"transform":{"data":{"o":{"x":220.594365,"y":97.55254,"type":"corner"},"t":{"x":-2.136365,"y":-3.39474}},"keys":{"s":[{"t":100,"v":{"x":1,"y":1}},{"t":200,"v":{"x":1,"y":0},"e":[0,0,0.58,1]},{"t":500,"v":{"x":1,"y":0},"e":[0,0,0.58,1]},{"t":700,"v":{"x":1,"y":1.1},"e":[0,0,0.58,1]},{"t":800,"v":{"x":1,"y":1}}]}}},"eMlTuqQS9eP21":{"#size":[{"t":100,"v":{"width":4.27273,"height":43}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":600,"v":{"width":4.27273,"height":45},"e":[0,0,0.58,1]},{"t":700,"v":{"width":4.27273,"height":43}}]},"eMlTuqQS9eP22":{"#size":[{"t":100,"v":{"width":4.27273,"height":31.68}},{"t":200,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":300,"v":{"width":4.27273,"height":0},"e":[0,0,0.58,1]},{"t":700,"v":{"width":4.27273,"height":35},"e":[0,0,0.58,1]},{"t":800,"v":{"width":4.27273,"height":31.68}}]}},"s":"MDSA1ZGNiNzJiNTGM1YzJiMWM0EYjliZmJlNzIA4YTg1ODM4MDUgwTTdjNzJiNIGI5YzJiNVJiQM2M0YjliZmJVlNzI4YTgxN2VM3MmI5YzRiNTWMyYjFjNEtiHOWJmYmVjMzcWyOGE4MDdjNzKJiNmI5YmNJYImM3MjhhODE3HYzcyYjFiY2MI0SmI1YzJiZWYIxYzRiNTcyOBGFiNmIxVmJjXYzNiNTdjNzJRjM2MwYjViNWAI0NzI4YTgxUQDdjNzJiNmMwXYzM3MjhhODET4MDgwY2Q/"}],"options":"MDSAxZTk4M2Y5MKDkxN2U4ZjkxAM2ZENTczZjkJwODA4ZjhjODDk4OTNmNDlJMC2Y5MDgwOGY4JY1E4OTg5M2YN1NzRmNTI5YQO|"},'https://cdn.svgator.com/ply/','__SVGATOR_PLAYER__','2022-05-04',window,document,'script','http://www.w3.org/2000/svg','http://www.w3.org/1999/xlink');
    (function(s,i,u,o,c,w,d,t,n,x,e,p,a,b){(a=Array.from(d.querySelectorAll('svg#' + i.root)).filter(n=> !n.svgatorPlayer)[0]||{}).svgatorPlayer={ready:(function(a){b=[];return function(c){return c?(b.push(c),a.svgatorPlayer):b}})(a)};w[o]=w[o]||{};w[o][s]=w[o][s]||[];w[o][s].push(i);e=d.createElementNS(n,t);e.async=true;e.setAttributeNS(x,'href',[u,s,'.','j','s','?','v','=',c].join(''));e.setAttributeNS(null,'src',[u,s,'.','j','s','?','v','=',c].join(''));p=d.getElementsByTagName(t)[0];p.parentNode.insertBefore(e,p);})('91c80d77',{"root":"epbloRDC0mK1","version":"2022-05-04","animations":[{"elements":{"epbloRDC0mK13":{"transform":{"data":{"o":{"x":202.70525,"y":78.177645,"type":"corner"},"t":{"x":-202.66,"y":-78.094299}},"keys":{"s":[{"t":1200,"v":{"x":1,"y":1.000001}},{"t":1500,"v":{"x":1,"y":-0.040626}},{"t":1800,"v":{"x":1,"y":-1}},{"t":3000,"v":{"x":1,"y":-1}},{"t":3300,"v":{"x":1,"y":0.040626}},{"t":3600,"v":{"x":1,"y":1}}]}}},"epbloRDC0mK15":{"d":[{"t":1500,"v":["M",170.990289,89.670233,"L",186.859588,106.708849,"L",203.564112,124.081556,"L",220.268637,106.207713,"L",236.639072,89.169096,"L",170.990289,89.670233,"Z"]},{"t":1800,"v":["M",170.990289,89.670233,"L",170.8351,132.45138,"L",236.506668,132.45138,"L",236.506668,108.794831,"L",236.639072,89.169096,"L",170.990289,89.670233,"Z"]},{"t":2600,"v":["M",170.990289,89.670233,"L",170.8351,132.45138,"L",236.506668,132.45138,"L",236.506668,108.794831,"L",236.639072,89.169096,"L",170.990289,89.670233,"Z"]},{"t":2800,"v":["M",170.990289,89.670233,"L",186.859588,106.708849,"L",203.564112,124.081556,"L",220.268637,106.207713,"L",236.639072,89.169096,"L",170.990289,89.670233,"Z"]}],"transform":{"data":{"t":{"x":-203.81468,"y":-106.625326}},"keys":{"o":[{"t":1500,"v":{"x":203.204549,"y":106.596668,"type":"corner"}},{"t":1800,"v":{"x":203.204549,"y":76.596668,"type":"corner"}},{"t":2000,"v":{"x":203.204549,"y":96.596668,"type":"corner"}},{"t":2400,"v":{"x":203.155083,"y":92.653706,"type":"corner"}},{"t":2600,"v":{"x":203.155083,"y":72.653706,"type":"corner"}},{"t":2800,"v":{"x":203.204549,"y":106.596668,"type":"corner"}}]}},"opacity":[{"t":1200,"v":0},{"t":1500,"v":1},{"t":2600,"v":1},{"t":3400,"v":1},{"t":3500,"v":0.59},{"t":3600,"v":0}]},"epbloRDC0mK16":{"transform":{"data":{"t":{"x":-203.155083,"y":-102.653705}},"keys":{"o":[{"t":1800,"v":{"x":203.155083,"y":72.653706,"type":"corner"}},{"t":2000,"v":{"x":203.155083,"y":92.653706,"type":"corner"}},{"t":2400,"v":{"x":203.155083,"y":92.653706,"type":"corner"}},{"t":2600,"v":{"x":203.155083,"y":72.653706,"type":"corner"}},{"t":2800,"v":{"x":203.204549,"y":106.596668,"type":"corner"}}]}},"opacity":[{"t":1500,"v":0},{"t":1700,"v":0},{"t":1800,"v":1},{"t":2600,"v":1},{"t":2800,"v":0}]}},"s":"MDXA1ZDlmNDY4OBDk5OTY4NTk4WTThkOTM5MjQD2NWVINTk1NzOU0NTQ1MDQ2OVDg4ZDk2ODk4AN045ODhkOTMX5MjQ2NWU1NTUUwNDY4ZDk4OTDk5Njg1OTg4PZDkzOTI5N0oN0NjVlNTQ1MDVQ2TDhhOGQ5MIEs5MDQ2NWU1DNTUwNDY4NTkTwOTg4OTk2OTQI4NTk4ODk0NDjVlOGE4NTkwIOTc4OTUwNDYC5Nzk0ODk4OTEg4NDY1ZTU1NQTA0NjhhOTQ5MNzQ2NWU1NTUO0RDU0YTE/"}],"options":"MDMAxZTk2M2Q4ZHThmN2M4ZDhmRM2RSNTVSM2QF4ZTdlOGQ4YTXg3ODczZDQ3MA2Q4ZTdlOGQ4MYTg3ODczZDUP1NGQ1MDk4"},'https://cdn.svgator.com/ply/','__SVGATOR_PLAYER__','2022-05-04',window,document,'script','http://www.w3.org/2000/svg','http://www.w3.org/1999/xlink');
    (function(s,i,u,o,c,w,d,t,n,x,e,p,a,b){(a=Array.from(d.querySelectorAll('svg#' + i.root)).filter(n=> !n.svgatorPlayer)[0]||{}).svgatorPlayer={ready:(function(a){b=[];return function(c){return c?(b.push(c),a.svgatorPlayer):b}})(a)};w[o]=w[o]||{};w[o][s]=w[o][s]||[];w[o][s].push(i);e=d.createElementNS(n,t);e.async=true;e.setAttributeNS(x,'href',[u,s,'.','j','s','?','v','=',c].join(''));e.setAttributeNS(null,'src',[u,s,'.','j','s','?','v','=',c].join(''));p=d.getElementsByTagName(t)[0];p.parentNode.insertBefore(e,p);})('91c80d77',{"root":"eka9IbBxHS21","version":"2022-05-04","animations":[{"elements":{"eka9IbBxHS214":{"opacity":[{"t":3600,"v":1},{"t":3700,"v":0},{"t":4400,"v":0},{"t":4500,"v":1}],"stroke-dashoffset":[{"t":3600,"v":0},{"t":4400,"v":23.592871},{"t":4800,"v":0}]},"eka9IbBxHS215":{"opacity":[{"t":3600,"v":1},{"t":3700,"v":0},{"t":4700,"v":0},{"t":4800,"v":1}],"stroke-dashoffset":[{"t":3600,"v":0},{"t":4700,"v":23.592584},{"t":5100,"v":0}]},"eka9IbBxHS216":{"#size":[{"t":3600,"v":{"width":47,"height":5}},{"t":3700,"v":{"width":0,"height":5}},{"t":4000,"v":{"width":0,"height":5}},{"t":4300,"v":{"width":47,"height":5}}]},"eka9IbBxHS217":{"#size":[{"t":3600,"v":{"width":47,"height":5}},{"t":3700,"v":{"width":0,"height":5}},{"t":4200,"v":{"width":0,"height":5}},{"t":4600,"v":{"width":47,"height":5}}]}},"s":"MDNA1ZGNkNzRiNQmM3YzRiM2M2AYmJjMWMwNzRYEOGM4Nzg1ODOI4MjdlNzRiNEmJiYzRiN09iBNWM2YmJjMWMOwNzQ4YzgzN2BU3NGJiYzZiNP2M0YjNjNmJiOYzFjMGM1NzQF4YzgyN2U3NGMI4YmJiZWJlNGzQ4YzgzN2U3VNGIzYmVjNmIE3QWM0YzBiM2XM2R2I3NzQ4YY1NiOGIzYmVjWNWI3N2U3NGMI1YzJiN2I3YjGY3NFg4YzgzNO2U3NGI4YzJXTYzU3NDhjODMD4MjgyY2Y/"}],"options":"MDJAxZThlMzU4NKjg3NzQ4NTg3BMzU0ZDM1ODYM3Njg1UzgyN2GZMN2YzNTNmMNzU4Njc2ODU4SMjdmN2YzNTRYkNDU0OFQ5MAB|"},'https://cdn.svgator.com/ply/','__SVGATOR_PLAYER__','2022-05-04',window,document,'script','http://www.w3.org/2000/svg','http://www.w3.org/1999/xlink');

    var acc = document.getElementsByClassName("accordion");
    var i;

    acc[0].classList.add("active");
    var firstPanel = acc[0].nextElementSibling;
    firstPanel.style.maxHeight = firstPanel.scrollHeight + "px";
    firstPanel.classList.add("active");

    for (i = 0; i < acc.length; i++) {
      acc[i].addEventListener("click", function() {
        var isActive = this.classList.contains("active");

        // Close all accordions and remove active class from panels
        for (var j = 0; j < acc.length; j++) {
          acc[j].classList.remove("active");
          var panel = acc[j].nextElementSibling;
          panel.style.maxHeight = null;
          panel.classList.remove("active");
        }

        // Toggle current accordion and set icon to minus
        if (!isActive) {
          this.classList.add("active");
          var panel = this.nextElementSibling;
          panel.style.maxHeight = panel.scrollHeight + "px";
          panel.classList.add("active");
        }
      });
    }
  }
}
</script>

<style lang="scss">
.hero {
  background-image: url('@/static/assets/bg/hero-bg.svg');
  background-size: cover;
  background-position: bottom;
  width: 100%;
  height: 100%; 
}

.hero-bg{
  background: rgba(255, 255, 255, 0.39);
  backdrop-filter: blur(12px);
}

.second-fold {
  background-image: url('@/static/assets/bg/second-fold.svg');
  background-size: cover;
  background-position: top;
  width: 100%;
  height: 100%; 
}

.fourth-fold {
  background-image: url('@/static/assets/bg/fourth-fold.svg');
  background-size: cover;
  background-position: top;
  position: absolute;
  width: 100%;
  height: 100%; 
  opacity: 0.5;
}

.fifth-fold {
  background-image: url('@/static/assets/bg/fifth-fold.svg');
  background-size: cover;
  background-position: top;
}

.sixth-fold {
  background-image: url('@/static/assets/bg/sixth-fold.svg');
  background-size: cover;
  background-position: top;
}

.card-bg {
  background-image: url('@/static/assets/bg/card-bg.svg');
  background-size: cover;
  background-position: top;
  width: 100%;
}

.panel.active{
  margin-bottom: 32px;
}


.primary-button{
  position: relative;
  border: double 2px transparent;
  border-radius: 80px;
  background-image: linear-gradient(#000, #000), linear-gradient(to right, #FF4C00 0%, #01FFF0 50%, #0005FF 100%);
  background-origin: border-box;
  background-clip: padding-box, border-box;
  font-size: 19px;
  color: #fff;
  width: 190px;
  transition: 0.5s;

  &:after {
    content: '»';
    position: absolute;
    opacity: 0;  
    font-size: 23px;
    top: 6px;
    color: 10px;
    right: 20px;
    transition: 0.5s;
  }

  &:hover{
    padding-right: 4px;
    padding-left:30px;
  }

  &:hover:after {
    opacity: 1;
    right: 26px;
  }
}

.email-input{ 
  width: 240px;
  height: 100%;
  padding: 8px 20px;
  border: double 2px transparent;
  border-radius: 80px;
  background-image: linear-gradient(white, white), linear-gradient(to right, #FD4507 0%, #6D49FF 50%, #CCBAFF 100%);
  background-origin: border-box;
  background-clip: padding-box, border-box;
  font-size: 19px;
  color: #575757;

  &::placeholder {
    color: #575757;
  }
}

.tabs{
  border: double 3px transparent;
  border-radius: 80px;
  background-image: linear-gradient(#FFFFFF, #FFFFFF), linear-gradient(to right, #5EFFF5 0%, #8D6BFA 50%, #FF4D47 100%);
  background-origin: border-box;
  background-clip: padding-box, border-box;
  font-size: 16px;
  backdrop-filter: blur(50px);

  @media (min-width: 1280px){
    font-size: 19px;
  }
}

.gg-arrow-long-down {
    box-sizing: border-box;
    position: relative;
    display: block;
    transform: scale(var(--ggs,1));
    border-right: 2px solid transparent;
    border-left: 2px solid transparent;
    box-shadow: inset 0 0 0 2px;
    height: 32px;
    width: 6px
}
.gg-arrow-long-down::after {
    content: "";
    display: block;
    box-sizing: border-box;
    position: absolute;
    width: 8px;
    height: 8px;
    border-bottom: 2px solid;
    border-right: 2px solid;
    transform: rotate(45deg);
    bottom: 0;
    left: -3px
}


.card3-img{
  margin-right: 2rem;

  @media (min-width: 375px){
     margin-right: 3rem;
  }
}

.accordion{
  .vertical{
    transform: rotate(0deg);
    transform-origin: center;
    transition: 0.5s;
  }
}

.accordion.active{
  .vertical{
    transform: rotate(90deg);
    transform-origin: center;
    transition: 0.5s;
  }
}
</style>