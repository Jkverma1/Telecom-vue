<template>
  <head>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
  </head>
  <nav class="nav">
    <div class="container">
      <div class="logo">
        <a href="/"
          ><div class="nav-brand">
            <img src="front-end/img/white-logo.png" alt="" />
            <h3 class="nav-title">TelcomData</h3>
          </div></a
        >
      </div>
      <div id="mainListDiv" class="main_list">
        <ul class="navlinks">
          <li onclick="serviceItems()">
            <a href="#"
              >Services <i class="fa-solid fa-chevron-down service-down"></i
            ></a>
            <ul id="service-items">
              <li>
                <a href="front-end/number-mapping.html">Number Mapping</a>
              </li>
              <li>
                <a href="front-end/number-scrubbing.html">Number Scrubbing</a>
              </li>
              <li><a href="#">Number Monitoring</a></li>
              <li>
                <a href="front-end/data-subscription.html">Data Subscription</a>
              </li>
              <li><a href="#">Number API </a></li>
            </ul>
          </li>
          <li><a href="front-end/pricing.html">Pricing</a></li>
          <li>
            <a><router-link to="/about">About Us</router-link></a>
          </li>
          <li>
            <a><router-link to="/api">API</router-link></a>
          </li>
          <li><a href="front-end/contact-us.html">Contact</a></li>
          <li id="login-container">
            <a
              class="login-btn-index"
              id="login-btn"
              href="/front-end/signin.html"
              >Log In</a
            >
          </li>
        </ul>
      </div>
      <span class="navTrigger" onclick="showMenu()">
        <i></i>
        <i></i>
        <i></i>
      </span>
    </div>
  </nav>
  <div class="banner-text-container">
    <h3 class="banner-sub-head">Simplify TCPA and DNC</h3>
    <h1 class="banner-head">
      Compiance technology <br />
      with a single platform
    </h1>
    <p class="banner-para">
      In this increasingly dynamic and complex regulatory environment, we help
      protect <br />
      your business environment from devastating fines and damage to your brand.
    </p>
    <button
      class="free-trial-btn"
      onclick="location.href='front-end/signin.html'"
    >
      Free trial
    </button>
  </div>

  <section class="home">
    <img class="w-100" src="front-end/img/homepage-banner.png" alt="" />
  </section>
  <section class="Services">
    <img class="horizontal-line" src="front-end/img/Line 30.png" alt="" />
    <h1 class="Service-head">Services</h1>

    <div class="service-feature">
      <div class="service-type">
        <svg
          class="box-collection"
          width="18"
          height="20"
          viewBox="0 0 18 20"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M16 8H2C0.897 8 0 8.897 0 10V18C0 19.103 0.897 20 2 20H16C17.103 20 18 19.103 18 18V10C18 8.897 17.103 8 16 8ZM2 18V10H16L16.002 18H2ZM2 4H16V6H2V4ZM4 0H14V2H4V0Z"
            fill="#008F7D"
          />
        </svg>
        <h3 class="service-head">Number Mapping</h3>
        <p class="service-para">
          We help you to map your numbers against any attributes you need
        </p>
        <button class="try-for-free-btn">Try for free</button>
      </div>
      <div class="service-type">
        <svg
          class="box-collection"
          width="16"
          height="18"
          viewBox="0 0 16 18"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M16 14V4C16 1.832 12.337 0 8 0C3.663 0 0 1.832 0 4V14C0 16.168 3.663 18 8 18C12.337 18 16 16.168 16 14ZM8 2C11.691 2 13.931 3.507 14 3.994C13.931 4.493 11.691 6 8 6C4.309 6 2.069 4.493 2 4.006C2.069 3.507 4.309 2 8 2ZM2 6.607C3.479 7.454 5.637 8 8 8C10.363 8 12.521 7.454 14 6.607V8.994C13.931 9.493 11.691 11 8 11C4.309 11 2.069 9.493 2 9V6.607ZM2 14V11.607C3.479 12.454 5.637 13 8 13C10.363 13 12.521 12.454 14 11.607V13.994C13.931 14.493 11.691 16 8 16C4.309 16 2.069 14.493 2 14Z"
            fill="#008F7D"
          />
        </svg>
        <h3 class="service-head">Number Scrubbing</h3>
        <p class="service-para">
          You can select different criteria to filter your list
        </p>
        <button class="try-for-free-btn">Try for free</button>
      </div>
      <div class="service-type">
        <svg
          class="box-collection"
          width="17"
          height="13"
          viewBox="0 0 17 13"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M0 0H11V2H0V0ZM0 4H11V6H0V4ZM0 8H7V10H0V8ZM15.299 5.292L10.999 9.583L9.707 8.292L8.293 9.707L10.999 12.411L16.711 6.708L15.299 5.292Z"
            fill="#008F7D"
          />
        </svg>

        <h3 class="service-head">Number Monitoring</h3>
        <p class="service-para">
          We monitor your numbers every minute and send you email if your
          numbers are flagged
        </p>
        <button class="try-for-free-btn">Try for free</button>
      </div>
      <div class="service-type">
        <svg
          class="box-collection"
          width="20"
          height="18"
          viewBox="0 0 20 18"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M2 16H4C4 17.103 4.897 18 6 18H14C15.103 18 16 17.103 16 16H18C19.103 16 20 15.103 20 14V4C20 2.897 19.103 2 18 2H16C16 0.897 15.103 0 14 0H6C4.897 0 4 0.897 4 2H2C0.897 2 0 2.897 0 4V14C0 15.103 0.897 16 2 16ZM18 4V14H16V4H18ZM6 2H14L14.001 16H6V2ZM2 4H4V14H2V4Z"
            fill="#008F7D"
          />
        </svg>

        <h3 class="service-head">Data Subscription</h3>
        <p class="service-para">
          We let you to have regular download of industry database
        </p>
        <button class="try-for-free-btn">Try for free</button>
      </div>
      <div class="service-type">
        <svg
          class="box-collection"
          width="20"
          height="20"
          viewBox="0 0 20 20"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M5.37547 14.781L6.62547 13.219L2.60147 9.99998L6.62547 6.78098L5.37547 5.21898L0.375469 9.21898C0.258315 9.31267 0.163737 9.4315 0.0987422 9.5667C0.0337473 9.70189 0 9.84998 0 9.99998C0 10.15 0.0337473 10.2981 0.0987422 10.4333C0.163737 10.5685 0.258315 10.6873 0.375469 10.781L5.37547 14.781ZM14.6255 5.21898L13.3755 6.78098L17.3995 9.99998L13.3755 13.219L14.6255 14.781L19.6255 10.781C19.7426 10.6873 19.8372 10.5685 19.9022 10.4333C19.9672 10.2981 20.0009 10.15 20.0009 9.99998C20.0009 9.84998 19.9672 9.70189 19.9022 9.5667C19.8372 9.4315 19.7426 9.31267 19.6255 9.21898L14.6255 5.21898ZM12.9765 1.21598L8.97647 19.216L7.02347 18.782L11.0235 0.781982L12.9765 1.21598Z"
            fill="#008F7D"
          />
        </svg>

        <h3 class="service-head">Number API</h3>
        <p class="service-para">
          We provide API for you to accomplish your number scrubbing and mapping
          needs
        </p>
        <button class="try-for-free-btn">Try for free</button>
      </div>
    </div>
  </section>
  <!-- number mapping -->
  <section class="number-mapping">
    <img src="front-end/img/Line 30.png" alt="" />
    <h1 class="Service-head">Number Mapping</h1>
    <h5 class="sub-head">Trial version</h5>
    <p class="service-sub-para">
      Upload a file with less than 100 numbers and we will map the file with
      parameters select for free
    </p>
    <h5 class="file-upload-head">File Upload</h5>

    <form class="form-container">
      <div class="upload-files-container">
        <div class="drag-file-area">
          <h3 class="dynamic-message m68-5">Upload number file</h3>
          <span class="browse-files">
            <label class="label"
              ><span class="browse-files">
                Click to <input type="file" class="default-file-input" />
                <span class="browse-files-text">browse</span>
                <span> or drag & drop</span>
              </span>
            </label>
          </span>
        </div>
        <div class="text-center checkbox-container">
          <label for="Select-field" class="select-field-head"
            >Select fields</label
          >
          <div class="checkbox-grid">
            <div class="checkBox">
              <input type="checkbox" />
              <label>DNC</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>State</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>LATA</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>Operating Company</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>Rate Center</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>Operator Type</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>FTC Database</label>
            </div>
            <div class="checkBox">
              <input type="checkbox" />
              <label>LNR</label>
            </div>
          </div>
          <div></div>
          <button type="button" class="upload-button">Submit</button>
        </div>
      </div>
    </form>
  </section>
  <!-- number scrubbing -->
  <section class="number-mapping">
    <img src="front-end/img/Line 30.png" alt="" />
    <h1 class="Service-head">Number Scrubbing</h1>
    <h5 class="sub-head">Trial version</h5>
    <p class="service-sub-para">
      Upload a file with less than 100 numbers and we will map the file with
      parameters select for free
    </p>
    <h5 class="file-upload-head">File Upload</h5>

    <form class="form-container">
      <div class="upload-files-container">
        <div class="drag-file-area">
          <h3 class="dynamic-message m68-5">Upload number file</h3>
          <span class="browse-files">
            <label class="label"
              ><span class="browse-files">
                Click to <input type="file" class="default-file-input" />
                <span class="browse-files-text">browse</span>
                <span>or drag & drop</span>
              </span>
            </label>
          </span>
        </div>

        <div class="text-center checkbox-container">
          <label for="Select-field" class="select-field-head"
            >Inclusion Criteria</label
          >
          <div class="include-exclude">
            <div class="include-exclude-top-container">
              <div class="include-exclude-select-tag-container">
                <div>
                  <label class="include-exclude-select-label" for="cars"
                    >Include / Exclude</label
                  >
                  <select class="include-exclude-select-tag" name="" id="">
                    <option value="">Include</option>
                    <option value="">Exclude</option>
                  </select>
                </div>
                <div>
                  <label class="include-exclude-select-label" for="cars"
                    >State</label
                  >
                  <input
                    class="state-select-tag"
                    type="text"
                    placeholder="California"
                    value="California"
                  />
                </div>
              </div>
              <div class="include-exclude-keyword-container">
                <h2 class="include-exclude-select-label mb-8">LATA</h2>
                <div class="tags-input-wrapper">
                  <span class="tag">Richmond<a>×</a></span
                  ><span class="tag">Westlake<a>×</a></span>
                  <i class="fa-solid fa-chevron-down keyword-box-down-icon"></i>
                </div>
              </div>
              <div class="cross-container">
                <span class="cross-mark-label">Delete Location</span>
                <svg
                  class="Cross-mark"
                  width="8"
                  height="8"
                  viewBox="0 0 8 8"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M0.645917 0.645917C0.692363 0.599354 0.747538 0.562411 0.808283 0.537204C0.869028 0.511998 0.93415 0.499023 0.999917 0.499023C1.06568 0.499023 1.13081 0.511998 1.19155 0.537204C1.2523 0.562411 1.30747 0.599354 1.35392 0.645917L3.99992 3.29292L6.64592 0.645917C6.6924 0.599429 6.74759 0.562553 6.80833 0.537394C6.86907 0.512234 6.93417 0.499285 6.99992 0.499285C7.06566 0.499285 7.13076 0.512234 7.1915 0.537394C7.25224 0.562553 7.30743 0.599429 7.35392 0.645917C7.4004 0.692405 7.43728 0.747594 7.46244 0.808333C7.4876 0.869073 7.50055 0.934173 7.50055 0.999917C7.50055 1.06566 7.4876 1.13076 7.46244 1.1915C7.43728 1.25224 7.4004 1.30743 7.35392 1.35392L4.70692 3.99992L7.35392 6.64592C7.4004 6.6924 7.43728 6.74759 7.46244 6.80833C7.4876 6.86907 7.50055 6.93417 7.50055 6.99992C7.50055 7.06566 7.4876 7.13076 7.46244 7.1915C7.43728 7.25224 7.4004 7.30743 7.35392 7.35392C7.30743 7.4004 7.25224 7.43728 7.1915 7.46244C7.13076 7.4876 7.06566 7.50055 6.99992 7.50055C6.93417 7.50055 6.86907 7.4876 6.80833 7.46244C6.74759 7.43728 6.6924 7.4004 6.64592 7.35392L3.99992 4.70692L1.35392 7.35392C1.30743 7.4004 1.25224 7.43728 1.1915 7.46244C1.13076 7.4876 1.06566 7.50055 0.999917 7.50055C0.934173 7.50055 0.869073 7.4876 0.808333 7.46244C0.747594 7.43728 0.692405 7.4004 0.645917 7.35392C0.599429 7.30743 0.562553 7.25224 0.537394 7.1915C0.512234 7.13076 0.499285 7.06566 0.499285 6.99992C0.499285 6.93417 0.512234 6.86907 0.537394 6.80833C0.562553 6.74759 0.599429 6.6924 0.645917 6.64592L3.29292 3.99992L0.645917 1.35392C0.599354 1.30747 0.562411 1.2523 0.537204 1.19155C0.511998 1.13081 0.499023 1.06568 0.499023 0.999917C0.499023 0.93415 0.511998 0.869028 0.537204 0.808283C0.562411 0.747538 0.599354 0.692363 0.645917 0.645917Z"
                    fill="#A0A7A7"
                  />
                </svg>
              </div>
            </div>
            <div class="include-exclude-top-container">
              <div
                class="include-exclude-select-tag-container"
                style="margin-top: 8px"
              >
                <div>
                  <select class="include-exclude-select-tag" name="" id="">
                    <option value="">Exclude</option>
                    <option value="">Include</option>
                  </select>
                </div>
                <div>
                  <input
                    class="state-select-tag"
                    type="text"
                    placeholder="California"
                    value="Florida"
                  />
                </div>
              </div>
              <div class="mt-16 include-exclude-keyword-container">
                <h2 class="include-exclude-select-label sec-lata mb-8">LATA</h2>
                <div class="tags-input-wrapper">
                  <span class="tag">all<a>×</a></span>
                  <i class="fa-solid fa-chevron-down keyword-box-down-icon"></i>
                </div>
              </div>
              <div class="cross-container">
                <span class="cross-mark-label">Delete Location</span>
                <svg
                  class="Cross-mark"
                  width="8"
                  height="8"
                  viewBox="0 0 8 8"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M0.645917 0.645917C0.692363 0.599354 0.747538 0.562411 0.808283 0.537204C0.869028 0.511998 0.93415 0.499023 0.999917 0.499023C1.06568 0.499023 1.13081 0.511998 1.19155 0.537204C1.2523 0.562411 1.30747 0.599354 1.35392 0.645917L3.99992 3.29292L6.64592 0.645917C6.6924 0.599429 6.74759 0.562553 6.80833 0.537394C6.86907 0.512234 6.93417 0.499285 6.99992 0.499285C7.06566 0.499285 7.13076 0.512234 7.1915 0.537394C7.25224 0.562553 7.30743 0.599429 7.35392 0.645917C7.4004 0.692405 7.43728 0.747594 7.46244 0.808333C7.4876 0.869073 7.50055 0.934173 7.50055 0.999917C7.50055 1.06566 7.4876 1.13076 7.46244 1.1915C7.43728 1.25224 7.4004 1.30743 7.35392 1.35392L4.70692 3.99992L7.35392 6.64592C7.4004 6.6924 7.43728 6.74759 7.46244 6.80833C7.4876 6.86907 7.50055 6.93417 7.50055 6.99992C7.50055 7.06566 7.4876 7.13076 7.46244 7.1915C7.43728 7.25224 7.4004 7.30743 7.35392 7.35392C7.30743 7.4004 7.25224 7.43728 7.1915 7.46244C7.13076 7.4876 7.06566 7.50055 6.99992 7.50055C6.93417 7.50055 6.86907 7.4876 6.80833 7.46244C6.74759 7.43728 6.6924 7.4004 6.64592 7.35392L3.99992 4.70692L1.35392 7.35392C1.30743 7.4004 1.25224 7.43728 1.1915 7.46244C1.13076 7.4876 1.06566 7.50055 0.999917 7.50055C0.934173 7.50055 0.869073 7.4876 0.808333 7.46244C0.747594 7.43728 0.692405 7.4004 0.645917 7.35392C0.599429 7.30743 0.562553 7.25224 0.537394 7.1915C0.512234 7.13076 0.499285 7.06566 0.499285 6.99992C0.499285 6.93417 0.512234 6.86907 0.537394 6.80833C0.562553 6.74759 0.599429 6.6924 0.645917 6.64592L3.29292 3.99992L0.645917 1.35392C0.599354 1.30747 0.562411 1.2523 0.537204 1.19155C0.511998 1.13081 0.499023 1.06568 0.499023 0.999917C0.499023 0.93415 0.511998 0.869028 0.537204 0.808283C0.562411 0.747538 0.599354 0.692363 0.645917 0.645917Z"
                    fill="#A0A7A7"
                  />
                </svg>
              </div>
            </div>
            <div></div>
          </div>
        </div>
        <span class="add-location-scrubbing">
          <svg
            width="12"
            height="12"
            viewBox="0 0 12 12"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M11.3336 5.5555H6.44468V0.666612C6.44468 0.548738 6.39786 0.435692 6.31451 0.352343C6.23116 0.268993 6.11811 0.222168 6.00024 0.222168C5.88236 0.222168 5.76932 0.268993 5.68597 0.352343C5.60262 0.435692 5.55579 0.548738 5.55579 0.666612V5.5555H0.666904C0.54903 5.5555 0.435984 5.60233 0.352634 5.68568C0.269285 5.76903 0.222459 5.88207 0.222459 5.99995C0.220266 6.05771 0.23048 6.11527 0.252413 6.16875C0.274345 6.22223 0.307487 6.27039 0.349604 6.30998C0.391722 6.34957 0.441836 6.37967 0.496571 6.39826C0.551305 6.41684 0.609387 6.42348 0.666904 6.41772H5.55579V11.3333C5.55579 11.4512 5.60262 11.5642 5.68597 11.6475C5.76932 11.7309 5.88236 11.7777 6.00024 11.7777C6.11811 11.7777 6.23116 11.7309 6.31451 11.6475C6.39786 11.5642 6.44468 11.4512 6.44468 11.3333V6.44439H11.3336C11.4514 6.44439 11.5645 6.39757 11.6478 6.31422C11.7312 6.23087 11.778 6.11782 11.778 5.99995C11.778 5.88207 11.7312 5.76903 11.6478 5.68568C11.5645 5.60233 11.4514 5.5555 11.3336 5.5555Z"
              fill="#008F7D"
            />
          </svg>
          Add location
        </span>
        <div class="checkbox-grid2">
          <div class="checkBox">
            <input type="checkbox" />
            <label>Excluse SPAM Number in Youmail</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Excluse Numbers in DNC</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Exclude Mobile Number</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Excluse Fraud Number in Youmail</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Excluse Numbers in FTC</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Exclude Landline Number</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Exclude Canada Number</label>
          </div>
          <div class="checkBox">
            <input type="checkbox" />
            <label>Exclude Non-US Number</label>
          </div>
        </div>
        <div class="row-6-6">
          <div>
            <h2 class="tags-add-label">Include Operators</h2>
            <div class="tags-input-wrapper">
              <span class="tag">Richmond<a>×</a></span
              ><span class="tag">Westlake<a>×</a></span>
              <i class="fa-solid fa-chevron-down keyword-box-down-icon"></i>
            </div>
          </div>
          <div>
            <h2 class="tags-add-label">Exclude Operators</h2>
            <div class="tags-input-wrapper">
              <span class="tag">Richmond<a>×</a></span
              ><span class="tag">Westlake<a>×</a></span>
              <i class="fa-solid fa-chevron-down keyword-box-down-icon"></i>
            </div>
          </div>
        </div>
        <div></div>
        <button
          type="button"
          class="upload-button"
          onclick="confirmPaymentTask()"
        >
          Submit
        </button>
      </div>
    </form>
  </section>

  <!-- checking for a number -->
  <section class="number-mapping">
    <img src="front-end/img/Line 30.png" alt="" />
    <h1 class="Service-head">Checking for a Number</h1>
    <h5 class="sub-head">Trial version</h5>
    <p class="service-sub-para">
      Enter Number and get back parameter <br />
      related to the number
    </p>

    <div class="number-checker-container" style="margin-top: 56.5px">
      <form class="number-checker-input-container" action="">
        <label class="number-checker-label" for="number-check"
          >Enter a Number</label
        >
        <input
          type="text"
          name="number-check"
          class="number-checker-input"
          value="(239) 555-0108"
        />
        <button class="check-button">Check Number</button>
      </form>
      <div class="number-detail">
        <h3 class="number-detail-head">
          LRN<span class="float-right">189485 66 0822</span>
        </h3>
        <h3 class="number-detail-head">
          Spam Score<span class="float-right">4567</span>
        </h3>
        <h3 class="number-detail-head">
          Fraud Score<span class="float-right">19</span>
        </h3>
        <h3 class="number-detail-head">
          LATA<span class="float-right">10</span>
        </h3>
        <h3 class="number-detail-head">
          Rate Center<span class="float-right">Center Name</span>
        </h3>
        <h3 class="number-detail-head">
          State<span class="float-right">California</span>
        </h3>
        <h3 class="number-detail-head">
          Operator Name<span class="float-right">Virgin Mobile</span>
        </h3>
        <h3 class="number-detail-head">
          Operator Type<span class="float-right">-</span>
        </h3>
        <h3 class="number-detail-head">
          Last Seen in FTC<span class="float-right">September 2022</span>
        </h3>
        <h3 class="number-detail-head">
          In DNC<span class="float-right">-</span>
        </h3>
      </div>
    </div>
  </section>

  <!-- Download Sample data file -->
  <section class="number-mapping">
    <img src="front-end/img/Line 30.png" alt="" />
    <h1 class="Service-head">Download Sample data file</h1>

    <div class="number-checker-container">
      <div class="number-detail">
        <h3 class="number-detail-head">
          FTC<span class="float-right"
            ><button class="sample-data-btn">
              <svg
                width="16"
                height="16"
                viewBox="0 0 16 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M8.00016 10.6665L10.6668 7.33317H8.66683V2.6665H7.3335V7.33317H5.3335L8.00016 10.6665Z"
                  fill="#3E4B4B"
                />
                <path
                  d="M13.3335 12.0002H2.66683V7.3335H1.3335V12.0002C1.3335 12.7355 1.9315 13.3335 2.66683 13.3335H13.3335C14.0688 13.3335 14.6668 12.7355 14.6668 12.0002V7.3335H13.3335V12.0002Z"
                  fill="#3E4B4B"
                />
              </svg>
              Download
            </button></span
          >
        </h3>
        <h3 class="number-detail-head">
          Lerg<span class="float-right"
            ><button class="sample-data-btn">
              <svg
                width="16"
                height="16"
                viewBox="0 0 16 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M8.00016 10.6665L10.6668 7.33317H8.66683V2.6665H7.3335V7.33317H5.3335L8.00016 10.6665Z"
                  fill="#3E4B4B"
                />
                <path
                  d="M13.3335 12.0002H2.66683V7.3335H1.3335V12.0002C1.3335 12.7355 1.9315 13.3335 2.66683 13.3335H13.3335C14.0688 13.3335 14.6668 12.7355 14.6668 12.0002V7.3335H13.3335V12.0002Z"
                  fill="#3E4B4B"
                />
              </svg>
              Download
            </button></span
          >
        </h3>
        <h3 class="number-detail-head">
          LRN<span class="float-right"
            ><button class="sample-data-btn">
              <svg
                width="16"
                height="16"
                viewBox="0 0 16 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M8.00016 10.6665L10.6668 7.33317H8.66683V2.6665H7.3335V7.33317H5.3335L8.00016 10.6665Z"
                  fill="#3E4B4B"
                />
                <path
                  d="M13.3335 12.0002H2.66683V7.3335H1.3335V12.0002C1.3335 12.7355 1.9315 13.3335 2.66683 13.3335H13.3335C14.0688 13.3335 14.6668 12.7355 14.6668 12.0002V7.3335H13.3335V12.0002Z"
                  fill="#3E4B4B"
                />
              </svg>
              Download
            </button></span
          >
        </h3>
        <h3 class="number-detail-head">
          DNC<span class="float-right"
            ><button class="sample-data-btn">
              <svg
                width="16"
                height="16"
                viewBox="0 0 16 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M8.00016 10.6665L10.6668 7.33317H8.66683V2.6665H7.3335V7.33317H5.3335L8.00016 10.6665Z"
                  fill="#3E4B4B"
                />
                <path
                  d="M13.3335 12.0002H2.66683V7.3335H1.3335V12.0002C1.3335 12.7355 1.9315 13.3335 2.66683 13.3335H13.3335C14.0688 13.3335 14.6668 12.7355 14.6668 12.0002V7.3335H13.3335V12.0002Z"
                  fill="#3E4B4B"
                />
              </svg>

              Download
            </button></span
          >
        </h3>
      </div>
    </div>
  </section>

  <!-- contact us form -->
  <section class="number-mapping contact-container">
    <h1 class="Service-head contact-head">Contact Us</h1>
    <p class="service-sub-para contact-sub-para">
      Leave us a message and we'll respond <br />
      as soon as possible!
    </p>

    <form class="contact-form" action="">
      <label for="fname">Full Name</label>
      <input type="text" id="fname" name="firstname" placeholder="John Doe" />

      <label for="email">Email</label>
      <input
        type="email"
        id="email-form"
        name="email"
        placeholder="john.doe@email.com"
      />

      <label for="phone-number">Phone Number</label>
      <input
        type="number"
        id="phone-number"
        name="phone-number"
        placeholder="Enter phone number"
      />

      <label for="message">Message</label>
      <textarea
        name="text"
        rows="3"
        placeholder="john.doe@email.com"
      ></textarea>
      <div class="submit-btn-center">
        <button class="contact-form-submit" type="submit">Submit</button>
      </div>
    </form>
  </section>
  <footer class="footer contact-container-index">
    <div class="footer-menu-start">
      <div class="nav-brand">
        <img src="front-end/img/white-logo.png" alt="" />
        <h3 class="nav-title">TelcomData</h3>
      </div>
      <div class="social-link-container">
        <a
          href="https://www.facebook.com/TelcomDataus-One-Stop-Shop-for-US-LERG-LRN-DNC-Data-161148389027028"
          ><i class="fa-brands fa-facebook-f"></i
        ></a>
        <a href="https://twitter.com/telcomdata1"
          ><i class="fa-brands fa-twitter"></i
        ></a>
        <a href="https://www.linkedin.com/company/telcomdata"
          ><i class="fa-brands fa-linkedin-in"></i
        ></a>
      </div>
      <p class="footer-para">
        Copyright © 2022 TelcomeData. <br />
        All rights reserved. Terms of service
      </p>
    </div>
    <div class="footer-menu-mid">
      <div class="footer-sub-menu">
        <h3 class="footer-menu-head">Services</h3>
        <ul class="footer-menu-list">
          <li>
            <a style="color: #fff" href="front-end/number-scrubbing.html"
              >Number Scubbing</a
            >
          </li>
          <li>
            <a style="color: #fff" href="front-end/number-mapping.html"
              >Number Mapping</a
            >
          </li>
          <li>Number Monitoring</li>
          <li>
            <a style="color: #fff" href="front-end/data-subscription.html"
              >Data Subscription</a
            >
          </li>
          <li>Number API</li>
        </ul>
      </div>
      <div class="footer-sub-menu">
        <h3 class="footer-menu-head">Menu</h3>
        <ul class="footer-menu-list">
          <li>
            <a style="color: #fff" href="front-end/pricing.html">Pricing</a>
          </li>
          <li>
            <a style="color: #fff" href="front-end/about-us.html">About Us</a>
          </li>
          <li>
            <a style="color: #fff" href="front-end/contact-us.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="footer-menu-end">
      <h3 class="footer-menu-head">Get in Touch</h3>
      <ul class="footer-menu-list">
        <li>
          <svg
            class="footer-icon"
            width="16"
            height="16"
            viewBox="0 0 16 16"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M7.99967 9.33333C9.47034 9.33333 10.6663 8.13733 10.6663 6.66667C10.6663 5.196 9.47034 4 7.99967 4C6.52901 4 5.33301 5.196 5.33301 6.66667C5.33301 8.13733 6.52901 9.33333 7.99967 9.33333ZM7.99967 5.33333C8.73501 5.33333 9.33301 5.93133 9.33301 6.66667C9.33301 7.402 8.73501 8 7.99967 8C7.26434 8 6.66634 7.402 6.66634 6.66667C6.66634 5.93133 7.26434 5.33333 7.99967 5.33333Z"
              fill="#869593"
            />
            <path
              d="M7.61372 14.5428C7.72655 14.6234 7.86173 14.6667 8.00038 14.6667C8.13903 14.6667 8.27422 14.6234 8.38705 14.5428C8.58972 14.3995 13.3531 10.9602 13.3337 6.66683C13.3337 3.72616 10.9411 1.3335 8.00038 1.3335C5.05972 1.3335 2.66705 3.72616 2.66705 6.6635C2.64772 10.9602 7.41105 14.3995 7.61372 14.5428ZM8.00038 2.66683C10.2064 2.66683 12.0004 4.46083 12.0004 6.67016C12.0144 9.62883 9.07505 12.2855 8.00038 13.1568C6.92638 12.2848 3.98638 9.6275 4.00038 6.66683C4.00038 4.46083 5.79438 2.66683 8.00038 2.66683Z"
              fill="#869593"
            />
          </svg>

          3524 Silverside Road Suite 35B,<br />
          Wilmington, Delaware, 19810
        </li>
        <li>
          <svg
            class="footer-icon"
            width="14"
            height="14"
            viewBox="0 0 14 14"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M10.8042 7.19514C10.7424 7.13318 10.6689 7.08402 10.588 7.05048C10.5072 7.01694 10.4205 6.99967 10.3329 6.99967C10.2453 6.99967 10.1587 7.01694 10.0778 7.05048C9.9969 7.08402 9.92343 7.13318 9.86157 7.19514L8.7989 8.25781C8.30624 8.11114 7.3869 7.77781 6.80424 7.19514C6.22157 6.61247 5.88824 5.69314 5.74157 5.20047L6.80424 4.13781C6.8662 4.07595 6.91536 4.00248 6.9489 3.9216C6.98244 3.84073 6.99971 3.75403 6.99971 3.66648C6.99971 3.57892 6.98244 3.49222 6.9489 3.41135C6.91536 3.33047 6.8662 3.257 6.80424 3.19514L4.13757 0.528475C4.07571 0.466511 4.00224 0.417353 3.92137 0.383812C3.84049 0.350272 3.75379 0.333008 3.66624 0.333008C3.57868 0.333008 3.49199 0.350272 3.41111 0.383812C3.33023 0.417353 3.25676 0.466511 3.1949 0.528475L1.3869 2.33648C1.13357 2.58981 0.990905 2.93781 0.996238 3.29314C1.01157 4.24248 1.2629 7.53981 3.86157 10.1385C6.46024 12.7371 9.75757 12.9878 10.7076 13.0038H10.7262C11.0782 13.0038 11.4109 12.8651 11.6629 12.6131L13.4709 10.8051C13.5329 10.7433 13.582 10.6698 13.6156 10.5889C13.6491 10.5081 13.6664 10.4214 13.6664 10.3338C13.6664 10.2463 13.6491 10.1596 13.6156 10.0787C13.582 9.9978 13.5329 9.92433 13.4709 9.86248L10.8042 7.19514ZM10.7196 11.6698C9.88757 11.6558 7.0409 11.4325 4.80424 9.19514C2.56024 6.95114 2.3429 4.09448 2.32957 3.27914L3.66624 1.94248L5.39024 3.66648L4.52824 4.52848C4.44988 4.60678 4.39227 4.70337 4.36061 4.80952C4.32895 4.91567 4.32424 5.02804 4.3469 5.13648C4.3629 5.21314 4.75424 7.03114 5.8609 8.13781C6.96757 9.24447 8.78557 9.63581 8.86224 9.65181C8.9706 9.67511 9.08309 9.67078 9.18934 9.63921C9.29559 9.60764 9.39219 9.54984 9.47024 9.47114L10.3329 8.60914L12.0569 10.3331L10.7196 11.6698Z"
              fill="#869593"
            />
          </svg>
          +1-484-424-9683
        </li>
        <li>
          <svg
            class="footer-icon"
            width="14"
            height="12"
            viewBox="0 0 14 12"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M12.333 0.666504H1.66634C0.931008 0.666504 0.333008 1.2645 0.333008 1.99984V9.99984C0.333008 10.7352 0.931008 11.3332 1.66634 11.3332H12.333C13.0683 11.3332 13.6663 10.7352 13.6663 9.99984V1.99984C13.6663 1.2645 13.0683 0.666504 12.333 0.666504ZM12.333 1.99984V2.3405L6.99967 6.48917L1.66634 2.34117V1.99984H12.333ZM1.66634 9.99984V4.02917L6.59034 7.85917C6.70708 7.95087 6.85123 8.00071 6.99967 8.00071C7.14812 8.00071 7.29227 7.95087 7.40901 7.85917L12.333 4.02917L12.3343 9.99984H1.66634Z"
              fill="#869593"
            />
          </svg>

          support@telcomdata.com
        </li>
        <p class="footer-para-mobile">
          Copyright © 2022 TelcomeData. <br />
          All rights reserved. Terms of service
        </p>
      </ul>
    </div>
  </footer>
</template>

<script lang="ts">
export default {
  name: "Master",
};
</script>

<style>
.tags-input-wrapper {
  padding: 14px 0 38px;
}
</style>
