agrinho<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agronegócio no Brasil - Soluções Sustentáveis</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Cabeçalho com Banner -->
    <header>
        <div class="banner">
            <h1>Agronegócio no Brasil: Inovação e Sustentabilidade</h1>
            <p>Descubra como tecnologia e boas práticas podem transformar o campo</p>
        </div>
    </header>

    <!-- Menu de Navegação -->
    <nav>
        <a href="#tecnologia"><i class="fas fa-robot"></i> Tecnologia</a>
        <a href="#sustentabilidade"><i class="fas fa-leaf"></i> Sustentabilidade</a>
        <a href="#logistica"><i class="fas fa-truck"></i> Logística</a>
        <a href="#politicas"><i class="fas fa-landmark"></i> Políticas</a>
        <a href="#depoimentos"><i class="fas fa-comments"></i> Depoimentos</a>
        <a href="#contato"><i class="fas fa-envelope"></i> Contato</a>
    </nav>

    <!-- Seção de Tecnologia -->
    <section id="tecnologia" class="section-with-image">
        <div class="content">
            <h2><i class="fas fa-robot"></i> Tecnologia no Campo</h2>
            <img src="https://images.unsplash.com/photo-1581093450025-7d0169044c8d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Drone agrícola">
            <p>O uso de <strong>drones, IoT e inteligência artificial</strong> está revolucionando a agricultura:</p>
            <ul>
                <li>Monitoramento preciso de plantações</li>
                <li>Controle automatizado de irrigação</li>
                <li>Previsão de safras com 95% de acerto</li>
            </ul>
            <div class="video-container">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/5T5IQznAxd4" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
    </section>

    <!-- Seção de Sustentabilidade -->
    <section id="sustentabilidade" class="section-with-image">
        <div class="content">
            <h2><i class="fas fa-leaf"></i> Sustentabilidade</h2>
            <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Agricultura sustentável">
            <p>Práticas que preservam o meio ambiente e aumentam a produtividade:</p>
            <ul>
                <li>Agrofloresta: combinando cultivos e floresta</li>
                <li>Uso de biofertilizantes</li>
                <li>Energia solar em propriedades rurais</li>
            </ul>
        </div>
    </section>

    <!-- Depoimentos -->
    <section id="depoimentos" class="testimonials">
        <h2><i class="fas fa-comments"></i> O que dizem os especialistas</h2>
        <div class="testimonial-grid">
            <div class="testimonial-card">
                <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Maria Silva">
                <p>"A tecnologia está reduzindo nossos custos em 30%."</p>
                <span class="name">Maria Silva, Produtora de Soja</span>
            </div>
            <div class="testimonial-card">
                <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Carlos Mendes">
                <p>"Precisamos de mais investimento em infraestrutura."</p>
                <span class="name">Carlos Mendes, Engenheiro Agrônomo</span>
            </div>
        </div>
    </section>

    <!-- Formulário de Contato -->
    <section id="contato" class="contact-form">
        <h2><i class="fas fa-envelope"></i> Envie sua sugestão</h2>
        <form id="contactForm">
            <input type="text" placeholder="Seu nome" required>
            <input type="email" placeholder="Seu e-mail" required>
            <textarea placeholder="Sua mensagem ou ideia para melhorar o agronegócio..." required></textarea>
            <button type="submit">Enviar <i class="fas fa-paper-plane"></i></button>
        </form>
    </section>

    <footer>
        <p>© 2024 Agronegócio Brasil | 
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Estilos Gerais */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
}

header {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), 
                url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1350&q=80');
    background-size: cover;
    color: white;
    text-align: center;
    padding: 4rem 0;
}

.banner h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

/* Navegação */
nav {
    background: #2E7D32;
    display: flex;
    justify-content: center;
    padding: 1rem;
    flex-wrap: wrap;
}

nav a {
    color: white;
    margin: 0 1.5rem;
    text-decoration: none;
    font-weight: bold;
    display: flex;
    align-items: center;
}

nav a i {
    margin-right: 8px;
}

/* Seções */
section {
    padding: 3rem 1rem;
    margin: 0 auto;
    max-width: 1200px;
}

.section-with-image img {
    width: 100%;
    max-width: 800px;
    border-radius: 8px;
    margin: 1rem 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.video-container {
    position: relative;
    padding-bottom: 56.25%;
    margin: 2rem 0;
}

.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border-radius: 8px;
}

/* Depoimentos */
.testimonials {
    background: #E8F5E9;
    text-align: center;
}

.testimonial-grid {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 2rem;
    margin-top: 2rem;
}

.testimonial-card {
    background: white;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    max-width: 300px;
}

.testimonial-card img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
}

.name {
    font-weight: bold;
    color: #2E7D32;
    display: block;
    margin-top: 1rem;
}

/* Formulário */
.contact-form {
    background: #2E7D32;
    color: white;
}

.contact-form form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.contact-form input, 
.contact-form textarea {
    padding: 0.8rem;
    border: none;
    border-radius: 4px;
    font-size: 1rem;
}

.contact-form textarea {
    height: 150px;
    resize: vertical;
}

.contact-form button {
    background: #FFC107;
    color: #333;
    border: none;
    padding: 1rem;
    font-weight: bold;
    cursor: pointer;
    border-radius: 4px;
    transition: background 0.3s;
}

.contact-form button:hover {
    background: #FFD54F;
}

/* Rodapé */
footer {
    text-align: center;
    padding: 2rem;
    background: #1B5E20;
    color: white;
}

footer a {
    color: white;
    margin: 0 10px;
    font-size: 1.2rem;
}

/* Responsividade */
@media (max-width: 768px) {
    nav {
        flex-direction: column;
        align-items: center;
        gap: 0.5rem;
    }
    
    .banner h1 {
        font-size: 1.8rem;
    }
}
// Efeito de rolagem suave
document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const targetId = this.getAttribute('href');
        document.querySelector(targetId).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Validação do formulário
document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Obrigado pela sua mensagem! Entraremos em contato em breve.');
    this.reset();
});

https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css

https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1350&q=80

