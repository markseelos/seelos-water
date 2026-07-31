/* =========================
   ABOUT PAGE
========================= */

.about-page {
  width: 100%;
}

.about-grid {
  display: grid;
  grid-template-columns: minmax(0, 1fr);
  gap: 28px;
}

.about-section,
.about-box {
  background: var(--white);
  border: 1px solid var(--border-light);
  border-radius: var(--radius);
  padding: 28px;
  box-shadow: var(--shadow-soft);
}

.about-section h2,
.about-box h2 {
  margin-bottom: 16px;
}

.about-section h3,
.about-box h3 {
  margin: 22px 0 10px;
}

/* About intro/profile layouts */
.about-intro,
.about-hero,
.about-profile {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 260px;
  gap: 36px;
  align-items: start;
}

/* =========================
   ABOUT HEADSHOT
========================= */

.about-headshot {
  width: 220px;
  height: 220px;
  object-fit: cover;
  border-radius: 18px;
  display: block;
  margin: 0 auto 24px;
  box-shadow: var(--shadow-soft);
}

/* Keep other legacy image classes working */
.about-photo,
.about-image,
.profile-photo {
  max-width: 260px;
  width: 100%;
  margin: 0 auto 24px;
}

.about-photo img,
.about-image img,
.profile-photo img,
img.about-photo,
img.profile-photo {
  width: 100%;
  max-width: 260px;
  height: auto;
  border-radius: 18px;
  display: block;
  margin: 0 auto;
  box-shadow: var(--shadow-soft);
}
