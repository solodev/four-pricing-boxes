# four-pricing-boxes
Anyone with a website normally wants to keep people on the page as long as they possibly can with as few distractions as possible. However, there are moments when it’s necessary for a user to exit your page and visit a third-party organization linked through your website. Sometimes it’s to fill out forms. Maybe it’s to see a special offering from a partnering business or group. But regardless of where your user will end up, it’s important to tell them they won’t be on your website once they click that link.
  		  
## Tutorial		  
For detailed instruction's, view Solodev's [How to Make an External Link Popup Box](https://www.solodev.com/blog/web-design/how-to-make-an-external-link-popup-box.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/ampzuxmf/).

## HTML

The tutorial contains the following basic HTML markup.

```
    <section class="pricing text-center mx-4 my-5">
        <div class="pricing-container d-block mx-auto">
          <h1 class="font-weight-normal">Pricing to fit your entertainment needs</h1>
          <h2 class="h3 pb-5 font-weight-normal">Sign up today for to start your entertainment journey</h2>
      
      
          <div class="pricing-section mt-5">
            <div class="row pricing-cards pricing-cards-monthly text-center">
              <div class="col-md-6 col-lg-3">
                <div class="pricing-card card-panel shadow">
                  <div class="icon"><img class="d-block mx-auto" alt="Monkey Wave" src="https://www.solodev.com/_/images/monkey.jpg" /></div>
      
                  <div class="text-center font-weight-bold pricing-title">Bronze</div>
      
                  <div class="price price-month text-center h3">$25<span class="text-bold">/month</span></div>
      
                  <div class="text-center price-month"><a class="btn btn-info d-block" href="https://www.solodev.com//free-trial/" title="Let’s Go">Let&rsquo;s Go</a></div>
      
      
                  <ul class="text-center p-0">
                    <li>Live Television</li>
                    <li>On-Demand Sporting Events</li>
                  </ul>
                </div>
              </div>
      
              <div class="col-md-6 col-lg-3">
                <div class="pricing-card card-panel shadow">
                  <div class="icon"><img class="d-block mx-auto" alt="Panda Astronaut" src="https://www.solodev.com/_/images/rocket-spacebear.jpg" /></div>
      
                  <div class="text-center font-weight-bold pricing-title">Silver</div>
      
                  <div class="price price-month text-center h3">$50<span class="text-bold">/month</span></div>
      
      
                  <div class="text-center price-month"><a class="btn btn-info d-block" href="https://www.solodev.com//free-trial/" title="Let’s Go">Let&rsquo;s Go</a></div>
      
      
                  <ul class="text-center p-0">
                    <li class="text-primary">Everything in Bronze <span class="lead pos-r">+</span></li>
                    <li>Premium Service Content</li>
                    <li>Live Sporting Events from the Most Popular Networks</li>
                  </ul>
                </div>
              </div>
      
              <div class="col-md-6 col-lg-3">
                <div class="pricing-card pricing-card-pro pt-4 card-panel shadow">
                  <p class="text-center text-danger most-popular">&ndash; Most Popular &ndash;</p>
      
                  <div class="icon"><img class="d-block mx-auto" alt="Captain Astronaut" src="https://www.solodev.com/_/images/kelvin-spacey.jpg" /></div>
      
                  <div class="text-center font-weight-bold pricing-title">Gold</div>
      
                  <div class="price price-month text-center h3">$75<span class="text-bold">/month</span></div>
      
      
                  <div class="text-center price-month"><a class="btn btn-info d-block btn-danger" href="https://www.solodev.com//free-trial/" title="Let’s Go">Let&rsquo;s Go</a></div>
      
      
                  <ul class="text-center p-0">
                    <li class="text-danger">Everything in Silver <span class="lead pos-r">+</span></li>
                    <li>All NFL/NBA/MLB Sporting Events</li>
                    <li>Home Workout Shows (Aerobics, Yoga, etc)</li>
                    <li>Apple Watch/Fitbit Compatibility</li>
                  </ul>
                </div>
              </div>
      
              <div class="col-md-6 col-lg-3">
                <div class="pricing-card card-panel shadow">
                  <div class="icon"><img class="d-block mx-auto" alt="Commander Astronaut" src="https://www.solodev.com/_/images/diana-spacey2.jpg" /></div>
      
                  <div class="text-center font-weight-bold pricing-title">Platinum</div>
      
                  <div class="price price-month text-center h3">$100<span class="text-bold">/month</span></div>
      
      
                  <div class="text-center price-month"><a class="btn btn-info d-block" href="https://www.solodev.com//free-trial/" title="Let’s Go">Let&rsquo;s Go</a></div>
      
      
                  <ul class="text-center p-0">
                    <li class="text-primary">Everything in Gold <span class="lead pos-r">+</span></li>
                    <li>Connect Up To 10 Different Accounts</li>
                    <li>All Shows on Demand Right After Air</li>
                    <li>One Free Game Download a Month</li>
                    <li>Access to Premium Content Weeks Before Release</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
```

## CSS

All required CSS is contained with four-pricing-boxes.css


## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

