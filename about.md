---
layout: page
title: "about-potatomilk"
permalink: /
---

<style>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  background: #FFF8DC;
}

.hero {
  position: relative;
  background: linear-gradient(135deg, #8B4513 0%, #6B4423 100%);
  color: #FFFFFF;
  padding: 60px 20px;
  text-align: center;
  border-radius: 10px;
  margin-bottom: 40px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}
.hero::after {
  content: "";
  position: absolute; inset: 0;
  background: rgba(0,0,0,0.18); /* subtle overlay for contrast */
  border-radius: 10px;
}
.hero > * { position: relative; } /* keep text above overlay */
.hero h2 {
  color: #FFF8DC;              /* cream */
  font-weight: 500;
  text-shadow: 0 2px 6px rgba(0,0,0,0.35);
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 10px;
}


.section {
  background: #FAF0E6;
  padding: 40px;
  margin: 30px 0;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
}

.feature-card {
  background: white;
  padding: 25px;
  border-radius: 8px;
  border-left: 4px solid #00CED1;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.feature-card h3 {
  color: #8B4513;
  margin-top: 0;
}

.cta-section {
  background: #00CED1;
  color: white;
  padding: 40px;
  text-align: center;
  border-radius: 8px;
  margin: 40px 0;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.styled-table {
  width: 100%;
  border-collapse: collapse;
  margin: 30px 0;
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.styled-table th, .styled-table td {
  padding: 15px;
  text-align: left;
  border-bottom: 1px solid #F5F5DC;
}

.styled-table th {
  background-color: #8B4513;
  color: white;
  font-weight: 600;
}

.styled-table tr:hover {
  background-color: #FFF8DC;
}

.benefits-list {
  list-style: none;
  padding: 0;
}

.benefits-list li {
  padding: 10px 0;
  border-bottom: 1px solid #F5F5DC;
}

.benefits-list li:before {
  content: "✓ ";
  color: #00CED1;
  font-weight: bold;
  margin-right: 10px;
}

.contact-links a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  padding: 10px 20px;
  background: rgba(139, 69, 19, 0.3);
  border-radius: 5px;
  display: inline-block;
  transition: background 0.3s;
}

.contact-links a:hover {
  background: rgba(139, 69, 19, 0.5);
}

.footer {
  text-align: center;
  margin-top: 40px;
  padding: 20px;
  color: #8B4513;
  font-size: 0.9em;
}

h2 {
  color: #8B4513;
  border-bottom: 2px solid #00CED1;
  padding-bottom: 10px;
}

.media-section {
  display: grid;
  grid-template-columns: 1fr 1.5fr;
  gap: 28px;
  align-items: center;
}
.media-section .media {
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
  background: #FAF0E6; /* cream */
}
.media-section .media img {
  width: 100%;
  height: auto;
  display: block;
}
.media-section .content h2 {
  color: #8B4513; /* rich brown */
  margin-top: 0;
  border-bottom: 2px solid #00CED1; /* teal accent */
  padding-bottom: 10px;
}
@media (max-width: 860px) {
  .media-section { grid-template-columns: 1fr; }
}

</style>

<div class="hero">
  <h1>🥔 Potato Milk</h1>
  <h2>The Ultimate Mid-Workout Fuel for Endurance Athletes</h2>
</div>

<div class="section media-section">
  <div class="media">
    <img src="/assets/images/potato-milk.jpg" alt="Potato Milk product">
  </div>
  <div class="content">
    <h2>🚀 What is Potato Milk?</h2>
    <p>Potato Milk is a revolutionary mid-workout energizing drink specifically designed for endurance athletes. Made from premium potato starch and natural ingredients, it delivers sustained energy without the crash associated with traditional sports drinks.</p>
    <ul class="benefits-list">
      <li>Steady, complex-carb energy</li>
      <li>Gentle on the stomach</li>
      <li>Plant-based and clean</li>
    </ul>
  </div>
</div>

<div class="section">
  <h2>💪 Why Choose Potato Milk?</h2>
  <div class="feature-grid">
    <div class="feature-card">
      <h3>Sustained Energy Release</h3>
      <ul class="benefits-list">
        <li>Complex carbohydrates from potato starch provide steady fuel</li>
        <li>No sugar crashes or energy spikes</li>
        <li>Perfect for long-distance training sessions</li>
      </ul>
    </div>
    
    <div class="feature-card">
      <h3>Easy Digestion</h3>
      <ul class="benefits-list">
        <li>Gentle on the stomach during intense exercise</li>
        <li>No bloating or digestive discomfort</li>
        <li>Rapid absorption for quick energy replenishment</li>
      </ul>
    </div>
    
    <div class="feature-card">
      <h3>Natural & Clean</h3>
      <ul class="benefits-list">
        <li>No artificial flavors or sweeteners</li>
        <li>Plant-based and vegan-friendly</li>
        <li>Minimal ingredients for maximum performance</li>
      </ul>
    </div>
  </div>
</div>

<div class="section">
  <h2>🏃‍♂️ Built For Endurance Athletes</h2>
  <div class="feature-grid">
    <div class="feature-card">
      <h3>Ideal For:</h3>
      <ul class="benefits-list">
        <li>Marathon runners</li>
        <li>Cyclists</li>
        <li>Triathletes</li>
        <li>Ultra-endurance events</li>
        <li>Long-distance swimmers</li>
      </ul>
    </div>
    
    <div class="feature-card">
      <h3>When to Use:</h3>
      <ul class="benefits-list">
        <li>During workouts lasting 60+ minutes</li>
        <li>Between training segments</li>
        <li>Race day fueling strategy</li>
        <li>Recovery sessions</li>
      </ul>
    </div>
  </div>
</div>

<div class="section">
  <h2>✨ Product Features</h2>
  <table class="styled-table">
    <thead>
      <tr>
        <th>Feature</th>
        <th>Benefit</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Electrolyte Balance</strong></td>
        <td>Maintains hydration and prevents cramping</td>
      </tr>
      <tr>
        <td><strong>25g Complex Carbs</strong></td>
        <td>Sustained energy release</td>
      </tr>
      <tr>
        <td><strong>Zero Added Sugar</strong></td>
        <td>Clean energy without the crash</td>
      </tr>
      <tr>
        <td><strong>Light Flavor</strong></td>
        <td>Easy to drink during intense exercise</td>
      </tr>
      <tr>
        <td><strong>Vegan & Gluten-Free</strong></td>
        <td>Suitable for all dietary preferences</td>
      </tr>
    </tbody>
  </table>
</div>

<div class="section">
  <h2>📊 Performance Data</h2>
  <div class="feature-grid">
    <div class="feature-card">
      <h3>Energy Duration</h3>
      <p>2-3 hours sustained fuel</p>
    </div>
    <div class="feature-card">
      <h3>Digestion Time</h3>
      <p>Under 15 minutes</p>
    </div>
    <div class="feature-card">
      <h3>Calories per Serving</h3>
      <p>120</p>
    </div>
    <div class="feature-card">
      <h3>Carbohydrates</h3>
      <p>25g</p>
    </div>
    <div class="feature-card">
      <h3>Sodium</h3>
      <p>200mg</p>
    </div>
  </div>
</div>

<div class="section">
  <h2>🎯 Get Started</h2>
  <div class="feature-grid">
    <div class="feature-card">
      <h3>Training Protocol</h3>
      <ol>
        <li><strong>Pre-Workout:</strong> 30 minutes before training</li>
        <li><strong>During:</strong> Every 45-60 minutes during long sessions</li>
        <li><strong>Post-Workout:</strong> Within 30 minutes for recovery</li>
      </ol>
    </div>
    
    <div class="feature-card">
      <h3>Flavors Available</h3>
      <ul class="benefits-list">
        <li>Natural Plain</li>
        <li>Light Berry</li>
        <li>Citrus Burst</li>
      </ul>
    </div>
  </div>
</div>

<div class="cta-section">
  <h2>📞 Ready to Fuel Your Performance?</h2>
  <p><strong>Join thousands of endurance athletes who've discovered the power of Potato Milk.</strong></p>
  <div class="contact-links">
    <a href="mailto:info@potatomilk.com">📧 Contact Us</a>
    <a href="https://twitter.com/potatomilk">🐦 Follow Us</a>
    <a href="https://instagram.com/potatomilk">📷 Instagram</a>
  </div>
</div>

<div class="footer">
  <p>© 2024 Potato Milk. Fueling Champions, One Sip at a Time.</p>
</div>