<html>
<body>
<h1>ARBC</h1>
<h2>Modules</h2>
<h3>API</h3>
<p>This module is responsible for handle the incoming requests and manage the image processing operations.</p>
<h4>Endpoints</h4>
<ul>
<li><em>GET /books</em><br>list all stored books</li>
<li><em>GET /books/:id</em><br>show an entry by id</li>
<li><em>POST /books</em><br>store new book<br>fields: cover::file, title::text, author::text, publisher::text, keywords::text (separated by spaces)</li>
<li><em>POST /books/recognize</em><br>recognize a book cover<br>fields: picture::file</li>
</ul>
<h3>Image Processing</h3>
<p>This module manage the most of the computation related tasks, including warping a book cover, calculating Lab color space cluster vectors, calculating the feature vectors and classification. This module also applies OCR in order to gain keywords from each processable book covers.</p>
<h4>Processes</h4>
<ul>
<li></li>
</ul>
<h2>Dependecies</h2>
<ul>
<li>OpenCV 2.4.9</li>
<li>Leptonica 1.7</li>
<li>Tesseract 3.0.2</li>
<li>NPM 1.4.3</li>
<li>Node 0.10.26</li>
</ul>
<h2>Installation</h2>
<p>To do: create build script.</p>
<h2>License</h2>
<p>MIT</p>
</body>
</html>
