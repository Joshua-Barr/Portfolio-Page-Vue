<template>
  <div class="home-container">
    <div class="home-navbar">
      <span class="home-heading">Joshua Barr</span>
      <svg viewBox="0 0 1024 1024" class="home-icon">
        <path
          d="M854 342v-86l-342 214-342-214v86l342 212zM854 170q34 0 59 26t25 60v512q0 34-25 60t-59 26h-684q-34 0-59-26t-25-60v-512q0-34 25-60t59-26h684z"
        ></path></svg
      ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon02">
        <path
          d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
        ></path></svg
      ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon04">
        <path
          d="M438.857 73.143c242.286 0 438.857 196.571 438.857 438.857 0 193.714-125.714 358.286-300 416.571-22.286 4-30.286-9.714-30.286-21.143 0-14.286 0.571-61.714 0.571-120.571 0-41.143-13.714-67.429-29.714-81.143 97.714-10.857 200.571-48 200.571-216.571 0-48-17.143-86.857-45.143-117.714 4.571-11.429 19.429-56-4.571-116.571-36.571-11.429-120.571 45.143-120.571 45.143-34.857-9.714-72.571-14.857-109.714-14.857s-74.857 5.143-109.714 14.857c0 0-84-56.571-120.571-45.143-24 60.571-9.143 105.143-4.571 116.571-28 30.857-45.143 69.714-45.143 117.714 0 168 102.286 205.714 200 216.571-12.571 11.429-24 30.857-28 58.857-25.143 11.429-89.143 30.857-127.429-36.571-24-41.714-67.429-45.143-67.429-45.143-42.857-0.571-2.857 26.857-2.857 26.857 28.571 13.143 48.571 64 48.571 64 25.714 78.286 148 52 148 52 0 36.571 0.571 70.857 0.571 81.714 0 11.429-8 25.143-30.286 21.143-174.286-58.286-300-222.857-300-416.571 0-242.286 196.571-438.857 438.857-438.857zM166.286 703.429c1.143-2.286-0.571-5.143-4-6.857-3.429-1.143-6.286-0.571-7.429 1.143-1.143 2.286 0.571 5.143 4 6.857 2.857 1.714 6.286 1.143 7.429-1.143zM184 722.857c2.286-1.714 1.714-5.714-1.143-9.143-2.857-2.857-6.857-4-9.143-1.714-2.286 1.714-1.714 5.714 1.143 9.143 2.857 2.857 6.857 4 9.143 1.714zM201.143 748.571c2.857-2.286 2.857-6.857 0-10.857-2.286-4-6.857-5.714-9.714-3.429-2.857 1.714-2.857 6.286 0 10.286s7.429 5.714 9.714 4zM225.143 772.571c2.286-2.286 1.143-7.429-2.286-10.857-4-4-9.143-4.571-11.429-1.714-2.857 2.286-1.714 7.429 2.286 10.857 4 4 9.143 4.571 11.429 1.714zM257.714 786.857c1.143-3.429-2.286-7.429-7.429-9.143-4.571-1.143-9.714 0.571-10.857 4s2.286 7.429 7.429 8.571c4.571 1.714 9.714 0 10.857-3.429zM293.714 789.714c0-4-4.571-6.857-9.714-6.286-5.143 0-9.143 2.857-9.143 6.286 0 4 4 6.857 9.714 6.286 5.143 0 9.143-2.857 9.143-6.286zM326.857 784c-0.571-3.429-5.143-5.714-10.286-5.143-5.143 1.143-8.571 4.571-8 8.571 0.571 3.429 5.143 5.714 10.286 4.571s8.571-4.571 8-8z"
        ></path>
      </svg>
      <div class="home-links-container">
        <a href="#Experience" class="home-link Navbar-Link">Experience</a>
        <a href="#Projects" class="home-link01">
          <span class="Navbar-Link">Projects</span>
          <br />
        </a>
        <span class="home-link02">
          <span>Download Resume</span>
          <br />
        </span>
      </div>
      <div data-role="BurgerMenu" class="home-burger-menu">
        <svg viewBox="0 0 1024 1024" class="home-icon06">
          <path
            d="M128 256h768v86h-768v-86zM128 554v-84h768v84h-768zM128 768v-86h768v86h-768z"
          ></path>
        </svg>
      </div>
      <div data-role="MobileMenu" class="home-mobile-menu">
        <div class="home-container01">
          <span class="Card-Heading home-heading1">Logo</span>
          <div data-role="CloseMobileMenu" class="home-close-menu">
            <svg viewBox="0 0 1024 1024" class="home-icon08">
              <path
                d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
              ></path>
            </svg>
          </div>
        </div>
        <div class="home-links-container1">
          <span class="home-link03 Navbar-Link">About</span>
          <span class="home-link04 Navbar-Link">Experience</span>
          <span class="home-link05 Navbar-Link">Portofolio</span>
          <span class="Navbar-Link">Contact</span>
        </div>
      </div>
    </div>
    <div class="home-whoami">
      <div class="home-hero-text-container">
        <h1 class="home-heading2 Section-Heading">c:\&gt; whoami</h1>
        <span class="home-text04">
          <span>Hi my name is Joshua,</span>
          <br />
          <span>I LOVE Information Security!!</span>
          <br />
          <span>
            My goal is to help businesses secure themselves against the
            ever-changing threat landscape using the latest tools and
            technologies. As a Cyber Security Specialist, it&apos;s also my
            passion to continue growing and to keep the work fun.
            <span v-html="rawnu89"></span>
          </span>
        </span>
        <div class="home-cta-btn-container">
          <a href="#Contact" class="home-cta-btn Anchor button">
            <span class="home-text10">Get in Contact</span>
          </a>
        </div>
      </div>
    </div>
    <div class="home-medium">
      <strong class="home-heading3">Check out my Medium</strong>
      <div class="home-div">
        <DangerousHTML
          html="<div id='retainable-rss-embed' data-rss='https://medium.com/feed/retainable,https://medium.com/feed/vue-mastery'
  data-maxcols='3' 
  data-layout='grid' 
  data-poststyle='inline' 
  data-readmore='Read the rest' 
  data-buttonclass='btn btn-primary' 
  data-offset='-100'>
  
  <script src='https://www.twilik.com/assets/retainable/rss-embed/retainable-rss-embed.js'></script>"
        ></DangerousHTML>
      </div>
    </div>
    <div class="home-projects">
      <strong id="Projects" class="home-text11">Projects</strong>
      <span class="home-text12">
        I love exploring cutting-edge technologies and building interactive
        applications and solutions for problems. Additionally my device
        vulnerability research and security related projects are listed below.
        Feel free to explore these projects and reach out to me if you&apos;d like
        more information.
      </span>
      <div class="home-gallery">
        <a
          href="https://github.com/Joshua-Barr/Vue_arbitrage"
          target="_blank"
          rel="noreferrer noopener"
        >
          <gallery-card1
            title="Arbitrage (Vue JS)"
            subtitle="A Vue web application coded in Javascript that can be staticly hosted and runs fully client-side for odds calculations. Data is pulled live from the Odds-API https://the-odds-api.com/."
            image_src="/screenshot%202023-06-03%20125652-1500h.png"
            rootClassName="rootClassName"
            class="home-component"
          ></gallery-card1>
        </a>
        <a
          href="https://github.com/Joshua-Barr/VIApp-ReactJS"
          target="_blank"
          rel="noreferrer noopener"
        >
          <gallery-card1
            title="VI App (React JS, Python)"
            subtitle="A React Web App with a custom Express.js API backend and a Python Web Scraper to pull live data from Yahoo Finance's website. The goal is to calculate fair price of businesses based on fundamentals."
            image_src="/screenshot%202023-06-03%20135152-1500h.png"
            rootClassName="rootClassName1"
            class="home-component1"
          ></gallery-card1>
        </a>
        <a
          href="https://ro.ecu.edu.au/ecuworks2012/157/"
          target="_blank"
          rel="noreferrer noopener"
        >
          <gallery-card1
            title="Optical Coherence Tomography Research"
            subtitle="Helped in development of an inexpensive interferometer that measured sample thickness in the micron to mm range.  Used to verify its use for retina scanning."
            image_src="/screenshot%202023-06-03%20134934-1500h.png"
            rootClassName="rootClassName2"
            class="home-component2"
          ></gallery-card1>
        </a>
        <a
          href="https://github.com/Joshua-Barr/Belkin_NetCam_Exploit_RCE-EDB-ID-42331"
          target="_blank"
          rel="noreferrer noopener"
        >
          <gallery-card1
            title="Vulnerability Research"
            subtitle="Independently Verified and performed write-up on https://www.exploit-db.com/exploits/42331. I was able to confirm the exploits as listed do exist on two variants of the camera's firmware. I was able to use an inbuilt web form to upload a web shell, browse files, enable ssh and gain root access."
            image_src="/screenshot%202023-06-03%20131759-1500h.png"
            rootClassName="rootClassName3"
            class="home-component3"
          ></gallery-card1>
        </a>
        <a
          href="https://github.com/Joshua-Barr/Selenium-Scraper---Sonicwall"
          target="_blank"
          rel="noreferrer noopener"
        >
          <gallery-card1
            title="Mongo and Selenium (C#, Firewall Patching)"
            subtitle="Using the power of Selenium to automate browser activities such as form filling, clicks and navigation. Used for automating data pull from multiple Sonicwalls at once and update a MongoDB with Firewall Information. Also used in production to patch Firewalls firmware on multiple simultaneously."
            image_src="/screenshot%202023-06-03%20131431-1500h.png"
            rootClassName="rootClassName4"
            class="home-component4"
          ></gallery-card1>
        </a>
        <a
          href="https://www.home-assistant.io/"
          target="_blank"
          rel="noreferrer noopener"
        >
          <gallery-card1
            title="Local Only Home Automation"
            subtitle="Goal: To automate all the things...        We are talking Sprinklers, Door Locks, Lights, TV's, Routers, Switches, Smart Speakers you name it.               How: via Home Assistant, All local, all VLAN'ed and firewalled with no external connections. This is a growing and ongoing project with much help from ESP32's."
            image_src="/logo-white.svg"
            rootClassName="rootClassName5"
            class="home-component5"
          ></gallery-card1>
        </a>
      </div>
    </div>
    <div class="home-in-progress">
      <strong id="In Progress" class="home-text13">In Progress</strong>
      <div class="home-logo-container">
        <div class="home-container02">
          <img
            alt="image"
            src="/cissp%20-%20square-200h.png"
            class="home-image"
          />
          <span class="home-text14">Estimated July 2023</span>
        </div>
        <div class="home-container03">
          <img
            alt="image"
            src="/aws-certified-solutions-architect-professional-200h.png"
            class="home-image1"
          />
          <span class="home-text15">Estimated Nov. 2023</span>
        </div>
        <div class="home-container04">
          <img alt="image" src="/logo-white.svg" class="home-image2" />
          <span class="home-text16">Home Automation, Ongoing</span>
        </div>
      </div>
    </div>
    <div class="home-experience">
      <strong id="Experience" class="home-text17">
        <span class="home-text18">Experience</span>
        <br />
      </strong>
      <div class="home-pricing-card-container">
        <div class="home-card">
          <div class="home-card-heading">
            <div class="home-container05">
              <span class="home-price">
                <span>Security Specialist</span>
                <br />
              </span>
              <span class="home-price01">
                <span>Office Solutions IT</span>
                <br />
              </span>
            </div>
          </div>
          <div class="home-card-content">
            <div class="home-container06">
              <span class="home-text24 Card-Text">Feature four</span>
              <span class="home-text25 Card-Text">UNLIMITED</span>
            </div>
          </div>
        </div>
      </div>
      <div class="home-pricing-card-container1">
        <div class="home-card1">
          <div class="home-card-heading1">
            <div class="home-container07">
              <span class="home-price02">
                <span>IT Manager</span>
                <br />
              </span>
              <span class="home-price03">
                <span>Office Solutions IT</span>
                <br />
              </span>
            </div>
          </div>
          <div class="home-card-content1">
            <div class="home-container08">
              <span class="home-text30 Card-Text">Feature four</span>
              <span class="home-text31 Card-Text">UNLIMITED</span>
            </div>
          </div>
        </div>
      </div>
      <div class="home-pricing-card-container2">
        <div class="home-card2">
          <div class="home-card-heading2">
            <div class="home-container09">
              <span class="home-price04">Project Engineer</span>
              <span class="home-price05">
                <span>Office Solutions IT</span>
                <br />
              </span>
            </div>
          </div>
          <div class="home-card-content2">
            <div class="home-container10">
              <span class="home-text34 Card-Text">Feature four</span>
              <span class="home-text35 Card-Text">UNLIMITED</span>
            </div>
          </div>
        </div>
      </div>
      <div class="home-pricing-card-container3">
        <div class="home-card3">
          <div class="home-card-heading3">
            <div class="home-container11">
              <span class="home-price06">
                <span>Systems Engineer</span>
                <br />
              </span>
              <span class="home-price07">
                <span>Office Solutions IT</span>
                <br />
              </span>
            </div>
          </div>
          <div class="home-card-content3">
            <div class="home-container12">
              <span class="home-text40 Card-Text">Feature four</span>
              <span class="home-text41 Card-Text">UNLIMITED</span>
            </div>
          </div>
        </div>
      </div>
      <div class="home-pricing-card-container4">
        <div class="home-card4">
          <div class="home-card-heading4">
            <div class="home-container13">
              <span class="home-price08">
                <span>Systems Engineer</span>
                <br />
              </span>
              <span class="home-price09">
                <span>ActivIT Systems</span>
                <br />
              </span>
            </div>
          </div>
          <div class="home-card-content4">
            <div class="home-container14">
              <span class="home-text46 Card-Text">Feature four</span>
              <span class="home-text47 Card-Text">UNLIMITED</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="home-badges">
      <strong id="Badges" class="home-text48">
        <span class="home-text49">Badges</span>
        <br />
      </strong>
      <div class="home-cards-container">
        <div class="home-card5">
          <div class="home-icon-container">
            <img
              alt="image"
              src="/aws-certified-solutions-architect-associate-300h.png"
              class="home-image3"
            />
          </div>
        </div>
        <div class="home-card6">
          <div class="home-icon-container1">
            <img alt="image" src="/ccna%20r%26s-1200w.jpg" class="home-image4" />
          </div>
        </div>
        <div class="home-card7">
          <div class="home-icon-container2">
            <img alt="image" src="/aplus.svg" class="home-image5" />
          </div>
        </div>
      </div>
    </div>
    <div class="home-career-stats-and-contacts">
      <div class="home-stats">
        <div class="home-stat">
          <h1 class="home-text51">800+</h1>
          <span class="home-text52">Happy clients</span>
        </div>
        <div class="home-stat1">
          <h1 class="home-text53">200+</h1>
          <span class="home-text54">Projects Delivered</span>
        </div>
        <div class="home-stat2">
          <h1 class="home-text55">12</h1>
          <span class="home-text56">
            <span class="home-text57">Years in Industry</span>
            <br />
          </span>
        </div>
        <div class="home-stat3">
          <h1 class="home-text59">~150</h1>
          <span class="home-text60">Engineer/Tech colleagues</span>
        </div>
      </div>
      <div class="home-footer">
        <div class="home-container15"></div>
        <span id="Contact" class="home-text61">
          <span class="home-text62">Get in contact...</span>
          <br />
          <br />
          <br />
          <br />
        </span>
        <div class="home-container16">
          <div class="home-contact">
            <span class="home-text67">
              <span class="home-text68">Email:</span>
              <span><span v-html="rawpn6k"></span></span>
              <a href="mailto:Joshbarr52@gmail.com?subject=Nice to e-meet you :)">
                Joshbarr52@gmail.com
              </a>
              <br />
              <span class="home-text71">Medium:</span>
              <span>
                site
                <span v-html="rawt65a"></span>
              </span>
              <br />
              <span class="home-text74">Linkedin:</span>
              <span> </span>
              <a
                href="https://www.linkedin.com/in/josh-barr-cs/"
                target="_blank"
                rel="noreferrer noopener"
                class="home-link14"
              >
                https://www.linkedin.com/in/josh-barr-cs/
              </a>
              <br />
            </span>
          </div>
          <div class="home-socials">
            <div class="home-icon-group">
              <svg viewBox="0 0 950.8571428571428 1024" class="home-icon10">
                <path
                  d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                ></path></svg
              ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon12">
                <path
                  d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                ></path></svg
              ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon14">
                <path
                  d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
                ></path>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>
    <span class="home-link15 Anchor">
      Static Site Hosted in Azure, Built by Josh using Vue 2023
    </span>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

import GalleryCard1 from '../components/gallery-card1'

export default {
  name: 'Home',
  components: {
    DangerousHTML,
    GalleryCard1,
  },
  data() {
    return {
      rawnu89: ' ',
      rawpn6k: ' ',
      rawt65a: ' ',
    }
  },
  metaInfo: {
    title: 'Portfolio Page',
    meta: [
      {
        property: 'og:title',
        content: 'Portfolio Page',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: var(--dl-color-light-background);
}
.home-navbar {
  width: 105%;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  border-color: var(--dl-color-dark-background);
  border-width: 1px;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-tripleunit);
  justify-content: space-between;
  background-color: var(--dl-color-dark-background);
}
.home-heading {
  color: var(--dl-color-gray-white);
  font-size: 50px;
  align-self: center;
  font-style: normal;
  font-family: Overpass;
  font-weight: 700;
  line-height: 1.55;
  text-transform: none;
  text-decoration: none;
}
.home-icon {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-left: var(--dl-space-space-fourunits);
  margin-right: var(--dl-space-space-unit);
}
.home-icon02 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.home-icon04 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.home-links-container {
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-direction: row;
}
.home-link {
  color: var(--dl-color-gray-white);
  align-self: center;
  margin-right: var(--dl-space-space-tripleunit);
  text-decoration: none;
}
.home-link01 {
  color: var(--dl-color-gray-white);
  align-self: center;
  margin-right: var(--dl-space-space-tripleunit);
  text-decoration: none;
}
.home-link02 {
  color: var(--dl-color-light-colour1);
  padding: 8px;
  font-size: 24px;
  align-self: center;
  font-family: Overpass;
  font-weight: 700;
  line-height: 1.55;
  border-radius: 8px;
  text-transform: none;
  text-decoration: none;
  background-color: var(--dl-color-light-color5);
}
.home-burger-menu {
  display: none;
  align-items: flex-start;
  flex-direction: column;
}
.home-icon06 {
  width: 36px;
  height: 36px;
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: var(--dl-space-space-tripleunit);
  position: absolute;
  align-items: flex-start;
  flex-direction: column;
  background-color: #fff;
}
.home-container01 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: row;
  justify-content: space-between;
}
.home-close-menu {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-icon08 {
  width: 24px;
  height: 24px;
}
.home-links-container1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-link03 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-link04 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-link05 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-whoami {
  width: 100%;
  height: 347px;
  display: flex;
  position: relative;
  max-width: var(--dl-size-size-maxcontent);
  align-items: flex-start;
  padding-top: var(--dl-space-space-doubleunit);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-light-background);
}
.home-hero-text-container {
  width: 75%;
  height: 281px;
  display: flex;
  z-index: 10;
  align-self: flex-start;
  align-items: flex-start;
  margin-left: 5%;
  flex-direction: column;
}
.home-heading2 {
  color: var(--dl-color-gray-white);
  margin-top: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-text04 {
  color: var(--dl-color-gray-white);
  font-size: 16px;
  font-family: Nunito;
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-cta-btn-container {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: flex-start;
}
.home-cta-btn {
  color: var(--dl-color-gray-white);
  width: 297px;
  height: 40px;
  text-align: center;
  margin-left: 0px;
  padding-top: var(--dl-space-space-doubleunit);
  margin-right: 0px;
  padding-left: var(--dl-space-space-tenunits);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-tenunits);
  padding-bottom: var(--dl-space-space-doubleunit);
  text-decoration: none;
  background-color: var(--dl-color-light-color5);
}
.home-text10 {
  color: var(--dl-color-gray-white);
}
.home-medium {
  width: 100%;
  height: 363px;
  display: flex;
  position: relative;
  max-width: var(--dl-size-size-maxcontent);
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-light-background);
}
.home-heading3 {
  color: var(--dl-color-gray-white);
  font-size: 34px;
  margin-top: var(--dl-space-space-doubleunit);
  font-family: Nunito;
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-div {
  width: 100%;
  height: 235px;
  align-self: center;
  margin-bottom: var(--dl-space-space-fiveunits);
}
.home-projects {
  width: 1120px;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  align-items: center;
  padding-top: 1px;
  padding-left: var(--dl-space-space-tripleunit);
  border-radius: 10px;
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  background-color: var(--dl-color-light-color4);
}
.home-text11 {
  color: var(--dl-color-gray-black);
  font-size: 34px;
  margin-top: var(--dl-space-space-tripleunit);
  font-family: Nunito;
  margin-left: var(--dl-space-space-fourunits);
  margin-right: var(--dl-space-space-fourunits);
  margin-bottom: var(--dl-space-space-tripleunit);
}
.home-text12 {
  color: var(--dl-color-gray-black);
  font-size: 18px;
  font-family: Nunito;
  margin-left: var(--dl-space-space-fourunits);
  margin-right: var(--dl-space-space-fourunits);
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-gallery {
  width: 100%;
  display: grid;
  padding: 48px;
  grid-gap: var(--dl-space-space-unit);
  max-width: 1400px;
  grid-template-columns: 1fr 1fr 1fr;
}
.home-component {
  text-decoration: none;
}
.home-component1 {
  text-decoration: none;
}
.home-component2 {
  text-decoration: none;
}
.home-component3 {
  text-decoration: none;
}
.home-component4 {
  text-decoration: none;
}
.home-component5 {
  text-decoration: none;
}
.home-in-progress {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  align-items: center;
  padding-left: var(--dl-space-space-tripleunit);
  margin-bottom: 21px;
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: 20px;
}
.home-text13 {
  color: var(--dl-color-gray-white);
  margin: var(--dl-space-space-tripleunit);
  font-size: 34px;
  margin-top: var(--dl-space-space-fourunits);
  font-family: Nunito;
  margin-left: var(--dl-space-space-fourunits);
  margin-right: var(--dl-space-space-fourunits);
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-logo-container {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-container02 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-left: 10%;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: center;
}
.home-image {
  width: 155px;
  height: 160px;
  object-fit: cover;
}
.home-text14 {
  color: var(--dl-color-gray-white);
}
.home-container03 {
  flex: 0 0 auto;
  width: 200px;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: center;
}
.home-image1 {
  width: 165px;
  height: 159px;
  object-fit: cover;
}
.home-text15 {
  color: var(--dl-color-gray-white);
}
.home-container04 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-right: 10%;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: center;
}
.home-image2 {
  width: 180px;
  height: 162px;
  object-fit: cover;
}
.home-text16 {
  color: var(--dl-color-gray-white);
}
.home-experience {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  margin-top: 1px;
  align-items: center;
  padding-top: 1px;
  flex-direction: column;
  padding-bottom: 36px;
}
.home-text17 {
  color: var(--dl-color-gray-white);
  margin: var(--dl-space-space-tripleunit);
  font-size: 34px;
  margin-top: var(--dl-space-space-fourunits);
  font-family: Nunito;
  margin-left: var(--dl-space-space-fourunits);
  margin-right: var(--dl-space-space-fourunits);
  margin-bottom: var(--dl-space-space-fourunits);
}
.home-pricing-card-container {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-self: center;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-card {
  width: 90%;
  display: flex;
  min-width: 350px;
  align-self: center;
  align-items: center;
  border-color: var(--dl-color-gray-900);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
}
.home-card-heading {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-light-color4);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.home-container05 {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-price {
  font-size: 30px;
  font-family: Nunito;
}
.home-price01 {
  font-size: 18px;
  font-family: Nunito;
  margin-left: 50%;
}
.home-card-content {
  width: 100%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: center;
}
.home-container06 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-text24 {
  color: var(--dl-color-gray-white);
}
.home-text25 {
  color: var(--dl-color-gray-white);
}
.home-pricing-card-container1 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-self: center;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-card1 {
  width: 90%;
  display: flex;
  min-width: 350px;
  align-self: center;
  align-items: center;
  border-color: var(--dl-color-gray-900);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
}
.home-card-heading1 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-light-color4);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.home-container07 {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-price02 {
  font-size: 30px;
  font-family: Nunito;
}
.home-price03 {
  font-size: 18px;
  font-family: Nunito;
  margin-left: 50%;
}
.home-card-content1 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: center;
}
.home-container08 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-text30 {
  color: var(--dl-color-gray-white);
}
.home-text31 {
  color: var(--dl-color-gray-white);
}
.home-pricing-card-container2 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-self: center;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-card2 {
  width: 90%;
  display: flex;
  min-width: 350px;
  align-self: center;
  align-items: center;
  border-color: var(--dl-color-gray-900);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
}
.home-card-heading2 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-light-color4);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.home-container09 {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-price04 {
  font-size: 30px;
  font-family: Nunito;
}
.home-price05 {
  font-size: 18px;
  font-family: Nunito;
  margin-left: 50%;
}
.home-card-content2 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: center;
}
.home-container10 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-text34 {
  color: var(--dl-color-gray-white);
}
.home-text35 {
  color: var(--dl-color-gray-white);
}
.home-pricing-card-container3 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-self: center;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-card3 {
  width: 90%;
  display: flex;
  min-width: 350px;
  align-self: center;
  align-items: center;
  border-color: var(--dl-color-gray-900);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
}
.home-card-heading3 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-light-color4);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.home-container11 {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-price06 {
  font-size: 30px;
  font-family: Nunito;
}
.home-price07 {
  font-size: 18px;
  font-family: Nunito;
  margin-left: 50%;
}
.home-card-content3 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: center;
}
.home-container12 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-text40 {
  color: var(--dl-color-gray-white);
}
.home-text41 {
  color: var(--dl-color-gray-white);
}
.home-pricing-card-container4 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-self: center;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-card4 {
  width: 90%;
  display: flex;
  min-width: 350px;
  align-self: center;
  align-items: center;
  border-color: var(--dl-color-gray-900);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
}
.home-card-heading4 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-unit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: var(--dl-color-light-color4);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}
.home-container13 {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-price08 {
  font-size: 30px;
  font-family: Nunito;
}
.home-price09 {
  font-size: 18px;
  font-family: Nunito;
  margin-left: 50%;
}
.home-card-content4 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: center;
}
.home-container14 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-doubleunit);
  justify-content: space-between;
}
.home-text46 {
  color: var(--dl-color-gray-white);
}
.home-text47 {
  color: var(--dl-color-gray-white);
}
.home-badges {
  width: 1122px;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  margin-top: 1px;
  align-items: center;
  border-color: var(--dl-color-light-background);
  border-width: 1px;
  padding-left: var(--dl-space-space-tripleunit);
  border-radius: 10px;
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  background-color: var(--dl-color-light-colour1);
}
.home-text48 {
  color: var(--dl-color-gray-white);
  font-size: 34px;
  margin-top: var(--dl-space-space-doubleunit);
  font-family: Nunito;
  margin-left: var(--dl-space-space-doubleunit);
  margin-right: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-cards-container {
  width: 100%;
  height: 237px;
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-card5 {
  width: 30%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
}
.home-icon-container {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  margin-bottom: var(--dl-space-space-tripleunit);
  flex-direction: column;
}
.home-image3 {
  width: 200px;
  object-fit: cover;
}
.home-card6 {
  width: 30%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
}
.home-icon-container1 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  margin-bottom: var(--dl-space-space-tripleunit);
  flex-direction: column;
}
.home-image4 {
  width: 80%;
  height: 100%;
  object-fit: cover;
  padding-top: var(--dl-space-space-fourunits);
}
.home-card7 {
  width: 30%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-doubleunit);
  margin-bottom: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
}
.home-icon-container2 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  margin-bottom: var(--dl-space-space-tripleunit);
  flex-direction: column;
}
.home-image5 {
  width: 200px;
  object-fit: cover;
}
.home-career-stats-and-contacts {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-light-background);
}
.home-stats {
  width: 100%;
  display: grid;
  padding: 48px;
  grid-gap: 32px;
  max-width: 1400px;
  padding-top: 29px;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}
.home-stat {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text51 {
  color: rgb(255, 124, 76);
  font-size: 3rem;
}
.home-text52 {
  color: var(--dl-color-gray-white);
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.home-stat1 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text53 {
  color: rgb(255, 124, 76);
  font-size: 3rem;
}
.home-text54 {
  color: var(--dl-color-gray-white);
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.home-stat2 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text55 {
  color: rgb(255, 124, 76);
  font-size: 3rem;
}
.home-text56 {
  color: var(--dl-color-gray-white);
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.home-stat3 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-text59 {
  color: rgb(255, 124, 76);
  font-size: 3rem;
}
.home-text60 {
  color: var(--dl-color-gray-white);
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-halfunit);
  text-align: center;
}
.home-footer {
  width: 1122px;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  align-self: center;
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  border-color: var(--dl-color-gray-black);
  border-width: 1px;
  padding-left: var(--dl-space-space-tripleunit);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-tripleunit);
  justify-content: space-between;
  background-color: var(--dl-color-light-color4);
}
.home-container15 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text61 {
  align-self: flex-start;
  font-weight: 700;
  margin-left: 10%;
  margin-bottom: 24px;
}
.home-text62 {
  font-size: 36px;
}
.home-container16 {
  width: 60%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-contact {
  width: 466px;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  margin-bottom: 24px;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text67 {
  align-self: flex-start;
  text-align: left;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text68 {
  font-weight: 700;
}
.home-text71 {
  font-weight: 700;
}
.home-text74 {
  font-weight: 700;
}
.home-link14 {
  text-decoration: underline;
}
.home-socials {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-icon-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: flex-start;
}
.home-icon10 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.home-icon12 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-unit);
}
.home-icon14 {
  width: 24px;
  height: 24px;
}
.home-link15 {
  color: var(--dl-color-gray-white);
  align-self: center;
  margin-top: var(--dl-space-space-doubleunit);
  text-align: center;
  margin-bottom: var(--dl-space-space-doubleunit);
}
@media(max-width: 991px) {
  .home-heading {
    text-align: center;
  }
  .home-heading1 {
    text-align: center;
  }
  .home-whoami {
    height: auto;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .home-hero-text-container {
    align-self: flex-start;
    align-items: flex-start;
    margin-bottom: var(--dl-space-space-fourunits);
  }
  .home-heading2 {
    text-align: center;
  }
  .home-text04 {
    align-self: center;
    text-align: left;
  }
  .home-medium {
    height: auto;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .home-heading3 {
    text-align: center;
  }
  .home-projects {
    width: 98%;
  }
  .home-text11 {
    align-self: center;
    text-align: left;
  }
  .home-text12 {
    align-self: center;
    text-align: left;
  }
  .home-gallery {
    grid-template-columns: 1fr 1fr;
  }
  .home-text13 {
    align-self: center;
    text-align: left;
  }
  .home-text17 {
    align-self: center;
    text-align: left;
  }
  .home-text18 {
    align-self: center;
    text-align: left;
  }
  .home-pricing-card-container {
    justify-content: center;
  }
  .home-pricing-card-container1 {
    justify-content: center;
  }
  .home-pricing-card-container2 {
    justify-content: center;
  }
  .home-pricing-card-container3 {
    justify-content: center;
  }
  .home-pricing-card-container4 {
    justify-content: center;
  }
  .home-badges {
    width: 98%;
  }
  .home-text48 {
    align-self: center;
    text-align: left;
  }
  .home-text49 {
    align-self: center;
    text-align: left;
  }
  .home-text51 {
    text-align: center;
  }
  .home-text53 {
    text-align: center;
  }
  .home-text55 {
    text-align: center;
  }
  .home-text59 {
    text-align: center;
  }
}
@media(max-width: 767px) {
  .home-navbar {
    position: relative;
  }
  .home-links-container {
    display: none;
  }
  .home-burger-menu {
    display: flex;
    padding: var(--dl-space-space-halfunit);
    margin-left: var(--dl-space-space-tripleunit);
    border-radius: var(--dl-radius-radius-radius4);
    background-color: var(--dl-color-gray-black);
  }
  .home-icon06 {
    fill: var(--dl-color-gray-white);
  }
  .home-cta-btn {
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
  }
  .home-gallery {
    padding-left: 32px;
    padding-right: 32px;
  }
  .home-cards-container {
    align-items: center;
    flex-direction: column;
  }
  .home-card5 {
    width: 70%;
    margin-bottom: var(--dl-space-space-tripleunit);
  }
  .home-card6 {
    width: 70%;
    margin-bottom: var(--dl-space-space-tripleunit);
  }
  .home-card7 {
    width: 70%;
    margin-bottom: var(--dl-space-space-tripleunit);
  }
  .home-stats {
    padding-left: 32px;
    padding-right: 32px;
    grid-template-columns: 1fr 1fr;
  }
  .home-text52 {
    text-align: center;
  }
  .home-text54 {
    text-align: center;
  }
  .home-text56 {
    text-align: center;
  }
  .home-text57 {
    text-align: center;
  }
  .home-text60 {
    text-align: center;
  }
}
@media(max-width: 479px) {
  .home-burger-menu {
    margin-left: var(--dl-space-space-doubleunit);
  }
  .home-hero-text-container {
    width: 90%;
    margin-right: 5%;
  }
  .home-cta-btn {
    width: 256px;
    height: 42px;
  }
  .home-gallery {
    padding-top: 32px;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: 32px;
  }
  .home-image {
    width: 128px;
    height: 136px;
  }
  .home-image1 {
    width: 120px;
    height: 137px;
  }
  .home-image2 {
    width: 136px;
    height: 133px;
  }
  .home-price01 {
    margin-left: 40%;
  }
  .home-price03 {
    margin-left: 40%;
  }
  .home-price05 {
    margin-left: 40%;
  }
  .home-price07 {
    margin-left: 40%;
  }
  .home-price09 {
    margin-left: 40%;
  }
  .home-card5 {
    width: 100%;
  }
  .home-card6 {
    width: 100%;
  }
  .home-card7 {
    width: 100%;
  }
  .home-stats {
    padding-top: 32px;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: 32px;
    grid-template-columns: 1fr;
  }
  .home-footer {
    width: 97%;
  }
  .home-container15 {
    margin-top: 24px;
    align-items: flex-start;
    margin-bottom: 0px;
  }
  .home-text61 {
    margin-left: 7%;
    margin-right: 2%;
  }
  .home-container16 {
    margin-top: 2%;
    align-items: flex-start;
    margin-bottom: 0px;
  }
  .home-contact {
    width: 92%;
    align-items: flex-start;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-text67 {
    width: 50%;
  }
}
</style>
