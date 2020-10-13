# Code Ed-Hackathon
Build an OCR-based engine that scans, convert image text into downloadable text using machine learning tech.
![Index](/ssindex.jpg)

## Tech Used
<ul>
  <li>Python</li>
  <li>Djnago framework</li>
  <li>Python-tesseract (optical character recognition tool)</li>
</ul>

## How to install
<ul>
  <li>First, let’s download and install tesseract through this <a href="http://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-setup-4.00.00dev.exe">link</a>.</li>
  <li>Update the tesseract installed path in the application.
    <ul>
      <li>open "project" directory.<br> <img src="img/directory.jpg"></li>
      <li>After that, you will find a file named "view.py".<br> <img src="img/projectfolderdirectory.jpg"></li>
      <li>Open it and on line 32 update the path where your tesseract is updated on the local PC<br><img src="img/pathupdate.jpg"></li>
      <li>Now you are good to go</li>
    </ul>
</ul>

## How to use
<ul>
  <li>Extract "CodeEd-Hackathon" zip file.</li>
  <li>Open command prompt in CodeEd-Hackathon folder</li>
  <li>To run the code, write following command in terminal.</li>
    <ul>
      <li>python manage.py runserver</li>
  </ul>
  <li>Type http://127.0.0.1:8000/ in URL bar of browser and press Enter. Machine Learning powered Web Application will start.</li>
  <li>Now you can upload text image or paste snippet on the web application to change it on text format.</li>
  <li>Even you can also download all your previously changed text using the download button web application</li>
</ul>
  
