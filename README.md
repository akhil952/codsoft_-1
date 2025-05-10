# codsoft_-1
This is a repository for codsoft level 2 task(1).

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Elon Musk Tribute</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(circle at center, #0d1b2a, #000);
      overflow-x: hidden;
      color: #ffffff;
      position: relative;
    }

    /* Star animation */
    body::before {
      content: '';
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('https://media.giphy.com/media/l3vR85PnGsBwu1PFK/giphy.gif') repeat;
      opacity: 0.15;
      z-index: 0;
      animation: moveStars 60s linear infinite;
    }

    @keyframes moveStars {
      from { background-position: 0 0; }
      to { background-position: 1000px 1000px; }
    }

    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 60px;
      z-index: 1;
      position: relative;
    }

    h1 {
      font-size: 3em;
      color: #00ffe0;
      text-shadow: 2px 2px 8px #00f2ff;
      z-index: 1;
      position: relative;
    }

    .image-container img {
      width: 550px;
      border-radius: 15px;
      margin: 20px 0;
      border: 2px solid #00ffe0;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.5);
      z-index: 1;
      position: relative;
    }

    .content {
      max-width: 800px;
      margin: 30px auto;
      padding: 30px;
      font-size: 1.1em;
      background-color: rgba(0, 0, 0, 0.6);
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(0,255,255,0.2);
      z-index: 1;
      position: relative;
    }

    p {
      line-height: 1.8;
      margin-bottom: 20px;
      color: #d0f0ff;
    }

    h2 {
      color: #00ffe0;
      margin-top: 40px;
    }

    ul {
      text-align: left;
      margin: 20px auto;
      max-width: 700px;
      padding: 0 20px;
      color: #ffffffdd;
    }

    li {
      margin-bottom: 15px;
      line-height: 1.5;
    }

    li strong {
      font-weight: 500;
      color: #00ffe0;
    }
  </style>
</head>
<body>
  <div class="hero">
    <h1>Elon Musk</h1>
    <div class="image-container">
      <img src="https://www.bankrate.com/brp/2025/02/06145605/elon-musk-2025-worlds-richest-person.jpg" alt="Elon Musk" />
    </div>
  </div>

  <div class="content">
    <p><strong>Elon Musk</strong> is one of the most innovative and daring entrepreneurs of the modern era. His vision spans from electric cars with Tesla to space exploration with SpaceX.</p>

    <p>He is admired for his relentless pursuit of ambitious goals and his ability to challenge the status quo. Whether it's revolutionizing transportation, tackling climate change, or dreaming of Mars colonization, Musk turns bold ideas into reality.</p>

    <p>Beyond technology, he inspires millions with his resilience, risk-taking, and belief in creating a better future for humanity. His journey reminds us to think big, act boldly, and never give up.</p>

    <h2>🚀 Major Achievements</h2>
    <ul>
      <li><strong>Founded SpaceX (2002):</strong> First private company to send astronauts to the ISS.</li>
      <li><strong>CEO of Tesla (since 2008):</strong> Popularized electric vehicles globally.</li>
      <li><strong>Co-founded PayPal:</strong> Transformed online payments, sold to eBay for $1.5 billion.</li>
      <li><strong>Founded Neuralink:</strong> Developing brain-machine interface technology.</li>
      <li><strong>Launched Starlink:</strong> Global satellite internet service for remote areas.</li>
      <li><strong>Co-founded OpenAI:</strong> Pushed forward safe AI development.</li>
      <li><strong>Founded The Boring Company:</strong> Innovating underground transportation.</li>
      <li><strong>Promotes renewable energy:</strong> Through Tesla’s solar and storage solutions.</li>
      <li><strong>Developed reusable rockets:</strong> Reduced space mission costs dramatically.</li>
    </ul>
  </div>
</body>
</html>

