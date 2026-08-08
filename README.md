# movie-streaming-landing-page
//html
<!-- 1. Navigation Bar -->
<header class="navbar">
    <div class="logo">CineStream</div>
    <nav>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#movies">Movies</a></li>
            <li><a href="#genres">Genres</a></li>
            <li><a href="#plans">Plans</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<main>
    <!-- 2. Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Unlimited Movies, TV Shows, & More</h1>
            <p>Watch anywhere. Cancel anytime. Stream your favorite content today.</p>
            <button class="btn btn-primary">Watch Now</button>
        </div>
    </section>

    <!-- 3. Featured Movies Section -->
    <section id="movies" class="section-container">
        <h2 class="section-title">Featured Movies</h2>
        <div class="movie-grid">
            <div class="movie-card">
                <img src="https://picsum.photos/id/10/300/400" alt="Movie 1 Poster" class="poster-img">
                <h3>Cyber Pulse</h3>
                <p class="movie-info">Action | ★ 8.5 | 2024</p>
            </div>
            <div class="movie-card">
                <img src="https://picsum.photos/id/11/300/400" alt="Movie 2 Poster" class="poster-img">
                <h3>Shadow Realm</h3>
                <p class="movie-info">Horror | ★ 7.9 | 2023</p>
            </div>
            <div class="movie-card">
                <img src="https://picsum.photos/id/12/300/400" alt="Movie 3 Poster" class="poster-img">
                <h3>Ocean's Depth</h3>
                <p class="movie-info">Adventure | ★ 8.2 | 2024</p>
            </div>
            <div class="movie-card">
                <img src="https://picsum.photos/id/13/300/400" alt="Movie 4 Poster" class="poster-img">
                <h3>Starlight Odyssey</h3>
                <p class="movie-info">Sci-Fi | ★ 9.0 | 2025</p>
            </div>
            <div class="movie-card">
                <img src="https://picsum.photos/id/14/300/400" alt="Movie 5 Poster" class="poster-img">
                <h3>Laugh Out Loud</h3>
                <p class="movie-info">Comedy | ★ 7.5 | 2023</p>
            </div>
            <div class="movie-card">
                <img src="https://picsum.photos/id/15/300/400" alt="Movie 6 Poster" class="poster-img">
                <h3>Silent Echo</h3>
                <p class="movie-info">Thriller | ★ 8.8 | 2024</p>
            </div>
        </div>
    </section>

    <!-- 4. Genres Section -->
    <section id="genres" class="section-container">
        <h2 class="section-title">Explore Genres</h2>
        <div class="genre-grid">
            <div class="genre-card">Action</div>
            <div class="genre-card">Adventure</div>
            <div class="genre-card">Comedy</div>
            <div class="genre-card">Horror</div>
            <div class="genre-card">Romance</div>
            <div class="genre-card">Sci-Fi</div>
            <div class="genre-card">Thriller</div>
            <div class="genre-card">Animation</div>
        </div>
    </section>

    <!-- 5. Subscription Plans Section -->
    <section id="plans" class="section-container">
        <h2 class="section-title">Subscription Plans</h2>
        <div class="plan-row">
            <div class="plan-card">
                <h3>Basic</h3>
                <div class="price">$8.99/mo</div>
                <p>720p Resolution • 1 Screen • Ad-Supported</p>
                <button class="btn">Select Plan</button>
            </div>
            <div class="plan-card highlight">
                <h3>Standard</h3>
                <div class="price">$13.99/mo</div>
                <p>1080p Resolution • 2 Screens • Ad-Free</p>
                <button class="btn btn-primary">Select Plan</button>
            </div>
            <div class="plan-card">
                <h3>Premium</h3>
                <div class="price">$17.99/mo</div>
                <p>4K + HDR • 4 Screens • Ad-Free + Downloads</p>
                <button class="btn">Select Plan</button>
            </div>
        </div>
    </section>

    <!-- 6. About Section -->
    <section id="about" class="section-container alt-bg">
        <h2 class="section-title">About CineStream</h2>
        <p class="about-text">
            CineStream is a next-generation online streaming service offering thousands of movies, television series, and exclusive originals. Designed for modern web devices, our platform delivers instant playback, high-definition resolution, and personalized content recommendations without interruption.
        </p>
    </section>

    <!-- 7. Contact Section -->
    <section id="contact" class="section-container">
        <h2 class="section-title">Contact Us</h2>
        <form class="contact-form" onsubmit="return false;">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" placeholder="Enter your full name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" placeholder="Enter your email address" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" rows="5" placeholder="Write your message here..." required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
    </section>
</main>

<!-- 8. Footer Section -->
<footer>
    <div class="footer-links">
        <a href="#">Privacy Policy</a>
        <a href="#">Terms and Conditions</a>
        <a href="#">Social Media Links</a>
    </div>
    <p>&copy; 2026 CineStream Platform. All rights reserved.</p>
</footer>

//css

/* Universal Styles & Reset */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background-color: #121212;
    color: #ffffff;
    line-height: 1.6;
}

/* 1. Navigation Bar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
    background-color: #000000;
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: #e50914;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 20px;
}

.nav-links a {
    color: #ffffff;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #e50914;
}

/* 2. Hero Section (Updated Background Image) */
.hero {
    height: 60vh;
    background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1489599849927-2ee91cede3ba') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 0 20px;
}

.hero-content h1 {
    font-size: 2.5rem;
    margin-bottom: 15px;
}

.hero-content p {
    font-size: 1.1rem;
    margin-bottom: 25px;
    color: #dddddd;
}

/* Buttons */
.btn {
    padding: 12px 24px;
    border: none;
    border-radius: 4px;
    background-color: #333333;
    color: #ffffff;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.2s;
}

.btn-primary {
    background-color: #e50914;
}

.btn:hover {
    opacity: 0.9;
    transform: translateY(-2px);
}

/* Layout Containers */
.section-container {
    padding: 50px 40px;
}

.alt-bg {
    background-color: #1a1a1a;
}

.section-title {
    font-size: 1.8rem;
    margin-bottom: 25px;
    border-left: 4px solid #e50914;
    padding-left: 10px;
}

/* 3. Featured Movies (CSS Grid) */
.movie-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 20px;
}

.movie-card {
    background-color: #1f1f1f;
    border-radius: 8px;
    padding: 10px;
    text-align: center;
    transition: transform 0.3s ease;
}

.movie-card:hover {
    transform: scale(1.05);
}

.poster-img {
    width: 100%;
    height: 240px;
    object-fit: cover;
    border-radius: 4px;
    margin-bottom: 10px;
    background-color: #333;
}

.movie-info {
    font-size: 0.85rem;
    color: #aaaaaa;
    margin-top: 5px;
}

/* 4. Genres Section (CSS Grid) */
.genre-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 15px;
}

.genre-card {
    background-color: #2a2a2a;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s;
}

.genre-card:hover {
    background-color: #e50914;
}

/* 5. Subscription Plans (Flexbox) */
.plan-row {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.plan-card {
    background-color: #1f1f1f;
    border: 2px solid #333333;
    border-radius: 8px;
    padding: 30px;
    width: 250px;
    text-align: center;
}

.plan-card.highlight {
    border-color: #e50914;
    transform: scale(1.05);
}

.price {
    font-size: 1.8rem;
    color: #e50914;
    margin: 15px 0;
    font-weight: bold;
}

/* 6. About Section */
.about-text {
    max-width: 800px;
    color: #cccccc;
    font-size: 1.1rem;
}

/* 7. Contact Section */
.contact-form {
    max-width: 600px;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
}

.form-group input, 
.form-group textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #333333;
    border-radius: 4px;
    background-color: #1f1f1f;
    color: #ffffff;
}

/* 8. Footer */
footer {
    text-align: center;
    padding: 30px;
    background-color: #000000;
    color: #666666;
}

.footer-links {
    margin-bottom: 15px;
}

.footer-links a {
    color: #aaaaaa;
    text-decoration: none;
    margin: 0 10px;
}

/* Media Queries for Mobile Responsiveness */
@media (max-width: 768px) {
    .navbar {
        flex-direction: column;
        gap: 15px;
    }

    .hero-content h1 {
        font-size: 2rem;
    }

    .section-container {
        padding: 40px 20px;
    }
}
