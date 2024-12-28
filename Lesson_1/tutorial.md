# TAILWIND CSS

## Extension:

- Live Server
- Tailwind CSS IntelliSense

## Command line

    1.  npx tailwindcss init
    2.  npx tailwindcss -i ./src/input.css -o ./build/css/style.css
    3.  npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch

## css width height

1rem == w-4 ==16px  
w-52 ==13rem
min-h-screen == min-height:100vh

### If tailwind class is not included

./input.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

.radial-blue {
background: radial-gradient(lightyellow, skyblue);
}
```
