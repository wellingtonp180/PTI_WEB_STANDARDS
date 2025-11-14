<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ConnectFit | Seu Personal Trainer em Casa</title>
    <!-- Link para o arquivo de estilo --><link rel="stylesheet" href="style.css">
    <!-- Fonte sugerida: Inter do Google Fonts para estética --><link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700;900&display=swap" rel="stylesheet">
</head>
<body>
    <!-- #1 HERO SECTION: PROPOSTA DE VALOR + CTA Imediato --><header id="inicio" class="hero-section" role="banner">
        <div class="hero-content">
            <!-- SUA LOGO: Adicionada no topo da seção, usando o link da imagem que você enviou --><img src="LOGOMARCA ConnectFit.png" alt="Logo da ConnectFit: fitness em casa com conexão" class="logo-hero">

            <!-- H1 deve ser o principal foco e único na página --><h1>Conquiste Seu Corpo Ideal <strong>Sem Sair de Casa!</strong></h1>
            <p class="subtitle">Treinos personalizados e acompanhamento 1-a-1, adaptados ao seu tempo e espaço.</p>
            
            <!-- CTA PRINCIPAL: AGORA COM LINK DIRETO PARA O WHATSAPP --><a 
                href="https://wa.me/5511963279727?text=Ol%C3%A1%2C%20gostaria%20de%20agendar%20minha%20avalia%C3%A7%C3%A3o%20gratuita%20com%20o%20ConnectFit." 
                target="_blank" 
                class="cta-button" 
                role="button" 
                aria-label="Agende sua avaliação gratuita e comece a treinar via WhatsApp"
            >
                AGENDE SUA AVALIAÇÃO GRÁTIS VIA WHATSAPP!
            </a>
        </div>
    </header>

    <!-- Conteúdo principal do site --><main>
        <!-- #2 O PROBLEMA / A SOLUÇÃO: Conexão e Credibilidade --><section class="solution-section" aria-labelledby="solucao-titulo">
            <h2 id="solucao-titulo">Cansado de Treinar Sozinho e Sem Resultados?</h2>
            <div class="solution-grid">
                <div class="problem">
                    <h3>❌ Os Desafios Comuns</h3>
                    <!-- Lista de dores do cliente --><ul>
                        <li>Falta de motivação e rotina.</li>
                        <li>Não sabe quais exercícios são eficazes em casa.</li>
                        <li>Medo de se lesionar sem orientação profissional.</li>
                    </ul>
                </div>
                <div class="solution">
                    <h3>✅ Nossa Solução ConnectFit</h3>
                    <!-- Lista de benefícios diretos --><ul>
                        <li>Plano 100% adaptado ao seu espaço e objetivos.</li>
                        <li>Aulas ao vivo ou gravadas com Personal Certificado.</li>
                        <li>Resultados visíveis e mensuráveis em 8 semanas.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- #3 PROVA SOCIAL / METODOLOGIA --><section class="proof-section" aria-labelledby="prova-titulo">
            <h2 id="prova-titulo">Quem Já Conquistou o Home Fitness?</h2>
            <div class="testimonials-flex">
                <!-- Testemunho 1 (Card) --><figure class="testimonial-card">
                    <blockquote>
                        "Graças ao ConnectFit, perdi 5kg em 2 meses, treinando apenas 3x por semana na sala!"
                    </blockquote>
                    <figcaption>— Ana L., Executiva.</figcaption>
                </figure>
                <!-- Testemunho 2 (Card) --><figure class="testimonial-card">
                    <blockquote>
                        "O Personal adaptou perfeitamente os treinos aos meus horários. É como ter uma academia particular!"
                    </blockquote>
                    <figcaption>— João C., Autônomo.</figcaption>
                </figure>
            </div>
            <!-- CTA SECUNDÁRIO: COM LINK DIRETO PARA O WHATSAPP --><a 
                href="https://wa.me/5511963279727?text=Ol%C3%A1%2C%20gostaria%20de%20agendar%20minha%20avalia%C3%A7%C3%A3o%20gratuita%20com%20o%20ConnectFit." 
                target="_blank" 
                class="cta-button secondary-cta" 
                role="button"
            >
                SIM! QUERO MEU TREINO PERSONALIZADO!
            </a>
        </section>

        <!-- #4 SOBRE O PROFISSIONAL: Autoridade e Conexão --><section class="about-section" aria-labelledby="sobre-titulo">
            <h2 id="sobre-titulo">Conheça seu Personal Homefit, o Especialista ConnectFit</h2>
            <div class="about-content">
                <!-- Imagem do profissional com descrição acessível --><figure class="profile-photo">
                    <img src="https://placehold.co/180x180/ff6b6b/ffffff?text=Personal" alt="Foto profissional do Personal Trainer, [Seu Nome].">
                </figure>
                <div class="about-text">
                    <h3>Especialista em Treinamento Funcional Doméstico</h3>
                    <p>Meu objetivo é provar que você não precisa de uma academia cheia ou equipamentos caros para ter o corpo que sempre sonhou. Transforme seu tempo e seu espaço em resultados reais e duradouros, com segurança e eficiência.</p>
                    <p><strong>Qualificações:</strong> CREF [Número], Especialista em Treinamento de Força e Performance.</p>
                </div>
            </div>
        </section>

        <!-- #5 FORMULÁRIO / CTA FINAL: Conversão --><section id="formulario" class="form-section" aria-labelledby="form-titulo">
            <h2 id="form-titulo">Preencha o formulário e receba sua avaliação grátis, ou nos chame no WhatsApp!</h2>
            <!-- Formulário com labels explícitas para acessibilidade e campos simples --><form class="contact-form">
                <label for="nome">Seu Nome Completo:</label>
                <input type="text" id="nome" placeholder="Nome" required>
                
                <label for="email">Seu Melhor E-mail:</label>
                <input type="email" id="email" placeholder="email@exemplo.com" required>
                
                <label for="whatsapp">WhatsApp (DDD + Número):</label>
                <input type="tel" id="whatsapp" placeholder="(99) 99999-9999" required>
                
                <!-- Botão de submissão para capturar o lead --><button type="submit" class="cta-button final-cta">Quero Receber Minha Avaliação!</button>
                <small aria-live="polite">Garantimos a privacidade de seus dados. Você será contatado em até 24h.</small>
                
                <!-- Link de contato de busca (WhatsApp) repetido para fácil acesso --><p class="whatsapp-contact-link">
                    Ou clique aqui para falar direto no 
                    <a 
                        href="https://wa.me/5511963279727?text=Ol%C3%A1%2C%20gostaria%20de%20agendar%20minha%20avalia%C3%A7%C3%A3o%20gratuita%20com%20o%20ConnectFit." 
                        target="_blank" 
                        title="Fale no WhatsApp"
                    >
                        WhatsApp!
                    </a>
                </p>
            </form>
        </section>
    </main>

    <!-- Rodapé --><footer role="contentinfo">
        <p>&copy; 2025 ConnectFit. Todos os direitos reservados. | Contato WhatsApp: +55 (11) 96327-9727 | <a href="#inicio">Voltar ao topo</a></p>
    </footer>
</body>
</html>

#
/* ---------------------------------- */
/* CORE & ACESSIBILIDADE */
/* ---------------------------------- */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    /* Variáveis para fácil manutenção de cores e espaçamentos */
    --primary-color: #ff6b6b; /* Vermelho: CTA e Destaque */
    --secondary-color: #4cd137; /* Verde: CTA de Conversão */
    --dark-bg: #333;
    --light-bg: #f4f4f4;
    --text-color: #333;
    --font-family: 'Arial', sans-serif;
    --section-padding: 60px 5%;
}

body {
    font-family: var(--font-family);
    line-height: 1.6;
    color: var(--text-color);
}

/* Foco Visível para Acessibilidade (Tabulação) */
a:focus, button:focus, input:focus {
    outline: 2px solid var(--primary-color);
    outline-offset: 3px;
}

/* ---------------------------------- */
/* CTA BOTÃO */
/* ---------------------------------- */
.cta-button {
    display: inline-block;
    background-color: var(--primary-color);
    color: white;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 8px;
    text-transform: uppercase;
    transition: background-color 0.3s, transform 0.2s;
    margin-top: 20px;
    border: none; /* Para usar em buttons */
    cursor: pointer;
}

.cta-button:hover {
    background-color: #ee5253; /* Tom mais escuro */
    transform: translateY(-2px);
}

.final-cta {
    background-color: var(--secondary-color);
}
.final-cta:hover {
    background-color: #449c32; 
}


/* ---------------------------------- */
/* #1 HERO SECTION (FLEXBOX) */
/* ---------------------------------- */
.hero-section {
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('') center/cover no-repeat;
    color: white;
    min-height: 85vh; 
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
}

.logo-hero {
    max-width: 200px;
    height: auto;
    margin-bottom: 20px;
}

.hero-content h1 {
    font-size: clamp(2rem, 5vw, 3.5rem); /* Tamanho de fonte responsivo */
    margin-bottom: 10px;
}

.hero-content .subtitle {
    font-size: clamp(1rem, 2vw, 1.4rem);
    font-weight: 300;
}

/* ---------------------------------- */
/* SEÇÕES GERAIS */
/* ---------------------------------- */
section {
    padding: var(--section-padding);
    text-align: center;
}

section h2 {
    margin-bottom: 40px;
    font-size: 2rem;
}

/* ---------------------------------- */
/* #2 SOLUÇÃO (FLEXBOX RESPONSIVO) */
/* ---------------------------------- */
.solution-grid {
    display: flex;
    gap: 30px;
    justify-content: center;
    text-align: left;
}

.problem, .solution {
    flex: 1; /* Distribuição igual do espaço */
    max-width: 450px;
    padding: 30px;
    border: 1px solid #ddd;
    border-radius: 10px;
    transition: box-shadow 0.3s;
}

.problem:hover, .solution:hover {
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

/* ---------------------------------- */
/* #3 PROVA SOCIAL (FLEXBOX) */
/* ---------------------------------- */
.proof-section {
    background-color: var(--light-bg);
}

.testimonials-flex {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-bottom: 40px;
    flex-wrap: wrap; /* Permite quebrar linha em telas pequenas */
}

.testimonial-card {
    flex-basis: calc(50% - 15px); /* Ocupa metade, descontando o gap */
    max-width: 450px;
    background: white;
    padding: 25px;
    border-left: 5px solid var(--primary-color);
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

/* ---------------------------------- */
/* #4 SOBRE O PROFISSIONAL (FLEXBOX) */
/* ---------------------------------- */
.about-content {
    display: flex;
    gap: 40px;
    text-align: left;
    align-items: center;
    max-width: 900px;
    margin: 0 auto;
}

.profile-photo img {
    width: 180px; 
    height: 180px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid var(--primary-color);
    flex-shrink: 0;
}

/* ---------------------------------- */
/* #5 FORMULÁRIO (FLEXBOX) */
/* ---------------------------------- */
.form-section {
    background-color: var(--dark-bg);
    color: white;
}

.contact-form {
    max-width: 500px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
    text-align: left; /* Alinha labels e inputs à esquerda */
}

.contact-form label {
    font-weight: bold;
    margin-top: 10px;
}

.contact-form input {
    padding: 15px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
}

/* ---------------------------------- */
/* RESPONSIVIDADE (MOBILE FIRST) */
/* ---------------------------------- */
@media (max-width: 768px) {
    
    /* Reverte layouts Flex para empilhamento vertical (Mobile First) */
    .solution-grid,
    .testimonials-flex,
    .about-content {
        flex-direction: column;
        gap: 20px;
    }
    
    .problem, .solution, .testimonial-card {
        max-width: 100%; /* Ocupa largura total no mobile */
    }

    .about-content {
        text-align: center; /* Centraliza o conteúdo no mobile */
    }
    
    .profile-photo {
        margin: 0 auto; /* Centraliza a foto */
    }
}

/* FOOTER */
footer {
    background-color: #222;
    color: #bbb;
    padding: 15px;
    text-align: center;
    font-size: 0.8rem;
}
