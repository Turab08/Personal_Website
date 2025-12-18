---
layout: default
title: About
permalink: /about/
---

<div class="about-page">
  <div class="container">
    <header class="page-header">
      <h1>About Me</h1>
      <p class="page-subtitle">Computer Science Student & Game Development Enthusiast</p>
    </header>

    <div class="about-content">
      <section class="about-section">
        <h2>Background</h2>
        <p>I'm a passionate computer science student with a deep love for creating interactive experiences and sharing knowledge with others. My journey into programming began with curiosity about how games work, which led me to explore the fascinating world of software development.</p>
        
        <p>What drives me most is the intersection of technology and creativity. Whether I'm coding a web application, composing music, or designing a game mechanic, I'm always looking for ways to use technology to tell stories and solve problems in innovative ways.</p>
      </section>

      <section class="about-section">
        <h2>Education</h2>
        <div class="education-item">
          <h3>Computer Science Studies</h3>
          <p class="education-details">Currently pursuing computer science education with focus on:</p>
          <ul>
            <li>Software Development & Programming</li>
            <li>Algorithms & Data Structures</li>
            <li>Web Technologies</li>
            <li>Game Development</li>
          </ul>
        </div>
      </section>

      <section class="about-section">
        <h2>Skills</h2>
        <div class="skills-grid">
          <div class="skill-category">
            <h3>Programming Languages</h3>
            <ul>
              <li>Python</li>
              <li>JavaScript</li>
              <li>HTML/CSS</li>
              <li>C#</li>
            </ul>
          </div>
          
          <div class="skill-category">
            <h3>Technologies & Tools</h3>
            <ul>
              <li>Git & GitHub</li>
              <li>Jekyll</li>
              <li>Unity Game Engine</li>
              <li>Web Development</li>
            </ul>
          </div>
          
          <div class="skill-category">
            <h3>Creative Skills</h3>
            <ul>
              <li>Music Production</li>
              <li>Game Design</li>
              <li>Digital Audio</li>
              <li>Teaching & Mentoring</li>
            </ul>
          </div>
        </div>
      </section>

      <section class="about-section">
        <h2>Activities & Experience</h2>
        
        <div class="experience-item">
          <h3>Game Development Club Leader</h3>
          <p class="experience-role">School Club • Present</p>
          <p>Founded and lead a game development club where I teach programming fundamentals, game design principles, and creative problem-solving to fellow students. We work on collaborative projects and explore different aspects of game creation.</p>
          <ul>
            <li>Teaching programming basics to beginners</li>
            <li>Organizing game development workshops</li>
            <li>Mentoring students on personal projects</li>
            <li>Building a community of creative developers</li>
          </ul>
        </div>
        
        <div class="experience-item">
          <h3>Personal Projects</h3>
          <p class="experience-role">Independent Learning • Ongoing</p>
          <p>Continuously working on personal coding projects to expand my skills and explore new technologies. From web applications to game prototypes, each project teaches me something new.</p>
          <ul>
            <li>Building responsive web applications</li>
            <li>Creating interactive game prototypes</li>
            <li>Experimenting with music and technology integration</li>
            <li>Contributing to open-source projects</li>
          </ul>
        </div>
      </section>
    </div>
  </div>
</div>

<style>
.about-page {
  padding: 2rem 0 4rem;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 1rem;
}

.page-header {
  text-align: center;
  margin-bottom: 3rem;
}

.page-header h1 {
  font-size: 2.5rem;
  color: #111827;
  margin-bottom: 0.5rem;
}

.page-subtitle {
  font-size: 1.25rem;
  color: #6b7280;
  margin: 0;
}

.about-content {
  line-height: 1.7;
}

.about-section {
  margin-bottom: 3rem;
}

.about-section h2 {
  font-size: 1.75rem;
  color: #111827;
  margin-bottom: 1.5rem;
  border-bottom: 2px solid #e5e7eb;
  padding-bottom: 0.5rem;
}

.about-section p {
  color: #4b5563;
  margin-bottom: 1rem;
}

.education-item, .experience-item {
  margin-bottom: 2rem;
}

.education-item h3, .experience-item h3 {
  font-size: 1.25rem;
  color: #111827;
  margin-bottom: 0.5rem;
}

.education-details, .experience-role {
  color: #6b7280;
  font-style: italic;
  margin-bottom: 1rem;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 1.5rem;
}

.skill-category {
  background: #f9fafb;
  padding: 1.5rem;
  border-radius: 8px;
  border: 1px solid #e5e7eb;
}

.skill-category h3 {
  font-size: 1.125rem;
  color: #111827;
  margin-bottom: 1rem;
}

.skill-category ul, .education-item ul, .experience-item ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.skill-category li, .education-item li, .experience-item li {
  color: #4b5563;
  padding: 0.25rem 0;
  position: relative;
  padding-left: 1.5rem;
}

.skill-category li:before, .education-item li:before, .experience-item li:before {
  content: '•';
  color: #3b82f6;
  font-weight: bold;
  position: absolute;
  left: 0;
}

@media (max-width: 768px) {
  .page-header h1 {
    font-size: 2rem;
  }
  
  .skills-grid {
    grid-template-columns: 1fr;
  }
  
  .container {
    padding: 0 1.5rem;
  }
}
</style>
