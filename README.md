
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ExploreWorld - Tourism Website</title>
</head>

<body>

    <!-- Header -->
    <header>
        <center>
            <h1>🌍 ExploreWorld</h1>
            <p>Discover Beautiful Places Around the World</p>
        </center>

        <hr>

        <!-- Navigation -->
        <nav>
            <center>
                <a href="#home">Home</a> |
                <a href="#destinations">Destinations</a> |
                <a href="#packages">Tour Packages</a> |
                <a href="#about">About Us</a> |
                <a href="#contact">Contact</a>
            </center>
        </nav>

        <hr>
    </header>

    <!-- Home Section -->
    <section id="home">
        <center>
            <h1>Explore the World with Us!</h1>

            <p>
                Travel to amazing destinations, discover new cultures,
                and create unforgettable memories.
            </p>

            <img
                src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?w=1000"
                alt="Beautiful mountains"
                width="80%"
                height="350"
            >

            <br><br>

            <a href="#destinations">Explore Destinations</a>
        </center>
    </section>

    <hr>

    <!-- Destinations Section -->
    <section id="destinations">
        <center>
            <h1>Popular Destinations</h1>
            <p>Explore some of the world's most beautiful places.</p>
        </center>

        <table width="100%" cellpadding="15">
            <tr>
                <td align="center">
                    <img
                        src="https://images.unsplash.com/photo-1564507592333-c60657eea523?w=400"
                        alt="Taj Mahal in India"
                        width="250"
                        height="180"
                    >
                    <h3>Agra, India</h3>
                    <p>Discover the magnificent Taj Mahal.</p>
                </td>

                <td align="center">
                    <img
                        src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=400"
                        alt="Beautiful natural landscape"
                        width="250"
                        height="180"
                    >
                    <h3>Manali, India</h3>
                    <p>Enjoy mountains, valleys, and nature.</p>
                </td>

                <td align="center">
                    <img
                        src="https://images.unsplash.com/photo-1533105079780-92b9be482077?w=400"
                        alt="Santorini coastal buildings"
                        width="250"
                        height="180"
                    >
                    <h3>Santorini, Greece</h3>
                    <p>Experience beautiful coastal views.</p>
                </td>
            </tr>

            <tr>
                <td align="center">
                    <img
                        src="https://images.unsplash.com/photo-1519501025264-65ba15a82390?w=400"
                        alt="New York city skyline"
                        width="250"
                        height="180"
                    >
                    <h3>New York, USA</h3>
                    <p>Explore the exciting city life.</p>
                </td>

                <td align="center">
                    <img
                        src="https://images.unsplash.com/photo-1514282401047-d79a71a590e8?w=400"
                        alt="Tropical island"
                        width="250"
                        height="180"
                    >
                    <h3>Maldives</h3>
                    <p>Relax on beautiful tropical beaches.</p>
                </td>

                <td align="center">
                    <img
                        src="https://images.unsplash.com/photo-1548013146-72479768bada?w=400"
                        alt="Historic Indian architecture"
                        width="250"
                        height="180"
                    >
                    <h3>Jaipur, India</h3>
                    <p>Discover royal palaces and rich history.</p>
                </td>
            </tr>
        </table>
    </section>

    <hr>

    <!-- Tour Packages -->
    <section id="packages">
        <center>
            <h1>Our Tour Packages</h1>
            <p>Choose a package for your next adventure.</p>
        </center>

        <table border="1" width="100%" cellpadding="15">
            <tr>
                <th>Package</th>
                <th>Duration</th>
                <th>Price (INR)</th>
                <th>Includes</th>
            </tr>

            <tr>
                <td>Manali Adventure</td>
                <td>4 Days / 3 Nights</td>
                <td>₹9,999</td>
                <td>Hotel, sightseeing, breakfast</td>
            </tr>

            <tr>
                <td>Jaipur Heritage Tour</td>
                <td>3 Days / 2 Nights</td>
                <td>₹6,999</td>
                <td>Hotel, local tour, breakfast</td>
            </tr>

            <tr>
                <td>Goa Beach Holiday</td>
                <td>5 Days / 4 Nights</td>
                <td>₹14,999</td>
                <td>Hotel, sightseeing, breakfast</td>
            </tr>

            <tr>
                <td>Maldives Getaway</td>
                <td>5 Days / 4 Nights</td>
                <td>₹29,999</td>
                <td>Resort stay, breakfast</td>
            </tr>
        </table>

        <p>
            <center>
                <small>Prices are illustrative and should be confirmed before booking.</small>
            </center>
        </p>
    </section>

    <hr>

    <!-- About Us -->
    <section id="about">
        <center>
            <h1>About ExploreWorld</h1>

            <p>
                ExploreWorld is a tourism website designed to help
                travelers discover exciting destinations and plan
                memorable holidays.
            </p>

            <p>
                Our goal is to make travel planning simple, enjoyable,
                and accessible for everyone.
            </p>

            <h3>Why Choose Us?</h3>
        </center>

        <ul>
            <li>Popular travel destinations</li>
            <li>Affordable tour package ideas</li>
            <li>Adventure and family holiday options</li>
            <li>Easy access to travel information</li>
            <li>Inspiration for your next trip</li>
        </ul>
    </section>

    <hr>

    <!-- Contact Form -->
    <section id="contact">
        <center>
            <h1>Contact Us</h1>
            <p>Have a question? Send us your travel enquiry.</p>

            <form action="#" method="get">
                <label for="name">Full Name:</label><br>
                <input
                    type="text"
                    id="name"
                    name="name"
                    placeholder="Enter your name"
                    required
                >
                <br><br>

                <label for="email">Email Address:</label><br>
                <input
                    type="email"
                    id="email"
                    name="email"
                    placeholder="Enter your email"
                    required
                >
                <br><br>

                <label for="destination">Choose Destination:</label><br>
                <select id="destination" name="destination">
                    <option value="manali">Manali</option>
                    <option value="jaipur">Jaipur</option>
                    <option value="goa">Goa</option>
                    <option value="maldives">Maldives</option>
                    <option value="other">Other</option>
                </select>
                <br><br>

                <label for="message">Your Message:</label><br>
                <textarea
                    id="message"
                    name="message"
                    rows="5"
                    cols="30"
                    placeholder="Tell us about your travel plans"
                ></textarea>
                <br><br>

                <button type="submit">Submit Enquiry</button>
            </form>
        </center>
    </section>

    <hr>

    <!-- Footer -->
    <footer>
        <center>
            <h3>🌍 ExploreWorld</h3>
            <p>Your Journey, Our Inspiration!</p>
            <p>Email: info@example.com</p>
            <p>&copy; 2026 ExploreWorld. All rights reserved.</p>
        </center>
    </footer>

</body>
</html>
