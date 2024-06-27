# Directory structure of data set folder
<html>
<head>
    <title>Directory Structure</title>
    <style>
        ul {
            list-style-type: none;
        }
        .folder::before {
            content: "📂";
            margin-right: 5px;
        }
        .file::before {
            content: "📄";
            margin-right: 5px;
        }
    </style>
</head>
<body>
    <h1>Directory Structure</h1>
    <ul>
        <li class="folder">chest_xray
            <ul>
                <li class="folder">test
                    <ul>
                        <li class="folder">NORMAL</li>
                        <li class="folder">PNEUMONIA</li>
                    </ul>
                </li>
                <li class="folder">train
                    <ul>
                        <li class="folder">NORMAL</li>
                        <li class="folder">PNEUMONIA</li>
                    </ul>
                </li>
            </ul>
        </li>
    </ul>
</body>
</html>

