<button class="clicked"></button>
<h3 align="left">Connect with me :</h3>
<p align="left">
  <a href="https://linkedin.com/in/mathis-sportiello" target="blank"
    ><img
      align="center"
      src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg"
      alt="mathis-sportiello"
      height="30"
      width="40"
  /></a>
  <a href="https://instagram.com/mathissportiello" target="blank"
    ><img
      align="center"
      src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg"
      alt="mathissportiello"
      height="30"
      width="40"
  /></a>
  <a href="https://discord.gg/elioboyy" target="blank"
    ><img
      align="center"
      src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg"
      alt="elioboyy"
      height="30"
      width="40"
  /></a>
</p>

<h3>Some of my GitHub stats :</h3>
<p>
  <img
    align="left"
    src="https://github-readme-stats.vercel.app/api/top-langs?username=elioboyy&show_icons=true&locale=en&layout=compact"
    alt="elioboyy"
    style="height: 30px"
  />
</p>

<p>
  <img
    align="center"
    src="https://github-readme-streak-stats.herokuapp.com/?user=elioboyy&"
    alt="elioboyy"
  />
</p>

<script>
  // Get the button element by its class name
  var btn = document.querySelector(".clicked");

  // Add a click event listener to the button
  btn.addEventListener("click", function () {
    // Get the body element
    var body = document.body;

    // Change the background color
    body.style.backgroundColor = getRandomColor();
  });

  function getRandomColor() {
    var letters = "0123456789ABCDEF";
    var color = "#";
    for (var i = 0; i < 6; i++) {
      color += letters[Math.floor(Math.random() * 16)];
    }
    return color;
  }
</script>
