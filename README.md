<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1" name="viewport" />
  <title>Profile Nofal</title>
  <style>
    body {
      background-color: #6f7ea7;
      padding: 1.5rem;
      font-family: Arial, sans-serif;
      margin: 0;
    }
    .container {
      max-width: 1120px;
      margin: 0 auto;
    }
    .top-section {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      align-items: flex-start;
    }
    .photo-column {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 0.5rem;
      min-width: 150px;
    }
    .photo-column img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 0.125rem;
      display: block;
    }
    .photo-column p {
      font-size: 20px;
      line-height: 1.4;
      color: black;
      text-align: center;
      margin: 0;
    }
    .intro-text {
      max-width: 600px;
      font-size: 20px;
      line-height: 1.4;
      color: black;
    }
    .intro-text p {
      margin-top: 0;
      margin-bottom: 1.5rem;
    }
    .intro-text p:first-child {
      margin-top: 0;
    }
    .bottom-section {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      margin-top: 4rem;
      max-width: 1120px;
    }
    .reason-box, .hobby-box {
      background-color: #4a417a;
      border-radius: 1.875rem;
      padding: 1.5rem;
      flex: 1 1 280px;
      font-size: 18px;
      line-height: 1.4;
      color: black;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .hobby-box h3 {
      font-weight: 700;
      margin-bottom: 0.75rem;
      text-align: center;
    }
    .hobby-box ul {
      margin: 0;
      padding-left: 1.25rem;
      list-style-type: disc;
    }
    .skill-box {
      border: 2px solid white;
      width: 140px;
      display: flex;
      flex-direction: column;
      text-align: center;
      color: white;
      font-size: 18px;
      font-weight: 600;
      border-radius: 0;
    }
    .skill-box > div {
      padding: 0.75rem 0;
      border-bottom: 2px solid white;
      background-color: #7f8dbd;
    }
    .skill-box > div:first-child {
      font-weight: 700;
      background-color: transparent;
      border-bottom: 2px solid white;
      color: white;
    }
    .skill-box > div:last-child {
      border-bottom: none;
    }
    @media (max-width: 768px) {
      .top-section {
        flex-direction: column;
        align-items: center;
      }
      .intro-text {
        max-width: 100%;
      }
      .bottom-section {
        flex-direction: column;
        align-items: center;
      }
      .reason-box, .hobby-box, .skill-box {
        width: 100%;
        max-width: 400px;
      }
      .skill-box {
        width: 100%;
        max-width: 400px;
        flex-direction: row;
        flex-wrap: wrap;
      }
      .skill-box > div {
        flex: 1 1 33.33%;
        border-bottom: none;
        border-right: 2px solid white;
        padding: 0.75rem 0;
      }
      .skill-box > div:last-child {
        border-right: none;
      }
      .skill-box > div:first-child {
        flex-basis: 100%;
        border-right: none;
        border-bottom: 2px solid white;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="top-section">
      <div class="photo-column">
        <img alt="Portrait of a young man wearing a white shirt and beige jacket standing in front of a building with a banner that says RERANI BESAR" src="payy.jpg".jpg" width="150" height="150" />
        <p>Hi, Nofal</p>
      </div>
      <div class="intro-text">
        <p>Halo, Nama saya M Nofa Syahwaludin.</p>
        <p>Saya seorang Mahasiswa di Universitas Djuanda Bogor dari Fakultas Ilmu Komputer Tahun angkatan 2024.</p>
      </div>
    </div>
    <div class="bottom-section">
      <div class="reason-box">
        Alasan saya mengambil Prodi Ilkom, saya melihat teknologi semakin hari makin berkembang karena itu saya ingin mempelajari dan mendalami tentang teknologi sekrang dan seterus nya.
      </div>
      <div class="hobby-box">
        <h3>Hobi</h3>
        <ul>
          <li>Bermain game</li>
          <li>Bermain Biliard</li>
          <li>Badminton</li>
        </ul>
      </div>
      <div class="skill-box">
        <div>SKIL</div>
        <div>PHP</div>
        <div>C ++</div>
        <div>HTML</div>
      </div>
    </div>
  </div>
</body>
</html>
