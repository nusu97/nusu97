<!DOCTYPE html> 
<html lang="en">
   <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Art Gallery</title>
      <link rel="stylesheet" href="style.css" />
      <style> /* Base Reset */ * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; } body { font-family: 'Roboto', sans-serif; background: linear-gradient(to bottom right, #f8f9fa, #e9ecef); color: #495057; line-height: 1.6; } header { background: linear-gradient(to right, #5e60ce, #6930c3); color: #ffffff; text-align: center; padding: 1.5rem; border-bottom: 4px solid #3a0ca3; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); } header h1 { font-size: 2.5rem; letter-spacing: 2px; text-transform: uppercase; font-weight: 700; font-family: 'Georgia', serif; } main { padding: 3rem; max-width: 1200px; margin: auto; } .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; } .photo-card { background: #ffffff; border-radius: 12px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15); overflow: hidden; text-align: center; transition: transform 0.3s, box-shadow 0.3s; } .photo-card:hover { transform: scale(1.05); box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2); } .photo-card h2 { font-size: 1.5rem; color: #343a40; padding: 1rem 0; border-bottom: 2px solid #e9ecef; } .photo-card img { max-width: 100%; height: 200px; object-fit: cover; } .photo-card .descriiption { font-size: 1rem; line-height: 1.5; padding: 1rem; color: #495057; } .photo-card .descriiption:first-letter { font-size: 1.2rem; font-weight: bold; } .photo-card .date { background: #6930c3; color: #ffffff; padding: 0.5rem 1rem; font-weight: 600; margin-top: auto; text-transform: uppercase; } footer { text-align: center; padding: 1rem; margin-top: 2rem; background: #343a40; color: #f8f9fa; font-size: 0.9rem; } footer a { color: #5e60ce; text-decoration: none; font-weight: 600; } footer a:hover { text-decoration: underline; } </style>
   </head>
   <body>
      <header>
         <h1>Rumi Poetry</h1>
      </header>
      <main>
         <section class="gallery">
            <article class="photo-card">
               <h2>Whirling Ecstasy</h2>
               <img src="ECSTASY.jpg" alt="image" /> 
               <p class="descriiption"> This vibrant painting depicts the mystical dance of the whirling dervishes, inspired by Rumi's poetry on ecstatic spiritual journeys. </p>
               <p class="date">1244</p>
            </article>
            <article class="photo-card">
               <h2>The Beloved's Gaze</h2>
               <img src="BELOVEDGAZE.jpg" alt="image" /> 
               <p class="descriiption"> A captivating portrait capturing the essence of Rumi's longing and devotion, with intricate details that convey the intensity of the lover's gaze. </p>
               <p class="date">1256</p>
            </article>
            <article class="photo-card">
               <h2>Soul's Journey</h2>
               <img src="soul.jpg" alt="image" /> 
               <p class="descriiption"> A thought-provoking mixed media artwork illustrating Rumi's metaphorical exploration of the soul's journey through life and the realms beyond. </p>
               <p class="date">1245</p>
            </article>
            <article class="photo-card">
               <h2>Union of Love</h2>
               <img src="unionoflove.jpg" alt="image" /> 
               <p class="descriiption"> A serene sculpture representing the union of divine love, inspired by Rumi's philosophy of transcending boundaries and merging with the beloved. </p>
               <p class="date">1246</p>
            </article>
            <article class="photo-card">
               <h2>Divine Melodies</h2>
               <img src="devinemelody.jpg" alt="image" /> 
               <p class="descriiption"> An enchanting musical composition inspired by Rumi's poetry, with visual elements that evoke the ethereal beauty and power of his words. </p>
               <p class="date">1250</p>
            </article>
            <article class="photo-card">
               <h2>Mystical Garden</h2>
               <img src="mystical.jpeg" alt="image" /> 
               <p class="descriiption"> A captivating photograph capturing the essence of Rumi's imagery of a mystical garden, with vibrant colors and delicate flowers symbolizing spiritual growth and [...] </p>
               <p class="date">1247</p>
            </article>
         </section>
      </main>
      <footer> Created with ❤️ by <a href="https://github.com/nusu97" target="_blank">Nuseyba Mohammed</a>. </footer>
   </body>
</html>