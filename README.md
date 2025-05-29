header {
  background-color: #ffffff;
  padding: 20px 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.logo {
  font-size: 24px;
  font-weight: 600;
  color: #2b9348;
}

nav a {
  margin-left: 30px;
  text-decoration: none;
  color: #2d2d2d;
  font-weight: 500;
}

.hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 100px 20px;
  background: linear-gradient(to right, #e6f4ea, #f7fff9);
  text-align: center;
}

.hero h1 {
  font-size: 42px;
  color: #1f693c;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  max-width: 600px;
  color: #444;
}

.btn-primary {
  background-color: #2b9348;
  color: white;
  border: none;
  padding: 14px 30px;
  font-size: 16px;
  border-radius: 6px;
  margin-top: 30px;
  cursor: pointer;
}

.categories {
  display: flex;
  justify-content: center;
  gap: 40px;
  padding: 60px 20px;
  flex-wrap: wrap;
}

.category {
  background: white;
  border-radius: 10px;
  padding: 30px;
  width: 200px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.07);
  text-align: center;
}

.category h3 {
  color: #2b9348;
  margin-top: 10px;
}

footer {
  text-align: center;
  padding: 30px;
  background: #ffffff;
  color: #999;
  font-size: 14px;
}

@media (max-width: 768px) {
  header {
    flex-direction: column;
    align-items: flex-start;
  }

  nav {
    margin-top: 10px;
  }

  .hero h1 {
    font-size: 32px;
  }

  .categories {
    flex-direction: column;
    align-items: center;
  }
}
