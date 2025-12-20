---
layout: default
title: Projects
permalink: /projects/
---

<div class="projects-page">
  <div class="container">
    <header class="page-header">
      <h1>My Projects</h1>
      <p class="page-subtitle">A showcase of my game development and programming work</p>
    </header>

    <div class="projects-grid">
      <div class="project-card">
        <div class="project-image">
          <iframe width="100%" height="200" src="https://www.youtube.com/embed/UPXXizUCb7o" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="project-content">
          <h3>Project 1</h3>
          <p>An exciting game development project showcasing interactive gameplay mechanics and creative design. This project demonstrates my skills in game programming, level design, and user experience.</p>
          <div class="project-links">
            <a href="https://www.youtube.com/watch?v=UPXXizUCb7o" target="_blank" rel="noopener noreferrer" class="project-link">Watch Demo</a>
          </div>
        </div>
      </div>

      <div class="project-card">
        <div class="project-image">
          <iframe width="100%" height="200" src="https://www.youtube.com/embed/YWAYIXMufWQ" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="project-content">
          <h3>Project 2</h3>
          <p>A comprehensive project that explores advanced programming concepts and innovative solutions. Features custom mechanics, polished visuals, and engaging gameplay elements.</p>
          <div class="project-links">
            <a href="https://www.youtube.com/watch?v=YWAYIXMufWQ" target="_blank" rel="noopener noreferrer" class="project-link">Watch Demo</a>
          </div>
        </div>
      </div>
    </div>

    <section class="additional-projects">
      <h2>Additional Projects</h2>
      <div class="projects-grid">
        <div class="project-card coming-soon">
          <div class="project-content">
            <h3>Published Games on Itch.io</h3>
            <p>A collection of games I've created and published on itch.io, showcasing different mechanics, art styles, and gameplay concepts. Each game represents a learning milestone in my game development journey.</p>
            <div class="project-links">
              <a href="https://jit-games.itch.io/" target="_blank" rel="noopener noreferrer" class="project-link">View Games</a>
            </div>
          </div>
        </div>

        <div class="project-card coming-soon">
          <div class="project-content">
            <h3>Interactive Game Mechanics</h3>
            <p>Exploring innovative gameplay mechanics and interactive storytelling through experimental game prototypes and creative coding projects.</p>
            <div class="project-status">
              <span class="status-badge">Coming Soon</span>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</div>

<style>
.projects-page {
  padding: 2rem 0 4rem;
  background: #111827;
  min-height: 100vh;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1rem;
}

.page-header {
  text-align: center;
  margin-bottom: 3rem;
}

.page-header h1 {
  font-size: 2.5rem;
  color: #f9fafb;
  margin-bottom: 0.5rem;
}

.page-subtitle {
  font-size: 1.25rem;
  color: #9ca3af;
  margin: 0;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

.project-card {
  background: #1f2937;
  border-radius: 12px;
  overflow: hidden;
  border: 1px solid #374151;
  transition: transform 0.2s, box-shadow 0.2s;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.project-image {
  width: 100%;
  height: 200px;
  background: #374151;
}

.project-image iframe {
  border-radius: 8px 8px 0 0;
}

.project-content {
  padding: 1.5rem;
}

.project-content h3 {
  font-size: 1.5rem;
  color: #f9fafb;
  margin-bottom: 1rem;
}

.project-content p {
  color: #d1d5db;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.project-links {
  display: flex;
  gap: 1rem;
}

.project-link {
  background: #3b82f6;
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  transition: background 0.2s;
}

.project-link:hover {
  background: #2563eb;
}

.additional-projects {
  margin-top: 4rem;
}

.additional-projects h2 {
  font-size: 2rem;
  color: #f9fafb;
  text-align: center;
  margin-bottom: 2rem;
  border-bottom: 2px solid #374151;
  padding-bottom: 1rem;
}

.coming-soon {
  opacity: 0.8;
}

.project-status {
  margin-top: 1rem;
}

.status-badge {
  background: #374151;
  color: #9ca3af;
  padding: 0.25rem 0.75rem;
  border-radius: 12px;
  font-size: 0.875rem;
  font-weight: 500;
}

@media (max-width: 768px) {
  .page-header h1 {
    font-size: 2rem;
  }
  
  .projects-grid {
    grid-template-columns: 1fr;
  }
  
  .project-image {
    height: 180px;
  }
}

@media (max-width: 480px) {
  .container {
    padding: 0 1rem;
  }
  
  .project-content {
    padding: 1rem;
  }
}
</style>
