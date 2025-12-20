---
layout: default
title: Home
---

<div class="hero-section">
  <div class="hero-container">
    <div class="hero-content">
      <div class="profile-photo">
        <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Turab Hasanli" />
      </div>
      
      <div class="hero-text">
        <h1>Hi, I'm Turab Hasanli</h1>
        <p class="tagline">Computer Science Student & Game Developer</p>
        
        <div class="intro">
          <p>Hi! I’m a student and game development enthusiast who loves creating interactive experiences and teaching others how games are made. I run a school game development club, where I help beginners learn programming, design, and creative problem-solving through hands-on projects. I’m especially interested in storytelling, gameplay mechanics, and using games as a tool for learning and creativity.</p>
        </div>
        
        <div class="cta-buttons">
          <a href="{{ '/projects/' | relative_url }}" class="btn-primary">View Projects</a>
          <a href="{{ '/about/' | relative_url }}" class="btn-secondary">Learn More</a>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="highlights-section">
  <div class="container">
    <h2>What I'm Working On</h2>
    <div class="highlights-grid">
      <div class="highlight-card">
        <h3>💻 Coding</h3>
        <p>Building games with Unity and C#, learning programming through interactive projects, and solving game development challenges.</p>
      </div>
      
      <div class="highlight-card">
        <h3>🎵 Music</h3>
        <p>Exploring music production, composition, and the intersection of technology and creative expression through digital audio.</p>
      </div>
      
      <div class="highlight-card">
        <h3>🎮 Game Development</h3>
        <p>Creating interactive experiences, teaching game development at my school club, and exploring storytelling through gameplay mechanics.</p>
      </div>
    </div>
  </div>
</div>

<style>
.hero-section {
  padding: 4rem 0 6rem;
  background: linear-gradient(135deg, #f8fafc 0%, #f1f5f9 100%);
}

.hero-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1rem;
}

.hero-content {
  display: grid;
  grid-template-columns: 200px 1fr;
  gap: 3rem;
  align-items: center;
}

.profile-photo {
  text-align: center;
}

.profile-photo img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #fff;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

.hero-text h1 {
  font-size: 2.5rem;
  font-weight: 700;
  color: #111827;
  margin: 0 0 0.5rem;
}

.tagline {
  font-size: 1.25rem;
  color: #6b7280;
  margin: 0 0 2rem;
  font-weight: 500;
}

.intro {
  margin-bottom: 2rem;
}

.intro p {
  color: #4b5563;
  line-height: 1.7;
  margin-bottom: 1rem;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
}

.btn-primary, .btn-secondary {
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.2s;
}

.btn-primary {
  background: #3b82f6;
  color: white;
}

.btn-primary:hover {
  background: #2563eb;
  transform: translateY(-1px);
}

.btn-secondary {
  background: transparent;
  color: #374151;
  border: 2px solid #d1d5db;
}

.btn-secondary:hover {
  border-color: #9ca3af;
  background: #f9fafb;
}

.highlights-section {
  padding: 4rem 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1rem;
}

.highlights-section h2 {
  text-align: center;
  font-size: 2rem;
  color: #ffffff;
  margin-bottom: 3rem;
}

.highlights-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.highlight-card {
  background: #fff;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
  border: 1px solid #e5e7eb;
}

.highlight-card h3 {
  font-size: 1.25rem;
  color: #111827;
  margin-bottom: 1rem;
}

.highlight-card p {
  color: #6b7280;
  line-height: 1.6;
  margin: 0;
}

@media (max-width: 768px) {
  .hero-content {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 2rem;
  }
  
  .hero-text h1 {
    font-size: 2rem;
  }
  
  .cta-buttons {
    justify-content: center;
    flex-wrap: wrap;
  }
  
  .highlights-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 480px) {
  .profile-photo img {
    width: 150px;
    height: 150px;
  }
  
  .hero-section {
    padding: 2rem 0 4rem;
  }
}
</style>
