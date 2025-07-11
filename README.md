# Feel Good News
Welcome to **Feel Good News** – your daily dose of uplifting stories, positive updates, and good vibes from around the world. This project is a feel-good news website that encourages positivity and counters the negativity often found in mainstream news. Feel Good News is a website dedicated to Good News with the aim to make people feel good, either by reading of sharing heart-warming uplifting stories, funny stories & just good things.
I firmly believe that there is more good news in the world than bad news - time to focus on what's good.

---

## 🌐 Live Site

[(https://dylanmcca.github.io/feel-good-news/)]

---

## 📁 Project Structure

### 1. `index.html`

Main landing page with site navigation and general information.

### 2. today.html

Secondary page with samples of uplifting stories for people read & enjoy. Future versions would have video & listening content.

#### Sample Code:

```html
<section id="hero2">       
            <div id="cover-text">
                <h2>Uplift Your Day</h2>
                <h3>Less bad news MORE good news👍</h3>
            </div> 
        <!--img src="assets/images/supernews.jpg" alt="Lots of smiley faces & thumbs up badges"-->

        <!-- Featured stories grid -->
        <div id="stories">
            <h2 class="hidden-heading">Top Stories</h2>
            <div id="good-news">
                <div>
                    <h3>Kindness <i class="fa-solid fa-hand-holding-heart"></i></h3>
                    <p>Local bakery feeds 300 people for free on Christmas.</p>
                </div>
                <div>
                    <h3>Innovation <i class="fa-solid fa-seedling"></i></h3>
                    <p>Teen invents device to clean microplastics from rivers.</p>
                </div>
                <div>
                    <h3>Animals <i class="fa-solid fa-paw"></i></h3>
                    <p>Rescued dog becomes therapy companion in care homes.</p>
                </div>
                <div>
                    <h3>Environment <i class="fa-solid fa-leaf"></i></h3>
                    <p>Community plants 10,000 trees in a single weekend.</p>
                </div>
                <div>
                    <h3>Joy <i class="fa-solid fa-smile-beam"></i></h3>
                    <p>103-year-old skydives to complete her bucket list.</p>
                </div>
            </div>
        </div>
</section>
```        

### 3. `signup.html`

Contains the signup form for users who wish to subscribe to the daily good news newsletter.

#### Sample Code:

```html
<form id="signup-form" method="POST" action="joined.html">
    <label for="first-name">First Name:</label>
    <input type="text" name="first_name" id="first-name" required>

    <label for="last-name">Last Name:</label>
    <input type="text" name="last_name" id="last-name" required>

    <label for="email-address">Email Address:</label>
    <input type="email" name="email_address" id="email-address" required>

    <button type="submit" class="join-button">Join Feel-Good News 😁</button>
</form>
```

### 3. `joined.html`

Confirmation page after a successful signup.

#### Sample Code:

```html
<section id="joined">       
    <div id="cover-text">
        <h2>Welcome to Feel-Good News 😁</h2>
        <h3>Less bad news MORE good news👍</h3>
    </div> 

    <div id="joined-main">
        <div id="cover-text-joined">
            <h2>Great to have you onboard 😁 only Feel Good News here 😁</h2>
        </div>
        <a href="index.html" class="button-home">Return to Home</a>          
</section>
```

---

## 🎨 CSS Styling

The site uses a combination of custom CSS and Bootstrap to ensure responsive design and visually appealing layouts.

### Fonts & Colors

- Fonts: `Lato`, `Oswald`, and `Bitcount Grid Double`
- Color palette: Primarily `aquamarine` and `rgba(234, 18, 194, 0.8)` for call-to-action areas

### Sample CSS Snippet

```css
body {
    color: #3a3a3a;
    font-family: 'Lato', sans-serif;
}

header {
    background-color: aquamarine;
    box-shadow: 0 2px 2px #3a3a3a;
}

#signup-form {
    background-color: aquamarine;
    padding: 30px;
}
```

---

## 💡 Features

- Fully responsive design
- Interactive signup form
- Social media links
- Dynamic background images for different sections
- Clean and vibrant aesthetic

---

## 🛠 Technologies Used

- HTML5
- CSS3
- [Bootstrap 5](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)

---

## 📸 Screenshots

![Feel Good News Home page](image.png)
![Feel Good News Todays News page](image-1.png)
![Feel Good News Sign up page](image-2.png)
![Feel Good News Joined page](image-3.png)

---

## Code check validation ##

- Index html validator check screenshot pass
![Index check screenshot pass](image-4.png)
- Today page html validator check & screenshot of pass
![Today page check & screenshot of pass](image-5.png)
- Sign up page html validator check & screenshot of pass
![Sign up page html validator check & screenshot of pass](image-6.png)
- Joined page html validator check screenshot pass
![Joined page html validator check screenshot pass](image-7.png)

- CSS code checked & small adjustment made to pass  in W3C CSS validator
![CSS code checked & small adjustment made to pass  in W3C CSS validator](image-8.png)

## 🙌 Acknowledgements

- [Font Awesome](https://fontawesome.com/) for icons
- [Unsplash](https://unsplash.com/) or original images used
- [iStock Getty Images](https://www.istockphoto.com/search/2/image?phrase=funny&mediatype=photography&irclickid=0IrQP%3A1i4xycUygVqcz7hRWAUksXoj1wbWKa0M0&irgwc=1&cid=IS&utm_medium=affiliate_SP&utm_source=FreeImages&clickid=0IrQP%3A1i4xycUygVqcz7hRWAUksXoj1wbWKa0M0&utm_term=funny&utm_campaign=landing_freephoto_searchbar-popup&utm_content=270498&irpid=246195) for animal images used
- Free educational resources and templates

---

## ✍️ Author 

- Name: (Dylan McCarthy)
- GitHub: (https://github.com/dylanmcca)