# agrinho.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agro Forte, Futuro Sustentável - Projeto Agrinho</title>
    <style>
        :root {
            --primary-color: #1b4332;
            --secondary-color: #2d6a4f;
            --accent-color: #52b788;
            --light-bg: #f4f9f4;
            --text-dark: #2d3748;
            --text-light: #ffffff;
            --card-shadow: 0 4px 6px rgba(0,0,0,0.05), 0 1px 3px rgba(0,0,0,0.1);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: #ffffff;
        }

        /* Top Accent Bar */
        .top-bar {
            background-color: var(--primary-color);
            height: 4px;
            width: 100%;
        }

        /* Hero Section */
        header {
            background: linear-gradient(rgba(27, 67, 50, 0.85), rgba(45, 106, 79, 0.9)), url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            color: var(--text-light);
            padding: 100px 20px;
            text-align: center;
        }

        .header-container {
            max-width: 1000px;
            margin: 0 auto;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        header p {
            font-size: 1.3rem;
            max-width: 700px;
            margin: 0 auto 30px auto;
            opacity: 0.9;
        }

        .badge {
            display: inline-block;
            background-color: var(--accent-color);
            color: var(--primary-color);
            padding: 6px 15px;
            border-radius: 20px;
            font-weight: 600;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 15px;
        }

        /* Main Content Container */
        main {
            max-width: 1100px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        /* Intro Section */
        .intro {
            text-align: center;
            max-width: 800px;
            margin: 0 auto 60px auto;
        }

        .intro h2 {
            font-size: 2.2rem;
            color: var(--primary-color);
            margin-bottom: 20px;
        }

        .intro p {
            font-size: 1.15rem;
            color: #4a5568;
        }

        /* Pillars Grid */
        .pillars-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }

        .pillar-card {
            background-color: var(--light-bg);
            border-left: 5px solid var(--accent-color);
            padding: 30px;
            border-radius: 4px;
            box-shadow: var(--card-shadow);
        }

        .pillar-card h3 {
            color: var(--secondary-color);
            font-size: 1.4rem;
            margin-bottom: 15px;
        }

        .pillar-card p {
            color: #4a5568;
            font-size: 1rem;
        }

        /* Deep Dive Sections */
        .detail-section {
            margin-bottom: 60px;
            padding: 40px 0;
            border-top: 1px solid #e2e8f0;
        }

        .detail-section h2 {
            color: var(--primary-color);
            font-size: 2rem;
            margin-bottom: 25px;
        }

        .tech-list {
            list-style-type: none;
        }

        .tech-list li {
            position: relative;
            padding-left: 30px;
            margin-bottom: 15px;
            font-size: 1.1rem;
        }

        .tech-list li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: var(--accent-color);
            font-weight: bold;
            font-size: 1.2rem;
        }

        /* Info Block */
        .info-block {
            background-color: #e9f5ed;
            border: 1px solid #c2e3ce;
            padding: 30px;
            border-radius: 6px;
            margin-top: 30px;
        }

        .info-block h4 {
            color: var(--primary-color);
            margin-bottom: 10px;
            font-size: 1.2rem;
        }

        /* Footer */
        footer {
            background-color: #1a202c;
            color: #a0aec0;
            padding: 40px 20px;
            font-size: 0.95rem;
            border-top: 1px solid #2d3748;
        }

        .footer-container {
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .footer-left p {
            margin-bottom: 5px;
        }

        /* Estilo Discreto para os dados da Aluna */
        .meta-stamp {
            font-size: 0.78rem;
            color: #4a5568; /* Contraste baixo no fundo escuro */
            letter-spacing: 0.5px;
            text-transform: uppercase;
            text-align: right;
            opacity: 0.6;
            transition: opacity 0.3s;
        }
        
        .meta-stamp:hover {
            opacity: 0.9;
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2.2rem; }
            .footer-container { flex-direction: column; text-align: center; }
            .meta-stamp { text-align: center; }
        }
    </style>
</head>
<body>

    <div class="top-bar"></div>

    <header>
        <div class="header-container">
            <span class="badge">Projeto Agrinho 2026</span>
            <h1>Agro Forte, Futuro Sustentável</h1>
            <p>O equilíbrio essencial entre a eficiência tecnológica na produção de alimentos e a preservação rigorosa do meio ambiente.</p>
        </div>
    </header>

    <main>
        <section class="intro">
            <h2>Alimentando o Mundo, Protegendo o Planeta</h2>
            <p>O agronegócio moderno enfrenta seu maior desafio histórico: aumentar a produtividade para suprir a demanda global enquanto reduz drasticamente sua pegada ecológica. A resposta para essa equação não está no retrocesso, mas na inovação e na harmonia com os ciclos naturais.</p>
        </section>

        <div class="pillars-grid">
            <div class="pillar-card">
                <h3>Conservação do Solo</h3>
                <p>Uso de práticas como o Plantio Direto e a rotação de culturas para evitar a erosão, manter os nutrientes da terra e potencializar o sequestro de carbono orgânico.</p>
            </div>
            <div class="pillar-card">
                <h3>Eficiência Hídrica</h3>
                <p>Implementação de sistemas de irrigação inteligente por gotejamento e sensores subterrâneos, reduzindo o desperdício de água e protegendo os mananciais hídricos.</p>
            </div>
            <div class="pillar-card">
                <h3>Agroecologia Integrada</h3>
                <p>Sistemas como a Integração Lavoura-Pecuária-Floresta (ILPF) promovem a biodiversidade, otimizam o uso do espaço e geram um ecossistema agrícola resiliente.</p>
            </div>
        </div>

        <section class="detail-section">
            <h2>Tecnologia e Sustentabilidade no Campo</h2>
            <p style="margin-bottom: 25px; font-size: 1.1rem;">A transformação digital no campo — ou Agro 4.0 — desempenha um papel crucial na sustentabilidade ao permitir que cada recurso seja aplicado com precisão milimétrica.</p>
            
            <ul class="tech-list">
                <li><strong>Drones e Sensoriamento Remoto:</strong> Mapeamento detalhado das lavouras para identificação precoce de pragas, permitindo o uso direcionado de defensivos apenas onde é estritamente necessário.</li>
                <li><strong>Tratores Autônomos e GPS de Alta Precisão:</strong> Otimização das rotas de plantio e colheita para reduzir o consumo de combustíveis fósseis e mitigar a compactação do solo.</li>
                <li><strong>Manejo Integrado de Pragas (MIP):</strong> Estímulo ao controle biológico natural através da preservação de insetos benéficos, reduzindo a dependência de insumos químicos externos.</li>
            </ul>

            <div class="info-block">
                <h4>O Papel do Código Florestal</h4>
                <p>A manutenção das Áreas de Preservação Permanente (APPs) e das Reservas Legais nas propriedades rurais brasileiras não é um entrave, mas um ativo de segurança biológica que garante serviços ecossistêmicos fundamentais, como a polinização e a regulação climática local.</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-container">
            <div class="footer-left">
                <p><strong>Agro Forte, Futuro Sustentável</strong></p>
                <p>Website educacional construído para disseminação de práticas de manejo sustentável.</p>
            </div>
            <div class="footer-right">
                <div class="meta-stamp">
                    Ref: BW-2B / Col. CCM JXXIII<br>
                    Estudos e Análises - 2026
                </div>
            </div>
        </div>
    </footer>

</body>
</html>
