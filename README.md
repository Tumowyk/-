<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>Світ Електроніки</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f4f4f4; margin: 0; }
    header { background: #003366; color: white; padding: 20px; text-align: center; }
    nav { background: #005599; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 20px; background: white; margin: 20px; border-radius: 10px; }
    input, select, button { margin: 5px 0; padding: 5px; }
  </style>
</head>
<body>
  <header>
    <h1>Світ Електроніки</h1>
    <p>Навчайся, експериментуй, створюй!</p>
  </header>
  <nav>
    <a href="#">Головна</a>
    <a href="#">Калькулятор</a>
    <a href="#">LED резистор</a>
    <a href="#">Теорія</a>
    <a href="#">Вікторина</a>
    <a href="#">Проекти</a>
  </nav>
  <section>
    <h2>Про сайт</h2>
    <p>Цей сайт створений для всіх, хто цікавиться електронікою. Тут є теорія, калькулятори, вікторини та інше.</p>
  </section>
  <section>
    <h2>Калькулятор кольорових кілець резистора</h2>
    <input type="text" placeholder="наприклад 4.7">
    <select>
      <option>Ом</option>
      <option>кОм</option>
      <option>МОм</option>
    </select>
    <button>Розрахувати</button>
  </section>
  <section>
    <h2>Калькулятор резистора для світлодіода</h2>
    <label>Напруга живлення (В): <input type="number"></label><br>
    <label>Падіння напруги на світлодіоді (В): <input type="number"></label><br>
    <label>Бажаний струм (мА): <input type="number" value="150"></label><br>
    <button>Обчислити</button>
  </section>
  <section>
    <h2>Теорія</h2>
    <ul>
      <li>Закон Ома: I = U / R</li>
      <li>Типи компонентів: резистори, транзистори, конденсатори</li>
      <li>Принцип роботи світлодіода</li>
      <li>Як користуватись мультиметром</li>
    </ul>
  </section>
</body>
</html>
