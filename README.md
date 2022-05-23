

## Technologies used 🛠️

- **HTML** 🚀
- **CSS** 🚀
- **JavaScript** 🚀
- **SASS** 🚀

---



## How To Use 🔧

From your command line, first clone NewPortfolio:

```bash
# Clone this repository
$ git clone https://github.com/LucianoRoagna/My-Portfolio

# Go into the repository
$ cd NewPortfolio

# Remove current origin repository
$ git remote remove origin
```

<br/>

Then you can install the dependencies

Using NPM:

```bash
# Install dependencies
$ npm install

# Listen to changes in CSS Preprocessor files ( SASS files )
$ npm run compile:scss
```

Once you run `npm run compile:scss`, then open the `index.html` inside your favorite browser or using the live server extension.

<br>

---

<br>




## Deployment 📦

Once you have done with your setup. You need to put your website online!

I highly recommend to use [Netlify](https://netlify.com) to achieve this on the EASIEST WAY

Whenever you wanna host a new site on Netlify. You will need to press the **Create New Site** button from the Netlify's dashboard once you login into Netlify.

Once you press the **Create Site Button** then you will have to follow the 3 steps:

1. You will have to select your Github account.

2. Then select the Repository which you wanna host, in this case its your Portfolio website ( Clone of Dopefolio )

3. In the 3rd step, you will have to modify the **Site settings and deploy**, keep everything as it is but just make sure to modify the **Build command** and set its value to **npm run build** and then modify the **Publish directory** and set its value to **/** as shown in the  **image** below

<div align="center">
  <img src="https://i.ibb.co/hDTTrPB/Set-Build-Command-to.png" alt="Dopefolio Build Command Example and Publish Directory Value" width="100%" />
  <br>
</div>

<br>

Then hit the **Deploy site** button and your **Portfolio Site** is live 🥳

<br>

---

<br>



