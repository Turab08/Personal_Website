---
layout: default
title: Blog
permalink: /blog/
---

<div class="blog-page">
  <div class="container">
    <header class="page-header">
      <h1>Blog</h1>
      <p class="page-subtitle">Thoughts on game development, programming, and creative projects</p>
    </header>

    <div class="blog-posts">
      {% if site.posts.size > 0 %}
        {% for post in site.posts %}
          <article class="blog-post">
            <header class="post-header">
              <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
              <time class="post-date">{{ post.date | date: "%B %d, %Y" }}</time>
            </header>
            
            <div class="post-excerpt">
              {{ post.excerpt }}
            </div>
            
            <footer class="post-footer">
              <a href="{{ post.url | relative_url }}" class="read-more">Read More →</a>
            </footer>
          </article>
        {% endfor %}
      {% else %}
        <div class="no-posts">
          <p>No blog posts yet. Check back soon for updates on my game development journey!</p>
        </div>
      {% endif %}
    </div>
  </div>
</div>

<style>
.blog-page {
  padding: 2rem 0 4rem;
  background: #111827;
  min-height: 100vh;
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
  color: #f9fafb;
  margin-bottom: 0.5rem;
}

.page-subtitle {
  font-size: 1.25rem;
  color: #9ca3af;
  margin: 0;
}

.blog-posts {
  display: flex;
  flex-direction: column;
  gap: 3rem;
}

.blog-post {
  background: #1f2937;
  padding: 2rem;
  border-radius: 12px;
  border: 1px solid #374151;
  transition: transform 0.2s, box-shadow 0.2s;
}

.blog-post:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
}

.post-header h2 {
  margin: 0 0 0.5rem;
}

.post-header h2 a {
  color: #f9fafb;
  text-decoration: none;
  font-size: 1.5rem;
  font-weight: 600;
}

.post-header h2 a:hover {
  color: #3b82f6;
}

.post-date {
  color: #9ca3af;
  font-size: 0.875rem;
  font-weight: 500;
}

.post-excerpt {
  color: #d1d5db;
  line-height: 1.6;
  margin: 1.5rem 0;
}

.post-excerpt p {
  margin: 0;
}

.post-footer {
  border-top: 1px solid #374151;
  padding-top: 1rem;
  margin-top: 1.5rem;
}

.read-more {
  color: #3b82f6;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s;
}

.read-more:hover {
  color: #2563eb;
}

.no-posts {
  text-align: center;
  padding: 3rem 0;
}

.no-posts p {
  color: #9ca3af;
  font-size: 1.125rem;
}

@media (max-width: 768px) {
  .page-header h1 {
    font-size: 2rem;
  }
  
  .blog-post {
    padding: 1.5rem;
  }
  
  .container {
    padding: 0 1rem;
  }
}
</style>