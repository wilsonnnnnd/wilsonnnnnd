# 👋 Hello World! I'm Wilson 🐼

![Coding Gif](https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif)

```jsx
import React from 'react';

const Wilson = () => {
  const [developer, setDeveloper] = React.useState({
    name: 'Wilson',
    languages: ['🇨🇳 Chinese', '🇬🇧 English'],
    skills: ['⚛️ Next.js', '🖖 Vue.js', '🚀 Node.js'],
    status: '💻 Web Developer',
    email: '📧 wilson.ding.wm@gmail.com',
    website: '🌐 https://weimengding.online/'
  });

  return (
    <div>
      <h1>{developer.name}</h1>
      <p>{developer.status}</p>
      <ul>
        {developer.skills.map((skill, index) => (
          <li key={index}>{skill}</li>
        ))}
      </ul>
      <p>{developer.email}</p>
      <p>{developer.website}</p>
    </div>
  );
};

export default Wilson;
