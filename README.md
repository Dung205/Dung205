-
<html lang="vi"
    __fvdsurfcanyoninserted="1"
    class="
        clickberry-extension
        clickberry-extension-standalone
        clickberry-extension
        clickberry-extension-standalone
        clickberry-extension
        clickberry-extension-standalone
    "
>
    <head>
        <meta charset="UTF-8" />
        <link rel="shortcut icon" type="image/png" href="./birthdayCake.png"/>
        <title>Happy Birthday</title>
        <link rel="stylesheet" href="./style.css">
        <script>
            window.open = function () {};
            window.print = function () {};
            // Support hover state for mobile.
            if (false) {
                window.ontouchstart = function () {};
            }
        </script>
        <script
            type="text/javascript"
            src="chrome-extension://bfbmjmiodbnnpllbbbfblcplfjjepjdn/js/injected.js"
        ></script>
        <meta content="clickberry-extension-here" />
    </head>

    <body>
        <link
            href="https://fonts.googleapis.com/css?family=Wendy+One"
            rel="stylesheet"
            type="text/css"
        />
        <div class="pyro">
            <div class="before">

            </div>
            <div class="after">

            </div>
            <div class="container">
                <!-- 2. Dòng chữ Happy Birthday
                Nếu bạn muốn thêm chữ vào thì phải thay đổi css tương ứng cho nó -->
                <div class="balloon">
                    <div><span>H</span></div>
                    <div><span>A</span></div>
                    <div><span>P</span></div>
                    <div><span>P</span></div>
                    <div><span>Y</span></div>
                    <div><span>B</span></div>
                    <div><span>I</span></div>
                    <div><span>R</span></div>
                    <div><span>T</span></div>
                    <div><span>H</span></div>
                    <div><span>D</span></div>
                    <div><span>A</span></div>
                    <div><span>Y</span></div>
                </div>
                <div class="avatar">
                    <!-- 3. Avatar của người bạn muốn gởi lời chúc -->
                    <img src="./MyAvatar.jpg" alt="" class="avatar__img" onclick="showMessage()" />
                    <!-- 4. Tên của người đó -->
                    <h1 onclick="showMessage()" class="avatar__title">Ngọc Tiến</h1>
                </div>

                <!-- 5. Phần nhạc -->
                <!-- <audio id="player" autoplay loop>
                    <source src="./music.mp3" type="audio/mp3">
                </audio> -->
            </div>
        </div>
        <script>
            if (document.location.search.match(/type=embed/gi)) {
                window.parent.postMessage("resize", "*");
            }
            function showMessage() {
                // 6. Lời nhắn hiện ra khi bấm vào tên hoặc avatar
                swal({
                    title: "Lời nhắn", // Tiêu đề của popup
                    text: "Gửi đến tôi, chàng trai năm 20 tuổi, hãy biết cố gắng thật nhiều để sau này không hối hận, hãy biết yêu thương bản thân để luôn có sức khỏe khỏe mạnh, hãy biết hiếu thuận gia đình để bố mẹ không bao giờ buồn, và cũng hãy đi tìm nàng công chúa của mình đi nào.", // Nội dung lời nhắn
                    button: {
                        text: "❤️️",
                    },
                });
            }
        </script>
        <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
    </body>
</html>
