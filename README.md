- 👋 Hi, I’m Dharmateja
- 👀 I’m interested to learn coding
- 🌱 I’m currently learning coding
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me kokurudharma@gmail.com

<!---
Dharma28/Dharma28 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
var xhr = new XMLHttpRequest();
xhr.open("GET", "https://api.example.com/data", true);
xhr.onreadystatechange = function() {
  if (xhr.readyState === 4 && xhr.status === 200) {
    var response = JSON.parse(xhr.responseText);
    console.log(response);
  }
};
xhr.send();
