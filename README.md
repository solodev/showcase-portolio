# showcase-portolio
One could argue that a majority of websites are largely a place to showcase work whether it is that of a personal portfolio, a client portfolio, or even an offering of products or services. Ultimately, whether you fit into any of those personas, you are all trying to do the same thing.  

You're all trying to showcase what you have to offer in a way that is aesthetically amazing so that others want to engage with you. Your website is the best place to do this but where your website is hosted and managed can have a massive effect on how much web design control you have over your showcase.  In this tutorial we are utilizing [echo.js]() to lazy load the images so you have a wonderfully designed portfolio without compromising on page speed.

## Tutorial

For detailed instructions, view Solodev's [How to Craft a Beautiful Web Design to Showcase your Portfolio](https://www.solodev.com/blog/web-design/how-to-craft-a-beautiful-web-design-to-showcase-your-portfolio.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/hpqnbnt0/).

## HTML

The portfolio contains the following basic HTML markup.

```
<section class="paddingSection100 work-tiles workTiles">
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-md-offset-2">
          <h2>Unlock your digital potential.</h2>
          <p class="paddingBottom45">Craft this web design into your own by replacing images and styles with that consistent with your goals.</p>
        </div>
      </div>
      <ul class="row">
        <li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 1" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-1.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 2" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-2.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 3" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-3.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 4" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-4.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 5" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-5.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 6" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-6.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 7" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-7.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 8" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-8.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 9" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-9.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 10" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-10.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 11" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-11.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
		<li class="col-xs-6 col-md-3 work-tiles-items">
          <div class="portfolioInner">
            <a href="#"><img alt="Image Alt 12" class="img-responsive" src="https://www.solodev.com/assets/featured-portfolio/client-loader.gif" data-echo="https://www.solodev.com/assets/featured-portfolio/portfolio-item-12.jpg"></a>
            <div class="textOverlay">
              <span>Portfolio Item Title</span>
            </div>
          </div>
        </li>
      </ul>
      <div class="text-center paddingTop40">
        <a href="#" class="btn btn-home">View Portfolio</a>
      </div>
    </div>
</section>
```

## CSS

All required CSS can be found in portfolio.css

## JavaScript

All required JavaScript is below and should be included inline:

```
<script>
  echo.init();
</script>
```
## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="portfolio.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://rawgit.com/toddmotto/echo/master/dist/echo.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
