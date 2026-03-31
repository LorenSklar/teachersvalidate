<main>
  <div class="hero">
    <h1>Be part of the movement changing EdTech.</h1>
    <div class="buttons">
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSe07j7lzdTbRIUZFis8LnMFXCH6EiXjIR2HXWCJaP2txzHbPg/viewform?usp=header" target="_blank" class="btn">
        I'm a founder. I need to move faster.
      </a>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSfYqPAK3osedzk9BVHCo_b7RM2D1PbYigYl3NdPjUoxtKfl5g/viewform?usp=header" target="_blank" class="btn">
        I'm a teacher. Stop asking me to help for free.
      </a>
    </div>
  </div>
</main>

<style>
  main {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #2000FF;
    padding: 2rem;
    font-family: 'Inter', sans-serif;
  }

  .hero {
    text-align: center;
    max-width: 680px;
  }

  h1 {
    font-size: clamp(1.8rem, 4vw, 2.8rem);
    color: #FFFFFF;
    font-weight: 700;
    line-height: 1.3;
    margin-bottom: 3rem;
  }

  .buttons {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1.2rem;
  }

  .btn {
    display: block;
    width: 100%;
    max-width: 480px;
    padding: 1.2rem 2rem;
    border: 2px solid #DFFF00;
    border-radius: 8px;
    color: #DFFF00;
    background: transparent;
    font-size: 1.1rem;
    font-weight: 400;
    text-decoration: none;
    transition: font-weight 0.1s;
  }

  .btn:hover {
    font-weight: 700;
  }

  @media (min-width: 640px) {
    .buttons {
      flex-direction: row;
      justify-content: center;
    }

    .btn {
      max-width: 320px;
    }
  }
</style>