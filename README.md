# hotel-rose-landing
<!doctype html>


<main class="hero">
<div class="main-photo" role="img" aria-label="Велика вілла з басейном"></div>


<div style="display:flex;flex-direction:column;gap:14px">
<div class="card">
<h2>Вільні будинки</h2>
<p class="lead">Оберіть віллу з реальними фото та ціною за добу. Швидке бронювання і прозорі умови.</p>


<div class="gallery">
<div class="item" style="background-image:url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder'); background-size:cover; background-position:center"></div>
<div class="item" style="background-image:url('https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder'); background-size:cover; background-position:center"></div>
</div>


<div class="price-row">
<div>
<div style="font-size:13px;color:var(--muted)">Класична вілла</div>
<div class="price">$100 <small>/ доба</small></div>
</div>
<div>
<div style="font-size:13px;color:var(--muted)">Сучасна вілла</div>
<div class="price">$150 <small>/ доба</small></div>
</div>
</div>


</div>


<div class="card" style="display:flex;gap:12px;align-items:center;justify-content:space-between">
<div>
<strong>Швидке бронювання</strong>
<div style="color:var(--muted);font-size:13px">Підтвердження миттєво, оплата онлайн.</div>
</div>
<a href="#" style="background:var(--brand);color:white;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600">Забронювати</a>
</div>
</div>
</main>


<aside>
<div class="team">
<h3>Команда</h3>
<div class="members">
<div class="member"><div class="av">А</div><div><div>Антон Сонячний</div><small>CEO</small></div></div>
<div class="member"><div class="av">М</div><div><div>Микита Кавун</div><small>Operations</small></div></div>
<div class="member"><div class="av">Т</div><div><div>Тимофій Грибний</div><small>Design</small></div></div>
<div class="member"><div class="av">С</div><div><div>Саша Лісний</div><small>Marketing</small></div></div>
</div>
</div>


<div class="card">
<h3>Контакти</h3>
<p style="margin:6px 0 0 0;color:var(--muted);font-size:14px">email: hello@hotelrose.example<br>тел: +380 00 000 0000</p>
</div>
</aside>


<footer>© Hotel Rose — Демонстраційний макет. Збережіть цей файл як index.html і завантажте в GitHub.</footer>
</div>


<script>
// Невелика функція для демонстрації — відкриває модаль з підтвердженням (placeholders)
document.querySelectorAll('a[href="#"]').forEach(a=>a.addEventListener('click', e=>{e.preventDefault(); alert('Функція демо: тут буде форма бронювання.')}))
</script>
</body>
</html>
