body {
  margin:0;
  font-family:Arial;
  background:#0a0f1c;
  color:#e5e7eb;
}

header {
  display:flex;
  justify-content:space-between;
  padding:15px 40px;
  background:#0f172a;
  position:sticky;
  top:0;
}

.logo {
  color:#60a5fa;
  font-weight:bold;
}

nav a {
  color:#cbd5e1;
  margin-left:15px;
  text-decoration:none;
}

.hero {
  text-align:center;
  padding:100px 20px;
}

.hero h1 {
  font-size:48px;
}

.btn {
  display:inline-block;
  margin-top:20px;
  padding:12px 20px;
  background:#2563eb;
  color:white;
  border-radius:8px;
  text-decoration:none;
}

.grid {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:15px;
  padding:40px;
}

.card {
  background:#111827;
  padding:20px;
  border-radius:12px;
  border:1px solid #1f2937;
  text-align:center;
}

.page {
  padding:60px 20px;
  text-align:center;
}

footer {
  text-align:center;
  padding:20px;
  color:#64748b;
}
