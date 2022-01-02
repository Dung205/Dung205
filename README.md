@import url(https://fonts.googleapis.com/css?family=Montserrat:400,700);

body {
  cursor: none;
  margin: 0;
  padding: 0;
  height: 100vh;
  overflow: hidden;
  font-family: 'Montserrat', sans-serif;
}

.container {
  display: grid;
  place-items: center;
  background: #1aabe3;
  width: 100%;
  height: 100vh;
  overflow-y: hidden;
}

.container * {
  z-index: 1;
}

.counter {
  display: grid;
  place-items: center;
  width: 50%;
  height: 50%;
}

.digit {
  text-align: center;
  text-shadow: 18px 20px 0px rgba(49, 78, 99, 0.57);
  font-size: 18em;
  color: rgba(255, 255, 255, 0.97);
  -webkit-text-stroke-color: #1679bf;
  -webkit-text-stroke-width: thin;
  font-weight: bolder;
