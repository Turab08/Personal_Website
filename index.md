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
        <p class="tagline">Computer Science Student & Aspiring Developer</p>
        
        <div class="intro">
          <p>I'm a passionate computer science student with a keen interest in software development, web technologies, and problem-solving. Currently expanding my skills through hands-on projects and continuous learning.</p>
          
          <p>When I'm not coding, you'll find me exploring new technologies, contributing to open-source projects, or diving deep into algorithms and data structures.</p>
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
        <h3>🎓 Learning</h3>
        <p>Expanding my knowledge in full-stack development, algorithms, and modern web frameworks.</p>
      </div>
      
      <div class="highlight-card">
        <h3>💻 Building</h3>
        <p>Creating personal projects to apply theoretical knowledge and build a strong portfolio.</p>
      </div>
      
      <div class="highlight-card">
        <h3>🚀 Growing</h3>
        <p>Actively participating in coding challenges and contributing to the developer community.</p>
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
  color: #111827;
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
