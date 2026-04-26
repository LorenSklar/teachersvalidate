<section>
  <h2>How do I earn?</h2>
  <div class="steps">
    <div class="step">
      <span class="number">01</span>
      <p>Founders post their edtech tool to the platform</p>
    </div>
    <div class="arrow">→</div>
    <div class="step">
      <span class="number">02</span>
      <p>You choose which projects you want to review</p>
    </div>
    <div class="arrow">→</div>
    <div class="step">
      <span class="number">03</span>
      <p>Founders pay you to hear what actually works in the classroom</p>
    </div>
  </div>
</section>

<style>
  section {
    width: 100%;
    max-width: 780px;
    padding: 4rem 2rem;
    box-sizing: border-box;
    text-align: center;
    border-top: 1px solid rgba(223, 255, 0, 0.2);
  }

  h2 {
    font-size: clamp(1.0rem, 2vw, 1.1rem);
    color: rgba(255, 255, 255, 0.45);
    font-weight: 400;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    margin: 0 0 3rem 0;
  }

  .steps {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1.5rem;
  }

  .step {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5rem;
    max-width: 220px;
  }

  .number {
    font-size: clamp(1.0rem, 2vw, 1.1rem);
    font-weight: 700;
    color: #DFFF00;
    letter-spacing: 0.1em;
  }

  p {
    font-size: clamp(1.15rem, 3vw, 1.35rem);
    color: #FFFFFF;
    line-height: 1.5;
    margin: 0;
  }

  .arrow {
    font-size: 1.4rem;
    color: rgba(223, 255, 0, 0.4);
    transform: rotate(90deg);
  }

  @media (min-width: 768px) {
    .steps {
      flex-direction: row;
      justify-content: center;
      align-items: flex-start;
      gap: 0;
    }

    .step {
      flex: 1;
      max-width: 220px;
    }

    .arrow {
      transform: none;
      padding-top: 1.2rem;
      flex-shrink: 0;
    }
  }
</style>
