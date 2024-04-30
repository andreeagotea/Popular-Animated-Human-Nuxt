<template>
  <div class="thq-section-padding"
    ><div class="team1-max-width thq-section-max-width"
      ><div class="team1-section-title"
        ><span class="thq-body-small team1-text">{{ content1 }}</span
        ><div class="team1-content"
          ><h2 class="thq-heading-2 team1-text01">{{ heading1 }}</h2
          ><p class="thq-body-large team1-text02">{{ content2 }}</p></div
        ></div
      ><div class="team1-content01"
        ><div class="team1-content02"
          ><div class="team1-row"
            ><div class="team1-container"
              ><div class="team1-card"
                ><img
                  :alt="member1Alt"
                  :src="member1Src"
                  class="team1-placeholder-image thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content03"
                  ><div class="team1-title"
                    ><span class="team1-text03 thq-body-small">{{ member1 }}</span
                    ><span class="team1-text04 thq-body-small"
                      >{{ member1Job }}</span
                    ></div
                  ><span class="team1-text05 thq-body-small"
                    >{{ member1Content }}</span
                  ></div
                ><div class="team1-social-icons"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div
              ><div class="team1-card1"
                ><img
                  :alt="member2Alt"
                  :src="member2Src"
                  class="team1-placeholder-image1 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content04"
                  ><div class="team1-title1"
                    ><span class="team1-text06 thq-body-small">{{ member2 }}</span
                    ><span class="team1-text07 thq-body-small"
                      >{{ member2Job }}</span
                    ></div
                  ><span class="team1-text08 thq-body-small"
                    >{{ member2Content }}</span
                  ></div
                ><div class="team1-social-icons1"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div></div
            ><div class="team1-container1"
              ><div class="team1-card2"
                ><img
                  :alt="member3Alt"
                  :src="member3Src"
                  class="team1-placeholder-image2 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content05"
                  ><div class="team1-title2"
                    ><span class="team1-text09 thq-body-small">{{ member3 }}</span
                    ><span class="team1-text10 thq-body-small"
                      >{{ member3Job }}</span
                    ></div
                  ><span class="team1-text11 thq-body-small"
                    >{{ member3Content }}</span
                  ></div
                ><div class="team1-social-icons2"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div
              ><div class="team1-card3"
                ><img
                  :alt="member4Alt"
                  :src="member4Src"
                  class="team1-placeholder-image3 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content06"
                  ><div class="team1-title3"
                    ><span class="team1-text12 thq-body-small">{{ member4 }}</span
                    ><span class="team1-text13 thq-body-small"
                      >{{ member4Job }}</span
                    ></div
                  ><span class="team1-text14 thq-body-small"
                    >{{ member4Content }}</span
                  ></div
                ><div class="team1-social-icons3"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div></div></div
          ><div class="team1-row1"
            ><div class="team1-container2"
              ><div class="team1-card4"
                ><img
                  :alt="member5Alt"
                  :src="member5Src"
                  class="team1-placeholder-image4 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content07"
                  ><div class="team1-title4"
                    ><span class="team1-text15 thq-body-small">{{ member5 }}</span
                    ><span class="team1-text16 thq-body-small"
                      >{{ member5Job }}</span
                    ></div
                  ><span class="team1-text17 thq-body-small"
                    >{{ member5Content }}</span
                  ></div
                ><div class="team1-social-icons4"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div
              ><div class="team1-card5"
                ><img
                  :alt="member6Alt"
                  :src="member6Src"
                  class="team1-placeholder-image5 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content08"
                  ><div class="team1-title5"
                    ><span class="team1-text18 thq-body-small">{{ member6 }}</span
                    ><span class="team1-text19 thq-body-small"
                      >{{ member6Job }}</span
                    ></div
                  ><span class="team1-text20 thq-body-small"
                    >{{ member6Content }}</span
                  ></div
                ><div class="team1-social-icons5"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div></div
            ><div class="team1-container3"
              ><div class="team1-card6"
                ><img
                  :alt="member7Alt"
                  :src="member7Src"
                  class="team1-placeholder-image6 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content09"
                  ><div class="team1-title6"
                    ><span class="team1-text21 thq-body-small">{{ member7 }}</span
                    ><span class="team1-text22 thq-body-small"
                      >{{ member7Job }}</span
                    ></div
                  ><span class="team1-text23 thq-body-small"
                    >{{ member7Content }}</span
                  ></div
                ><div class="team1-social-icons6"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div
              ><div class="team1-card7"
                ><img
                  :alt="member8Alt"
                  :src="member8Src"
                  class="team1-placeholder-image7 thq-img-round thq-img-ratio-1-1" /><div
                  class="team1-content10"
                  ><div class="team1-title7"
                    ><span class="team1-text24 thq-body-small">{{ member8 }}</span
                    ><span class="team1-text25 thq-body-small"
                      >{{ member8Job }}</span
                    ></div
                  ><span class="team1-text26 thq-body-small"
                    >{{ member8Content }}</span
                  ></div
                ><div class="team1-social-icons7"
                  ><svg
                    viewBox="0 0 877.7142857142857 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                    ></path></svg
                  ><svg
                    viewBox="0 0 950.8571428571428 1024"
                    class="thq-icon-small"
                  >
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg></div></div></div></div></div
        ><div class="team1-content11"
          ><div class="team1-content12"
            ><h2 class="thq-heading-2 team1-text27">{{ heading2 }}</h2
            ><span class="thq-body-small team1-text28">{{ content3 }}</span></div
          ><button class="team1-button thq-button-filled"
            ><span class="thq-body-small">{{ actionContent }}</span></button
          ></div
        ></div
      ></div
    ></div
  >
</template>

<script>
export default {
  name: 'Team1',
  props: {
    member3Alt: {
      type: String,
      default: 'Member Alt',
    },
    actionContent: {
      type: String,
      default: 'Open positions',
    },
    member6: {
      type: String,
      default: 'Full name',
    },
    member5Job: {
      type: String,
      default: 'Job title',
    },
    member3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDJ8fHVzZXJ8ZW58MHx8fHwxNzEwOTQyNjEyfDA&ixlib=rb-4.0.3&w=500',
    },
    member6Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    content2: {
      type: String,
      default: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. ',
    },
    member8Alt: {
      type: String,
      default: 'Member Alt',
    },
    member5: {
      type: String,
      default: 'Full name',
    },
    member4Alt: {
      type: String,
      default: 'Member Alt',
    },
    member1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDF8fHVzZXJ8ZW58MHx8fHwxNzEwOTQyNjEyfDA&ixlib=rb-4.0.3&w=500',
    },
    member5Alt: {
      type: String,
      default: 'Member Alt',
    },
    member2: {
      type: String,
      default: 'Full name',
    },
    member4Job: {
      type: String,
      default: 'Job title',
    },
    member2Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    member7Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    member1: {
      type: String,
      default: 'Full name',
    },
    member6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1619895862022-09114b41f16f?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDE2fHx1c2VyfGVufDB8fHx8MTcxMDk0MjYxMnww&ixlib=rb-4.0.3&w=500',
    },
    content3: {
      type: String,
      default: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. ',
    },
    member2Job: {
      type: String,
      default: 'Job title',
    },
    member7Job: {
      type: String,
      default: 'Job title',
    },
    member4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDV8fHVzZXJ8ZW58MHx8fHwxNzEwOTQyNjEyfDA&ixlib=rb-4.0.3&w=500',
    },
    member7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1560250097-0b93528c311a?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDd8fHVzZXJ8ZW58MHx8fHwxNzEwOTQyNjEyfDA&ixlib=rb-4.0.3&w=500',
    },
    member4: {
      type: String,
      default: 'Full name',
    },
    member3: {
      type: String,
      default: 'Full name',
    },
    member7Alt: {
      type: String,
      default: 'Member Alt',
    },
    member3Job: {
      type: String,
      default: 'Job title',
    },
    member7: {
      type: String,
      default: 'Full name',
    },
    member8: {
      type: String,
      default: 'Full name',
    },
    member1Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    member3Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    member2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDN8fHVzZXJ8ZW58MHx8fHwxNzEwOTQyNjEyfDA&ixlib=rb-4.0.3&w=500',
    },
    heading1: {
      type: String,
      default: 'Meet our team',
    },
    member6Alt: {
      type: String,
      default: 'Member Alt',
    },
    member8Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    member5Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    heading2: {
      type: String,
      default: 'We’re hiring!',
    },
    member6Job: {
      type: String,
      default: 'Job title',
    },
    member1Job: {
      type: String,
      default: 'Job title',
    },
    member5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDR8fHVzZXJ8ZW58MHx8fHwxNzEwOTQyNjEyfDA&ixlib=rb-4.0.3&w=500',
    },
    member8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1573497019940-1c28c88b4f3e?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDExfHx1c2VyfGVufDB8fHx8MTcxMDk0MjYxMnww&ixlib=rb-4.0.3&w=500',
    },
    member1Alt: {
      type: String,
      default: 'Member Alt',
    },
    content1: {
      type: String,
      default: 'Join Our Team Today!',
    },
    member8Job: {
      type: String,
      default: 'Job title',
    },
    member4Content: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.',
    },
    member2Alt: {
      type: String,
      default: 'Member Alt',
    },
  },
}
</script>

<style scoped>
.team1-max-width {
  gap: var(--dl-space-space-fiveunits);
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.team1-section-title {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-content {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-content01 {
  gap: var(--dl-space-space-sixunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-content02 {
  gap: 64px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.team1-row {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
  justify-content: center;
}
.team1-container {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.team1-card {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image {
  width: 80px;
  height: 80px;
}
.team1-content03 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text03 {
  font-style: normal;
  font-weight: 600;
}
.team1-text04 {
  text-align: center;
}
.team1-text05 {
  text-align: center;
}
.team1-social-icons {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-card1 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image1 {
  width: 80px;
  height: 80px;
}
.team1-content04 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title1 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text06 {
  font-style: normal;
  font-weight: 600;
}
.team1-text07 {
  text-align: center;
}
.team1-text08 {
  text-align: center;
}
.team1-social-icons1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-container1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.team1-card2 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image2 {
  width: 80px;
  height: 80px;
}
.team1-content05 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title2 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text09 {
  font-style: normal;
  font-weight: 600;
}
.team1-text10 {
  text-align: center;
}
.team1-text11 {
  text-align: center;
}
.team1-social-icons2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-card3 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image3 {
  width: 80px;
  height: 80px;
}
.team1-content06 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title3 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text12 {
  font-style: normal;
  font-weight: 600;
}
.team1-text13 {
  text-align: center;
}
.team1-text14 {
  text-align: center;
}
.team1-social-icons3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-row1 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
  justify-content: center;
}
.team1-container2 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.team1-card4 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image4 {
  width: 80px;
  height: 80px;
}
.team1-content07 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title4 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text15 {
  font-style: normal;
  font-weight: 600;
}
.team1-text16 {
  text-align: center;
}
.team1-text17 {
  text-align: center;
}
.team1-social-icons4 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-card5 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image5 {
  width: 80px;
  height: 80px;
}
.team1-content08 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title5 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text18 {
  font-style: normal;
  font-weight: 600;
}
.team1-text19 {
  text-align: center;
}
.team1-text20 {
  text-align: center;
}
.team1-social-icons5 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-container3 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.team1-card6 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image6 {
  width: 80px;
  height: 80px;
}
.team1-content09 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title6 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text21 {
  font-style: normal;
  font-weight: 600;
}
.team1-text22 {
  text-align: center;
}
.team1-text23 {
  text-align: center;
}
.team1-social-icons6 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-card7 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  flex-grow: 1;
  max-width: 500px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-placeholder-image7 {
  width: 80px;
  height: 80px;
}
.team1-content10 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-title7 {
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.team1-text24 {
  font-style: normal;
  font-weight: 600;
}
.team1-text25 {
  text-align: center;
}
.team1-text26 {
  text-align: center;
}
.team1-social-icons7 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
.team1-content11 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-direction: column;
}
.team1-content12 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.team1-button {
  width: 100%;
  max-width: 300px;
}
@media(max-width: 991px) {
  .team1-content01 {
    gap: var(--dl-space-space-fourunits);
  }
}
@media(max-width: 767px) {
  .team1-row {
    align-items: center;
    flex-direction: column;
  }
  .team1-row1 {
    align-items: center;
    flex-direction: column;
  }
}
@media(max-width: 479px) {
  .team1-text {
    text-align: center;
  }
  .team1-text01 {
    text-align: center;
  }
  .team1-text02 {
    text-align: center;
  }
  .team1-container {
    flex-direction: column;
  }
  .team1-container1 {
    flex-direction: column;
  }
  .team1-container2 {
    flex-direction: column;
  }
  .team1-container3 {
    flex-direction: column;
  }
  .team1-text27 {
    text-align: center;
  }
  .team1-text28 {
    text-align: center;
  }
  .team1-button {
    width: 100%;
  }
}
</style>
