* {
  box-sizing: border-box;
}

body {
  min-height: 100vh;
  margin: 0;
  padding: 32px 16px;
  display: grid;
  place-items: center;
  font-family: Arial, sans-serif;
  color: #243247;
  background: #eef3f8;
}

.page {
  width: 100%;
  max-width: 420px;
}

.profile-card {
  overflow: hidden;
  border: 1px solid #d5dfE9;
  border-radius: 20px;
  background: #fff;
  box-shadow: 0 12px 32px #21374d1c;
}

.profile-image-wrap {
  position: relative;
  height: 260px;
}

.profile-image {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.availability-badge {
  position: absolute;
  top: 16px;
  right: 16px;
  padding: 8px 12px;
  border: 1px solid #b3e6cd;
  border-radius: 20px;
  background: #e4f8ed;
  color: #17633d;
  font-size: 0.8rem;
  font-weight: bold;
}

.profile-content {
  padding: 24px;
}

.profile-role {
  margin: 0 0 6px;
  color: #3973a8;
  font-size: 0.85rem;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.profile-name {
  margin: 0 0 12px;
  font-size: 1.8rem;
}

.profile-description {
  margin: 0 0 20px;
  color: #526477;
  line-height: 1.6;
}

.skills-heading {
  margin: 0 0 10px;
  font-size: 1rem;
}

.skills-list {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0 0 24px;
  padding: 0;
  list-style: none;
}

.skills-list li {
  padding: 7px 10px;
  border: 1px solid #d6e3ef;
  border-radius: 16px;
  background: #f3f7fb;
  font-size: 0.85rem;
}

.contact-button {
  display: block;
  padding: 13px 18px;
  border-radius: 9px;
  background: #28699f;
  color: #fff;
  font-weight: bold;
  text-align: center;
  text-decoration: none;
}

.contact-button:hover {
  background: #1e527e;
}

@media (max-width: 360px) {
  body {
    padding: 16px 10px;
  }

  .profile-image-wrap {
    height: 210px;
  }

  .profile-content {
    padding: 18px;
  }
}