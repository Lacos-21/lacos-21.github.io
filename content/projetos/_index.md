---
title: "Projetos em Andamento"
date: 2025-04-10
type: "page"
layout: "list"  # Layout customizado (crie em layouts/section/projects.html se quiser)
featured_image: "/images/featured-default.jpg"
description: "Iniciativas ativas do nosso laboratório"
---
## Nossas Áreas

<div class="areas-outer-container">
  <div class="areas-inner-container">
    <div class="areas-grid">
      <!-- Bloco 1 -->
      <div class="area-card">
        <div class="area-icon">📚</div>
        <h3>Shortfalls</h3>
        <p>Lacunas do conhecimento da Biodiversidade</p>
        <a href="/shortfalls" class="area-btn">Entenda</a>
      </div>  
      <!-- Bloco 2 -->
      <div class="area-card">
        <div class="area-icon">🌎</div>
        <h3>Conservação</h3>
        <p>Conservação e Macroecologia</p>
        <a href="/conservacao" class="area-btn">Descubra</a>
      </div>  
      <!-- Bloco 3 -->
      <div class="area-card">
        <div class="area-icon">🌐</div>
        <h3>Culturomics</h3>
        <p>Culturomics e iEcology</p>
        <a href="/culturomics" class="area-btn">Explore</a>
      </div>  
      <!-- Bloco 4 -->
      <div class="area-card">
        <div class="area-icon">⚖️</div>
        <h3>Sinbiose</h3>
        <p>EquiDados</p>
        <a href="/projetos/sinbiose" class="area-btn">Saiba Mais</a>
      </div>
    </div>
  </div>
</div>

<style>
  /* CONTAINER EXTERNO - LARGURA TOTAL */
  .areas-outer-container {
    width: 100vw;
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    background: #f8f9fa;
    padding: 3rem 0;
    overflow: hidden;
  }

  /* CONTAINER INTERNO - CONTROLE DE LARGURA */
  .areas-inner-container {
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 20px;
  }

  /* GRID FLEXÍVEL */
  .areas-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    justify-items: center;
  }

  /* CARDS */
  .area-card {
    background: white;
    border-radius: 10px;
    padding: 2rem;
    text-align: center;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    width: 100%;
    max-width: 280px;
  }

  .area-icon {
    font-size: 2.8rem;
    color: #2E7D32;
    margin-bottom: 1rem;
  }

  .area-card h3 {
    margin: 0.5rem 0 1rem;
    color: #2c3e50;
    font-size: 1.3rem;
  }

  .area-card p {
    color: #555;
    margin-bottom: 1.5rem;
    line-height: 1.5;
    min-height: 4.5rem;
  }

  /* BOTÕES */
  .area-btn {
    display: inline-block;
    background: #2E7D32;
    color: white !important;
    padding: 0.8rem 2.2rem;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 500;
    transition: all 0.3s;
    font-size: 1rem;
  }

  .area-btn:hover {
    background: #1B5E20;
    transform: translateY(-3px);
    box-shadow: 0 6px 16px rgba(0,0,0,0.12);
  }

  /* RESPONSIVIDADE */
  @media (max-width: 1200px) {
    .areas-grid {
      grid-template-columns: repeat(2, minmax(250px, 1fr));
    }
  }

  @media (max-width: 768px) {
    .areas-grid {
      grid-template-columns: 1fr;
      max-width: 400px;
      margin: 0 auto;
    }
  
    .area-card {
      padding: 1.8rem;
    }
  }
</style>
