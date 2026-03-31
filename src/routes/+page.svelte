<script>
  const teacherForm = "YOUR_TEACHER_FORM_URL";
  const founderForm = "YOUR_FOUNDER_FORM_URL";
</script>

<main>
  <div class="hero">
    <h1>Be part of the movement changing EdTech.</h1>
    <div class="button-container">
      <a href={founderForm} target="_blank" class="button">
        <span>I'm a founder.</span>
        <span>I need real feedback to iterate faster.</span>
      </a>
      <a href={teacherForm} target="_blank" class="button">
        <span>I'm a teacher.</span>
        <span>Stop asking me to help for free.</span>
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
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
  }

  .hero {
    text-align: center;
    max-width: 680px;
    width: 100%;
  }

  h1 {
    font-size: clamp(2.7rem, 4vw, 3.3rem);
    color: #FFFFFF;
    font-weight: 700;
    line-height: 1.3;
    margin-bottom: 3rem;
  }

  .button-container {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  gap: 1.2rem;
  width: 100%;
  }

  .button {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  width: 100%;
  max-width: 480px;
  padding: 1.2rem 2rem;
  border: 2px solid #DFFF00;
  border-radius: 8px;
  color: #DFFF00;
  background: transparent;
  font-size: 1.3rem;
  font-weight: 400;
  text-decoration: none;
  transition: font-weight 0.1s;
  box-sizing: border-box;
  }

  .button:hover {
    font-weight: 700;
    border-width: 5px;
  }

  @media (min-width: 768px) {
    .button-container {
      flex-direction: row;
      justify-content: center;
      align-items: stretch;
    }

    .button {
      max-width: 320px;
    }
  }
</style>