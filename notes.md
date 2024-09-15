get 20 images each for: Phones, Laptops, Tablets, Monitors, TVs, Smart Watches, Cameras, Drones
create productData object in a .json file with following properties:

- name
- description
- price
- img
- alt
-

Design

- Content
- Layout (Low Fidelity Wireframe)
- Design (High Fidelity Wireframe) - Fonts - Colours - Images - Icons
  Figma
- Responsive Design
- Protoypes

To Do:

- Create Homepage (Using Baymard Guidelines)

Backlog Features:

- create a mega menu
- wish list
- cart
- checkout
-

Cart Html
Cart Css

Cart Html

<aside>
      <article id="cart">
        <h1>Your Cart <span class="no-of-items"></span></h1>
        <ul class="products-wrapper">
          <!-- product -->
          <li class="product-wrap">
            <article class="product">
              <!-- details -->
              <div class="product-info">
                <img
                  class="product-img"
                  src="../img/phone-1.avif"
                  alt="smartphone one"
                />
                <div class="product-details">
                  <h3 class="product-name">Device Name</h3>
                  <p class="product-description">
                    Description of the device...
                  </p>
                </div>
              </div>
              <div class="items-quantity-price">
                <p class="product-price">£999</p>
                <!-- Quantity of items -->
                <article class="quantity">
                  <button class="minus">-</button>
                  <span class="quantity">0</span>
                  <button class="add">+</button>
                </article>
              </div>
            </article>
          </li>
          <!-- product -->
          <li class="product-wrap">
            <article class="product">
              <!-- details -->
              <div class="product-info">
                <img
                  class="product-img"
                  src="../img/phone-1.avif"
                  alt="smartphone one"
                />
                <div class="product-details">
                  <h3 class="product-name">Device Name</h3>
                  <p class="product-description">
                    Description of the device...
                  </p>
                </div>
              </div>
              <div class="items-quantity-price">
                <p class="product-price">£999</p>
                <!-- Quantity of items -->
                <article class="quantity">
                  <button class="minus">-</button>
                  <span class="quantity">0</span>
                  <button class="add">+</button>
                </article>
              </div>
            </article>
          </li>
          <!-- product -->
          <li class="product-wrap">
            <article class="product">
              <!-- details -->
              <div class="product-info">
                <img
                  class="product-img"
                  src="../img/phone-1.avif"
                  alt="smartphone one"
                />
                <div class="product-details">
                  <h3 class="product-name">Device Name</h3>
                  <p class="product-description">
                    Description of the device...
                  </p>
                </div>
              </div>
              <div class="items-quantity-price">
                <p class="product-price">£999</p>
                <!-- Quantity of items -->
                <article class="quantity">
                  <button class="minus">-</button>
                  <span class="quantity">0</span>
                  <button class="add">+</button>
                </article>
              </div>
            </article>
          </li>
          <!-- product -->
          <li class="product-wrap">
            <article class="product">
              <!-- details -->
              <div class="product-info">
                <img
                  class="product-img"
                  src="../img/phone-1.avif"
                  alt="smartphone one"
                />
                <div class="product-details">
                  <h3 class="product-name">Device Name</h3>
                  <p class="product-description">
                    Description of the device...
                  </p>
                </div>
              </div>
              <div class="items-quantity-price">
                <p class="product-price">£999</p>
                <!-- Quantity of items -->
                <article class="quantity">
                  <button class="minus">-</button>
                  <span class="quantity">0</span>
                  <button class="add">+</button>
                </article>
              </div>
            </article>
          </li>
          <!-- product -->
          <li class="product-wrap">
            <article class="product">
              <!-- details -->
              <div class="product-info">
                <img
                  class="product-img"
                  src="../img/phone-1.avif"
                  alt="smartphone one"
                />
                <div class="product-details">
                  <h3 class="product-name">Device Name</h3>
                  <p class="product-description">
                    Description of the device...
                  </p>
                </div>
              </div>
              <div class="items-quantity-price">
                <p class="product-price">£999</p>
                <!-- Quantity of items -->
                <article class="quantity">
                  <button class="minus">-</button>
                  <span class="quantity">0</span>
                  <button class="add">+</button>
                </article>
              </div>
            </article>
          </li>
        </ul>
        <hr />
        <p class="sum">Total: <span class="total">£899</span></p>
        <a href="" class="btn">checkout</a>
      </article>
    </aside>

Cart Css

#cart {
font-size: 0.9em;
background-color: antiquewhite;
padding: 1em;
position: absolute;
top: 0;
right: 0;
height: 100vh;
width: 320px;
}

#cart h1 {
font-size: 2.8em;
padding-block: 1em;
}

#cart .products-wrapper {
flex-direction: column;
width: 95%;
height: 65%;
}

#cart .product-wrap {
padding: 1em;
min-width: 100%;
}

#cart .product {
display: flex;
flex-direction: column;
align-items: center;
}

#cart .product-info {
display: flex;
flex-direction: column;
text-align: center;
}

#cart .product-img {
height: 80px;
width: 80px;
margin-inline: auto;
}

#cart .product-details {
display: flex;
flex-direction: column;
justify-content: center;
}

#cart .product-name {
font-size: 1.2em;
}

#cart .product-description {
margin: 0;
}

#cart .product-price {
text-align: center;
}

#cart .quantity {
display: flex;
align-items: center;
gap: 0.5em;
background-color: lightgrey;
padding: 0.25em;
border-radius: 1.5em;
}

#cart .minus,
#cart .add {
padding: 0.4em 0.7em;
background-color: gray;
color: #fff;
border-radius: 2em;
}

#cart .btn {
width: 100%;
text-align: center;
font-size: 1.3em;
text-transform: capitalize;
padding: 0.5em;
margin-top: 1em;
}

#cart .sum {
font-size: 3em;
}

#cart .total {
font-weight: bold;
color: red;
margin-left: 0.5em;
}

Intermediary Category Page Html

<main id="main">
      <section id="product-list-items">
        <div class="container">
          <h1 class="section-heading">Devices</h1>
          <ul class="categories-wrapper">
            <!-- category -->
            <li class="category-wrap">
              <a href="pages/category/devices.html">
                <article class="category-bg devices">
                  <h3 class="category-name">Devices</h3>
                  <p class="category-description">Check out the devices.</p>
                </article>
              </a>
            </li>

            <!-- category -->
            <li class="category-wrap">
              <a href="pages/category/gadgets.html">
                <article class="category-bg gadgets">
                  <h3 class="category-name">Gadgets</h3>
                  <p class="category-description">Check out the gadgets.</p>
                </article>
              </a>
            </li>

            <li class="category-wrap">
              <a href="pages/category/accessories.html">
                <article class="category-bg accessories">
                  <h3 class="category-name">Accessories</h3>
                  <p class="category-description">Check out the accessories.</p>
                </article>
              </a>
            </li>
          </ul>
        </div>
      </section>
    </main>

Intermediary Category Page Styles

#product-list-items .categories-wrapper {
display: grid;
grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
}

Product Css

/_ Breadcrumbs _/
#breadcrumbs {
padding-block: 1em;
font-size: 1.5em;
}

#breadcrumbs a {
color: black;
}

#product-display {
display: flex;
align-items: center;
justify-content: center;
gap: 8em;
flex-wrap: wrap;
}

#product-display > \* {
width: 500px;
}

.product-images {
display: flex;
flex-direction: column;
}

.other-images {
margin-top: 2em;
width: 500px;
display: flex;
flex-wrap: wrap;
justify-content: space-between;
}

.product-name {
font-size: 4em;
margin-bottom: 0.2em;
}

.product-summary {
font-size: 2em;
}

summary {
font-size: 1.7em;
padding: 0.5em;
}

.add-to-cart-btn {
margin-top: 1.5em;
margin-left: 0.5em;
}

#product-display .btn {
font-size: 1.2em;
}

.product-price {
font-size: 2.5em;
margin-left: 0.8em;
font-weight: bold;
}

.read-more-btn {
color: black;
font-size: 1.2em;
}

@media screen and (max-width: 520px) {
.main-product-img {
height: 300px;
width: 300px;
}
.other-images {
width: 300px;
}
.other-image {
width: 65px;
height: 65px;
}
#product-display {
gap: 3em;
}
}

Checkout Form Html

      <section id="checkout">
        <div class="container">
          <h1 class="section-heading">Checkout</h1>
          <section class="checkout">
            <form class="checkout-form">
              <h2 class="section-heading">Checkout Form</h2>
              <p>Please fill in the checkout form below.</p>
              <fieldset class="your-info">
                <legend>Your information</legend>
                <ul class="form-fields">
                  <li class="form-field">
                    <label for="full-name">Full Name</label>
                    <input
                      type="text"
                      id="full-name"
                      name="full-name"
                      placeholder="Bob Smith"
                    />
                  </li>
                  <li class="form-field">
                    <label for="email">Email</label>
                    <input
                      type="email"
                      id="email"
                      name="email"
                      placeholder="bobsmith@example.com"
                    />
                  </li>
                </ul>
              </fieldset>
              <fieldset class="payment-details">
                <legend>Payment Details</legend>
                <ul class="form-fields">
                  <li class="form-field">
                    <label for="card">Credit Card</label>
                    <input
                      type="tel"
                      id="card"
                      name="card"
                      placeholder="XXXX XXXX XXXX XXXX"
                    />
                  </li>
                  <li class="form-field">
                    <label for="expiry">Expiry Date</label>
                    <input
                      type="tel"
                      id="expiry"
                      name="expiry"
                      placeholder="XX / XX"
                    />
                  </li>
                </ul>
              </fieldset>
            </form>
            <aside class="order-summary"></aside>
          </section>
        </div>
      </section>

Template Product Page Html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <meta
      name="description"
      content="160 characters description of web page..."
    />
    <!-- Font awesome -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
      integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <!-- styles -->
    <link rel="stylesheet" href="../styles/product.css" />
    <link rel="stylesheet" href="../styles/style.css" />
    <!-- scripts -->
    <script src="app.js" defer></script>
    <title>60 character title...</title>
  </head>
  <body id="body">
    <header id="header">
      <!-- Secondary Nav -->
      <nav id="secondary-nav">
        <div class="container">
          <!-- social links -->
          <ul class="social-links">
            <li class="social-link">
              <a href="" title="Pimoky on Facebook">
                <i class="fab fa-facebook"></i>
              </a>
            </li>
            <li class="social-link">
              <a href="" title="Pimoky on Twitter">
                <i class="fab fa-twitter"></i>
              </a>
            </li>
            <li class="social-link">
              <a href="" title="Pimoky on Instagram">
                <i class="fab fa-instagram"></i>
              </a>
            </li>
            <li class="social-link">
              <a href="" title="Pimoky on TikTok">
                <i class="fab fa-tiktok"></i>
              </a>
            </li>
          </ul>

          <!-- secondary nav links -->
          <menu class="secondary-nav-links">
            <li class="secondary-nav-link"><a href="">About Pimoky</a></li>
            <li class="secondary-nav-link"><a href="">FAQs</a></li>
            <li class="secondary-nav-link"><a href="">Customer Service</a></li>
            <li class="secondary-nav-link help-link"><a href="">Help</a></li>
          </menu>
        </div>
      </nav>

      <!-- Search -->
      <article id="search">
        <div class="container">
          <!-- logo -->
          <a class="logo-link" href="../index.html" title="Pimoky homepage">
            <img
              class="logo-img"
              src="../../img/pimoky-logo.svg"
              alt="The logo of the brand Pimoky, an online retailer supplying technology devices i.e. laptops, phones, tvs, smart watches."
              loading="lazy"
            />
          </a>

          <!-- search bar -->
          <input
            class="search-bar"
            type="search"
            name="search-bar"
            id="search-bar"
            class="search-bar"
            placeholder="e.g. Iphone XR"
          />

          <!-- search button -->
          <button
            class="search-button"
            type="button"
            title="Search for a product"
          >
            <i class="search-icon fas fa-search"></i><br />
            <label for="search-bar">SEARCH</label>
          </button>

          <!-- sign in button -->
          <button
            class="sign-in-button"
            type="button"
            title="Log in to your account or sign up"
          >
            <i class="fas fa-user"></i>
            <p>SIGN-IN</p>
          </button>

          <!-- cart button -->
          <button class="cart-button" title="See products in your cart">
            <i class="cart-icon fas fa-shopping-cart"></i>
            <p for="cart">CART</p>
          </button>
        </div>
      </article>

      <!-- Primary Nav -->
      <menu id="primary-nav">
        <div class="container">
          <!-- nav links -->
          <ul class="primary-nav-links">
            <li class="primary-nav-link"><a href="#">Phones</a></li>
            <li class="primary-nav-link"><a href="#">Laptops</a></li>
            <li class="primary-nav-link"><a href="#">Tablets</a></li>
            <li class="primary-nav-link"><a href="#">Monitors</a></li>
            <li class="primary-nav-link"><a href="#">TVs</a></li>
            <li class="primary-nav-link"><a href="#">Smart Watches</a></li>
            <li class="primary-nav-link"><a href="#">Cameras</a></li>
            <li class="primary-nav-link"><a href="#">Drones</a></li>
          </ul>
        </div>
      </menu>
    </header>

    <!-- Breadcrumbs -->
    <aside id="breadcrumbs">
      <div class="container">
        <a href="" class="link">Devices</a>&nbsp;&nbsp;&nbsp;
        <span>/</span>&nbsp;&nbsp;&nbsp;
        <a href="" class="link">Phones</a>
      </div>
    </aside>

    <!-- Main -->
    <main id="main">
      <div class="container">
        <section id="product-display" class="section-padding">
          <!-- Product images -->
          <article id="product-images">
            <img
              class="main-product-img product-img"
              src="../../img/phone-1.avif"
              alt=""
              width="500px"
              height="500px"
              loading="lazy"
            />
            <div class="other-images">
              <img
                class="other-image product-img"
                src="../../img/phone-1.avif"
                alt=""
                width="100px"
                height="100px"
                loading="lazy"
              />
              <img
                class="other-image product-img"
                src="../../img/phone-1.avif"
                alt=""
                width="100px"
                height="100px"
                loading="lazy"
              />
              <img
                class="other-image product-img"
                src="../../img/phone-1.avif"
                alt=""
                width="100px"
                height="100px"
                loading="lazy"
              />
              <img
                class="other-image product-img"
                src="../../img/phone-1.avif"
                alt=""
                width="100px"
                height="100px"
                loading="lazy"
              />
            </div>
          </article>
          <!-- Product details -->
          <article id="product-details">
            <h1 class="product-name">Product Name</h1>
            <p class="product-summary">A short summary of the product...</p>
            <a href="#" class="read-more-btn link">read more</a>

            <details>
              <summary>Product description</summary>
              This is a description of this product. A more detailed description
              goes here.
            </details>
            <details>
              <summary>Specifications</summary>
              <table>
                <caption>
                  Product Name Specifications
                </caption>
              </table>
            </details>
            <details>
              <summary>FAQs</summary>
            </details>
            <a href="#" class="buy-now-btn btn">Buy now</a>
            <a href="#" class="add-to-cart-btn btn btn-outline"
              ><i class="fas fa-shopping-cart"></i> Add to cart</a
            >
            <span class="product-price">£899.99</span>
          </article>
        </section>
      </div>
    </main>

    <!-- Sidebar -->
    <aside id="aside" class="section-padding">
      <div class="container">
        <h2 class="section-heading">People also bought</h2>
        <ul class="featured-accessories-wrapper products-wrapper">
          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <article class="accessory-product product">
              <img
                class="accessory-img product-img"
                src="../img/accessory-1.webp"
                alt=""
                width="300"
                height="250"
              />
              <p class="product-price">£999</p>
              <h3 class="accessory-name product-name">Device Name</h3>
              <p class="accessory-description product-description">
                Description of the device...
              </p>
              <a href="pages/product.html" class="btn">View device</a>
              <a href="" class="btn"
                ><i class="fas fa-shopping-cart"></i> Add to cart</a
              >
            </article>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <a href="#">
              <article class="accessory-product product">
                <img
                  class="accessory-img product-img"
                  src="../img/accessory-2.jpeg"
                  alt=""
                  width="300"
                  height="250"
                />
                <p class="product-price">£999</p>
                <h3 class="accessory-name product-name">Device Name</h3>
                <p class="accessory-description product-description">
                  Description of the device...
                </p>
                <a href="pages/product.html" class="btn">View device</a>
                <a href="" class="btn"
                  ><i class="fas fa-shopping-cart"></i> Add to cart</a
                >
              </article>
            </a>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <article class="accessory-product product">
              <img
                class="accessory-img product-img"
                src="../img/acessory-3.webp"
                alt=""
                width="300"
                height="250"
              />
              <p class="product-price">£999</p>
              <h3 class="accessory-name product-name">Device Name</h3>
              <p class="accessory-description product-description">
                Description of the device...
              </p>
              <a href="pages/product.html" class="btn">View device</a>
              <a href="" class="btn"
                ><i class="fas fa-shopping-cart"></i> Add to cart</a
              >
            </article>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <a href="#">
              <article class="accessory-product product">
                <img
                  class="accessory-img product-img"
                  src="../img/accessory-4.jpeg"
                  alt=""
                  width="300"
                  height="250"
                />
                <p class="product-price">£999</p>
                <h3 class="accessory-name product-name">Device Name</h3>
                <p class="accessory-description product-description">
                  Description of the device...
                </p>
                <a href="pages/product.html" class="btn">View device</a>
                <a href="" class="btn"
                  ><i class="fas fa-shopping-cart"></i> Add to cart</a
                >
              </article>
            </a>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <a href="#">
              <article class="accessory-product product">
                <img
                  class="accessory-img product-img"
                  src="../img/accessory-4.webp"
                  alt=""
                  width="300"
                  height="250"
                />
                <p class="product-price">£999</p>
                <h3 class="accessory-name product-name">Device Name</h3>
                <p class="accessory-description product-description">
                  Description of the device...
                </p>
                <a href="" class="btn"
                  ><i class="fas fa-shopping-cart"></i> Add to cart</a
                >
              </article>
            </a>
          </li>
        </ul>
      </div>
    </aside>

    <!-- Sidebar -->
    <aside id="aside" class="section-padding">
      <div class="container">
        <h2 class="section-heading">People were also interested in</h2>
        <ul class="featured-accessories-wrapper products-wrapper">
          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <article class="accessory-product product">
              <img
                class="accessory-img product-img"
                src="../img/accessory-1.webp"
                alt=""
                width="300"
                height="250"
              />
              <p class="product-price">£999</p>
              <h3 class="accessory-name product-name">Device Name</h3>
              <p class="accessory-description product-description">
                Description of the device...
              </p>
              <a href="pages/product.html" class="btn">View device</a>
              <a href="" class="btn"
                ><i class="fas fa-shopping-cart"></i> Add to cart</a
              >
            </article>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <a href="#">
              <article class="accessory-product product">
                <img
                  class="accessory-img product-img"
                  src="../img/accessory-2.jpeg"
                  alt=""
                  width="300"
                  height="250"
                />
                <p class="product-price">£999</p>
                <h3 class="accessory-name product-name">Device Name</h3>
                <p class="accessory-description product-description">
                  Description of the device...
                </p>
                <a href="pages/product.html" class="btn">View device</a>
                <a href="" class="btn"
                  ><i class="fas fa-shopping-cart"></i> Add to cart</a
                >
              </article>
            </a>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <article class="accessory-product product">
              <img
                class="accessory-img product-img"
                src="../img/acessory-3.webp"
                alt=""
                width="300"
                height="250"
              />
              <p class="product-price">£999</p>
              <h3 class="accessory-name product-name">Device Name</h3>
              <p class="accessory-description product-description">
                Description of the device...
              </p>
              <a href="pages/product.html" class="btn">View device</a>
              <a href="" class="btn"
                ><i class="fas fa-shopping-cart"></i> Add to cart</a
              >
            </article>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <a href="#">
              <article class="accessory-product product">
                <img
                  class="accessory-img product-img"
                  src="../img/accessory-4.jpeg"
                  alt=""
                  width="300"
                  height="250"
                />
                <p class="product-price">£999</p>
                <h3 class="accessory-name product-name">Device Name</h3>
                <p class="accessory-description product-description">
                  Description of the device...
                </p>
                <a href="pages/product.html" class="btn">View device</a>
                <a href="" class="btn"
                  ><i class="fas fa-shopping-cart"></i> Add to cart</a
                >
              </article>
            </a>
          </li>

          <!-- device product -->
          <li class="featured-accessory-wrap product-wrap">
            <a href="#">
              <article class="accessory-product product">
                <img
                  class="accessory-img product-img"
                  src="../img/accessory-4.webp"
                  alt=""
                  width="300"
                  height="250"
                />
                <p class="product-price">£999</p>
                <h3 class="accessory-name product-name">Device Name</h3>
                <p class="accessory-description product-description">
                  Description of the device...
                </p>
                <a href="" class="btn"
                  ><i class="fas fa-shopping-cart"></i> Add to cart</a
                >
              </article>
            </a>
          </li>
        </ul>
      </div>
    </aside>

    <!-- Foooter -->
    <footer id="footer" class="section-padding">
      <div class="container">
        <h2 class="section-heading invisible-but-accessible">Footer</h2>
        <ul class="footer-groups">
          <!-- footer group -->
          <li class="footer-group">
            <!-- logo -->
            <img
              class="footer-logo"
              src="../img/pimoky-logo.svg"
              alt="Pimoky logo"
            />
            <!-- company description -->
            <p class="company-description">
              Primoky is an online superstore supplying customers with a whole
              range of products from Laptops, TVs and Fridges to Washing
              Machines.
            </p>
            <ul class="social-links">
              <li class="social-link">
                <a href="" title="Pimoky on Facebook">
                  <i class="fab fa-facebook"></i>
                </a>
              </li>
              <li class="social-link">
                <a href="" title="Pimoky on Twitter">
                  <i class="fab fa-twitter"></i>
                </a>
              </li>
              <li class="social-link">
                <a href="" title="Pimoky on Instagram">
                  <i class="fab fa-instagram"></i>
                </a>
              </li>
              <li class="social-link">
                <a href="" title="Pimoky on TikTok">
                  <i class="fab fa-tiktok"></i>
                </a>
              </li>
            </ul>
          </li>

          <!-- footer group -->
          <li class="footer-group">
            <!-- footer group heading -->
            <h3 class="footer-group-heading">Sign up to our Newsletter!</h3>
            <!-- footer group links -->
            <form id="email-optin">
              <label for="email" class="invisible-but-accessible">Email</label>
              <input
                type="email"
                placeholder="bob@example.com"
                name="email"
                id="email"
              />
              <button type="submit" value="Subscribe">Subscribe</button>
            </form>
          </li>

          <!-- footer group -->
          <li class="footer-group">
            <!-- footer group heading -->
            <h3 class="footer-group-heading">Quick links</h3>
            <!-- footer group links -->
            <ul class="footer-group-links">
              <li class="footer-group-li">
                <a href="#" class="footer-group-link">Devices</a>
              </li>
              <li class="footer-group-li">
                <a href="#" class="footer-group-link">Appliances</a>
              </li>
              <li class="footer-group-li">
                <a href="#" class="footer-group-link">Accessories</a>
              </li>
            </ul>
          </li>

          <!-- footer group -->
          <li class="footer-group">
            <!-- footer group heading -->
            <h3 class="footer-group-heading">Quick links</h3>
            <!-- footer group links -->
            <ul class="footer-group-links">
              <li class="footer-group-li">
                <a href="#" class="footer-group-link">About</a>
              </li>
              <li class="footer-group-li">
                <a href="#" class="footer-group-link">Help</a>
              </li>
              <li class="footer-group-li">
                <a href="#" class="footer-group-link">Contact</a>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </footer>

  </body>
</html>
