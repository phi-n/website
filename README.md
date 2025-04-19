# website

/* style.css */

body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #1f2d3d;
  color: white;
  text-align: center;
  padding: 2rem 1rem;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

header p {
  font-weight: 300;
  font-size: 1.2rem;
}

main {
  max-width: 1000px;
  margin: 2rem auto;
  padding: 0 1rem;
}

.project {
  background-color: white;
  margin-bottom: 2rem;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  overflow: hidden;
  transition: transform 0.3s ease;
}

.project:hover {
  transform: scale(1.02);
}

.project img {
  width: 100%;
  height: auto;
  display: block;
}

.project h2 {
  margin: 1rem;
  font-size: 1.8rem;
  color: #1f2d3d;
}

.project p {
  padding: 0 1rem 1rem;
  font-size: 1rem;
}

.reflection {
  background-color: #e6ecf1;
  border-left: 6px solid #1f2d3d;
  padding: 1rem;
  margin-top: 3rem;
  border-radius: 8px;
}

.reflection h2 {
  margin-top: 0;
  font-size: 1.5rem;
  color: #1f2d3d;
}

footer {
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
  background-color: #1f2d3d;
  color: #fff;
  margin-top: 2rem;
}
