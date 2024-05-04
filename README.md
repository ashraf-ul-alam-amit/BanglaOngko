<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BanglaOngko Dataset</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }

        h1 {
            text-align: center;
            margin-bottom: 20px;
        }

        p {
            margin-bottom: 10px;
        }

        .citation {
            margin-top: 40px;
            font-style: italic;
        }

        .category {
            font-weight: bold;
        }
    </style>
</head>

<body>
    <h1>Welcome to the BanglaOngko Dataset</h1>

    <p>The BanglaOngko dataset is a collection of images designed specifically for detecting and recognizing mathematical expressions written in the Bengali language. The dataset comprises 267 images that feature a diverse range of Bengali digits, operators, and parentheses. These images were captured using mobile-phone cameras and sourced from various demographics and individuals, including undergraduate students, general people of Bangladesh, and professionals.</p>

    <p>The dataset encompasses a total of 21 classes, including Bengali digits from ০ to ৯, along with operators such as equals (=), minus (-), multiplication (×), division (÷), and addition (+). Furthermore, it includes parentheses (opening "(" and closing ")"), curly braces (opening "{" and closing "}"), and square brackets (opening "[" and closing "]"). The dataset consists of a total of 7,648 objects distributed across its 21 classes, including Bengali digits, operators, and parentheses.</p>

    <p>To facilitate object detection and recognition tasks, the dataset has undergone preprocessing steps. Initially, the images were subjected to inverse binarization, converting them into black and white format. This process enhances contrast and effectively separates foreground objects from the background. Subsequently, the dataset was annotated using Roboflow for object detection utilizing the YOLOv8 algorithm.</p>

    <p>Please cite the following paper and this GitHub repository, if you use this dataset in your work: <br>
        Ashraf-Ul-Alam; Soumit Das; Sudipta Progga Islam, “BanglaOngko: A New Dataset for Accurate Bengali Mathematical Expression Detection Utilizing YOLOv8 Architecture”, doi: <span id="doi">DOI will be added soon</span></p>

    <p>The Bengali Mathematical Expression Detection dataset is highly valuable for developing algorithms to accurately detect and recognize Bengali mathematical expressions. It has numerous applications in document processing, automatic grading systems, handwriting recognition, and educational technology. Training on this dataset enables algorithms to efficiently interpret and analyze mathematical expressions, bringing automation and efficiency to tasks involving Bengali mathematics.</p>

    <div class="category">
        <p>Categories:</p>
        <ul>
            <li>Mathematics</li>
            <li>Mathematics-Number</li>
            <li>Bengali Language</li>
            <li>Annotation</li>
            <li>Handwriting Recognition</li>
            <li>Optical Character Recognition</li>
        </ul>
    </div>

    <script>
        // Replace the placeholder text with the actual DOI when it becomes available
        document.getElementById("doi").textContent = "DOI will be added soon";
    </script>

</body>

</html>
