/* =========================
   CONTACT PAGE
========================= */

.contact-page {
  width: 100%;
  max-width: 760px;
  margin: 0 auto;
}

.contact-card {
  width: 100%;
}

.contact-card h1 {
  margin-bottom: 22px;
}

.contact-card .lead {
  max-width: 680px;
  margin-bottom: 34px;
  color: var(--muted);
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 20px;
  width: 100%;
}

.form-field {
  display: flex;
  flex-direction: column;
  gap: 7px;
  width: 100%;
}

.form-field label {
  color: var(--heading);
  font-size: 0.92rem;
  font-weight: 650;
}

.form-field input,
.form-field select,
.form-field textarea {
  display: block;
  width: 100%;
  box-sizing: border-box;
  padding: 13px 14px;
  border: 1px solid var(--border);
  border-radius: 12px;
  background: #ffffff;
  color: var(--text);
  font-family: inherit;
  font-size: 1rem;
  line-height: 1.4;
  appearance: none;
  transition: border-color 0.2s ease, box-shadow 0.2s ease;
}

.form-field select {
  background-image:
    linear-gradient(45deg, transparent 50%, var(--muted) 50%),
    linear-gradient(135deg, var(--muted) 50%, transparent 50%);
  background-position:
    calc(100% - 18px) 50%,
    calc(100% - 13px) 50%;
  background-size:
    5px 5px,
    5px 5px;
  background-repeat: no-repeat;
  padding-right: 42px;
}

.form-field textarea {
  min-height: 170px;
  resize: vertical;
}

.form-field input:focus,
.form-field select:focus,
.form-field textarea:focus {
  outline: none;
  border-color: var(--accent);
  box-shadow: 0 0 0 4px rgba(47, 111, 126, 0.12);
}

.contact-form button {
  align-self: flex-start;
  margin-top: 4px;
  padding: 12px 20px;
  border: none;
  border-radius: 999px;
  background: var(--accent);
  color: #ffffff;
  font-family: inherit;
  font-size: 0.95rem;
  font-weight: 700;
  cursor: pointer;
  transition: background 0.2s ease, transform 0.2s ease;
}

.contact-form button:hover {
  background: var(--accent-dark);
  transform: translateY(-1px);
}

.form-honeypot {
  display: none !important;
}

@media (max-width: 600px) {
  .contact-page {
    max-width: 100%;
  }

  .contact-form button {
    width: 100%;
  }
}
