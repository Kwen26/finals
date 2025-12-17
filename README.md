 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: linear-gradient(135deg, #ffd1e8, #ffc0cb);
  color: #333;
}

/* ===================== HEADER ===================== */
header {
  background: rgba(255, 255, 255, 0.9);
  padding: 20px;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 100;
}

header h1 {
  color: #e91e63;
  margin-bottom: 10px;
}

nav button {
  margin: 5px;
  padding: 10px 18px;
  border: none;
  border-radius: 20px;
  background-color: #e91e63;
  color: #fff;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

nav button:hover {
  background-color: #c2185b;
}

/* ===================== SECTION ===================== */
section {
  padding: 50px 20px;
  max-width: 1100px;
  margin: auto;
}

/* Headings in sections */
section h2 {
  color: #e91e63;
  text-align: center;
  margin-bottom: 20px;
}

/* ===================== ABOUT ME ===================== */
.about {
  background: #fff;
  padding: 30px;
  border-radius: 20px;
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  align-items: center;
  justify-content: center;
}

.about img {
  width: 250px;
  border-radius: 20px;
  object-fit: cover;
  height: 250px;
}

.about div {
  max-width: 600px;
}

/* ===================== PROJECTS ===================== */
.projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: #fff;
  padding: 15px;
  border-radius: 16px;
  text-align: center;
  box-shadow: 0 5px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
  cursor: default;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.15);
  cursor: pointer;
}

.card img {
  width: 100%;
  border-radius: 12px;
  height: 160px;
  object-fit: cover;
  margin-bottom: 10px;
}

/* ===================== SKILLS ===================== */
.skills {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.skill {
  background: #fff;
  padding: 20px;
  border-radius: 20px;
  width: 120px;
  text-align: center;
  box-shadow: 0 5px 10px rgba(0,0,0,0.1);
  font-weight: bold;
  font-size: 1rem;
  cursor: default;
}

/* ===================== CONTACTS ===================== */
.contacts {
  background: #fff;
  padding: 30px;
  border-radius: 20px;
  text-align: center;
}

/* ===================== FOOTER ===================== */
footer {
  background: #e91e63;
  color: #fff;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}
