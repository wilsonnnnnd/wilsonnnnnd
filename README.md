# 👋 Hello World! I'm Weimeng Ding 🐼
🎯 **Web & Mobile Developer** | 💡 **Lifelong Learner** | 🚀 **Problem Solver**

I love building scalable and user-friendly solutions across web and mobile.  
Currently sharpening my skills in **React Native (Expo)**, **React.js**, **Node.js**, and **DevOps**.  
Always curious. Always shipping.
![Coding Gif](https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif)
```jsx
import React from 'react';

const Wilson = () => {
  const [developer] = React.useState({
    name: 'Weimeng Ding',
    languages: ['English', 'Chinese'],
    frontend: ['⚛️ React.js', '🖖 Vue.js', '📱 React Native (Expo)', '🎨 UI/UX Design'],
    backend: ['🚀 Node.js', '🐘 Express.js', '🐘 PHP'],
    database: ['📊 MySQL', '🗄️ SQL Server', '🔥 Firebase Realtime DB'],
    devOps: ['🛠️ Git / Bitbucket', '☁️ Azure', '☁️ Firebase Hosting'],
    data: ['📈 D3.js', '🔗 GraphQL', '📦 REST APIs'],
    status: '💻 Full-stack Developer',
    email: '📧 wilson.ding.wm@gmail.com',
    website: '🌐 https://weimengding.online/'
  });

  return (
    <div>
      <h1>{developer.name}</h1>
      <p>{developer.status}</p>
    </div>
  );
};
export default Wilson;
