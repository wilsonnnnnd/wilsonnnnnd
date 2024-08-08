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
    email: '404 🙈',
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
    </div>
  );
};

export default Wilson;
