# 👋 Hello World! I'm Wilson 🐼

![Cute Yellow Dino](https://media.giphy.com/media/XbxZ41fWLeRECPsGIJ/giphy.gif)

```jsx
import React from 'react';

const Wilson = () => {
  const [developer, setDeveloper] = React.useState({
    name: 'Wilson',
    languages: ['🇨🇳 Chinese', '🇬🇧 English'],
    skills: ['⚛️ Next.js', '🖖 Vue.js', '🚀 Node.js'],
    database: ['📊 MySQL', '🍃 MongoDB', '🔥 Firebase'],
    devOps: ['🛠️ Git'],
    status: '💻 Web Developer',
    email: '📧 wilson.ding.wm@gmail.com',
    website: '🌐 https://weimengding.online/'
  });

  return (
    <div>
      <h1>{developer.name}</h1>
      <p>{developer.status}</p>
      <h2>Skills:</h2>
      <ul>
        {developer.skills.map((skill, index) => (
          <li key={index}>{skill}</li>
        ))}
      </ul>
      <h2>Database:</h2>
      <ul>
        {developer.database.map((db, index) => (
          <li key={index}>{db}</li>
        ))}
      </ul>
      <h2>DevOps:</h2>
      <ul>
        {developer.devOps.map((tool, index) => (
          <li key={index}>{tool}</li>
        ))}
      </ul>
      <p>{developer.email}</p>
      <p>{developer.website}</p>
    </div>
  );
};

export default Wilson;
