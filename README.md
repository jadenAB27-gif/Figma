# Ex08 Event Registration Web Application
## Date: 20/03/26

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
HTML SCREEN 1

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <meta name="description" content="Where The Light Is - John Mayer Live in LA" />
    <title>Where The Light Is - John Mayer</title>
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <main class="iphone-pro-max">
      <!-- Album Title -->
      <h1 class="text-wrapper">Where The Light Is</h1>
      <!-- Artist Name -->
      <p class="text-wrapper-3">John Mayer</p>
      <!-- Album Cover Image -->
      <img
        class="where-the-light-is"
        src="img/where-the-light-is-1.png"
        alt="Where The Light Is - John Mayer Live in Los Angeles album cover"
      />
      <!-- Concert Description -->
      <p class="p">December 2007 - Live in Los Angles</p>
      <!-- Live in LA Button -->
      <div class="div" role="button" aria-label="Live in LA">
        <span class="text-wrapper-2">Live in LA</span>
      </div>
      <!-- Register Now Button -->
      <div class="rectangle-2" role="button" aria-label="Register Now">
        <span class="text-wrapper-5">Register Now</span>
      </div>
      <!-- User Registration Info -->
      <div class="rectangle">
        <span class="text-wrapper-4">Jaden Samuel Abraham (25003451)</span>
      </div>
    </main>
  </body>
</html>

CSS SCREEN 1

.iphone-pro-max {
  background-color: #000000;
  border: 1px solid;
  border-color: #000000d9;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 724px;
  left: 22px;
  width: 349px;
  height: 39px;
  background-color: var(--colors-accents-mint);
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 96px;
  left: 12px;
  width: 370px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 606px;
  left: 97px;
  width: 199px;
  height: 30px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 609px;
  left: 139px;
  width: 115px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .where-the-light-is {
  position: absolute;
  top: 218px;
  left: 0;
  width: 393px;
  height: 306px;
  aspect-ratio: 1.28;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 147px;
  left: 12px;
  width: 141px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: var(--colors-accents-mint);
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 727px;
  left: 31px;
  width: 356px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 651px;
  left: 97px;
  width: 199px;
  height: 33px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 654px;
  left: 120px;
  width: 176px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .p {
  position: absolute;
  top: 555px;
  left: 68px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 23px;
  white-space: nowrap;
}
/* Original style.css content injected here */

.iphone-pro-max {
  background-color: #000000;
  border: 1px solid;
  border-color: #000000d9;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 724px;
  left: 22px;
  width: 349px;
  height: 39px;
  background-color: var(--colors-accents-mint);
  display: flex;
  align-items: center;
  padding-left: 9px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 96px;
  left: 12px;
  width: 370px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  margin: 0;
}

.iphone-pro-max .div {
  position: absolute;
  top: 606px;
  left: 97px;
  width: 199px;
  height: 30px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}

.iphone-pro-max .text-wrapper-2 {
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .where-the-light-is {
  position: absolute;
  top: 218px;
  left: 0;
  width: 393px;
  height: 306px;
  aspect-ratio: 1.28;
  display: block;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 147px;
  left: 12px;
  width: 141px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: var(--colors-accents-mint);
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  margin: 0;
}

.iphone-pro-max .text-wrapper-4 {
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 651px;
  left: 97px;
  width: 199px;
  height: 33px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}

.iphone-pro-max .text-wrapper-5 {
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .p {
  position: absolute;
  top: 555px;
  left: 68px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 23px;
  white-space: nowrap;
  margin: 0;
}

HTML SCREEN 2

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <title>Setlist</title>
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <main class="iphone">
      <!-- White card background -->
      <div class="rectangle" role="presentation"></div>
      <!-- Page heading -->
      <h1 class="setlist"><span class="text-wrapper">S</span><span class="span">etlist</span></h1>
      <!-- Setlist items -->
      <ul class="neon-stop-this-train" aria-label="Setlist songs">
        <li>Neon</li>
        <li>Stop This Train</li>
        <li>In Your Atmosphere (LA Song)</li>
        <li>Daughters</li>
        <li>Free Fallin&#39; (Tom Petty cover)</li>
        <li>Everyday I Have The Blues (Aaron Sparks cover)</li>
        <li>Wait Until Tomorrow (Jimi Hendrix cover)</li>
        <li>Who Did You Think I Was</li>
        <li>Come When I Call</li>
        <li>Good Love Is On the Way</li>
        <li>Out of My Mind</li>
        <li>Vultures</li>
        <li>Bold as Love (Jimi Hendrix cover)</li>
        <li>Waiting on the World to Change</li>
        <li>Slow Dancing in a Burning Room</li>
        <li>Why Georgia</li>
        <li>The Heart of Life</li>
        <li>I Don&#39;t Need No Doctor (Ray Charles cover)</li>
        <li>Gravity</li>
        <li>I Don&#39;t Trust Myself (With Loving You)</li>
        <li>Belief</li>
      </ul>
      <!-- Photo grid row 1 -->
      <figure class="photo photo--j3">
        <img class="j-3" src="img/j4-1.png" alt="John Mayer performing live on stage with guitar" />
      </figure>
      <figure class="photo photo--element-1">
        <img class="element" src="img/47b46354-59e3-442a-b1f9-eb376be84581-1.png" alt="John Mayer concert photo" />
      </figure>
      <figure class="photo photo--img-1">
        <img class="img" src="img/j1-1.png" alt="John Mayer performing with band members" />
      </figure>
      <figure class="photo photo--j2">
        <img class="j-2" src="img/j3-1.png" alt="John Mayer guitar close-up" />
      </figure>
      <figure class="photo photo--j4">
        <img class="j-4" src="img/j6-1.png" alt="John Mayer on stage with spotlight" />
      </figure>
      <!-- Photo grid row 2 -->
      <figure class="photo photo--element-2">
        <img
          class="element element--second"
          src="img/47b46354-59e3-442a-b1f9-eb376be84581-2.png"
          alt="John Mayer acoustic performance"
        />
      </figure>
      <figure class="photo photo--img-2">
        <img class="img img--second" src="img/j1-2.png" alt="John Mayer cityscape photo" />
      </figure>
      <figure class="photo photo--j2-second">
        <img class="j-2 j-2--second" src="img/j3-2.png" alt="John Mayer performing solo" />
      </figure>
      <figure class="photo photo--j">
        <img class="j" src="img/j2-1.png" alt="John Mayer backstage photo" />
      </figure>
    </main>
  </body>
</html>

CSS SCREEN 2

.iphone {
  background-color: #000000;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 95px;
  left: 20px;
  width: 351px;
  height: 531px;
  background-color: #ffffff;
  border-radius: 10px;
}

.iphone .element {
  position: absolute;
  top: 636px;
  left: 20px;
  width: 122px;
  height: 80px;
  aspect-ratio: 1.52;
}

.iphone .setlist {
  position: absolute;
  top: 39px;
  left: 20px;
  width: 373px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper {
  color: #00c8b3;
}

.iphone .span {
  color: #ffffff;
}

.iphone .j {
  position: absolute;
  top: 726px;
  left: 20px;
  width: 100px;
  height: 73px;
  aspect-ratio: 1.37;
}

.iphone .img {
  position: absolute;
  top: 636px;
  left: 131px;
  width: 97px;
  height: 80px;
  aspect-ratio: 1.21;
}

.iphone .j-2 {
  position: absolute;
  top: 726px;
  left: 131px;
  width: 97px;
  height: 73px;
  aspect-ratio: 1.33;
}

.iphone .j-3 {
  position: absolute;
  top: 636px;
  left: 228px;
  width: 143px;
  height: 80px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.iphone .j-4 {
  position: absolute;
  top: 723px;
  left: 239px;
  width: 132px;
  height: 76px;
  aspect-ratio: 1.74;
}

.iphone .neon-stop-this-train {
  position: absolute;
  top: 105px;
  left: 27px;
  width: 344px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 23px;
}
/* =============================================
   ORIGINAL CSS INJECTED BELOW
   ============================================= */

.iphone {
  background-color: #000000;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 95px;
  left: 20px;
  width: 351px;
  height: 531px;
  background-color: #ffffff;
  border-radius: 10px;
}

.iphone .setlist {
  position: absolute;
  top: 39px;
  left: 20px;
  width: 373px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  margin: 0;
  padding: 0;
}

.iphone .text-wrapper {
  color: #00c8b3;
}

.iphone .span {
  color: #ffffff;
}

/* =============================================
   SETLIST (ul) — replaces the paragraph
   ============================================= */

.iphone .neon-stop-this-train {
  position: absolute;
  top: 105px;
  left: 27px;
  width: 344px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 23px;
  margin: 0;
  padding: 0 0 0 20px;
  list-style-type: disc;
}

.iphone .neon-stop-this-train li {
  display: list-item;
}

/* =============================================
   PHOTO FIGURE WRAPPERS — zero out figure defaults
   ============================================= */

.iphone .photo {
  position: absolute;
  margin: 0;
  padding: 0;
  line-height: 0;
}

/* =============================================
   ROW 1 PHOTOS
   ============================================= */

/* element (first instance) — top-left of photo grid */
.iphone .photo--element-1 {
  top: 636px;
  left: 20px;
}

.iphone .element {
  width: 122px;
  height: 80px;
  aspect-ratio: 1.52;
  display: block;
}

/* img (first instance) — top-middle of photo grid */
.iphone .photo--img-1 {
  top: 636px;
  left: 131px;
}

.iphone .img {
  width: 97px;
  height: 80px;
  aspect-ratio: 1.21;
  display: block;
}

/* j-3 — top-right of photo grid */
.iphone .photo--j3 {
  top: 636px;
  left: 228px;
}

.iphone .j-3 {
  width: 143px;
  height: 80px;
  aspect-ratio: 1.78;
  object-fit: cover;
  display: block;
}

/* =============================================
   ROW 2 PHOTOS
   ============================================= */

/* j — bottom-left of photo grid */
.iphone .photo--j {
  top: 726px;
  left: 20px;
}

.iphone .j {
  width: 100px;
  height: 73px;
  aspect-ratio: 1.37;
  display: block;
}

/* j-2 (first instance) — bottom-middle of photo grid */
.iphone .photo--j2 {
  top: 726px;
  left: 131px;
}

.iphone .j-2 {
  width: 97px;
  height: 73px;
  aspect-ratio: 1.33;
  display: block;
}

/* j-4 — bottom-right of photo grid */
.iphone .photo--j4 {
  top: 723px;
  left: 239px;
}

.iphone .j-4 {
  width: 132px;
  height: 76px;
  aspect-ratio: 1.74;
  display: block;
}

/* =============================================
   ROW 3 PHOTOS (second set)
   ============================================= */

/* element (second instance) */
.iphone .photo--element-2 {
  top: 636px;
  left: 20px;
}

.iphone .element--second {
  width: 122px;
  height: 80px;
  aspect-ratio: 1.52;
  display: block;
}

/* img (second instance) */
.iphone .photo--img-2 {
  top: 636px;
  left: 131px;
}

.iphone .img--second {
  width: 97px;
  height: 80px;
  aspect-ratio: 1.21;
  display: block;
}

/* j-2 (second instance) */
.iphone .photo--j2-second {
  top: 726px;
  left: 131px;
}

.iphone .j-2--second {
  width: 97px;
  height: 73px;
  aspect-ratio: 1.33;
  display: block;
}

HTML SCREEEN 3

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <title>Registration</title>
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <main class="iphone">
      <!-- Bottom background image -->
      <img class="j" src="img/j6-2.png" alt="Concert background bottom" />
      <!-- Registration form card -->
      <section class="rectangle" aria-label="Registration form card">
        <!-- Form title -->
        <h1 class="registration"><span class="span">R</span><span class="text-wrapper-5">egistration</span></h1>
        <!-- Registration form -->
        <form class="registration-form" novalidate>
          <!-- Full Name field -->
          <div class="field-wrapper">
            <label for="full-name" class="visually-hidden">Full Name</label>
            <input
              class="rectangle-4 form-input"
              type="text"
              id="full-name"
              name="full-name"
              placeholder="FULL NAME"
              autocomplete="name"
              aria-label="Full Name"
            />
          </div>
          <!-- Email field -->
          <div class="field-wrapper">
            <label for="email" class="visually-hidden">Email</label>
            <input
              class="rectangle-3 form-input"
              type="email"
              id="email"
              name="email"
              placeholder="EMAIL"
              autocomplete="email"
              aria-label="Email"
            />
          </div>
          <!-- Phone No field -->
          <div class="field-wrapper">
            <label for="phone" class="visually-hidden">Phone Number</label>
            <input
              class="rectangle-2 form-input"
              type="tel"
              id="phone"
              name="phone"
              placeholder="PHONE NO"
              autocomplete="tel"
              aria-label="Phone Number"
            />
          </div>
          <!-- Address field -->
          <div class="field-wrapper">
            <label for="address" class="visually-hidden">Address</label>
            <input
              class="div form-input"
              type="text"
              id="address"
              name="address"
              placeholder="ADDRESS"
              autocomplete="street-address"
              aria-label="Address"
            />
          </div>
          <!-- Submit button -->
          <button type="submit" class="rectangle-5 sign-up-btn" aria-label="Sign Up">
            <span class="text-wrapper-6">Sign Up</span>
          </button>
        </form>
      </section>
      <!-- Top background image -->
      <img class="img" src="img/j4-2.png" alt="Concert background top" />
    </main>
  </body>
</html>


CSS SCREEN 3

.iphone {
  background-color: #000000;
  width: 100%;
  min-width: 394px;
  min-height: 844px;
  position: relative;
}

.iphone .j {
  position: absolute;
  top: 621px;
  left: 0;
  width: 385px;
  height: 223px;
  aspect-ratio: 1.74;
}

.iphone .rectangle {
  position: absolute;
  top: 205px;
  left: 20px;
  width: 350px;
  height: 433px;
}

.iphone .text-wrapper {
  position: absolute;
  top: 407px;
  left: 59px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 532px;
  left: 42px;
  width: 302px;
  height: 29px;
  background-color: #ffffff;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 467px;
  left: 41px;
  width: 302px;
  height: 29px;
  background-color: #ffffff;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 402px;
  left: 42px;
  width: 302px;
  height: 29px;
  background-color: #ffffff;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 337px;
  left: 42px;
  width: 302px;
  height: 29px;
  background-color: #ffffff;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 342px;
  left: 59px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 536px;
  left: 59px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 470px;
  left: 59px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .registration {
  position: absolute;
  top: 251px;
  left: 42px;
  width: 226px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: var(--colors-accents-mint);
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .span {
  color: #00c8b3;
}

.iphone .text-wrapper-5 {
  color: #000000;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 584px;
  left: 131px;
  width: 119px;
  height: 33px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 585px;
  left: 148px;
  width: 102px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .img {
  position: absolute;
  top: 15px;
  left: 41px;
  width: 297px;
  height: 167px;
  aspect-ratio: 1.78;
  object-fit: cover;
}
/* =============================================
   ORIGINAL CSS INJECTED BELOW
   ============================================= */

.iphone {
  background-color: #000000;
  width: 100%;
  min-width: 394px;
  min-height: 844px;
  position: relative;
}

.iphone .j {
  position: absolute;
  top: 621px;
  left: 0;
  width: 385px;
  height: 223px;
  aspect-ratio: 1.74;
}

/* Rectangle is now a <section> element — reset default section styles */
.iphone .rectangle {
  position: absolute;
  top: 205px;
  left: 20px;
  width: 350px;
  height: 433px;
  background: transparent;
  border: none;
  padding: 0;
  margin: 0;
  display: block;
}

/* Registration form layout inside the card */
.iphone .registration-form {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

/* Field wrapper for each input group */
.iphone .field-wrapper {
  position: static;
  display: block;
}

/* Visually hidden labels for accessibility */
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

/* Base styles for all form inputs — replaces placeholder divs */
.iphone .form-input {
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  background-color: #ffffff;
  border: none;
  outline: none;
  padding: 0 17px;
  display: block;
  cursor: text;
  appearance: none;
  -webkit-appearance: none;
}

.iphone .form-input::placeholder {
  color: #000000;
  opacity: 1;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  font-size: 16px;
}

/* Individual input positioning — mirrors original rectangle divs */
.iphone .rectangle-4 {
  position: absolute;
  top: 337px;
  left: 42px;
  width: 302px;
  height: 29px;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 402px;
  left: 42px;
  width: 302px;
  height: 29px;
}

.iphone .rectangle-2 {
  position: absolute;
  top: 467px;
  left: 41px;
  width: 302px;
  height: 29px;
}

.iphone .div {
  position: absolute;
  top: 532px;
  left: 42px;
  width: 302px;
  height: 29px;
}

/* Registration heading */
.iphone .registration {
  position: absolute;
  top: 251px;
  left: 42px;
  width: 226px;
  font-family: "Allerta-Regular", Helvetica;
  font-weight: 400;
  color: var(--colors-accents-mint);
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  margin: 0;
  padding: 0;
}

.iphone .span {
  color: #00c8b3;
}

.iphone .text-wrapper-5 {
  color: #000000;
}

/* Sign Up button — replaces rectangle-5 div */
.iphone .rectangle-5 {
  position: absolute;
  top: 584px;
  left: 131px;
  width: 119px;
  height: 33px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
  border: none;
  cursor: pointer;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

.iphone .sign-up-btn {
  position: absolute;
  top: 584px;
  left: 131px;
  width: 119px;
  height: 33px;
  border-radius: 56.5px;
  background: linear-gradient(
      0deg,
      rgba(0, 200, 179, 1) 0%,
      rgba(0, 200, 179, 1) 100%
    ),
    linear-gradient(
      0deg,
      rgba(217, 217, 217, 1) 0%,
      rgba(217, 217, 217, 1) 100%
    );
  background-color: var(--colors-accents-mint);
  border: none;
  cursor: pointer;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

.iphone .text-wrapper-6 {
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  display: block;
  width: 102px;
  text-align: center;
}

/* Top concert image */
.iphone .img {
  position: absolute;
  top: 15px;
  left: 41px;
  width: 297px;
  height: 167px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

HTML SCREEN 4

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <main class="iphone">
      <img
        class="invitation"
        src="img/invitation-background-3.png"
        alt="Concert invitation background showing a live music stage"
      />
      <div class="rectangle" role="presentation" aria-hidden="true"></div>
      <p class="thank-you-we-can-t">Thank You<br />We can't wait to see you <br />live!</p>
    </main>
  </body>
</html>

CSS SCREEN 4

.iphone {
  background-color: #000000;
  width: 100%;
  min-width: 388px;
  min-height: 844px;
  position: relative;
}

.iphone .invitation {
  position: absolute;
  top: 33px;
  left: 14px;
  width: 359px;
  height: 778px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 308px;
  left: 32px;
  width: 323px;
  height: 227px;
  background-color: #ffffff1a;
  border-radius: 21px;
  box-shadow:
    0px 4px 4px #00000040, inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
}

.iphone .thank-you-we-can-t {
  position: absolute;
  top: calc(50.00% - 48px);
  left: calc(50.00% - 108px);
  width: 215px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
/* Original style.css styles injected here */

.iphone {
  background-color: #000000;
  width: 100%;
  min-width: 388px;
  min-height: 844px;
  position: relative;
}

.iphone .invitation {
  position: absolute;
  top: 33px;
  left: 14px;
  width: 359px;
  height: 778px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 308px;
  left: 32px;
  width: 323px;
  height: 227px;
  background-color: #ffffff1a;
  border-radius: 21px;
  box-shadow:
    0px 4px 4px #00000040,
    inset 0 1px 0 rgba(255, 255, 255, 0.4),
    inset 1px 0 0 rgba(255, 255, 255, 0.32),
    inset 0 -1px 1px rgba(0, 0, 0, 0.13),
    inset -1px 0 1px rgba(0, 0, 0, 0.11);
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
}

.iphone .thank-you-we-can-t {
  position: absolute;
  top: calc(50.00% - 48px);
  left: calc(50.00% - 108px);
  width: 215px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot 2026-03-20 142822.png>)
![alt text](<Screenshot 2026-03-20 142833.png>)
![alt text](<Screenshot 2026-03-20 142845.png>)
![alt text](<Screenshot 2026-03-20 142858.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
