<!DOCTYPE html>
<html>

  <head>
    <title>Paisley & Oak</title>
    <meta charSet="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta name="description" content="More Than Just A Dress Rack">
    <meta property="og:image" content="">
    <link rel="shortcut icon" href="https://www.launchaco.com/static/favicon.ico" />
    <link href="https://fonts.googleapis.com/css?family=Poppins:300,400" rel="stylesheet">

    <link rel="stylesheet" href="https://www.launchaco.com/static/AllTemplates.min.css">

    <style>
      .launchaco-promo {
        position: fixed;
        bottom: 20px;
        left: 20px;
        cursor: pointer;
        width: 0;
        height: 0;
        z-index: 999999;
      }

      .launchaco-promo__active {
        width: initial;
        height: initial;
      }

      .launchaco-promo-speechbubble {
        font-family: -apple-system, BlinkMacSystemFont, Roboto, "Open Sans", "Helvetica Neue", sans-serif;
        position: absolute;
        left: 50px;
        top: -11px;
        padding: 9px;
        color: white;
        border-radius: 3px;
        background: linear-gradient(#227ef7, #1290fc);
        font-size: 14px;
        font-weight: 600;
        width: 93px;
        box-sizing: border-box;
        opacity: 0;
        pointer-events: none;
        transition: opacity .15s ease-in-out;
      }

      .launchaco-promo__active:hover .launchaco-promo-speechbubble {
        opacity: 1;
      }

      .launchaco-promo svg {
        transition: all .3s ease-in-out;
        opacity: 0;
      }

      .launchaco-promo__active svg {
        opacity: 1;
      }

      .launchaco-promo-speechbubble:before {
        content: "";
        width: 10px;
        height: 10px;
        transform: rotate(45deg);
        left: -4px;
        bottom: 10px;
        border-radius: 3px;
        background: #1290fc;
        z-index: 2;
        position: absolute
      }

      .launchaco-promo__active .launchaco-promo-speechbubble__animate {
        animation: popinpopup 3s linear forwards 0.1s;
      }

      @keyframes popinpopup {
        0% {
          opacity: 0;
          transform: translate3d(0, 3px, 0)
        }
        7%,
        93% {
          opacity: 1;
          transform: translate3d(0, 0, 0)
        }
        100% {
          opacity: 0;
          transform: translate3d(0, -4px, 0)
        }
      }

      .launchaco-promo-animate:hover {
        opacity: 1 !important;
      }
    </style>


    <style>
    </style>
  </head>

  <body class="font-modern">
    <div class="olive-white background background-white">
      <div class="bg">
        <div class="bg-image" style="background-image: url(&quot;https://cdn.launchaco.com/images/d1aeed1d-b0cb-4e24-94cf-cb5d640e9cd5.jpg&quot;);"></div>
        <!---->
      </div>
      <header class="header">
        <div class="container-lrg">
          <div class="flex col-12 spread">
            <a class="logo primary-color launchaco-builder-hoverable logo">Paisley &amp; Oak</a>
            <a href="mailto:contact@pandoak.com" class="nav-link secondary-color mr0">Contact</a>
          </div>
        </div>
      </header>
      <section class="section">
        <div class="container mb40">
          <div class="col-12 text-center">
            <h1 class="heading-lrg primary-color launchaco-builder-hoverable">More Than Just A Dress Rack</h1>
            <h2 class="subheading secondary-color mt20 launchaco-builder-hoverable">A functional space for your daughter's most cherished memories.</h2>
            <div class="mt40">
              <a href="https://www.instagram.com/paisley.oak/" target="_blank" class="button mobile-text-center mt10 launchaco-builder-hoverable mr10 mobile-text-center accent-bg fill-white primary-color">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 489.84 489.84">
                  <path d="M244.92 44.13c65.4 0 73.14.25 99 1.43 23.85 1.11 36.82 5.11 45.45 8.43a75.88 75.88 0 0 1 28.16 18.32 75.88 75.88 0 0 1 18.32 28.16c3.35 8.63 7.34 21.6 8.43 45.48 1.18 25.83 1.43 33.57 1.43 99s-.25 73.14-1.43 99c-1.09 23.88-5.08 36.85-8.43 45.48a81.11 81.11 0 0 1-46.48 46.48c-8.63 3.35-21.6 7.34-45.48 8.43-25.82 1.18-33.57 1.43-99 1.43s-73.15-.25-99-1.43c-23.88-1.09-36.85-5.08-45.48-8.43a75.88 75.88 0 0 1-28.11-18.38 75.88 75.88 0 0 1-18.31-28.16c-3.35-8.63-7.34-21.6-8.43-45.48-1.18-25.83-1.43-33.57-1.43-99s.25-73.14 1.43-99c1.09-23.88 5.08-36.85 8.43-45.48a75.88 75.88 0 0 1 18.31-28.1 75.88 75.88 0 0 1 28.16-18.32c8.63-3.35 21.6-7.34 45.48-8.43 25.83-1.18 33.57-1.43 99-1.43m0-44.13c-66.52 0-74.86.28-101 1.47S100.07 6.8 84.49 12.85a120.06 120.06 0 0 0-43.38 28.26 120.06 120.06 0 0 0-28.25 43.38c-6.06 15.58-10.2 33.38-11.39 59.45S0 178.4 0 244.94s.28 74.86 1.47 101 5.33 43.87 11.38 59.45a120.06 120.06 0 0 0 28.25 43.38 120.06 120.06 0 0 0 43.38 28.25c15.58 6.05 33.38 10.19 59.45 11.38s34.46 1.47 101 1.47 74.86-.28 101-1.47 43.87-5.33 59.45-11.38a125.24 125.24 0 0 0 71.63-71.63c6.05-15.58 10.19-33.38 11.38-59.45s1.47-34.46 1.47-101-.28-74.86-1.47-101-5.33-43.87-11.38-59.45a120.06 120.06 0 0 0-28.25-43.38 120.06 120.06 0 0 0-43.38-28.25C389.77 6.8 371.97 2.67 345.9 1.47S311.44 0 244.9 0z"></path>
                  <path d="M244.92 119.15a125.77 125.77 0 1 0 125.77 125.77 125.77 125.77 0 0 0-125.77-125.77zm0 207.41a81.64 81.64 0 1 1 81.64-81.64 81.64 81.64 0 0 1-81.64 81.64z"></path>
                  <circle cx="375.66" cy="114.18" r="29.39"></circle>
                </svg>
                <span> Learn More </span>
              </a>
              <a href="" target="_blank" class="button mobile-text-center mt10 launchaco-builder-hoverable">
                <span> Order Now </span>
              </a>
            </div>
          </div>
        </div>
        <!---->
      </section>
    </div>
    <section id="pricing-1" class="section olive-white" sitemeta="[object Object]" activepage="Landing">
      <div class="container mb75 text-center">
        <div class="col-12">
          <h4 class="heading primary-color launchaco-builder-hoverable">Simple Pricing</h4>
          <p class="paragraph secondary-color launchaco-builder-hoverable">Endless Memories</p>
        </div>
      </div>
      <div class="container-lrg">
        <div class="col-12">
          <div class="card flex mobile-flex-wrap">
            <div class="col-4 pad30 flex flex-column spread launchaco-builder-hoverable">
              <div class="mb20">
                <h4 class="bold primary-color">Child Sized Rack</h4>
                <b class="heading primary-color">$119.99</b>
                <span class="paragraph secondary-color"></span>
                <ul class="mt20">
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Handmade Wooden Rack</span>
                  </li>
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Parent Practical</span>
                  </li>
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Kid Approved</span>
                  </li>
                </ul>
              </div>
              <a href="" target="_blank" class="button mobile-text-center mt10 launchaco-builder-hoverable button__full mobile-text-center accent-bg primary-color">
                <span> Buy Now </span>
              </a>
            </div>
            <div class="col-4 pad30 flex flex-column spread launchaco-builder-hoverable">
              <div class="mb20">
                <h4 class="bold primary-color">Doll Sized Rack</h4>
                <b class="heading primary-color">$59.99</b>
                <span class="paragraph secondary-color"></span>
                <ul class="mt20">
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Handmade Wooden Rack</span>
                  </li>
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Perfect for American Girl Doll Clothes</span>
                  </li>
                </ul>
              </div>
              <a href="" target="_blank" class="button mobile-text-center mt10 launchaco-builder-hoverable button__full mobile-text-center accent-bg primary-color">
                <span> Buy Now </span>
              </a>
            </div>
            <div class="col-4 pad30 flex flex-column spread launchaco-builder-hoverable">
              <div class="mb20">
                <h4 class="bold primary-color">Rack Bundle</h4>
                <b class="heading primary-color">$149.99</b>
                <span class="paragraph secondary-color"></span>
                <ul class="mt20">
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Both Racks Included</span>
                  </li>
                  <li class="flex mb20">
                    <svg width="22px" height="22px" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="svg-fill noshrink mr20">
                      <g transform="translate(4.000000, 5.000000)">
                        <path d="M5.24961475,8.39956394 L2.16512063,5.35475362 C1.74038521,4.93548271 1.05017933,4.9352057 0.624646383,5.35526395 C0.199019838,5.77541456 0.198881924,6.45614266 0.624129379,6.8759191 L4.35212111,10.555948 C4.38658274,10.6034965 4.42544251,10.6488955 4.46870038,10.6915969 C4.70907746,10.9288814 5.03375662,11.0320952 5.3475228,11.0013023 C5.59592563,10.9812599 5.83876209,10.8774981 6.02880771,10.6898975 C6.06831079,10.6509027 6.10414872,10.6096632 6.13632157,10.5665961 L13.9850992,2.81879759 C14.4107939,2.39857976 14.410861,1.71746456 13.985328,1.29740632 C13.5597015,0.8772557 12.8697673,0.877449143 12.444108,1.29763217 L5.24961475,8.39956394 Z"></path>
                      </g>
                    </svg>
                    <span class="span secondary-color">Shipped Straight To Your Door</span>
                  </li>
                </ul>
              </div>
              <a href="" target="_blank" class="button mobile-text-center mt10 launchaco-builder-hoverable button__full mobile-text-center accent-bg primary-color">
                <span> Buy Now </span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="feature-2" class="section olive-flat" sitemeta="[object Object]" activepage="Landing">
      <div class="container-lrg flex">
        <div class="flex col-6 flex-column mobile-text-center center-vertical">
          <i class="icon mobile-center-icon secondary-bg launchaco-builder-hoverable">
            <svg class="svg-fill" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 25 25">
              <path d="M8.354 6.146c-.951-.95-.903-3.794-.706-5.169a12.502 12.502 0 0 1 11.919 1.216 3.221 3.221 0 0 0-.981 2.017 4.127 4.127 0 0 0 1.06 3.143c.365.366.362 2.283-.19 4.116a2.2 2.2 0 0 1-4.249-.224c-.132-.676-.85-4.095-1.853-5.098-.678-.678-1.69-.364-2.67-.063-1.106.34-1.865.53-2.33.063zm12.033-3.34a2.233 2.233 0 0 0-.806 1.506 3.148 3.148 0 0 0 .772 2.335c.902.902.53 3.55.06 5.11a3.198 3.198 0 0 1-6.186-.318 12.355 12.355 0 0 0-1.58-4.585c-.251-.25-.97-.03-1.669.186-1.071.33-2.405.74-3.331-.186-1.174-1.175-1.199-3.791-1.061-5.367a12.482 12.482 0 0 0-2.52 20.22c.18-2.598.849-7.13 3.323-7.694a3.717 3.717 0 0 1 2.96.306 4.396 4.396 0 0 1 1.642 3.088c.383 2.03 1.552 3.093 2.509 3.093.647 0 1.415-1.083 2.092-2.04.857-1.209 1.743-2.46 2.908-2.46 1.662 0 2.79 1.43 3.13 3.803a12.47 12.47 0 0 0-2.243-16.997zM19.5 17c-.647 0-1.415 1.083-2.092 2.04-.857 1.209-1.743 2.46-2.908 2.46-1.622 0-3.058-1.607-3.491-3.907A3.578 3.578 0 0 0 9.8 15.155a2.796 2.796 0 0 0-2.19-.168c-1.735.397-2.467 4.412-2.59 7.512a12.446 12.446 0 0 0 16.712-1.594C21.65 18.94 21.037 17 19.5 17z"></path>
            </svg>
          </i>
          <h3 class="bold primary-color launchaco-builder-hoverable">Handmade</h3>
          <p class="paragraph secondary-color launchaco-builder-hoverable">Paisley &amp; Oak takes pride in crafting the best experience for your child. Every detail is carefully thought out and meticulously implemented.</p>
        </div>
        <div class="col-6 flex center-horizontal center-vertical">
          <div class="launchaco-builder-hoverable">
            <div class="">
              <img src="https://cdn.launchaco.com/images/bb84512f-0217-41ff-9b50-6189c61cbedc.jpg" alt="Screenshot of small App" class="custom-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="cta-3" class="section olive-white" sitemeta="[object Object]" activepage="Landing">
      <!---->
      <div class="container text-center">
        <div class="col-12">
          <h4 class="heading primary-color launchaco-builder-hoverable">We'd Love To Serve You</h4>
          <p class="paragraph mt20 secondary-color launchaco-builder-hoverable">Let us craft a rack just for you.</p>
          <div class="mt40">
            <a href="" target="_blank" class="button mobile-text-center mt10 launchaco-builder-hoverable mobile-text-center accent-bg primary-color">
              <span> Order Now </span>
            </a>
          </div>
        </div>
      </div>
    </section>
    <footer id="footer-4" class="section text-center olive-white" sitemeta="[object Object]" activepage="Landing">
      <div class="container col-12">
        <!---->
        <div>
          <!---->
          <a href="https://facebook.com/paisleyandoak" target="_blank" class="socialicons accent-bg facebook"></a>
          <a href="mailto:contact@pandoak.com" class="socialicons accent-bg email"></a>
          <a href="https://instagram.com/paisley.oak" target="_blank" class="socialicons accent-bg instagram"></a>
        </div>
        <div class="mt50">
          <span class="span secondary-color">©</span>
          <span class="span secondary-color">Paisley &amp; Oak</span>
        </div>
      </div>
    </footer>

    <a id="visual-dreamer" class="launchaco-promo" target="_blank" href="https://www.launchaco.com/">
      <svg width="40" height="40" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient x1="9.394%" y1="57.704%" x2="105.69%" y2="27.607%" id="a">
            <stop stop-color="#007FFF" offset="0%" />
            <stop stop-color="#1290FC" offset="100%" />
          </linearGradient>
          <linearGradient x1="50%" y1="0%" x2="50%" y2="137.557%" id="b">
            <stop stop-color="#FF9386" offset="0%" />
            <stop stop-color="#FF5F86" offset="100%" />
          </linearGradient>
          <linearGradient x1="30.817%" y1="-31.6%" x2="63.808%" y2="151.297%" id="c">
            <stop stop-color="#D7EDFF" offset="0%" />
            <stop stop-color="#FFF" stop-opacity="0" offset="100%" />
          </linearGradient>
        </defs>
        <g fill="none">
          <circle fill="url(#a)" cx="19.832" cy="19.832" r="19.832" />
          <path d="M26.616.325l4.308 12.587-4.669-.315L26.218.388c0-.105.091-.19.204-.191.088 0 .166.051.194.128z" fill="url(#b)" transform="rotate(45 28.571 6.555)" />
          <path d="M32.031 35.658c-6.164 2.721-12.745-4.33-11.992-10.011 2.617.782 4.626.997 7.904 2.01 2.34.769 4.152.479 5.386-1.13 1.234-1.607 1.316-3.502 0-5.158-4.826-5.49 0 0-10.516-12.264l2.923-2.95C.117 4.123 5.302 32.333 6.903 35.095c4.01 3.54 14.11 8.709 25.128.563z"
            fill="#FFF" />
          <path d="M9.782 19.176l-.034-.016c0 5.76 4.425 21.794 22.185 16.378-6.148 2.716-12.71-4.29-12.006-9.97a7.394 7.394 0 0 1-2.73.519c-3.922 0-7.135-3.047-7.415-6.911z" fill="url(#c)" />
          <ellipse fill="#354158" cx="22.185" cy="14.958" rx="2.017" ry="1.849" />
          <ellipse fill="#354158" cx="22.185" cy="14.958" rx="2.017" ry="1.849" />
        </g>
      </svg>
      <div class="launchaco-promo-speechbubble launchaco-promo-speechbubble__animate">Built With Launchaco</div>
      <div class="launchaco-promo-speechbubble">Built With Launchaco</div>
    </a>
  </body>

  <script>
    window.onscroll = function()
    {
      showAd()
    }

    function showAd()
    {
      var scrollBarPosition = window.pageYOffset | document.body.scrollTop;

      // At specifiv position do what you want
      if (scrollBarPosition > 300)
      {
        document.getElementById("visual-dreamer").className = "launchaco-promo launchaco-promo__active";
        window.onscroll = function() {};
      }
    }
  </script>

</html>
