<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Large-Scale Datasets</title>
<style>
  html {
    scroll-behavior: smooth;
  }
  body {
    font-family: Arial, sans-serif;
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
    line-height: 1.6;
    color: #333;
  }
  h1, h2, h3 {
    margin-top: 2rem;
  }
  a {
    color: #0366d6;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  hr {
    margin: 2rem 0;
  }
  table {
    border-collapse: collapse;
    width: 100%;
    margin: 1rem 0;
  }
  th, td {
    border: 1px solid #ddd;
    padding: 0.5rem;
  }
  th {
    background-color: #f6f8fa;
    text-align: left;
  }
  ul {
    padding-left: 1.2rem;
  }
</style>
</head>
<body>

<h1>🛰️ Large-Scale Datasets</h1>

<p>This repository provides a curated collection of <strong>large-scale datasets</strong> focused on <strong>remote sensing</strong>, <strong>semantic segmentation</strong>, and <strong>object detection</strong> from aerial and satellite imagery. It's designed to help researchers, engineers, and enthusiasts quickly find and explore the most relevant datasets for Earth observation tasks.</p>

<hr />

<h2>📌 Table of Contents</h2>
<ul>
  <li><a href="#dota">DOTA</a></li>
  <li><a href="#loveDA">LoveDA</a></li>
  <li><a href="#fair">FAIR1M</a></li>
  <li><a href="#aid">AID</a></li>
  <li><a href="#comparison-table">Comparison Table</a></li>
  <li><a href="#coming-soon">Coming Soon</a></li>
</ul>

<hr />

<h2 id="why-this-repo">❓ Why This Repo?</h2>
<p>Working with large-scale satellite or aerial imagery data can be overwhelming. This repo:</p>
<ul>
  <li>Collects the most impactful and widely used datasets.</li>
  <li>Lists key details like tasks, classes, size, and links.</li>
  <li>Aims to save time for people starting new projects or doing research.</li>
</ul>

<hr />

<h2>🌍 Featured Datasets</h2>

<h3 id="dota">1. DOTA (Dataset for Object Detection in Aerial Images)</h3>
<ul>
  <li><strong>Task</strong>: Object Detection</li>
  <li><strong>Images</strong>: ~2,800 high-resolution aerial images</li>
  <li><strong>Annotations</strong>: ~188,000 object instances</li>
  <li><strong>Image Resolution</strong>: Ranges from 800×800 to 4000×4000 pixels</li>
  <li><strong>Classes</strong>: 15 (e.g., plane, ship, storage tank, vehicle, etc.)</li>
  <li><strong>Annotation Format</strong>: Oriented bounding boxes</li>
  <li><strong>Split</strong>: Train / Val / Test</li>
  <li><strong>Published By</strong>: Wuhan University</li>
  <li><strong>Website</strong>: <a href="https://captain-whu.github.io/DOTA/dataset.html" target="_blank" rel="noopener noreferrer">https://captain-whu.github.io/DOTA/dataset.html</a></li>
  <li><strong>Paper</strong>: <a href="https://arxiv.org/abs/1711.10398" target="_blank" rel="noopener noreferrer">Link to Paper</a></li>
</ul>

<hr />

<h3 id="loveDA">2. LoveDA (Land-cover Classification in Very High Resolution)</h3>
<ul>
  <li><strong>Task</strong>: Semantic Segmentation</li>
  <li><strong>Images</strong>: 5987 image patches (512x512 px)</li>
  <li><strong>Scenes</strong>: Urban and Rural</li>
  <li><strong>Classes</strong>: 7 (Background, Building, Road, Water, Barren, Forest, Agricultural)</li>
  <li><strong>Split</strong>: Train (2522) / Val (1669) / Test (1796)</li>
  <li><strong>Unique Point</strong>: Designed to evaluate model generalization between urban and rural environments</li>
  <li><strong>Published By</strong>: Nanjing University</li>
  <li><strong>Website</strong>: <a href="https://github.com/Junjue-Wang/LoveDA" target="_blank" rel="noopener noreferrer">https://github.com/Junjue-Wang/LoveDA</a></li>
  <li><strong>Paper</strong>: <a href="https://arxiv.org/abs/2108.08874" target="_blank" rel="noopener noreferrer">https://arxiv.org/abs/2108.08874</a></li>
</ul>

<hr />

<h3 id="fair">3. FAIR1M (Fine-Grained Object Recognition in Aerial Images)</h3>
<ul>
  <li><strong>Task</strong>: Fine-Grained Object Detection</li>
  <li><strong>Images</strong>: 15,000+ high-resolution aerial images</li>
  <li><strong>Annotations</strong>: 1 million+ object instances</li>
  <li><strong>Classes</strong>: 37 fine-grained categories (e.g., different airplane models, types of ships, etc.)</li>
  <li><strong>Annotation Format</strong>: Oriented bounding boxes</li>
  <li><strong>Published By</strong>: Chinese Academy of Sciences (AIR)</li>
  <li><strong>Website</strong>: <a href="https://www.aircas.ac.cn/databases/FAIR1M/" target="_blank" rel="noopener noreferrer">https://www.aircas.ac.cn/databases/FAIR1M/</a></li>
  <li><strong>Paper</strong>: <a href="https://arxiv.org/abs/2103.05569" target="_blank" rel="noopener noreferrer">https://arxiv.org/abs/2103.05569</a></li>
</ul>

<hr />

<h3 id="aid">4. AID (Aerial Image Dataset)</h3>
<ul>
  <li><strong>Task</strong>: Scene Classification</li>
  <li><strong>Images</strong>: 10,000 RGB aerial images</li>
  <li><strong>Resolution</strong>: 600 × 600 pixels</li>
  <li><strong>Classes</strong>: 30 scene types</li>
  <li><strong>Scene Types</strong>: Urban, rural, industrial, agricultural, etc.</li>
  <li><strong>Labeling</strong>: Each image has a single scene label</li>
  <li><strong>Split</strong>: No fixed split — can be customized</li>
  <li><strong>Published By</strong>: Wuhan University</li>
  <li><strong>Website</strong>: <a href="https://captain-whu.github.io/AID/" target="_blank" rel="noopener noreferrer">AID Dataset</a></li>
  <li><strong>Paper</strong>: <a href="https://ieeexplore.ieee.org/document/7444843" target="_blank" rel="noopener noreferrer">https://ieeexplore.ieee.org/document/7444843</a></li>
</ul>

<hr />

<h2 id="comparison-table">📊 Comparison Table</h2>
<table>
  <thead>
    <tr>
      <th>Dataset</th>
      <th>Task</th>
      <th># Images</th>
      <th># Classes</th>
      <th>Size</th>
      <th>Resolution</th>
      <th>Annotations</th>
      <th>Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>DOTA</td>
      <td>Object Detection</td>
      <td>2,806</td>
      <td>15</td>
      <td>~188k objects</td>
      <td>up to 4000×4000</td>
      <td>Oriented Bounding Box</td>
      <td><a href="https://captain-whu.github.io/DOTA/dataset.html" target="_blank" rel="noopener noreferrer">🔗</a></td>
    </tr>
    <tr>
      <td>LoveDA</td>
      <td>Semantic Segmentation</td>
      <td>5,987</td>
      <td>7</td>
      <td>~1.2 GB</td>
      <td>512×512</td>
      <td>Per-pixel class map</td>
      <td><a href="https://github.com/Junjue-Wang/LoveDA" target="_blank" rel="noopener noreferrer">🔗</a></td>
    </tr>
    <tr>
      <td>FAIR1M</td>
      <td>Fine-Grained Detection</td>
      <td>15,000+</td>
      <td>37</td>
      <td>1M+ objects</td>
      <td>Very high-res</td>
      <td>Oriented Bounding Box</td>
      <td><a href="https://www.aircas.ac.cn/databases/FAIR1M/" target="_blank" rel="noopener noreferrer">🔗</a></td>
    </tr>
    <tr>
      <td>AID</td>
      <td>Scene Classification</td>
      <td>10,000</td>
      <td>30</td>
      <td>~2.2 GB</td>
      <td>600×600</td>
      <td>Single scene label</td>
      <td><a href="https://captain-whu.github.io/AID/" target="_blank" rel="noopener noreferrer">🔗</a></td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="coming-soon">🔜 Coming Soon</h2>
<p>More datasets will be added soon, including:</p>
<ul>
  <li><strong>xView</strong> – Object detection, 1 million objects</li>
  <li><strong>SpaceNet</strong> – Building & road extraction</li>
  <li><strong>DeepGlobe</strong> – Land cover, road, and building segmentation</li>
  <li><strong>BigEarthNet</strong> – Multi-label classification using Sentinel-2</li>
  <li><strong>SEN12MS</strong> – Multispectral image dataset for classification and segmentation</li>
</ul>

</body>
</html>
