<template>
  <nav class="nav taffix">
    <div class="container">
      <div class="logo">
        <a href="/"
          ><div class="nav-brand">
            <img src="img/white-logo.png" alt="" />
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
              <li><a href="number-mapping.html">Number Mapping</a></li>
              <li><a href="number-scrubbing.html">Number Scrubbing</a></li>
              <li><a href="#">Number Monitoring</a></li>
              <li><a href="data-subscription.html">Data Subscription</a></li>
              <li><a href="#">Number API </a></li>
            </ul>
          </li>
          <li><a href="pricing.html">Pricing</a></li>
          <li><a href="about-us.html">About Us</a></li>
          <li><a href="api-key.html">API</a></li>
          <li><a href="contact-us.html">Contact</a></li>
          <li id="login-container">
            <a class="login-btn topfix" id="login-btn" onclick="logoutbtn()"
              >Log Out</a
            >
          </li>
        </ul>
      </div>
      <span class="navTrigger taffix">
        <i></i>
        <i></i>
        <i></i>
      </span>
    </div>
  </nav>

  <section class="api-key-section">
    <svg
      width="25"
      height="24"
      viewBox="0 0 25 24"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M7.87547 16.7812L9.12547 15.2192L5.10147 12.0002L9.12547 8.78123L7.87547 7.21923L2.87547 11.2192C2.75831 11.3129 2.66374 11.4317 2.59874 11.5669C2.53375 11.7021 2.5 11.8502 2.5 12.0002C2.5 12.1502 2.53375 12.2983 2.59874 12.4335C2.66374 12.5687 2.75831 12.6875 2.87547 12.7812L7.87547 16.7812ZM17.1255 7.21923L15.8755 8.78123L19.8995 12.0002L15.8755 15.2192L17.1255 16.7812L22.1255 12.7812C22.2426 12.6875 22.3372 12.5687 22.4022 12.4335C22.4672 12.2983 22.5009 12.1502 22.5009 12.0002C22.5009 11.8502 22.4672 11.7021 22.4022 11.5669C22.3372 11.4317 22.2426 11.3129 22.1255 11.2192L17.1255 7.21923ZM15.4765 3.21623L11.4765 21.2162L9.52347 20.7822L13.5235 2.78223L15.4765 3.21623Z"
        fill="#008F7D"
      />
    </svg>
    <h1 class="api-key-head">API Key</h1>
    <div class="api-key-container">
      <label class="api-label" for="">Your API Key</label>
      <input class="api-key-input" type="text" value="sHmfg45mAwz" />
      <div class="text-align-center">
        <button class="api-refresh-btn">Refresh Key</button>
      </div>
    </div>
  </section>

  <footer class="footer">
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
          <li>Number Scubbing</li>
          <li>Number Mapping</li>
          <li>Number Monitoring</li>
          <li>Data Subscription</li>
          <li>Number API</li>
        </ul>
      </div>
      <div class="footer-sub-menu">
        <h3 class="footer-menu-head">Menu</h3>
        <ul class="footer-menu-list">
          <li>Pricing</li>
          <li>About Us</li>
          <li>Contact</li>
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
  name: "api",
};
</script>

<style></style>
