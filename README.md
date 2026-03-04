<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Sisi Education Platform offers trusted online learning from pre-primary to advanced with certificates, free and paid courses." />
  <meta name="keywords" content="Sisi Education Platform, online courses, Tanzania education, digital skills, AI tools" />
  <meta name="author" content="Sisi Education Platform" />
  <title>Sisi Education Platform | Learn, Grow, Succeed</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header" id="top">
    <div class="container nav-wrap">
      <a class="logo" href="#top">Sisi Education <span>Platform</span></a>
      <button id="menuToggle" class="menu-toggle" aria-label="Toggle menu">☰</button>
      <nav id="siteNav">
        <a href="#courses">Courses</a>
        <a href="#free-courses">Free Courses</a>
        <a href="#pricing">Pricing</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#blog">Blog</a>
        <a href="#faq">FAQ</a>
        <a href="#admin">Admin</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-grid">
        <div>
          <p class="badge">Trusted learning platform in Dar Es Salaam</p>
          <h1>Build your future with practical, certificate-based learning.</h1>
          <p>
            From pre-primary to advanced, Sisi Education Platform delivers professional online programs in Graphics Design,
            AI Tools, Computer Skills, and Digital Skills.
          </p>
          <div class="hero-actions">
            <a href="#courses" class="btn btn-primary">Start Learning Today</a>
            <a href="#register" class="btn btn-outline">Create Student Account</a>
          </div>
        </div>
        <div class="hero-card card">
          <h3>Why families & professionals trust us</h3>
          <ul>
            <li>Structured and easy-to-follow courses</li>
            <li>Free and paid learning tracks</li>
            <li>Downloadable completion certificates</li>
            <li>Progress tracking dashboard</li>
            <li>Mobile money payment options</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section" id="categories">
      <div class="container">
        <h2>Course categories</h2>
        <div class="grid cols-4">
          <article class="card"><h3>Pre-Primary</h3><p>Foundational literacy and digital awareness content.</p></article>
          <article class="card"><h3>Primary & Secondary</h3><p>Supportive academic and computer literacy learning.</p></article>
          <article class="card"><h3>College & Professional</h3><p>Career-focused training for high-growth industries.</p></article>
          <article class="card"><h3>Advanced Tech</h3><p>AI tools, design systems, productivity, and workflow mastery.</p></article>
        </div>
      </div>
    </section>

    <section class="section" id="courses">
      <div class="container">
        <h2>Featured courses</h2>
        <div class="grid cols-3" id="courseGrid"></div>
      </div>
    </section>

    <section class="section accent" id="free-courses">
      <div class="container">
        <h2>Featured free courses</h2>
        <p>Try our free starter courses and upgrade any time.</p>
        <div class="grid cols-3" id="freeCourseGrid"></div>
      </div>
    </section>

    <section class="section" id="pricing">
      <div class="container">
        <h2>Simple pricing</h2>
        <div class="grid cols-3">
          <article class="card price-card"><h3>Starter</h3><p class="price">Tsh 10,000</p><p>Single paid course access.</p></article>
          <article class="card price-card featured"><h3>Professional</h3><p class="price">Tsh 25,000</p><p>Any 3 courses + support.</p></article>
          <article class="card price-card"><h3>Expert</h3><p class="price">Tsh 50,000</p><p>Full bundle + mentorship.</p></article>
        </div>
      </div>
    </section>

    <section class="section" id="register">
      <div class="container two-col">
        <div>
          <h2>Student registration</h2>
          <p>Register with your legal full name so it appears correctly on your certificate.</p>
          <form id="registerForm" class="card form">
            <label>Full Name *<input required name="fullName" /></label>
            <label>Email<input type="email" required name="email" /></label>
            <label>Phone<input required name="phone" /></label>
            <button class="btn btn-primary" type="submit">Register</button>
          </form>
        </div>
        <div>
          <h2>Student dashboard</h2>
          <div class="card" id="dashboard">
            <p>No student registered yet.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section accent" id="payment">
      <div class="container two-col">
        <div>
          <h2>Payment & confirmation</h2>
          <p>For paid courses, complete payment using mobile money then upload confirmation for admin approval.</p>
          <ul>
            <li>M-Pesa: +255 740 767 638</li>
            <li>Yas: +255 779 767 638</li>
          </ul>
        </div>
        <form id="paymentForm" class="card form">
          <label>Student Name<input required name="studentName" /></label>
          <label>Course Title<input required name="courseTitle" /></label>
          <label>Network
            <select name="network"><option>M-Pesa</option><option>Yas</option></select>
          </label>
          <label>Transaction ID<input required name="txid" /></label>
          <label>Upload Proof<input type="file" name="proof" /></label>
          <button class="btn btn-primary" type="submit">Submit Payment Proof</button>
        </form>
      </div>
    </section>

    <section class="section" id="testimonials">
      <div class="container">
        <h2>Testimonials</h2>
        <div class="grid cols-3">
          <article class="card"><p>“The graphics course was practical and clear. I now get freelance work.”</p><strong>— Amina, Student</strong></article>
          <article class="card"><p>“Professional platform and great support for my child’s computer skills.”</p><strong>— Mr. Juma, Parent</strong></article>
          <article class="card"><p>“The AI tools training improved my office productivity in weeks.”</p><strong>— Neema, Professional</strong></article>
        </div>
      </div>
    </section>

    <section class="section" id="blog">
      <div class="container">
        <h2>Educational blog</h2>
        <div class="grid cols-3">
          <article class="card"><h3>How to start with digital skills</h3><p>A roadmap for learners at every level.</p></article>
          <article class="card"><h3>Top AI tools in 2026</h3><p>Tools to boost study and work performance.</p></article>
          <article class="card"><h3>Design thinking for beginners</h3><p>Creativity and problem-solving basics.</p></article>
        </div>
      </div>
    </section>

    <section class="section" id="faq">
      <div class="container">
        <h2>Frequently asked questions</h2>
        <details><summary>Are certificates free?</summary><p>Yes. Once course progress reaches 100%, a downloadable certificate is available.</p></details>
        <details><summary>Do you offer free courses?</summary><p>Yes, we provide selected free courses for trial and foundational learning.</p></details>
        <details><summary>How long does payment verification take?</summary><p>Usually within 24 hours after payment proof submission.</p></details>
      </div>
    </section>

    <section class="section accent" id="admin">
      <div class="container">
        <h2>Admin panel (demo)</h2>
        <div class="grid cols-2">
          <form id="courseForm" class="card form">
            <h3>Add / Edit Course</h3>
            <label>Course Title<input required name="title" /></label>
            <label>Description<input required name="description" /></label>
            <label>Instructor<input required name="instructor" /></label>
            <label>Price<input required name="price" /></label>
            <label>Duration<input required name="duration" /></label>
            <label>Type<select name="type"><option value="paid">Paid</option><option value="free">Free</option></select></label>
            <button class="btn btn-primary" type="submit">Save Course</button>
          </form>
          <div class="card">
            <h3>Admin tools</h3>
            <ul>
              <li>Approve pending payments</li>
              <li>View student registrations</li>
              <li>Export student list (JSON)</li>
              <li>Manage generated certificates</li>
              <li>Track analytics metrics</li>
            </ul>
            <button id="exportStudents" class="btn btn-outline">Export Students</button>
            <pre id="adminOutput"></pre>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="subscribe">
      <div class="container two-col">
        <div>
          <h2>Email subscription</h2>
          <p>Newsletter subscriptions and contact submissions are configured to be sent/stored for <strong>issahmoh01@gmail.com</strong>.</p>
        </div>
        <form id="subscribeForm" class="card form">
          <label>Email<input required type="email" name="email" /></label>
          <label>Discount / Referral Code<input name="code" placeholder="Optional" /></label>
          <button class="btn btn-primary" type="submit">Subscribe</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container grid cols-3">
      <div>
        <h3>Sisi Education Platform</h3>
        <p>Dar Es Salaam</p>
        <p>Phone: +255 740 767 638</p>
        <p>Email: issahmoh01@gmail.com</p>
      </div>
      <div>
        <h3>Quick Links</h3>
        <a href="#courses">Courses</a>
        <a href="#register">Register</a>
        <a href="#payment">Payments</a>
      </div>
      <div>
        <h3>Follow us</h3>
        <p>Facebook | Instagram | LinkedIn | YouTube</p>
      </div>
    </div>
  </footer>

  <a
    class="whatsapp-float"
    target="_blank"
    href="https://wa.me/255740767638?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20courses%20on%20Sisi%20Education%20Platform."
    aria-label="Chat on WhatsApp"
  >WhatsApp</a>

  <script src="script.js"></script>
</body>
</html>
