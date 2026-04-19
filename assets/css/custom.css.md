body {
  max-width: 850px;
  margin: auto;
  font-size: 1.05rem;
  line-height: 1.7;
}

h1, h2, h3 {
  margin-top: 2rem;
  font-weight: 600;
}

p {
  margin-bottom: 0.8rem;
}

.callout {
  border-radius: 8px;
  padding: 12px;
  font-size: 0.95rem;
}

.callout-note {
  background-color: #EEF4FF;
}

.callout-tip {
  background-color: #EEFBEF;
}

.callout-warning {
  background-color: #FFF8E1;
}

body[data-bs-theme="dark"] .callout-note {
  background-color: #1e293b;
}

body[data-bs-theme="dark"] .callout-tip {
  background-color: #1e3a2f;
}

body[data-bs-theme="dark"] .callout-warning {
  background-color: #3a2e1e;
}

code {
  background-color: #f5f5f5;
  padding: 2px 4px;
  border-radius: 4px;
}

pre code {
  background-color: #f5f5f5;
  padding: 12px;
  border-radius: 6px;
}

body[data-bs-theme="dark"] code {
  background-color: #2d2d2d;
}

body[data-bs-theme="dark"] pre code {
  background-color: #2d2d2d;
}

ul, ol {
  margin-bottom: 1rem;
}

.hero {
  background-image: url("../img/capa-fam.jpg");
  background-size: cover;
  background-position: center;
  padding: 8rem 2rem;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.full-width {
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  width: 100vw;
}

.hero h2 {
  font-weight: 400;
}

.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.5);
}

.hero * {
  position: relative;
}
