body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #fdfdfd;
  color: #333;
}
header {
  background-color: #c8102e;
  color: white;
  padding: 1rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}
.logo {
  font-size: 1.5rem;
  font-weight: bold;
  display: flex;
  align-items: center;
}
.logo img {
  height: 40px;
  margin-right: 0.5rem;
}
nav a {
  color: white;
  margin-left: 1rem;
  text-decoration: none;
}
.hero {
  text-align: center;
  padding: 3rem 1rem;
}
.hero h1 {
  font-size: 2rem;
}
.categories {
  padding: 1rem;
  text-align: center;
}
.categories h2 {
  font-size: 1.5rem;
}
.categories ul {
  list-style: none;
  padding: 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}
.categories li {
  background-color: #eee;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-weight: bold;
}
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  padding: 2rem;
}
.product {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 1rem;
  background-color: #fff;
  text-align: center;
}
.product img {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
}
.product h3 {
  margin: 0.5rem 0 0.25rem;
}
.product p {
  margin: 0.25rem 0;
}
.dashboard {
  padding: 2rem;
  background-color: #f0f0f0;
}
.dashboard h2 {
  text-align: center;
}
.dashboard form {
  max-width: 600px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.dashboard input, .dashboard textarea, .dashboard button {
  padding: 0.75rem;
  font-size: 1rem;
  border-radius: 5px;
  border: 1px solid #ccc;
}
.dashboard button {
  background-color: #c8102e;
  color: white;
  border: none;
  cursor: pointer;
}
footer {
  background-color: #222;
  color: #fff;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
@media (max-width: 600px) {
  header, .products, .dashboard form {
    flex-direction: column;
  }
  nav a {
    margin: 0.5rem 0;
  }
}
