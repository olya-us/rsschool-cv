# Olya Us

### Frontend Developer

### Contact information:

**E-mail:** olyaus0809@gmail.com<br>
**Telegram:** @us_olya<br>
**Discord:** olya_08434<br>
**Portfolio:** https://olyaus.netlify.app

### Professional Summary:

I specialize in crafting dynamic and responsive web applications using modern frontend technologies.

I'm proficient in using in using JavaScript/TypeScript and React to create dynamic and interactive websites. Additionally, I am skilled in setting up build and development processes using tools such as npm, Vite, Jest, and Git, which helps me to efficiently manage and track my code.

To ensure high-quality code, I use tools like ESLint and Stylelint to improve the code's readability, maintainability, and consistency. I am also a responsible team player who works well with others and constantly seeks to learn and improve my skills.

### Key Skills:

- React / React-Query
- Javascript / Typescript
- CSS / SCSS
- Git / GitHub
- Vite / Webpack / Gulp
- Jest / Testing Library

### Code example:

This code defines a LanguageSwitcher component in React that allows users to switch between Russian and English languages, using the react-i18next library for translation and localStorage to persist the selected language.

```
import { useState, useEffect } from 'react';
import { useTranslation } from 'react-i18next';
import TabNavigation from './Tabs'; 

const LanguageSwitcher = () => {
  const { i18n } = useTranslation();
  const [activeLang, setActiveLang] = useState('ru');

  useEffect(() => {
    const storedLang = localStorage.getItem('lng') || 'ru';
    setActiveLang(storedLang);
    i18n.changeLanguage(storedLang);
  }, [i18n]);

  const changeLanguage = (lng) => {
    i18n.changeLanguage(lng);
    localStorage.setItem('lng', lng);
    setActiveLang(lng);
  };

  const tabs = [
    { id: 0, label: 'Ru', onClick: () => changeLanguage('ru') },
    { id: 1, label: 'En', onClick: () => changeLanguage('en') },
  ];

  return <TabNavigation tabs={tabs} activeTab={activeLang === 'ru' ? 0 : 1} />;
};

export default LanguageSwitcher;
```

### Work Experience:

Work as Frontend Developer in ust.inc (August 2019 – present).

Transforming complex robotics systems into user-friendly experiences is my specialty. At UST, I leverage cutting-edge technologies like React, JavaScript, and CSS/SCSS to create powerful and intuitive interfaces that make controlling and interacting with robots seamless and efficient.

Key Contributions:

- Creation and improvement of Pixel Perfect HTML prototypes, which I with the front-end team turn into working components.
- All CSS styles of the system go through visual regression testing to avoid problems with the visual part in production.
- Constant code review and discussion of technical aspects with other developers to create the perfect product.
- Deliver engaging user experience through optimization of images, code, and cross-browser compatibility, which reduced page load times by up to 30%.
- Implemented websites, mobile applications, and landing pages from concept through deployment.
- Translated design team’s UX wireframes and mockups into responsive, interactive features, using HTML/CSS, JavaScript, React.js.
- Expand features, refine code, and improve processes, producing smoother operations and enhancing user engagement.
- Created, maintained, and enforced front-end code and documentation standards.

### Courses:

- Udemy Courese «Полный курс по JavaScript + React - с нуля до результата»
- Great Learning «JavaScript Projects»
- Udemy Courese «React - Полный Курс по React»
- Sololearn Course «JavaScript Intermediate»
- Udemy Courese «Тестирование JavaScript и React приложений»
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)


### Languages:

- English - Intermediate
- Russian - Native
