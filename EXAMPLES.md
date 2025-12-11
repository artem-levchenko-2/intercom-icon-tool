# Приклади SVG для використання

## Приклади фонів

### 1. Градієнт (Фіолетовий → Рожевий)
```xml
<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="200" height="200" fill="url(#grad1)" />
  <circle cx="200" cy="0" r="80" fill="rgba(255,255,255,0.1)" />
  <circle cx="0" cy="200" r="80" fill="rgba(255,255,255,0.1)" />
</svg>
```

### 2. Градієнт (Синій → Бірюзовий)
```xml
<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="blueGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#4facfe;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#00f2fe;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="200" height="200" fill="url(#blueGrad)" />
</svg>
```

### 3. Градієнт (Червоний → Помаранчевий)
```xml
<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sunsetGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#FF6B6B;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#FFD93D;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="200" height="200" fill="url(#sunsetGrad)" />
  <circle cx="100" cy="100" r="60" fill="rgba(255,255,255,0.1)" />
</svg>
```

### 4. Геометричний патерн
```xml
<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <pattern id="pattern1" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
      <circle cx="10" cy="10" r="2" fill="#667eea" opacity="0.3"/>
    </pattern>
  </defs>
  <rect width="200" height="200" fill="#f0f0f0"/>
  <rect width="200" height="200" fill="url(#pattern1)"/>
</svg>
```

### 5. Хвилі
```xml
<svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#11998e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#38ef7d;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="200" height="200" fill="url(#waveGrad)"/>
  <path d="M0,100 Q50,80 100,100 T200,100 L200,200 L0,200 Z" fill="rgba(255,255,255,0.1)"/>
  <path d="M0,120 Q50,100 100,120 T200,120 L200,200 L0,200 Z" fill="rgba(255,255,255,0.05)"/>
</svg>
```

## Приклади іконок

### 1. Зірка
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 2. Серце
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 3. Молнія (потужність)
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M13 2L3 14h8l-1 8 10-12h-8l1-8z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 4. Музика
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 3v10.55c-.59-.34-1.27-.55-2-.55-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4V7h4V3h-6z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 5. Камера
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M9 2L7.17 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2h-3.17L15 2H9zm3 15c-2.76 0-5-2.24-5-5s2.24-5 5-5 5 2.24 5 5-2.24 5-5 5z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
  <circle cx="12" cy="12" r="3" fill="rgba(0,0,0,0.2)"/>
</svg>
```

### 6. Літак (подорожі)
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M21 16v-2l-8-5V3.5c0-.83-.67-1.5-1.5-1.5S10 2.67 10 3.5V9l-8 5v2l8-2.5V19l-2 1.5V22l3.5-1 3.5 1v-1.5L13 19v-5.5l8 2.5z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 7. Книга
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M18 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zM6 4h5v8l-2.5-1.5L6 12V4z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 8. Кубок (досягнення)
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M19 5h-2V3H7v2H5c-1.1 0-2 .9-2 2v1c0 2.55 1.92 4.63 4.39 4.94.63 1.5 1.98 2.63 3.61 2.96V19H7v2h10v-2h-4v-3.1c1.63-.33 2.98-1.46 3.61-2.96C19.08 12.63 21 10.55 21 8V7c0-1.1-.9-2-2-2zM5 8V7h2v3.82C5.84 10.4 5 9.3 5 8zm14 0c0 1.3-.84 2.4-2 2.82V7h2v1z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

### 9. Ракета
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 2.5s4.5 2.04 4.5 10.5c0 2.49-1.04 5.57-1.6 7H9.1c-.56-1.43-1.6-4.51-1.6-7C7.5 4.54 12 2.5 12 2.5z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
  <circle cx="12" cy="9" r="2" fill="rgba(0,0,0,0.2)"/>
  <path d="M12 20.5v1M9.1 20h5.8l-1.4 3.5h-3z" fill="rgba(255,255,255,0.7)"/>
</svg>
```

### 10. Корона
```xml
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <path d="M5 16L3 5l5.5 5L12 4l3.5 6L21 5l-2 11H5zm14 3c0 .6-.4 1-1 1H6c-.6 0-1-.4-1-1v-1h14v1z" 
        fill="white" stroke="rgba(0,0,0,0.2)" stroke-width="0.5"/>
</svg>
```

## Поради щодо використання

1. **Колір іконок**: Білі іконки найкраще виглядають на темних/яскравих фонах
2. **Розмір іконки**: Рекомендовані значення 50-70% для гармонійного співвідношення
3. **ViewBox**: Переконайтесь, що viewBox вказаний коректно і для фону, і для іконки
4. **Градієнти**: Використовуйте унікальні ID для градієнтів, щоб уникнути конфліктів

## Де знайти більше іконок

- **Heroicons**: https://heroicons.com/
- **Feather Icons**: https://feathericons.com/
- **Material Icons**: https://fonts.google.com/icons
- **Font Awesome**: https://fontawesome.com/icons
- **Ionicons**: https://ionic.io/ionicons
- **Bootstrap Icons**: https://icons.getbootstrap.com/
