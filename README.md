<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Supremo Ferramentas | Qualidade Industrial</title>
    <meta name="description" content="Supremo Ferramentas - Ferramentas industriais de alta qualidade e precisão. Baixe nosso catálogo e entre em contato para orçamentos.">
    <meta name="keywords" content="ferramentas industriais, catálogo ferramentas, ferramentas profissionais, Muriaé MG, construção civil, maquinário industrial, ferramentas de precisão, baixar catálogo">
    <meta name="author" content="Supremo Ferramentas">
    <meta property="og:title" content="Supremo Ferramentas">
    <meta property="og:description" content="Ferramentas industriais de alta qualidade e precisão. Baixe nosso catálogo completo!">
    <meta property="og:image" content="https://seusite.com/logo-azul.png">
    <meta property="og:url" content="https://seusite.com">
    <meta property="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="robots" content="index, follow">
    
    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="https://img.icons8.com/color/96/tools.png">
    
    <style>
        /* Otimização para preferência de movimento reduzido */
        @media (prefers-reduced-motion: reduce) {
            * {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
            }
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --primary-blue: #1a365d;
            --accent-blue: #2d5aa0;
            --light-blue: #4299e1;
            --dark-gray: #2d3748;
            --medium-gray: #718096;
            --light-gray: #f7fafc;
            --gold-accent: #d4af37;
            --whatsapp-green: #25D366;
            --instagram-purple: #E4405F;
            --catalog-orange: #FF6B35;
        }
        
        body {
            font-family: 'Inter', 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }
        
        /* Efeitos de partículas no background */
        .particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            opacity: 0.3;
            pointer-events: none;
        }
        
        .particle {
            position: absolute;
            background: linear-gradient(45deg, var(--light-blue), var(--gold-accent));
            border-radius: 50%;
            opacity: 0.3;
        }
        
        @keyframes float {
            0% { transform: translate(0, 0) rotate(0deg); }
            100% { transform: translate(var(--tx, 50px), var(--ty, 50px)) rotate(360deg); }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .container {
            max-width: 1200px;
            width: 100%;
            position: relative;
            z-index: 1;
        }
        
        .main-card {
            background: rgba(15, 23, 42, 0.85);
            backdrop-filter: blur(20px);
            border-radius: 24px;
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 
                0 20px 40px rgba(0, 0, 0, 0.4),
                0 0 0 1px rgba(255, 255, 255, 0.03),
                inset 0 1px 0 rgba(255, 255, 255, 0.05);
            padding: 60px 40px;
            position: relative;
            overflow: hidden;
        }
        
        /* Elemento decorativo do canto */
        .corner-decoration {
            position: absolute;
            top: 0;
            right: 0;
            width: 200px;
            height: 200px;
            background: linear-gradient(135deg, transparent 50%, var(--accent-blue) 50%);
            clip-path: polygon(100% 0, 0 0, 100% 100%);
            opacity: 0.1;
        }
        
        .logo-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 50px;
            position: relative;
        }
        
        .logo-frame {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary-blue), var(--accent-blue));
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 40px;
            position: relative;
            box-shadow: 
                0 10px 30px rgba(26, 54, 93, 0.3),
                0 0 0 8px rgba(255, 255, 255, 0.03),
                inset 0 0 20px rgba(255, 255, 255, 0.05);
            border: 2px solid rgba(255, 255, 255, 0.1);
            animation: glow 3s ease-in-out infinite;
        }
        
        .logo-frame::after {
            content: '';
            position: absolute;
            inset: -4px;
            background: linear-gradient(135deg, var(--light-blue), var(--gold-accent));
            border-radius: 50%;
            z-index: -1;
            opacity: 0.5;
            filter: blur(10px);
        }
        
        .logo {
            width: 140px;
            height: 140px;
            object-fit: contain;
            filter: brightness(1.2) drop-shadow(0 5px 15px rgba(0, 0, 0, 0.3));
        }
        
        .brand-name {
            text-align: center;
            margin-bottom: 10px;
        }
        
        .brand-main {
            font-size: 5rem;
            font-weight: 900;
            letter-spacing: 8px;
            background: linear-gradient(to right, #fff, var(--light-blue));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 5px;
            text-transform: uppercase;
            position: relative;
            display: inline-block;
        }
        
        .brand-main::after {
            content: 'SUPREMO';
            position: absolute;
            top: 2px;
            left: 2px;
            background: linear-gradient(to right, var(--gold-accent), var(--light-blue));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            z-index: -1;
            opacity: 0.5;
        }
        
        .brand-subtitle {
            font-size: 2.8rem;
            font-weight: 600;
            color: var(--gold-accent);
            letter-spacing: 3px;
            position: relative;
            padding-top: 15px;
            display: inline-block;
        }
        
        .brand-subtitle::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 120px;
            height: 3px;
            background: linear-gradient(90deg, 
                transparent, 
                var(--gold-accent), 
                transparent);
        }
        
        .tagline {
            text-align: center;
            margin-top: 30px;
            font-size: 1.4rem;
            color: rgba(255, 255, 255, 0.8);
            font-weight: 300;
            letter-spacing: 2px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.6;
        }
        
        /* SEÇÃO DE CATÁLOGO */
        .catalog-section {
            margin: 50px 0;
            padding: 50px;
            background: linear-gradient(135deg, rgba(26, 54, 93, 0.3), rgba(212, 175, 55, 0.1));
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .catalog-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(255,255,255,0.02)"/></svg>');
            pointer-events: none;
        }
        
        .catalog-title {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: var(--gold-accent);
            position: relative;
            display: inline-block;
        }
        
        .catalog-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 3px;
            background: linear-gradient(90deg, 
                transparent, 
                var(--catalog-orange), 
                transparent);
        }
        
        .catalog-description {
            font-size: 1.2rem;
            color: rgba(255, 255, 255, 0.8);
            max-width: 700px;
            margin: 0 auto 40px;
            line-height: 1.6;
        }
        
        .catalog-features {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            margin-bottom: 40px;
        }
        
        .catalog-feature {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 200px;
        }
        
        .catalog-feature-icon {
            font-size: 2.5rem;
            color: var(--catalog-orange);
            margin-bottom: 15px;
            background: rgba(255, 255, 255, 0.1);
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 2px solid rgba(255, 255, 255, 0.2);
        }
        
        .catalog-feature p {
            font-size: 0.95rem;
            color: rgba(255, 255, 255, 0.9);
            text-align: center;
        }
        
        .download-catalog-btn {
            display: inline-flex;
            align-items: center;
            gap: 15px;
            padding: 20px 50px;
            background: linear-gradient(135deg, var(--catalog-orange), #FF8B35);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.3rem;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            box-shadow: 0 10px 30px rgba(255, 107, 53, 0.3);
            animation: pulse 2s ease-in-out infinite;
            position: relative;
            overflow: hidden;
        }
        
        .download-catalog-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.5s ease;
        }
        
        .download-catalog-btn:hover::before {
            left: 100%;
        }
        
        .download-catalog-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(255, 107, 53, 0.5);
        }
        
        .download-catalog-btn:active {
            transform: translateY(-2px);
        }
        
        .download-info {
            margin-top: 25px;
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.6);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .file-size {
            display: inline-block;
            background: rgba(255, 255, 255, 0.1);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.85rem;
            margin-top: 15px;
        }
        
        /* Modal de confirmação de download */
        .modal-overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            z-index: 1000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        
        .modal-content {
            background: linear-gradient(135deg, #1e293b, #0f172a);
            border-radius: 20px;
            padding: 40px;
            max-width: 500px;
            width: 100%;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
            position: relative;
            animation: modalAppear 0.3s ease-out;
        }
        
        @keyframes modalAppear {
            from {
                opacity: 0;
                transform: translateY(-20px) scale(0.95);
            }
            to {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
        }
        
        .modal-close {
            position: absolute;
            top: 20px;
            right: 20px;
            background: none;
            border: none;
            color: rgba(255, 255, 255, 0.6);
            font-size: 1.5rem;
            cursor: pointer;
            transition: color 0.3s ease;
        }
        
        .modal-close:hover {
            color: var(--catalog-orange);
        }
        
        .modal-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--gold-accent);
            text-align: center;
        }
        
        .modal-text {
            color: rgba(255, 255, 255, 0.8);
            margin-bottom: 25px;
            line-height: 1.6;
            text-align: center;
        }
        
        .modal-actions {
            display: flex;
            gap: 15px;
            justify-content: center;
        }
        
        .modal-btn {
            padding: 12px 30px;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            border: none;
            font-size: 1rem;
            min-width: 120px;
        }
        
        .modal-btn.download {
            background: var(--catalog-orange);
            color: white;
        }
        
        .modal-btn.cancel {
            background: rgba(255, 255, 255, 0.1);
            color: white;
        }
        
        .modal-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        /* SEÇÃO DE CONTATOS */
        .contacts-section {
            margin: 50px 0;
            padding: 40px;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .contacts-title {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 40px;
            color: var(--gold-accent);
            position: relative;
            display: inline-block;
            width: 100%;
        }
        
        .contacts-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background: linear-gradient(90deg, 
                transparent, 
                var(--gold-accent), 
                transparent);
        }
        
        .contact-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        
        .contact-card {
            background: rgba(255, 255, 255, 0.02);
            border-radius: 16px;
            padding: 30px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .contact-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent-blue);
            box-shadow: 0 15px 30px rgba(26, 54, 93, 0.2);
        }
        
        .contact-card.whatsapp {
            border-top: 4px solid var(--whatsapp-green);
        }
        
        .contact-card.instagram {
            border-top: 4px solid var(--instagram-purple);
        }
        
        .contact-card.phone {
            border-top: 4px solid var(--light-blue);
        }
        
        .contact-icon {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        
        .contact-card.whatsapp .contact-icon {
            color: var(--whatsapp-green);
        }
        
        .contact-card.instagram .contact-icon {
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .contact-card.phone .contact-icon {
            color: var(--light-blue);
        }
        
        .contact-info h3 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: #fff;
        }
        
        .phone-number {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--gold-accent);
            margin: 15px 0;
            direction: ltr;
            unicode-bidi: bidi-override;
            padding: 10px;
            display: inline-block;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .phone-number:hover {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 8px;
        }
        
        .contact-link {
            display: inline-block;
            padding: 12px 30px;
            background: var(--whatsapp-green);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            margin-top: 15px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            min-height: 44px;
            line-height: 1.4;
        }
        
        .contact-link.instagram {
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
        }
        
        .contact-link.phone {
            background: var(--light-blue);
        }
        
        .contact-link:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        .whatsapp-info {
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.6);
            margin-top: 10px;
            font-style: italic;
        }
        
        .instagram-username {
            font-size: 1.5rem;
            font-weight: 600;
            color: white;
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin: 15px 0;
        }
        
        /* SEÇÃO DE LOCALIZAÇÃO */
        .map-section {
            margin: 40px 0;
            padding: 30px;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            text-align: center;
        }
        
        .map-section h3 {
            font-size: 2rem;
            margin-bottom: 25px;
            color: var(--gold-accent);
        }
        
        .map-container {
            border-radius: 16px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        
        .map-container iframe {
            display: block;
        }
        
        /* SEÇÃO DE COMPARTILHAMENTO */
        .share-section {
            text-align: center;
            margin: 40px 0;
            padding: 30px;
            background: rgba(255, 255, 255, 0.02);
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .share-title {
            font-size: 1.8rem;
            margin-bottom: 25px;
            color: var(--gold-accent);
        }
        
        .share-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .share-button {
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            color: white;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            min-height: 44px;
            font-size: 1rem;
        }
        
        .share-button.whatsapp {
            background: var(--whatsapp-green);
        }
        
        .share-button.facebook {
            background: #1877F2;
        }
        
        .share-button.copy-link {
            background: var(--accent-blue);
        }
        
        .share-button.sms {
            background: #34B7F1;
        }
        
        .share-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        .copy-success {
            display: none;
            margin-top: 15px;
            color: var(--gold-accent);
            font-weight: 600;
            font-size: 1rem;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .qr-section {
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 16px;
            display: inline-block;
        }
        
        .qr-code-container {
            padding: 20px;
            background: white;
            border-radius: 12px;
            display: inline-block;
        }
        
        .qr-code-container img {
            display: block;
            max-width: 150px;
            height: auto;
        }
        
        /* FEATURES */
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 60px;
            padding-top: 40px;
            border-top: 1px solid rgba(255, 255, 255, 0.08);
        }
        
        .feature {
            text-align: center;
            padding: 25px;
            border-radius: 16px;
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.3s ease;
        }
        
        .feature:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.05);
            border-color: var(--accent-blue);
            box-shadow: 0 10px 20px rgba(26, 54, 93, 0.2);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: var(--gold-accent);
        }
        
        .feature h3 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: #fff;
        }
        
        .feature p {
            color: rgba(255, 255, 255, 0.7);
            font-size: 0.95rem;
            line-height: 1.5;
        }
        
        .footer {
            margin-top: 50px;
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.08);
            color: rgba(255, 255, 255, 0.6);
            font-size: 0.9rem;
        }
        
        /* Animação de brilho */
        @keyframes glow {
            0%, 100% { opacity: 1; filter: brightness(1); }
            50% { opacity: 0.8; filter: brightness(1.2); }
        }
        
        /* Responsividade */
        @media (max-width: 1024px) {
            .brand-main {
                font-size: 4rem;
                letter-spacing: 6px;
            }
            
            .brand-subtitle {
                font-size: 2.2rem;
            }
            
            .phone-number {
                font-size: 1.6rem;
            }
            
            .catalog-title {
                font-size: 2.2rem;
            }
        }
        
        @media (max-width: 768px) {
            .main-card {
                padding: 40px 25px;
            }
            
            .brand-main {
                font-size: 3rem;
                letter-spacing: 4px;
            }
            
            .brand-subtitle {
                font-size: 1.8rem;
                letter-spacing: 2px;
            }
            
            .logo-frame {
                width: 160px;
                height: 160px;
            }
            
            .logo {
                width: 110px;
                height: 110px;
            }
            
            .tagline {
                font-size: 1.2rem;
            }
            
            .catalog-section {
                padding: 30px 20px;
            }
            
            .catalog-title {
                font-size: 1.8rem;
            }
            
            .catalog-description {
                font-size: 1.1rem;
            }
            
            .download-catalog-btn {
                padding: 18px 40px;
                font-size: 1.2rem;
            }
            
            .contacts-section {
                padding: 30px 20px;
            }
            
            .contacts-title {
                font-size: 1.8rem;
            }
            
            .contact-cards {
                grid-template-columns: 1fr;
            }
            
            .share-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .share-button {
                width: 100%;
                max-width: 300px;
                justify-content: center;
            }
            
            .features {
                grid-template-columns: 1fr;
            }
            
            .map-section {
                padding: 20px 15px;
            }
            
            .map-section h3 {
                font-size: 1.6rem;
            }
            
            .modal-content {
                padding: 30px 20px;
            }
            
            .modal-actions {
                flex-direction: column;
            }
            
            .modal-btn {
                width: 100%;
            }
        }
        
        @media (max-width: 480px) {
            body {
                padding: 15px;
            }
            
            .main-card {
                padding: 30px 20px;
            }
            
            .brand-main {
                font-size: 2.2rem;
                letter-spacing: 3px;
            }
            
            .brand-subtitle {
                font-size: 1.4rem;
            }
            
            .logo-frame {
                width: 130px;
                height: 130px;
            }
            
            .logo {
                width: 90px;
                height: 90px;
            }
            
            .phone-number {
                font-size: 1.4rem;
            }
            
            .contact-link, .share-button {
                padding: 14px 20px;
                font-size: 0.95rem;
            }
            
            .catalog-title {
                font-size: 1.6rem;
            }
            
            .catalog-description {
                font-size: 1rem;
            }
            
            .download-catalog-btn {
                padding: 16px 30px;
                font-size: 1.1rem;
            }
            
            .catalog-features {
                flex-direction: column;
                align-items: center;
            }
            
            .catalog-feature {
                max-width: 100%;
            }
        }
    </style>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <!-- Ícones Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <!-- Schema Markup para SEO -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "LocalBusiness",
        "name": "Supremo Ferramentas",
        "image": "https://seusite.com/logo-azul.png",
        "telephone": "+553235612012",
        "address": {
            "@type": "PostalAddress",
            "streetAddress": "Rua Maxímiano Fraga, 280 - Térreo",
            "addressLocality": "Muriaé",
            "addressRegion": "MG",
            "addressCountry": "BR",
            "postalCode": "36883-191"
        },
        "openingHours": "Mo-Fr 07:30-18:00",
        "priceRange": "$$",
        "url": "https://seusite.com"
    }
    </script>
</head>
<body>
    <!-- Partículas no background -->
    <div class="particles" id="particles"></div>
    
    <!-- Modal de confirmação de download -->
    <div class="modal-overlay" id="downloadModal">
        <div class="modal-content">
            <button class="modal-close" id="modalClose">&times;</button>
            <h3 class="modal-title">Baixar Catálogo</h3>
            <p class="modal-text">
                Você está prestes a baixar o catálogo completo da Supremo Ferramentas em PDF (12 MB). 
                O arquivo contém todas as nossas ferramentas industriais com especificações técnicas detalhadas.
            </p>
            <p class="modal-text">
                Deseja prosseguir com o download?
            </p>
            <div class="modal-actions">
                <button class="modal-btn download" id="confirmDownload">Baixar Agora</button>
                <button class="modal-btn cancel" id="cancelDownload">Cancelar</button>
            </div>
        </div>
    </div>
    
    <main class="container" role="main">
        <div class="main-card" role="region" aria-label="Informações da empresa">
            <div class="corner-decoration"></div>
            
            <div class="logo-section">
                <div class="logo-frame">
                    <img src="logo-azul.png" alt="Supremo Ferramentas" class="logo" onerror="this.onerror=null; this.src='https://img.icons8.com/color/96/tools.png';">
                </div>
                
                <div class="brand-name">
                    <h1 class="brand-main">SUPREMO</h1>
                    <h2 class="brand-subtitle">FERRAMENTAS</h2>
                </div>
                
                <p class="tagline">
                    <i class="fas fa-star" style="color: var(--gold-accent); margin-right: 10px;"></i>
                    Fabricação de alta precisão para profissionais exigentes
                    <i class="fas fa-star" style="color: var(--gold-accent); margin-left: 10px;"></i>
                </p>
            </div>
            
            <!-- SEÇÃO DO CATÁLOGO -->
            <div class="catalog-section">
                <h2 class="catalog-title">Catálogo Completo</h2>
                <p class="catalog-description">
                    Explore nosso catálogo digital com todas as ferramentas industriais disponíveis. 
                    Especificações técnicas detalhadas, fotos em alta resolução e informações completas 
                    para sua escolha.
                </p>
                
                <div class="catalog-features">
                    <div class="catalog-feature">
                        <div class="catalog-feature-icon">
                            <i class="fas fa-file-pdf"></i>
                        </div>
                        <p>Formato PDF de alta qualidade</p>
                    </div>
                    
                    <div class="catalog-feature">
                        <div class="catalog-feature-icon">
                            <i class="fas fa-search"></i>
                        </div>
                        <p>Especificações técnicas detalhadas</p>
                    </div>
                    
                    <div class="catalog-feature">
                        <div class="catalog-feature-icon">
                            <i class="fas fa-images"></i>
                        </div>
                        <p>Fotos em alta resolução</p>
                    </div>
                    
                    <div class="catalog-feature">
                        <div class="catalog-feature-icon">
                            <i class="fas fa-download"></i>
                        </div>
                        <p>Download gratuito e instantâneo</p>
                    </div>
                </div>
                
                <button class="download-catalog-btn" id="downloadCatalogBtn">
                    <i class="fas fa-download"></i>
                    BAIXAR CATÁLOGO COMPLETO
                    <i class="fas fa-arrow-down"></i>
                </button>
                
                <div class="download-info">
                    <i class="fas fa-info-circle"></i>
                    <span>Formato: PDF | Tamanho: 12 MB | Atualizado: Janeiro 2024</span>
                </div>
                
                <div class="file-size">
                    <i class="fas fa-file-alt"></i> Catálogo_Supremo_Ferramentas_2024.pdf
                </div>
            </div>
            
            <!-- SEÇÃO DE CONTATOS -->
            <div class="contacts-section">
                <h2 class="contacts-title">Entre em Contato</h2>
                
                <div class="contact-cards">
                    <!-- WhatsApp -->
                    <div class="contact-card whatsapp">
                        <div class="contact-icon">
                            <i class="fab fa-whatsapp"></i>
                        </div>
                        <div class="contact-info">
                            <h3>Atendimento via WhatsApp</h3>
                            <div class="phone-number" id="whatsapp-number">(32) 98702-6620</div>
                            <p class="whatsapp-info">Clique abaixo para conversar diretamente</p>
                            <a href="https://wa.me/+5532987026620?text=Olá! Gostaria de mais informações sobre as ferramentas Supremo" 
                               class="contact-link" 
                               target="_blank" 
                               id="whatsapp-link"
                               data-link-type="whatsapp">
                                <i class="fab fa-whatsapp"></i> Conversar no WhatsApp
                            </a>
                        </div>
                    </div>
                    
                    <!-- Telefone Fixo -->
                    <div class="contact-card phone">
                        <div class="contact-icon">
                            <i class="fas fa-phone-alt"></i>
                        </div>
                        <div class="contact-info">
                            <h3>Telefone Comercial</h3>
                            <div class="phone-number" id="phone-number">(32) 3561-2012</div>
                            <p>Horário de atendimento: Segunda a Sexta, 7:30h às 18h</p>
                            <a href="tel:+553235612012" class="contact-link phone" data-link-type="phone">
                                <i class="fas fa-phone-alt"></i> Ligar Agora
                            </a>
                        </div>
                    </div>
                    
                    <!-- Instagram -->
                    <div class="contact-card instagram">
                        <div class="contact-icon">
                            <i class="fab fa-instagram"></i>
                        </div>
                        <div class="contact-info">
                            <h3>Siga-nos no Instagram</h3>
                            <div class="instagram-username" id="instagram-username">@supremoferramentas</div>
                            <p>Acompanhe novidades, promoções e dicas</p>
                            <a href="https://instagram.com/supremoferramentas" 
                               class="contact-link instagram" 
                               target="_blank"
                               data-link-type="instagram">
                                <i class="fab fa-instagram"></i> Seguir no Instagram
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- SEÇÃO DE LOCALIZAÇÃO -->
            <div class="map-section">
                <h3>Nossa Localização</h3>
                <div class="map-container">
                    <iframe 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3750.858478944547!2d-42.368539!3d-21.130833!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjHCsDA3JzUxLjAiUyA0MsKwMjInMDYuNyJX!5e0!3m2!1spt-BR!2sbr!4v1680000000000!5m2!1spt-BR!2sbr" 
                        width="100%" 
                        height="300" 
                        style="border:0;" 
                        allowfullscreen="" 
                        loading="lazy" 
                        referrerpolicy="no-referrer-when-downgrade"
                        title="Localização da Supremo Ferramentas">
                    </iframe>
                </div>
                <p style="margin-top: 20px; color: rgba(255, 255, 255, 0.8);">
                    <i class="fas fa-map-marker-alt"></i> Rua Maxímiano Fraga, 280 - Térreo - João XXIII, Muriaé - MG, 36883-191
                </p>
            </div>
            
            <!-- SEÇÃO DE COMPARTILHAMENTO -->
            <div class="share-section">
                <h3 class="share-title">Compartilhe Nossa Página</h3>
                <p style="margin-bottom: 20px; color: rgba(255, 255, 255, 0.8);">
                    Ajude-nos a alcançar mais profissionais. Compartilhe nosso link!
                </p>
                
                <div class="share-buttons">
                    <a href="#" class="share-button whatsapp" id="share-whatsapp">
                        <i class="fab fa-whatsapp"></i> WhatsApp
                    </a>
                    
                    <a href="#" class="share-button facebook" id="share-facebook">
                        <i class="fab fa-facebook-f"></i> Facebook
                    </a>
                    
                    <button class="share-button copy-link" id="copy-link" aria-label="Copiar link da página">
                        <i class="fas fa-copy"></i> Copiar Link
                    </button>
                    
                    <button class="share-button sms" id="share-sms">
                        <i class="fas fa-sms"></i> SMS
                    </button>
                </div>
                
                <div class="copy-success" id="copy-success">
                    <i class="fas fa-check-circle"></i> Link copiado com sucesso!
                </div>
                
                <!-- QR Code Section -->
                <div class="qr-section">
                    <p style="margin-bottom: 15px; color: rgba(255, 255, 255, 0.8);">
                        <i class="fas fa-qrcode"></i> QR Code para acesso rápido
                    </p>
                    <div class="qr-code-container" id="qr-code-container">
                        <!-- QR Code será gerado aqui -->
                    </div>
                </div>
            </div>
            
            <!-- FEATURES -->
            <div class="features">
                <div class="feature">
                    <div class="feature-icon">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <h3>Tecnologia Avançada</h3>
                    <p>Ferramentas desenvolvidas com a mais recente tecnologia industrial para máximo desempenho.</p>
                </div>
                
                <div class="feature">
                    <div class="feature-icon">
                        <i class="fas fa-award"></i>
                    </div>
                    <h3>Garantia de Qualidade</h3>
                    <p>Todos os produtos passam por rigorosos controles de qualidade e testes de durabilidade.</p>
                </div>
                
                <div class="feature">
                    <div class="feature-icon">
                        <i class="fas fa-tools"></i>
                    </div>
                    <h3>Ampla Variedade</h3>
                    <p>Milhares de ferramentas especializadas para diferentes aplicações e setores industriais.</p>
                </div>
                
                <div class="feature">
                    <div class="feature-icon">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <h3>Catálogo Digital</h3>
                    <p>Acesso completo ao nosso catálogo com todas as especificações técnicas e fotos.</p>
                </div>
            </div>
            
            <div class="footer">
                <p id="copyright">© 2023 Supremo Ferramentas. Todos os direitos reservados. | Qualidade que transforma seu trabalho.</p>
                <p style="margin-top: 10px; font-size: 0.8rem; color: rgba(255, 255, 255, 0.5);">
                    <i class="fas fa-map-marker-alt"></i> Rua Maxímiano Fraga, 280 - Térreo - João XXIII, Muriaé - MG, 36883-191
                </p>
            </div>
        </div>
    </main>

    <script>
        // CONFIGURAÇÃO DOS CONTATOS E CATÁLOGO
        const config = {
            whatsapp: {
                number: '5532987026620',
                display: '(32) 98702-6620'
            },
            phone: {
                number: '+553235612012',
                display: '(32) 3561-2012'
            },
            instagram: '@supremoferramentas',
            pageUrl: window.location.href,
            pageTitle: 'Supremo Ferramentas - Qualidade Industrial',
            catalog: {
                // URL do catálogo PDF - SUBSTITUA PELA SUA URL REAL
                pdfUrl: 'https://exemplo.com/catalogo/catalogo_supremo_ferramentas_2024.pdf',
                fileName: 'Catalogo_Supremo_Ferramentas_2024.pdf',
                fileSize: '12 MB',
                lastUpdate: 'Janeiro 2024'
            }
        };
        
        // Inicializar contatos
        function initContacts() {
            // WhatsApp
            document.getElementById('whatsapp-number').textContent = config.whatsapp.display;
            const whatsappLink = document.getElementById('whatsapp-link');
            whatsappLink.href = `https://wa.me/${config.whatsapp.number}?text=Olá! Gostaria de mais informações sobre as ferramentas Supremo e também gostaria de receber o catálogo completo.`;
            
            // Telefone
            document.getElementById('phone-number').textContent = config.phone.display;
            const phoneLink = document.querySelector('a[href^="tel:"]');
            phoneLink.href = `tel:${config.phone.number}`;
            
            // Instagram
            document.getElementById('instagram-username').textContent = config.instagram;
            const instagramLink = document.querySelector('a[href*="instagram"]');
            instagramLink.href = `https://instagram.com/${config.instagram.replace('@', '')}`;
        }
        
        // Criar partículas animadas
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            const particleCount = window.innerWidth < 768 ? 15 : 25;
            
            // Limpar partículas existentes
            particlesContainer.innerHTML = '';
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                
                const size = Math.random() * 50 + 10;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                particle.style.left = `${Math.random() * 100}%`;
                particle.style.top = `${Math.random() * 100}%`;
                
                // Cor aleatória entre azul e dourado
                const hue = Math.random() * 60 + 200; // Tons de azul
                particle.style.background = `hsla(${hue}, 70%, 60%, ${Math.random() * 0.2 + 0.1})`;
                
                const duration = Math.random() * 20 + 10;
                const delay = Math.random() * 5;
                const tx = Math.random() * 100 - 50;
                const ty = Math.random() * 100 - 50;
                
                particle.style.setProperty('--tx', `${tx}px`);
                particle.style.setProperty('--ty', `${ty}px`);
                particle.style.animation = `float ${duration}s ease-in-out ${delay}s infinite`;
                particlesContainer.appendChild(particle);
            }
        }
        
        // FUNCIONALIDADES DO CATÁLOGO
        function initCatalog() {
            const downloadBtn = document.getElementById('downloadCatalogBtn');
            const modal = document.getElementById('downloadModal');
            const modalClose = document.getElementById('modalClose');
            const confirmDownload = document.getElementById('confirmDownload');
            const cancelDownload = document.getElementById('cancelDownload');
            
            // Abrir modal ao clicar no botão de download
            downloadBtn.addEventListener('click', function() {
                modal.style.display = 'flex';
                document.body.style.overflow = 'hidden';
                trackClick('catalog', 'open_modal');
            });
            
            // Fechar modal
            function closeModal() {
                modal.style.display = 'none';
                document.body.style.overflow = 'auto';
            }
            
            modalClose.addEventListener('click', closeModal);
            cancelDownload.addEventListener('click', closeModal);
            
            // Fechar modal ao clicar fora
            modal.addEventListener('click', function(e) {
                if (e.target === modal) {
                    closeModal();
                }
            });
            
            // Confirmar download
            confirmDownload.addEventListener('click', function() {
                // Simular download do arquivo
                simulateDownload();
                closeModal();
                showDownloadSuccess();
                trackClick('catalog', 'download_complete');
            });
            
            // Simular download (substitua pelo download real quando tiver o PDF)
            function simulateDownload() {
                // Se você tiver um PDF real, use esta linha:
                // window.open(config.catalog.pdfUrl, '_blank');
                
                // Simulação enquanto não tem o PDF
                console.log(`📥 Iniciando download do catálogo: ${config.catalog.fileName}`);
                console.log(`🔗 URL: ${config.catalog.pdfUrl}`);
                
                // Criar link de download temporário
                const link = document.createElement('a');
                link.href = '#';
                link.download = config.catalog.fileName;
                document.body.appendChild(link);
                link.click();
                document.body.removeChild(link);
                
                // Para download real, descomente:
                // window.location.href = config.catalog.pdfUrl;
            }
            
            // Mostrar mensagem de sucesso
            function showDownloadSuccess() {
                const originalText = downloadBtn.innerHTML;
                downloadBtn.innerHTML = '<i class="fas fa-check"></i> CATÁLOGO BAIXADO COM SUCESSO!';
                downloadBtn.style.background = 'linear-gradient(135deg, #25D366, #128C7E)';
                downloadBtn.style.animation = 'none';
                
                setTimeout(() => {
                    downloadBtn.innerHTML = originalText;
                    downloadBtn.style.background = 'linear-gradient(135deg, var(--catalog-orange), #FF8B35)';
                    downloadBtn.style.animation = 'pulse 2s ease-in-out infinite';
                }, 3000);
            }
        }
        
        // COMPARTILHAMENTO
        function initShare() {
            const currentUrl = window.location.href;
            const pageTitle = config.pageTitle;
            const message = `🏭 *Supremo Ferramentas* 🛠️

Ferramentas industriais de alta qualidade e precisão!

📚 *Catálogo Disponível*: Baixe nosso catálogo completo gratuitamente!

📞 WhatsApp: ${config.whatsapp.display}
📱 Instagram: ${config.instagram}

📍 Endereço: Rua Maxímiano Fraga, 280 - Térreo - João XXIII, Muriaé - MG

⏰ Horário: Segunda a Sexta, 7:30h às 18h

🔗 Acesse: ${currentUrl}

#SupremoFerramentas #Ferramentas #Muriaé #MG #Construção #FerramentasIndustriais`;
            
            // Compartilhar no WhatsApp
            document.getElementById('share-whatsapp').addEventListener('click', function(e) {
                e.preventDefault();
                const whatsappUrl = `https://api.whatsapp.com/send?text=${encodeURIComponent(message)}`;
                window.open(whatsappUrl, '_blank');
                trackClick('share', 'whatsapp');
            });
            
            // Compartilhar no Facebook
            document.getElementById('share-facebook').addEventListener('click', function(e) {
                e.preventDefault();
                const facebookUrl = `https://www.facebook.com/sharer/sharer.php?u=${encodeURIComponent(currentUrl)}&quote=${encodeURIComponent('Conheça a Supremo Ferramentas - Qualidade Industrial! Baixe nosso catálogo completo gratuitamente.')}`;
                window.open(facebookUrl, '_blank', 'width=600,height=400');
                trackClick('share', 'facebook');
            });
            
            // Compartilhar via SMS
            document.getElementById('share-sms').addEventListener('click', function(e) {
                e.preventDefault();
                const smsText = `Supremo Ferramentas - Catálogo completo disponível! ${currentUrl}`;
                const smsUrl = `sms:?body=${encodeURIComponent(smsText)}`;
                window.location.href = smsUrl;
                trackClick('share', 'sms');
            });
            
            // Copiar link
            document.getElementById('copy-link').addEventListener('click', function() {
                navigator.clipboard.writeText(currentUrl).then(() => {
                    showCopySuccess();
                    trackClick('share', 'copy_link');
                }).catch(err => {
                    console.error('Erro ao copiar link:', err);
                    // Fallback para navegadores antigos
                    const textArea = document.createElement('textarea');
                    textArea.value = currentUrl;
                    document.body.appendChild(textArea);
                    textArea.select();
                    document.execCommand('copy');
                    document.body.removeChild(textArea);
                    showCopySuccess();
                    trackClick('share', 'copy_link');
                });
            });
            
            function showCopySuccess() {
                const successMsg = document.getElementById('copy-success');
                successMsg.style.display = 'flex';
                setTimeout(() => {
                    successMsg.style.display = 'none';
                }, 3000);
            }
        }
        
        // Gerar QR Code
        function generateQRCode() {
            const qrUrl = `https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=${encodeURIComponent(config.pageUrl)}`;
            const qrContainer = document.getElementById('qr-code-container');
            qrContainer.innerHTML = `<img src="${qrUrl}" alt="QR Code para ${config.pageUrl}" loading="lazy">`;
        }
        
        // Animações de entrada
        function initAnimations() {
            const elements = [
                '.logo-frame',
                '.brand-main',
                '.brand-subtitle',
                '.tagline',
                '.catalog-section',
                '.contact-card',
                '.map-section',
                '.share-section',
                '.feature'
            ];
            
            elements.forEach((selector, index) => {
                const els = document.querySelectorAll(selector);
                els.forEach(element => {
                    element.style.opacity = '0';
                    element.style.transform = 'translateY(20px)';
                    
                    setTimeout(() => {
                        element.style.transition = `opacity 0.6s ease ${index * 0.2}s, transform 0.6s ease ${index * 0.2}s`;
                        element.style.opacity = '1';
                        element.style.transform = 'translateY(0)';
                    }, 100);
                });
            });
        }
        
        // Efeito de brilho na logo
        function initLogoEffects() {
            const logoFrame = document.querySelector('.logo-frame');
            
            logoFrame.addEventListener('mouseenter', function() {
                this.style.animation = 'glow 1s ease-in-out infinite';
            });
            
            logoFrame.addEventListener('mouseleave', function() {
                this.style.animation = 'glow 3s ease-in-out infinite';
            });
        }
        
        // Contador de visitas e downloads
        function initVisitorCounter() {
            // Contador de visitas
            if(!localStorage.getItem('visitas_supremo')) {
                localStorage.setItem('visitas_supremo', 1);
            } else {
                let visitas = parseInt(localStorage.getItem('visitas_supremo')) + 1;
                localStorage.setItem('visitas_supremo', visitas);
            }
            
            // Contador de downloads do catálogo
            if(!localStorage.getItem('downloads_catalogo')) {
                localStorage.setItem('downloads_catalogo', 0);
            }
            
            console.log('👥 Total de visitas:', localStorage.getItem('visitas_supremo'));
            console.log('📥 Downloads do catálogo:', localStorage.getItem('downloads_catalogo'));
        }
        
        // Atualizar copyright
        function updateCopyright() {
            const year = new Date().getFullYear();
            const copyrightElement = document.getElementById('copyright');
            if (copyrightElement) {
                copyrightElement.innerHTML = copyrightElement.innerHTML.replace('2023', year);
            }
            
            // Atualizar data do catálogo se necessário
            const catalogYear = document.querySelector('.catalog-title');
            if (catalogYear) {
                // Pode atualizar dinamicamente se quiser
            }
        }
        
        // Tracking de cliques
        function trackClick(category, action) {
            console.log(`📊 Evento: ${category} - ${action}`);
            
            // Contar downloads do catálogo
            if (category === 'catalog' && action === 'download_complete') {
                let downloads = parseInt(localStorage.getItem('downloads_catalogo')) + 1;
                localStorage.setItem('downloads_catalogo', downloads);
                console.log(`✅ Catálogo baixado! Total: ${downloads}`);
            }
            
            // Para Google Analytics (descomente quando configurar)
            /*
            if (typeof gtag !== 'undefined') {
                gtag('event', action, {
                    'event_category': category,
                    'event_label': config.pageUrl
                });
            }
            */
        }
        
        // Inicializar tracking de cliques em links
        function initClickTracking() {
            document.querySelectorAll('a, button').forEach(element => {
                element.addEventListener('click', function(e) {
                    const linkType = this.getAttribute('data-link-type') || 'button';
                    trackClick('engagement', linkType);
                });
            });
        }
        
        // Reposicionar partículas no resize
        function handleResize() {
            createParticles();
        }
        
        // Atalho de teclado para download (Ctrl + D)
        function initKeyboardShortcuts() {
            document.addEventListener('keydown', function(e) {
                // Ctrl + D para abrir modal de download
                if (e.ctrlKey && e.key === 'd') {
                    e.preventDefault();
                    document.getElementById('downloadCatalogBtn').click();
                }
                
                // ESC para fechar modal
                if (e.key === 'Escape') {
                    const modal = document.getElementById('downloadModal');
                    if (modal.style.display === 'flex') {
                        modal.style.display = 'none';
                        document.body.style.overflow = 'auto';
                    }
                }
            });
        }
        
        // Inicializar tudo quando a página carregar
        document.addEventListener('DOMContentLoaded', () => {
            createParticles();
            initContacts();
            initCatalog();
            initShare();
            generateQRCode();
            initAnimations();
            initLogoEffects();
            initVisitorCounter();
            updateCopyright();
            initClickTracking();
            initKeyboardShortcuts();
            
            // Adicionar listener para resize
            window.addEventListener('resize', handleResize);
            
            // Dicas para divulgação no console
            console.log(`
            🚀 COMO DIVULGAR SUA PÁGINA E CATÁLOGO:
            
            1. NO INSTAGRAM (@supremoferramentas):
               - Poste sobre o lançamento do catálogo
               - Use no stories com a função "Link"
               - Destaque: "Catálogo gratuito disponível!"
            
            2. NO WHATSAPP:
               - Envie para clientes: "Nosso catálogo 2024 está disponível!"
               - Configure como resposta automática
               - Compartilhe em grupos do setor
            
            3. EM MATERIAIS IMPRESSOS:
               - Adicione QR Code do catálogo em cartões de visita
               - Cole em veículos e fachada
               - Inclua em propostas comerciais
            
            4. ATALHOS DE TECLADO:
               - Pressione Ctrl + D para abrir o download do catálogo
               - ESC para fechar modais
            
            Link para compartilhar: ${config.pageUrl}
            Link do catálogo: ${config.catalog.pdfUrl}
            
            5. ESTATÍSTICAS:
               - Visitas: ${localStorage.getItem('visitas_supremo')}
               - Downloads do catálogo: ${localStorage.getItem('downloads_catalogo')}
            `);
        });
    </script>
</body>
</html>
