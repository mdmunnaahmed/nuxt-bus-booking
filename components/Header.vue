<template>
  <header class="header">
    <div class="header-top">
      <div class="container">
        <div class="header-top-area">
          <ul class="left-content">
            <li>
              <i class="las la-phone"></i>
              <NuxtLink to="tel:012839"> +880 2483 03940 </NuxtLink>
            </li>
            <li>
              <i class="las la-envelope-open"></i>
              <NuxtLink to="mailto:msdmuntoa@gmail.com"> shohanuahman@gmail.com </NuxtLink>
            </li>
          </ul>
          <div class="right-content">
            <NuxtLink class="cancel-ticket" to="cancel-ticket.html">Cancel Ticket</NuxtLink>
            <div>
              <select class="langSel">
                <option value="lang1">English</option>
                <option value="lang2">Bangla</option>
              </select>
            </div>
            <ul class="header-login">
              <li>
                <NuxtLink class="sign-in" to="sign-in.html"><i class="fas fa-sign-in-alt"></i>Sign In</NuxtLink>
              </li>
              <li>/</li>
              <li>
                <NuxtLink class="sign-up" to="sign-up.html"><i class="fas fa-user-plus"></i>Sign Up</NuxtLink>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="header-bottom">
      <div class="container">
        <div class="header-bottom-area">
          <div class="logo">
            <NuxtLink to="./index.html">
              <img src="/images/logo.png" alt="logo" />
            </NuxtLink>
          </div>

          <ul class="menu">
            <li>
              <NuxtLink to="index.html">Home</NuxtLink>
            </li>
            <li>
              <NuxtLink to="about.html">About</NuxtLink>
            </li>
            <li>
              <NuxtLink to="#0">Booking</NuxtLink>
              <ul class="sub-menu">
                <li>
                  <NuxtLink to="bus-ticket.html">Bus Ticket</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="reserve.html">Reserve Bus</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="cancel-ticket.html">Cancel Ticket</NuxtLink>
                </li>
              </ul>
            </li>
            <li>
              <NuxtLink to="faq.html">Faq</NuxtLink>
            </li>
            <li>
              <NuxtLink to="#0">Pages</NuxtLink>
              <ul class="sub-menu">
                <li>
                  <NuxtLink to="user-dashboard.html">Dashboard</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="sign-in.html">Sign In</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="sign-up.html">Sign Up</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="packages.html">Packages</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="terms-condition.html">Terms & Conditions</NuxtLink>
                </li>
              </ul>
            </li>
            <li>
              <NuxtLink to="#0">Blog</NuxtLink>
              <ul class="sub-menu">
                <li>
                  <NuxtLink to="blog.html">Blog</NuxtLink>
                </li>
                <li>
                  <NuxtLink to="blog-details.html">Blog Details</NuxtLink>
                </li>
              </ul>
            </li>
            <li>
              <NuxtLink to="contact.html">Contact</NuxtLink>
            </li>
          </ul>

          <div class="d-flex">
            <NuxtLink to="bus-ticket.html" class="cmn--btn btn--sm me-4 me-lg-0">Buy Tickets</NuxtLink>
            <div class="header-trigger-wrapper d-flex d-lg-none">
              <div class="header-trigger d-block d-lg-none">
                <span></span>
              </div>
              <div class="top-bar-trigger">
                <i class="las la-ellipsis-v"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  // Your script code
};
</script>

<style lang="scss">
/* Your SASS/SCSS code */
</style>