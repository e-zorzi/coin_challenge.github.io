<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CoIN Challenge 2026</title>

<style>
:root {
    --primary: #2563eb;
    --bg: #f8fafc;
    --text: #1e293b;
    --muted: #64748b;
    --border: #e2e8f0;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Inter, Arial, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

.container {
    width: min(1100px, 90%);
    margin: 0 auto;
}

/* Header */
header {
    background: white;
    border-bottom: 1px solid var(--border);
    position: sticky;
    top: 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0;
}

.logo {
    font-size: 1.25rem;
    font-weight: 700;
}

.nav-links {
    display: flex;
    gap: 1.5rem;
}

.nav-links a {
    text-decoration: none;
    color: var(--muted);
}

.nav-links a:hover {
    color: var(--primary);
}

/* Hero */
.hero {
    padding: 3rem 0;
    text-align: center;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 0rem;
}

.hero p {
    max-width: 700px;
    margin: 0 auto 1rem;
    color: var(--muted);
}

.hero-buttons {
    display: flex;
    justify-content: center;
    gap: 1rem;
}

.btn {
    padding: 0.8rem 1.4rem;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
}

.btn-primary {
    background: var(--primary);
    color: white;
}

.btn-secondary {
    border: 1px solid var(--border);
    color: var(--text);
    background: white;
}


.mini-person {
  min-height: 220px;
  padding: 24px 14px 18px;
  text-align: center;
}

.mini-photo {
  display: block;
  width: 84px;
  height: 84px;
  margin: 0 auto 16px;
  border-radius: 999px;
  background: #d9dce5;
  background-size: cover;
  background-position: center;
}

/* Sections */
.section {
    padding: 2rem 0;
}

.section h2 {
    margin-bottom: 1rem;
}

.placeholder {
    background: white;
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 2rem;
    color: var(--muted);
}

.section h2 {
  margin-top: 0.8rem;
}

/* Cards */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
}

.card {
    background: white;
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 1.5rem;
}

/* Footer */
footer {
    margin-top: 4rem;
    padding: 2rem 0;
    border-top: 1px solid var(--border);
    text-align: center;
    color: var(--muted);
}
</style>
</head>

<body>

<header>
    <div class="container navbar">
        <div class="logo">CoIN Challenge 2026</div>

        <nav class="nav-links">
            <a href="#overview">Overview</a>
            <a href="#dates">Dates</a>
            <a href="#leaderboard">Leaderboard</a>
            <a href="#submission">Submission</a>
            <a href="#organizers">Organizers</a>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="container">
        <h1>CoIN Challenge 2026</h1>
        <p>
            Collaborative Instance-object Navigation (CoIN) challenge at Embodied Agent and Dialog Workshop @ ECCV 2026.
        </p>

        <div class="hero-buttons">
            <a href="#" class="btn btn-primary">Submit</a>
            <a href="https://arxiv.org/abs/2604.00265" class="btn btn-secondary">Paper</a>
            <a href="#" class="btn btn-secondary">Code</a>
        </div>
    </div>
</section>
<div class="container">
    <img src="assets/teaser.png" style="width: 70%; display: block; margin: 0 auto;" alt="Teaser Image">
</div>
<section id="overview" class="section">
    <div class="container">
        <h1>Overview</h1>
        <div class="aaa">
            Collaborative Instance-object Navigation (CoIN) requires an agent to navigate to a target object instance specified by natural language, <strong>collaborating, along the way, with a human user</strong>, in cluttered environments with many similar objects (distractors).
            On of the most important capabilities of such agents is the ability to ask the user for clarifying questions when facing uncertain detections or ambiguous instructions. Therefore, this challenge will <strong>test the agents' ability to ask questions to disambiguate similar objects during navigation.</strong> 
        </div>
        <h2>Challenge</h2>
        In this challenge, participants will be asked to <strong>train multimodal agents</strong> that, given a object description in natural language and a image of an object, can either
<p>1) determine whether the object shown in the image matches the given object description, or not (when sufficient information is available) </p>
<p>2) ask a clarifying question to the user when the description and the image are ambiguous</p>
<strong>The goal of the agents is to correctly identify the image that matches the object description, while asking as few questions as possible to the user.</strong> 
<h2> Evaluation </h2>
Each multimodal agent will be evaluated on N episodes, on a varied set of object descriptions and images. Each episode contains a variable number of images presented to the agent sequentially. 
The agents will be evaluated on a combination of accuracy and number of questions asked, with a strong emphasis on accuracy.
    </div>
</section>


<section id="dates" class="section">
    <div class="container">
        <h2>Dates</h2>
        <strong>Challenge start date:</strong> June 15th 2026
        <p><strong>Challenge end date:</strong> August 15th 2026</p>
        
    </div>
</section>


<section id="leaderboard" class="section">
    <div class="container">
        <h2>Leaderboard</h2>

        <div class="grid">
            <div class="card">
                <h3>🥇 1st Place</h3>
                <p>TBD</p>
            </div>

            <div class="card">
                <h3>🥈 2nd Place</h3>
                <p>TBD</p>
            </div>

            <div class="card">
                <h3>🥉 3rd Place</h3>
                <p>TBD</p>
            </div>
        </div>
    </div>
</section>

<section id="submission" class="section">
    <div class="container">
        <h2>Submission</h2>
            The participants will have access to <strong>the codebase and a training set of episodes</strong> to use to train and tune their agents. 
            The participants will be asked to submit their trained agents (weights uploaded to huggingface) before the deadline, alongside a technical report and the original code. 
            These agents will be evaluated on a held-out test set of episodes that will be released after the deadline. 
        
    </div>
</section>

<section id="organizers" class="section">
    <div class="container">
        <h2>Organizers</h2>

        <div class="grid">
            <article class="mini-person"><a class="mini-photo" href="" target="_blank" rel="noopener" style="background-image:url('assets/edoardozorzi.jpg')"></a><h3><a href="" target="_blank" rel="noopener">Edoardo Zorzi</a></h3><p>Sapienza University of Rome, Italy</p><span>Ph.D Student.</span></article>
            <article class="mini-person"><a class="mini-photo" href="https://www.yimingwang.me/" target="_blank" rel="noopener" style="background-image:url('assets/yimingwang.jpeg')"></a><h3><a href="" target="_blank" rel="noopener">Yiming Wang</a></h3><p>Fondazione Bruno Kessler, Trento, Italy</p><span>Senior Researcher.</span></article>
        </div>
    </div>
</section>

<section id="citation" class="section">
    <div class="container">
      <h2>Citation</h2>
      <p>
        If you use the provided materials, please cite the relevant paper below.
      </p>
      <div class="split-grid">
        <div class="card">
          <h3 id="citation-rain">CoIN</h3>
          <pre><code>@InProceedings{taioli2025coin,
          author    = {Taioli, Francesco and Zorzi, Edoardo and Franchi, Gianni and Castellini, Alberto and Farinelli, 
            Alessandro and Cristani, Marco and Wang, Yiming},
          title     = {Collaborative Instance Object Navigation: Leveraging Uncertainty-Awareness to Minimize Human-Agent Dialogues},
          booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
          month     = {October},
          year      = {2025},
          pages     = {18781-18792}
      }</code></pre>
        </div>
        <div class="card">
          <h3 id="citation-rain">Question asking for CoIN</h3>
          <pre><code>@InProceedings{zorzi2026coinqa,
          author    = {Zorzi, Edoardo and Taioli, Francesco and Wang, Yiming and Cristani, Marco and Farinelli, 
            Alessandro and Castellini, Alberto and Bazzani, Loris},
          title     = {Benchmarking Interaction, Beyond Policy: a Reproducible Benchmark for Collaborative Instance Object Navigation},
          booktitle = {https://arxiv.org/pdf/2604.00265},
          month     = {March},
          year      = {2026},
      }</code></pre>
        </div>
      </div>
      </div>
    </section>


<footer>
    <div class="container">
        CoIN Challenge 2026 - ECCV 2026 Workshop on Embodied Agents and Dialog. All rights reserved.
    </div>
</footer>

</body>
</html>
