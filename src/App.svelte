<script>

</script>

<style>
  div.home-container {
    margin: 0;
    padding: 0;
    top: 0;
    border: 0;
    outline: 0;
    height: 100%;
    display: grid;
    grid-template-columns: 2fr 2fr;
    grid-template-rows: 150px auto;
  }

  section.logo-section {
    background-image: url("assets/main-bg.svg");
    background-size: cover;
    background-repeat: no-repeat;
    display: inline-grid;
    grid-column: 2/4;
    grid-row: 1/3;
  }

  section div.podcre-logo-container {
    align-self: center;
    align-items: center;
    align-content: center;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    cursor: default;
  }

  p.podcre-field {
    font-size: 100px;
    font-weight: bold;
    text-shadow: -1px 4px 10px rgba(0, 0, 0, 0.55);
    letter-spacing: 12px;
  }

  p.podcast-field {
    color: #dadada;
    font-size: 30px;
    text-shadow: -1px 4px 10px rgba(0, 0, 0, 0.25);
  }

  p.podcast-blabla {
    align-self: center;
    align-content: center;
    margin-top: 25px;
    color: #444;
    font-weight: bold;
    font-size: 20px;
    max-width: 500px;
  }

  header {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  header > div.header-buttons-container {
    display: inline-block;
    border: 4px solid #71ae99;
    border-radius: 12px;
    text-align: center;
    color: #71ae99;
    font-size: 48px;
    font-weight: bold;
    width: auto;
    padding: 14px;
  }

  main.player-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    text-align: center;
    cursor: default;
  }

  main > p.last-episode-label {
    font-weight: bold;
    font-size: 25px;
    letter-spacing: 2.5px;
  }

  main > p.like-label {
    color: #444;
    font-size: 26px;
    font-weight: bold;
  }

  main > div > button.more-episodes-button {
    margin-top: 30px;
    padding: 20px;
    font-weight: bold;
    font-size: 26px;
    background: #3deeb0;
    color: #444;
    border: 0;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    cursor: pointer;
    border-radius: 60px;
    transition: 500ms ease-in-out;
  }

  main > div > button.more-episodes-button:hover {
    transform: translateY(-8px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
  }
</style>

<div class="home-container">
  <header>
    <div class="header-buttons-container">INÍCIO EPISÓDIOS SOBRE</div>
  </header>
  <section class="logo-section">
    <div class="podcre-logo-container">
      <p class="podcre-field">PodCrê</p>
      <p class="podcast-field">PodCast</p>
      <p class="podcast-blabla">
        3 PESSOAS COM UMA IDEIA DE M$@#$ DE GRAVAR UM PODCAST
      </p>
    </div>
  </section>
  <main class="player-container">
    <p class="last-episode-label">ESCUTE O ULTIMO EPISÓDIO LANÇADO</p>
    <p class="like-label">ESTRANHAMENTE EU GOSTEI DISSO,</p>
    <div>
      <button class="more-episodes-button">VER MAIS EPISÓDIOS</button>
    </div>
  </main>
</div>
