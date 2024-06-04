<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile App Landing Page</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
        }

        .hero {
            background: url('https://via.placeholder.com/1500x800') no-repeat center center/cover;
            height: 100vh;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 30px;
        }

        .navbar {
            padding: 15px 10px;
        }

        .navbar-brand {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .section {
            padding: 60px 0;
        }

        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 40px;
        }

        .section p {
            font-size: 1.2rem;
        }

        #features .col-md-4 {
            margin-bottom: 20px;
        }

        #features .fa-3x {
            color: #007bff;
        }

        #download .btn {
            margin: 10px;
        }

        footer {
            background: #333;
            color: #fff;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">AppName</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#features">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#download">Download</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero d-flex align-items-center">
        <div class="container text-center">
            <h1 class="display-4">Welcome to AppName</h1>
            <p class="lead">Your ultimate app for managing tasks and boosting productivity.</p>
            <a href="#download" class="btn btn-primary btn-lg">Download Now</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="section">
        <div class="container">
            <h2 class="text-center">Features</h2>
            <div class="row text-center mt-4">
                <div class="col-md-4">
                    <i class="fas fa-check-circle fa-3x mb-3"></i>
                    <h3>Easy to Use</h3>
                    <p>Simple and intuitive interface for everyone.</p>
                </div>
                <div class="col-md-4">
                    <i class="fas fa-chart-line fa-3x mb-3"></i>
                    <h3>Productivity</h3>
                    <p>Boost your productivity with powerful tools.</p>
                </div>
                <div class="col-md-4">
                    <i class="fas fa-cloud fa-3x mb-3"></i>
                    <h3>Cloud Sync</h3>
                    <p>Sync your data across all your devices.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Download Section -->
    <section id="download" class="section bg-light">
        <div class="container text-center">
            <h2>Download the App</h2>
            <p>Available on iOS and Android.</p>
            <div class="mt-4">
                <a href="#" class="btn btn-outline-dark btn-lg"><i class="fab fa-apple"></i> App Store</a>
                <a href="#" class="btn btn-outline-dark btn-lg"><i class="fab fa-google-play"></i> Google Play</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <div class="row mt-4">
                <div class="col-md-8 mx-auto">
                    <form>
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Your Name">
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Your Email">
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea class="form-control" id="message" rows="5" placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-4 bg-dark text-white text-center">
        <p>&copy; 2024 AppName. All rights reserved.</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
