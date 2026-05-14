<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>S2278492-TMA01</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f7fb;
      margin: 40px;
      line-height: 1.6;
    }
    h1 {
      color: #234f8e;
      text-align: center;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .author {
      text-align: center;
      font-style: italic;
      margin-bottom: 30px;
    }
    .content {
      max-width: 800px;
      margin: 0 auto;
      background-color: #ffffff;
      padding: 20px 30px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .content p {
      text-align: justify;
    }
    .highlight {
      color: #c0392b;
      font-weight: bold;
    }
    img {
      display: block;
      max-width: 100%;
      height: auto;
      margin: 20px auto;
      border: 3px solid #234f8e;
      border-radius: 6px;
    }
    .caption {
      font-size: 0.9em;
      text-align: center;
      color: #555555;
      margin-top: 5px;
    }
    .footer {
      margin-top: 25px;
      font-size: 0.9em;
      color: #555555;
    }
    a {
      color: #234f8e;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h1>Representing Sound in Digital Form</h1>
  <div class="author">Simonas Matuzevicius (S2278492)</div>

  <div class="content">
    <p>
      <!-- Around 150 words, in your own words -->
      An analogue sound is a continuous wave, but a computer can only store
      <span class="highlight">discrete</span> values. To convert sound into digital form,
      the analogue signal is first sampled: its amplitude is measured at regular time
      intervals, known as the <span class="highlight">sampling rate</span>. A higher sampling
      rate captures more detail from the original wave.
    </p>
    <p>
      Each sample is then <span class="highlight">quantised</span>, which means its amplitude
      is rounded to the nearest value from a fixed set of levels. The number of bits used
      per sample (the <span class="highlight">bit depth</span>) determines how many levels
      are available and how accurately the amplitude can be represented. Finally, these
      quantised values are stored as a sequence of binary numbers. Together, sampling and
      quantisation allow a continuous analogue sound to be represented and processed as
      digital data.
    </p>

    <img src="images/soundwave.png" alt="Diagram showing analogue sound being sampled and quantised">
    <div class="caption">
      Figure: Example of an analogue waveform being sampled and converted into digital values.
    </div>

    <div class="footer">
      <p><strong>Image acknowledgement:</strong> Describe source here, e.g. “Image © Author’s own photo” or full credit for Media PNGEGG/ copyright-free web source.</p>
      <p><strong>Link to my Open Sites page:</strong>https://tm111.open.ac.uk/opensites/users/sm49742/S2278492-TMA01.htm <a href="">https://tm111.open.ac.uk/opensites/users/sm49742/S2278492-TMA01.htm</a></p>
    </div>
  </div>

</body>
</html>
