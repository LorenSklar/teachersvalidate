<script>
  const teacherForm = "https://forms.gle/6vyEzT8jDiGYbEzn9";
  const founderForm = "https://forms.gle/RPSzZNqYLedcp1d96";
</script>

<section>
  <p class="label">Which one are you?</p>
  <div class="buttons">
    <a href={founderForm} target="_blank" class="button">I'm a founder</a>
    <a href={teacherForm} target="_blank" class="button">I'm a teacher</a>
  </div>
</section>

<style>
  section {    width: 100%;
    max-width: 680px;
    padding: 4rem 2rem;
    box-sizing: border-box;
    text-align: center;
    border-top: 1px solid rgba(223, 255, 0, 0.2);
  }

  .label {
    font-size: clamp(1.0rem, 2vw, 1.1rem);
    color: rgba(255, 255, 255, 0.45);
    text-transform: uppercase;
    letter-spacing: 0.15em;
    margin: 0 0 1.5rem 0;
  }

  .buttons {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
  }

  .button {
    display: block;
    text-align: center;
    width: 100%;
    max-width: 280px;
    padding: 1.2rem 2rem;
    border: 2px solid #DFFF00;
    border-radius: 8px;
    color: #DFFF00;
    background: transparent;
    font-size: clamp(1.15rem, 3vw, 1.35rem);
    text-decoration: none;
    box-sizing: border-box;
    transition: border-width 0.1s;
  }

  .button:hover {
    border-width: 4px;
    font-weight: 700;
  }

  @media (min-width: 768px) {
    .buttons {
      flex-direction: row;
      justify-content: center;
    }
  }
</style>
