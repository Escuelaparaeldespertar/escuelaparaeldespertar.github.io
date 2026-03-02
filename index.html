// ══════════════════════
// ARRAY DE LIBROS
// ══════════════════════
const libros = [
  { categoria:'Ken Wilber', titulo:'Gracia y Coraje', autor:'Ken Wilber', imagen:'Libros/gracia_y_coraje.jpg', url:'https://e.pcloud.link/publink/show?code=XZQJ43ZuB9j90ho1L8VgXowljU6d5xgRe1y' },
  { categoria:'Barbara Ann Brenan', titulo:'Manos que Curan', autor:'Barbara Ann Brennan', imagen:'Libros/Manosquecuran.jpg', url:'' },
  { categoria:'Barbara Ann Brenan', titulo:'Hágase la Luz', autor:'Barbara Ann Brennan', imagen:'Libros/Manosquecuran_2.jpg', url:'' },
  { categoria:'Biodescodificación', titulo:'La Descodificación Biológica de las Enfermedades', autor:'Enric Corbera', imagen:'Libros/Biodescodificacion.jpg', url:'' },
  { categoria:'Biodescodificación', titulo:'Causas Emocionales de las Enfermedades', autor:'Jacques Martel', imagen:'Libros/Causasdolencias.jpg', url:'', imgPosition:'right' },
  { categoria:'Budismo', titulo:'El Libro Tibetano de los Muertos', autor:'Timothy Leary', imagen:'Libros/librotibetanomuertos.jpg', url:'' },
  { categoria:'Budismo', titulo:'Budismo Esotérico', autor:'Alfred Percy Sinnett', imagen:'Libros/Budismoesoterico.jpg', url:'', imgPosition:'top' },
  { categoria:'Carolyne Myss', titulo:'Anatomía del Espíritu', autor:'Caroline Myss', imagen:'Libros/Caroline_Myss/Anatomía_espiritu.jpg', url:'' },
  { categoria:'Carolyne Myss', titulo:'Arquetipos', autor:'Caroline Myss', imagen:'Libros/Caroline_Myss/Arquetipos.jpg', url:'' },
  { categoria:'Carolyne Myss', titulo:'El Contrato Sagrado', autor:'Caroline Myss', imagen:'Libros/Caroline_Myss/Contratosagrado.png', url:'' },
  { categoria:'Carolyne Myss', titulo:'Desafiar la Gravedad', autor:'Caroline Myss', imagen:'Libros/Caroline_Myss/Desafiargravedad.jpg', url:'' },
  { categoria:'Carolyne Myss', titulo:'La Medicina de la Energía', autor:'Caroline Myss', imagen:'Libros/Caroline_Myss/Medicinadelaenergia.jpg', url:'' },
  { categoria:'Carolyne Myss', titulo:'El Poder Invisible en Acción', autor:'Caroline Myss', imagen:'Libros/Caroline_Myss/Myss_Caroline_El_Poder_Invisible.jpg', url:'' },
  { categoria:'Cristaloterapia', titulo:'La Biblia de los Cristales', autor:'Judy Hall', imagen:'Libros/Bibliacristales.png', url:'', imgContain:true },
  { categoria:'Filosofía y Religión', titulo:'Practicando la Presencia', autor:'Joel Goldsmith', imagen:'Libros/Filosofia_Religion/PracticandoPresencia.jpg', url:'' },
  { categoria:'Filosofía y Religión', titulo:'Análisis Espiritual (2da Edición)', autor:'F. Javier Sánchez Campuzano', imagen:'Libros/Filosofia_Religion/Analisis_espiritual.jpg', url:'' },
  { categoria:'Filosofía y Religión', titulo:'Santa Teresa de Ávila, compañera espiritual de la Sierva de Dios, Dorothy Day', autor:'Francis J. Sicius', imagen:'Libros/Filosofia_Religion/SantaTeresa.jpg', url:'', imgPosition:'center top' },
  { categoria:'Filosofía y Religión', titulo:'La Vida Sempiterna 1', autor:'Duane S. Crowther', imagen:'Libros/Filosofia_Religion/VidaSempiterna1.jpg', url:'' },
  { categoria:'Filosofía y Religión', titulo:'La Vida Sempiterna 2', autor:'Duane S. Crowther', imagen:'Libros/Filosofia_Religion/VidaSempiterna2.jpg', url:'' },
  { categoria:'Geometría Sagrada', titulo:'Introducción a la Ciencia Sagrada', autor:'Federico González', imagen:'Libros/Geometria_Sagrada/Introduccionciencia.jpg', url:'' },
  { categoria:'Geometría Sagrada', titulo:'El Antiguo Secreto de la Flor de la Vida Vol. 1', autor:'Drunvalo Melchizedek', imagen:'Libros/Geometria_Sagrada/SecretoFlorVida.jpg', url:'' },
  { categoria:'Geometría Sagrada', titulo:'El Antiguo Secreto de la Flor de la Vida Vol. 2', autor:'Drunvalo Melchizedek', imagen:'Libros/Geometria_Sagrada/SecretoFlorVida2.jpg', url:'' },
  { categoria:'Geometría Sagrada', titulo:'Serpiente de Luz Vol. 4', autor:'Drunvalo Melchizedek', imagen:'Libros/Geometria_Sagrada/Serpienteluz.jpg', url:'' },
  { categoria:'Geometría Sagrada', titulo:'Viviendo en el Corazón', autor:'Drunvalo Melchizedek', imagen:'Libros/Geometria_Sagrada/ViviendoCorazon.jpg', url:'' }
];

// ══════════════════════
// PANEL CATEGORÍAS Y LIBROS
// ══════════════════════
const panelCats  = document.getElementById('panelCats');
const panelBooks = document.getElementById('panelBooks');

// Función para abrir categoría
function abrirCategoria(cat) {
  const filtrados = libros.filter(l => l.categoria === cat);

  document.getElementById('booksCatName').textContent = cat;
  document.getElementById('booksCount').textContent = filtrados.length > 0
    ? filtrados.length + (filtrados.length === 1 ? ' libro' : ' libros')
    : 'Próximamente';

  const grid = document.getElementById('booksInner');
  if (filtrados.length === 0) {
    grid.innerHTML = `<div class="empty-msg">Próximamente libros<br>en esta colección ✦</div>`;
  } else {
    grid.innerHTML = filtrados.map((l, i) => `
      <div class="book-card" style="animation-delay:${i*0.07}s">
        <div class="book-cover-wrap" style="${l.imgHeight?'padding-top:'+l.imgHeight:''}">
          <img src="${l.imagen}" alt="${l.titulo}" style="${l.imgPosition?'object-position:'+l.imgPosition+';':''}${l.imgContain?'object-fit:contain;background:#1a0f05;':''}" onerror="this.style.display='none'">
          <div class="book-cover-placeholder"></div>
        </div>
        <div class="book-info">
          <div class="book-title">${l.titulo}</div>
          <div class="book-author">${l.autor}</div>
          ${l.url? `<a class="book-btn" href="${l.url}" target="_blank">Abrir libro</a>` : `<span class="book-btn" style="opacity:0.4;cursor:default;">Próximamente</span>`}
        </div>
      </div>
    `).join('');
  }

  panelCats.classList.add('slide-out');
  panelBooks.classList.add('slide-in');
  panelBooks.scrollTop = 0;
}

// Volver al inicio
function volverInicio() {
  panelBooks.classList.remove('slide-in');
  panelCats.classList.remove('slide-out');
  window.scrollTo(0,0);
}

// ══════════════════════
// GENERAR BOTONES DE CATEGORÍAS AUTOMÁTICOS
// ══════════════════════
function generarCategorias() {
  const categorias = [...new Set(libros.map(l => l.categoria))];
  panelCats.innerHTML = categorias.map(cat => `
    <div class="cat-card" onclick="abrirCategoria('${cat}')">
      ${cat}
    </div>
  `).join('');
}

// Llamar al inicio
generarCategorias();

// ══════════════════════
// PARTÍCULAS
// ══════════════════════
const cont = document.getElementById('particles');
for (let i=0; i<30; i++){
  const p = document.createElement('div');
  p.className='particle';
  p.style.cssText = `left:${Math.random()*100}%;animation-duration:${8+Math.random()*15}s;animation-delay:${Math.random()*10}s;width:${1+Math.random()*2}px;height:${1+Math.random()*2}px;`;
  cont.appendChild(p);
}

// ══════════════════════
// MÚSICA
// ══════════════════════
const audio = document.getElementById('musicaFondo');
audio.volume = 0.5;

function iniciarMusica(){
  audio.play();
  ['inicioMusica','inicioMusicaM'].forEach(id=>document.getElementById(id).style.display='none');
  ['botonMusica','botonMusicaM'].forEach(id=>document.getElementById(id).style.display='flex');
  ['volumenControl','volumenM'].forEach(id=>document.getElementById(id).style.display='block');
}

function toggleAudio(){
  const playing = !audio.paused;
  playing ? audio.pause() : audio.play();
  ['botonMusica','botonMusicaM'].forEach(id=>document.getElementById(id).textContent = playing?'🔈':'🔊');
}

function cambiarVolumen(){
  const isMobile = window.innerWidth <= 600;
  audio.volume = document.getElementById(isMobile?'volumenM':'volumenControl').value;
}
