<10520133 林家麒>
<html lang="en">
 <head>

 <!-- Required meta tags -->
 <meta charset="utf-8">
 <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
 <!-- Bootstrap CSS -->
 <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
 <title>10520133 林家麒</title>
 </head>
 <body>
 <h1>學習心得</h1>
 <!-- Optional JavaScript -->
 <!-- jQuery first, then Popper.js, then Bootstrap JS -->
 在這堂課當中我學習到了許多有關<font color="#FF0000">網頁設計的知識以及常識</font>。<p><P>
 當然這堂課並不是只有表面上的學習網頁設計這麼簡單，這堂課有趣的地方就是結合了<font color="#FF0000">服務學習</font>。<p>
 平常其他的課程完全沒辦法讓我們體驗到這種<font color="#FF0000">這麼不一樣的感受</font>，有趣又有學到東西。<P>
 網頁應用<font color="blue">這堂課的設計以及與社福團體溝通</font>令我感受到這堂課真的是十分值得選修的課程，<font color="#FF0000">老師的用心以及能照顧且幫助到社福團體的小朋友們</font>，都是選這堂課的好理由，我希望電機系的課程都能朝這方面邁進。<P>
 遠距教學的部分也是沒話說，老師準備的十分充足，而且<font color="#FF0000">這堂課十分適合遠距</font>，<span style="border:3px blue dashed;">可以在家跟著老師一步一步的做，不用在學校聽完課才能回家弄</span>(因為只有兩台電腦沒辦法同時完成兩個人)。
 <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
 <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
 <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
</body>
</html>
Konva Ellipse Demoview raw
<!DOCTYPE html>
<html>
  <head>
    <script src="https://unpkg.com/konva@5.0.3/konva.min.js"></script>
    <meta charset="utf-8" />
    <title>Konva Ellipse Demo</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #f0f0f0;
      }
    </style>
  </head>
  <body>
    <div id="container"></div>
    <script>
      var width = window.innerWidth;
      var height = window.innerHeight;

      var stage = new Konva.Stage({
        container: 'container',
        width: width,
        height: height
      });

      var layer = new Konva.Layer();

      var oval = new Konva.Ellipse({
        x: stage.width() / 2,
        y: stage.height() / 2,
        radiusX: 100,
        radiusY: 50,
        fill: 'yellow',
        stroke: 'black',
        strokeWidth: 4
      });

      // add the shape to the layer
      layer.add(oval);

      // add the layer to the stage
      stage.add(layer);
    </script>
  </body>
</html>




