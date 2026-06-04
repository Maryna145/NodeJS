# NodeJS
# Встановлення та налаштування середовища Node.js

---

## Виконані кроки

### Крок 1: Встановлення Node.js
- Метод встановлення: офіційний інсталятор
- З офіційного сайту [nodejs.org](https://nodejs.org) завантажено стабільну версію **Node.js LTS**
- Запущено `.msi` інсталятор, встановлення виконано з налаштуваннями за замовчуванням

---

### Крок 2: Перевірка встановлення
Для перевірки успішності встановлення у терміналі (PowerShell / CMD) виконано команди:

```bash
node -v
npm -v
```

**Очікуваний результат:** відображення версій Node.js та npm  
<img width="361" height="156" alt="Знімок екрана 2026-06-04 151116" src="https://github.com/user-attachments/assets/a694805f-8132-4072-b97e-0016ceeef012" />


---

### Крок 3: Робота в інтерактивному середовищі REPL
Запущено REPL за допомогою команди:

```bash
node
```

У середовищі виконано базові операції:

```javascript
5 + 10
20 - 7
```

REPL успішно виконав цикл Read → Evaluate → Print → Loop.
<img width="417" height="206" alt="Знімок екрана 2026-06-04 151133" src="https://github.com/user-attachments/assets/12465851-b83e-47d6-8bcb-165837018731" />


---

### Крок 4: Створення та запуск скрипту `main.js`

Створено файл `main.js` з таким кодом:

```javascript
const a = 10;
const b = 5;

console.log(`Сума: ${a + b}`);
console.log(`Різниця: ${a - b}`);
console.log(`Добуток: ${a * b}`);
console.log(`Частка: ${a / b}`);
```

Запуск файлу виконується командою:

```bash
node main.js
```
<img width="757" height="182" alt="Знімок екрана 2026-06-04 151457" src="https://github.com/user-attachments/assets/b56549b4-1c18-4c38-8a9d-d81bf28cfec4" />


