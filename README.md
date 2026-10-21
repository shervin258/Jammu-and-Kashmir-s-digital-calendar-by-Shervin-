

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jammu & Kashmir Digital Calendar 2027</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #f5f0e5;
  color: #243b35;
  line-height: 1.6;
}

header {
  background: linear-gradient(135deg, #153e35, #427765);
  color: white;
  text-align: center;
  padding: 45px 15px;
}

header h1 {
  font-size: 34px;
  margin-bottom: 10px;
}

header p {
  font-size: 17px;
}

.intro {
  text-align: center;
  padding: 25px 15px;
  max-width: 900px;
  margin: auto;
}

.months {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 22px;
  padding: 20px;
  max-width: 1250px;
  margin: auto;
}

.card {
  background: white;
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 5px 15px #00000018;
  border: 1px solid #ddd5c3;
}

.card img {
  width: 100%;
  height: 210px;
  object-fit: cover;
}

.card-content {
  padding: 18px;
}

.card h2 {
  color: #27634f;
  margin-bottom: 10px;
}

.card p {
  margin: 7px 0;
  font-size: 14px;
}

.sdg {
  background: #e5f1e8;
  padding: 12px;
  margin-top: 12px;
  border-left: 4px solid #35845c;
  border-radius: 5px;
}

.calendar {
  margin-top: 15px;
  width: 100%;
  border-collapse: collapse;
  text-align: center;
  font-size: 12px;
}

.calendar th {
  background: #27634f;
  color: white;
  padding: 7px 2px;
}

.calendar td {
  border: 1px solid #e2e2e2;
  padding: 6px 2px;
}

.calendar td:first-child {
  color: #b53a36;
}

footer {
  background: #153e35;
  color: white;
  text-align: center;
  padding: 30px 15px;
  margin-top: 30px;
}

footer h2 {
  color: #f4d58d;
  margin-bottom: 10px;
}

@media print {
  body { background: white; }
  .months { display: block; }
  .card {
    break-inside: avoid;
    margin-bottom: 20px;
  }
}
</style>
</head>

<body>

<header>
  <h1>JAMMU &amp; KASHMIR</h1>
  <h2>Heaven on Earth</h2>
  <p>Digital Calendar 2027</p>
  <p>Nature • Culture • Tourism • Traditions</p>
</header>

<section class="intro">
  <h2>Welcome to the Paradise of India!</h2>
  <p>
    Explore the breathtaking landscapes, colourful festivals,
    traditional handicrafts, delicious cuisine and famous tourist
    destinations of Jammu & Kashmir throughout the year.
  </p>
  <p><strong>Our Mission:</strong> Support local livelihoods through
  responsible tourism and promote SDG 8 – Decent Work and Economic Growth.</p>
</section>

<main class="months" id="months"></main>

<footer>
  <h2>SDG 8 – Decent Work and Economic Growth</h2>
  <p>
    Tourism creates employment for local guides, artisans, farmers,
    hotel workers, drivers, chefs and shopkeepers.
  </p>
  <p>
    Let us protect nature, respect local culture and buy authentic
    Kashmiri products to support local communities.
  </p>
  <p><strong>Made for a Sustainable Future | 2027</strong></p>
</footer>

<script>
const year = 2027;

const data = [
{
month:"January", title:"Winter Wonderland",
place:"Gulmarg",
image:"https://images.unsplash.com/photo-1517299321609-52687d1bc55a?auto=format&fit=crop&w=900&q=80",
culture:"Enjoy Kashmiri winter traditions and warm woollen clothing.",
food:"Traditional Kahwa tea.",
sdg:"Winter tourism supports hotel workers, guides and winter sports instructors."
},
{
month:"February", title:"The Golden Saffron",
place:"Pampore",
image:"https://images.unsplash.com/photo-1470252649378-9c29740c9fa8?auto=format&fit=crop&w=900&q=80",
culture:"Discover the famous saffron-growing heritage of Kashmir.",
food:"Saffron-flavoured Kahwa.",
sdg:"Saffron farming provides income for farmers, traders and local businesses."
},
{
month:"March", title:"Spring Blossoms",
place:"Badamwari, Srinagar",
image:"https://images.unsplash.com/photo-1490750967868-88aa4486c946?auto=format&fit=crop&w=900&q=80",
culture:"Celebrate spring and admire beautiful almond blossoms.",
food:"Kashmiri breads and tea.",
sdg:"Spring tourism benefits gardeners, photographers and local vendors."
},
{
month:"April", title:"Tulip Paradise",
place:"Srinagar Tulip Garden",
image:"https://images.unsplash.com/photo-1499002238440-d264edd596ec?auto=format&fit=crop&w=900&q=80",
culture:"Explore colourful flowers and Kashmiri embroidery.",
food:"Kashmiri Kahwa.",
sdg:"Flower tourism creates seasonal jobs and supports nearby shops."
},
{
month:"May", title:"Valleys of Beauty",
place:"Pahalgam",
image:"https://images.unsplash.com/photo-1472396961693-142e6e269027?auto=format&fit=crop&w=900&q=80",
culture:"Discover Pashmina shawls and traditional crafts.",
food:"Kashmiri rice dishes.",
sdg:"Tourism supports local guides, transport workers and artisans."
},
{
month:"June", title:"Life on Dal Lake",
place:"Srinagar",
image:"https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=900&q=80",
culture:"Experience shikaras, houseboats and Kashmiri hospitality.",
food:"Kashmiri Kahwa and local breads.",
sdg:"Houseboats and shikara rides provide livelihoods for local families."
},
{
month:"July", title:"Meadows of Gold",
place:"Sonamarg",
image:"https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=900&q=80",
culture:"Explore mountain scenery and traditional woollen crafts.",
food:"Local rice and vegetable dishes.",
sdg:"Nature tourism creates work for guides, pony handlers and shopkeepers."
},
{
month:"August", title:"Heritage of Jammu",
place:"Bahu Fort",
image:"https://images.unsplash.com/photo-1467269204594-9661b134dd2b?auto=format&fit=crop&w=900&q=80",
culture:"Discover Dogra traditions, historic forts and local festivals.",
food:"Rajma chawal.",
sdg:"Heritage tourism supports restaurants, guides and transport services."
},
{
month:"September", title:"Art and Handicrafts",
place:"Srinagar",
image:"https://images.unsplash.com/photo-1452860606245-08befc0ff44b?auto=format&fit=crop&w=900&q=80",
culture:"Discover papier-mâché, walnut wood carving and carpet weaving.",
food:"Traditional Kashmiri bakery products.",
sdg:"Buying local handicrafts supports skilled artisans and their families."
},
{
month:"October", title:"Golden Autumn",
place:"Kashmir Valley",
image:"https://images.unsplash.com/photo-1441974231531-c6227db76b6e?auto=format&fit=crop&w=900&q=80",
culture:"Admire golden Chinar leaves and autumn traditions.",
food:"Seasonal local produce.",
sdg:"Autumn tourism benefits photographers, hotels and local markets."
},
{
month:"November", title:"Flavours of Kashmir",
place:"Kashmir",
image:"https://images.unsplash.com/photo-1547592180-85f173990554?auto=format&fit=crop&w=900&q=80",
culture:"Learn about Wazwan and traditional Kashmiri hospitality.",
food:"Rogan Josh and Kahwa.",
sdg:"Food tourism supports chefs, farmers, food producers and restaurants."
},
{
month:"December", title:"Faith and Togetherness",
place:"Vaishno Devi, Jammu",
image:"https://images.unsplash.com/photo-1519681393784-d120267933ba?auto=format&fit=crop&w=900&q=80",
culture:"Discover Dogra heritage, pilgrimage traditions and local crafts.",
food:"Jammu's traditional dishes.",
sdg:"Pilgrimage tourism supports accommodation providers, drivers and shopkeepers."
}
];

function makeCalendar(monthIndex) {
  const firstDay = new Date(year, monthIndex, 1).getDay();
  const totalDays = new Date(year, monthIndex + 1, 0).getDate();

  let html = '<table class="calendar"><thead><tr>';
  html += '<th>Sun</th><th>Mon</th><th>Tue</th><th>Wed</th>';
  html += '<th>Thu</th><th>Fri</th><th>Sat</th></tr></thead><tbody><tr>';

  for (let i = 0; i < firstDay; i++) {
    html += '<td></td>';
  }

  for (let day = 1; day <= totalDays; day++) {
    html += `<td>${day}</td>`;

    if ((firstDay + day) % 7 === 0 && day !== totalDays) {
      html += '</tr><tr>';
    }
  }

  html += '</tr></tbody></table>';
  return html;
}

const container = document.getElementById("months");

data.forEach((item, index) => {
  const card = document.createElement("article");
  card.className = "card";

  card.innerHTML = `
    <img src="${item.image}" alt="${item.title} in Jammu and Kashmir"
         loading="lazy">
    <div class="card-content">
      <h2>${item.month} 2027</h2>
      <h3>${item.title}</h3>
      <p><strong>Destination:</strong> ${item.place}</p>
      <p><strong>Culture:</strong> ${item.culture}</p>
      <p><strong>Local Cuisine:</strong> ${item.food}</p>
      ${makeCalendar(index)}
      <div class="sdg">
        <strong>SDG 8 – Local Livelihoods</strong>
        <p>${item.sdg}</p>
      </div>
    </div>
  `;

  container.appendChild(card);
});
</script>

</body>
</html>
