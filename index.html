<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Física Biológica II | Universidad de Antioquia</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Playfair+Display:wght@600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        :root {
            --udea-green: #005a2e;
            --udea-green-light: #007a3d;
            --udea-green-dark: #003d1f;
            --udea-green-accent: #00a855;
            --white: #ffffff;
            --cream: #f8f9f5;
            --light-green: #e8f5e9;
            --text-dark: #1a1a1a;
            --text-medium: #4a4a4a;
            --text-light: #6b7280;
            --border: #e5e7eb;
            --shadow: 0 4px 20px rgba(0, 90, 46, 0.08);
            --shadow-hover: 0 8px 40px rgba(0, 90, 46, 0.15);
            --radius: 16px;
            --radius-sm: 8px;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body {
            font-family: 'Inter', sans-serif;
            color: var(--text-dark);
            background: var(--white);
            line-height: 1.6;
            overflow-x: hidden;
        }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: var(--cream); }
        ::-webkit-scrollbar-thumb { background: var(--udea-green); border-radius: 4px; }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        @keyframes spin-slow {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        @keyframes wave {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
        .animate {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease-out;
        }
        .animate.visible {
            opacity: 1;
            transform: translateY(0);
        }
        .animate-delay-1 { transition-delay: 0.1s; }
        .animate-delay-2 { transition-delay: 0.2s; }
        .animate-delay-3 { transition-delay: 0.3s; }
        .animate-delay-4 { transition-delay: 0.4s; }
        .header {
            position: fixed;
            top: 0; left: 0; right: 0;
            z-index: 1000;
            background: rgba(255,255,255,0.95);
            backdrop-filter: blur(20px);
            border-bottom: 1px solid rgba(0,90,46,0.1);
            transition: all 0.3s ease;
        }
        .header.scrolled { box-shadow: 0 2px 20px rgba(0,90,46,0.1); }
        .header-inner {
            max-width: 1200px;
            margin: 0 auto;
            padding: 12px 24px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .logo-area {
            display: flex;
            align-items: center;
            gap: 14px;
        }
        .logo-area img { height: 48px; width: auto; }
        .logo-text { display: flex; flex-direction: column; }
        .logo-text span {
            font-size: 0.75rem;
            color: var(--udea-green);
            font-weight: 600;
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }
        .logo-text strong {
            font-size: 0.9rem;
            color: var(--text-dark);
            font-weight: 700;
        }
        .nav-links {
            display: flex;
            gap: 32px;
            align-items: center;
        }
        .nav-links a {
            text-decoration: none;
            color: var(--text-medium);
            font-size: 0.9rem;
            font-weight: 500;
            transition: color 0.3s;
            position: relative;
        }
        .nav-links a:hover { color: var(--udea-green); }
        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -4px; left: 0;
            width: 0; height: 2px;
            background: var(--udea-green);
            transition: width 0.3s;
        }
        .nav-links a:hover::after { width: 100%; }
        .btn-contact {
            background: var(--udea-green);
            color: white !important;
            padding: 10px 24px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 0.85rem;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        .btn-contact:hover {
            background: var(--udea-green-dark);
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(0,90,46,0.3);
        }
        .btn-contact::after { display: none !important; }
        .menu-toggle {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            color: var(--udea-green);
            cursor: pointer;
        }
        .hero {
            min-height: 100vh;
            background: linear-gradient(135deg, var(--udea-green-dark) 0%, var(--udea-green) 50%, var(--udea-green-light) 100%);
            position: relative;
            display: flex;
            align-items: center;
            overflow: hidden;
            padding-top: 80px;
        }
        .hero-bg-pattern {
            position: absolute;
            inset: 0;
            opacity: 0.08;
            background-image:
                radial-gradient(circle at 20% 50%, white 1px, transparent 1px),
                radial-gradient(circle at 80% 20%, white 1px, transparent 1px),
                radial-gradient(circle at 60% 80%, white 1px, transparent 1px);
            background-size: 60px 60px;
        }
        .hero-wave {
            position: absolute;
            bottom: 0; left: 0; right: 0;
            height: 120px;
        }
        .hero-wave svg {
            position: absolute;
            bottom: 0;
            width: 200%;
            height: 100%;
            animation: wave 15s linear infinite;
        }
        .hero-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 24px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
            position: relative;
            z-index: 2;
        }
        .hero-text h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            font-weight: 800;
            color: white;
            line-height: 1.1;
            margin-bottom: 16px;
            animation: fadeInUp 0.8s ease-out;
        }
        .hero-text h1 span { color: var(--udea-green-accent); }
        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            padding: 8px 20px;
            border-radius: 50px;
            color: white;
            font-size: 0.85rem;
            font-weight: 500;
            margin-bottom: 24px;
            animation: fadeInUp 0.8s ease-out 0.1s both;
            border: 1px solid rgba(255,255,255,0.2);
        }
        .hero-badge i { color: #ffd700; }
        .hero-text p {
            font-size: 1.15rem;
            color: rgba(255,255,255,0.85);
            margin-bottom: 32px;
            max-width: 500px;
            line-height: 1.7;
            animation: fadeInUp 0.8s ease-out 0.2s both;
        }
        .hero-cta {
            display: flex;
            gap: 16px;
            flex-wrap: wrap;
            animation: fadeInUp 0.8s ease-out 0.3s both;
        }
        .btn-primary {
            background: white;
            color: var(--udea-green);
            padding: 14px 32px;
            border-radius: 50px;
            font-weight: 700;
            font-size: 0.95rem;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        .btn-outline {
            background: transparent;
            color: white;
            padding: 14px 32px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 0.95rem;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            border: 2px solid rgba(255,255,255,0.4);
            transition: all 0.3s ease;
        }
        .btn-outline:hover {
            background: rgba(255,255,255,0.1);
            border-color: white;
        }
        .hero-visual {
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .hero-circle {
            width: 400px;
            height: 400px;
            border-radius: 50%;
            background: rgba(255,255,255,0.05);
            border: 2px solid rgba(255,255,255,0.1);
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            animation: float 6s ease-in-out infinite;
        }
        .hero-circle-inner {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.15);
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .hero-icon { font-size: 6rem; color: rgba(255,255,255,0.9); }
        .orbit {
            position: absolute;
            width: 100%;
            height: 100%;
            animation: spin-slow 20s linear infinite;
        }
        .orbit-dot {
            position: absolute;
            width: 12px; height: 12px;
            background: var(--udea-green-accent);
            border-radius: 50%;
            box-shadow: 0 0 20px var(--udea-green-accent);
        }
        .orbit-dot:nth-child(1) { top: 0; left: 50%; transform: translateX(-50%); }
        .orbit-dot:nth-child(2) { bottom: 20%; right: 10%; }
        .orbit-dot:nth-child(3) { bottom: 20%; left: 10%; }
        .hero-info-cards {
            position: absolute;
            bottom: -20px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 16px;
            z-index: 3;
        }
        .info-card {
            background: white;
            padding: 16px 24px;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            display: flex;
            align-items: center;
            gap: 12px;
            min-width: 180px;
        }
        .info-card i { font-size: 1.5rem; color: var(--udea-green); }
        .info-card div strong {
            display: block;
            font-size: 0.85rem;
            color: var(--text-light);
            font-weight: 500;
        }
        .info-card div span {
            font-size: 1rem;
            font-weight: 700;
            color: var(--text-dark);
        }
        .section {
            padding: 100px 24px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .section-header {
            text-align: center;
            margin-bottom: 60px;
        }
        .section-label {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            color: var(--udea-green);
            font-weight: 600;
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 12px;
        }
        .section-title {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--text-dark);
            margin-bottom: 16px;
        }
        .section-subtitle {
            font-size: 1.1rem;
            color: var(--text-light);
            max-width: 600px;
            margin: 0 auto;
        }
        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }
        .about-text p {
            font-size: 1.05rem;
            color: var(--text-medium);
            margin-bottom: 20px;
            line-height: 1.8;
        }
        .about-features {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 32px;
        }
        .feature-item {
            display: flex;
            align-items: flex-start;
            gap: 12px;
        }
        .feature-item i {
            width: 40px; height: 40px;
            background: var(--light-green);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--udea-green);
            font-size: 1rem;
            flex-shrink: 0;
        }
        .feature-item div strong {
            display: block;
            font-size: 0.95rem;
            color: var(--text-dark);
            margin-bottom: 4px;
        }
        .feature-item div span {
            font-size: 0.85rem;
            color: var(--text-light);
        }
        .about-visual { position: relative; }
        .about-visual-main {
            background: linear-gradient(135deg, var(--udea-green) 0%, var(--udea-green-light) 100%);
            border-radius: var(--radius);
            padding: 40px;
            color: white;
            position: relative;
            overflow: hidden;
        }
        .about-visual-main::before {
            content: '';
            position: absolute;
            top: -50%; right: -50%;
            width: 100%; height: 100%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
        }
        .about-visual-main h3 {
            font-size: 1.5rem;
            margin-bottom: 24px;
            position: relative;
        }
        .stat-row {
            display: flex;
            justify-content: space-between;
            padding: 16px 0;
            border-bottom: 1px solid rgba(255,255,255,0.2);
            position: relative;
        }
        .stat-row:last-child { border-bottom: none; }
        .stat-row span:first-child { font-size: 0.9rem; opacity: 0.9; }
        .stat-row span:last-child { font-weight: 700; font-size: 1rem; }
        .about-visual-badge {
            position: absolute;
            bottom: -20px; right: -20px;
            background: white;
            padding: 20px 28px;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            text-align: center;
        }
        .about-visual-badge strong {
            display: block;
            font-size: 2rem;
            color: var(--udea-green);
            font-weight: 800;
        }
        .about-visual-badge span {
            font-size: 0.8rem;
            color: var(--text-light);
            font-weight: 500;
        }
        .modules-section {
            background: var(--cream);
            padding: 100px 24px;
        }
        .modules-section .section { padding: 0; }
        .modules-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 24px;
        }
        .module-card {
            background: white;
            border-radius: var(--radius);
            padding: 28px;
            box-shadow: var(--shadow);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
            border: 1px solid var(--border);
            display: flex;
            flex-direction: column;
        }
        .module-card:hover {
            transform: translateY(-8px);
            box-shadow: var(--shadow-hover);
            border-color: var(--udea-green);
        }
        .module-card::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0;
            height: 4px;
            background: linear-gradient(90deg, var(--udea-green), var(--udea-green-accent));
            opacity: 0;
            transition: opacity 0.3s;
        }
        .module-card:hover::before { opacity: 1; }
        .module-number {
            width: 44px; height: 44px;
            background: var(--light-green);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--udea-green);
            font-weight: 800;
            font-size: 1.1rem;
            margin-bottom: 16px;
        }
        .module-card h3 {
            font-size: 1.05rem;
            font-weight: 700;
            color: var(--text-dark);
            margin-bottom: 10px;
        }
        .module-card p {
            font-size: 0.88rem;
            color: var(--text-light);
            line-height: 1.6;
            margin-bottom: 16px;
            flex-grow: 1;
        }
        .module-topics {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
            margin-bottom: 16px;
        }
        .module-topics span {
            background: var(--cream);
            color: var(--udea-green);
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 500;
        }
        .module-hours {
            display: flex;
            align-items: center;
            gap: 6px;
            padding-top: 12px;
            border-top: 1px solid var(--border);
            font-size: 0.8rem;
            color: var(--text-light);
            margin-bottom: 12px;
        }
        .module-hours i { color: var(--udea-green); }
        .module-links {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }
        .module-link-btn {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px 14px;
            border-radius: var(--radius-sm);
            font-size: 0.82rem;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            border: 1.5px solid;
        }
        .module-link-btn i { font-size: 0.9rem; }
        .module-link-btn.btn-slides {
            background: var(--light-green);
            color: var(--udea-green);
            border-color: var(--udea-green);
        }
        .module-link-btn.btn-slides:hover {
            background: var(--udea-green);
            color: white;
            transform: translateY(-2px);
        }
        .module-link-btn.btn-videos {
            background: #fff3e0;
            color: #e65100;
            border-color: #e65100;
        }
        .module-link-btn.btn-videos:hover {
            background: #e65100;
            color: white;
            transform: translateY(-2px);
        }
        .module-link-btn.btn-docs {
            background: #e3f2fd;
            color: #1565c0;
            border-color: #1565c0;
        }
        .module-link-btn.btn-docs:hover {
            background: #1565c0;
            color: white;
            transform: translateY(-2px);
        }
        .module-link-btn.btn-lab {
            background: #fce4ec;
            color: #c2185b;
            border-color: #c2185b;
        }
        .module-link-btn.btn-lab:hover {
            background: #c2185b;
            color: white;
            transform: translateY(-2px);
        }
        .module-link-btn.btn-quiz {
            background: #f3e5f5;
            color: #7b1fa2;
            border-color: #7b1fa2;
        }
        .module-link-btn.btn-quiz:hover {
            background: #7b1fa2;
            color: white;
            transform: translateY(-2px);
        }
        .module-link-btn.disabled {
            opacity: 0.5;
            cursor: not-allowed;
            pointer-events: none;
        }
        .eval-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: start;
        }
        .eval-table-wrap {
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            overflow: hidden;
            border: 1px solid var(--border);
        }
        .eval-table-header {
            background: var(--udea-green);
            color: white;
            padding: 20px 24px;
        }
        .eval-table-header h3 {
            font-size: 1.1rem;
            font-weight: 700;
        }
        .eval-table-header p {
            font-size: 0.85rem;
            opacity: 0.9;
            margin-top: 4px;
        }
        .eval-table {
            width: 100%;
            border-collapse: collapse;
        }
        .eval-table tr { border-bottom: 1px solid var(--border); }
        .eval-table tr:last-child { border-bottom: none; }
        .eval-table td {
            padding: 16px 24px;
            font-size: 0.95rem;
        }
        .eval-table td:last-child {
            text-align: right;
            font-weight: 700;
            color: var(--udea-green);
            width: 80px;
        }
        .eval-table tr.total td {
            background: var(--light-green);
            font-weight: 700;
        }
        .eval-table tr.total td:last-child { font-size: 1.1rem; }
        .eval-info {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .eval-info-card {
            background: white;
            border-radius: var(--radius);
            padding: 24px;
            box-shadow: var(--shadow);
            border: 1px solid var(--border);
            border-left: 4px solid var(--udea-green);
        }
        .eval-info-card h4 {
            font-size: 1rem;
            font-weight: 700;
            color: var(--text-dark);
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .eval-info-card h4 i { color: var(--udea-green); }
        .eval-info-card p {
            font-size: 0.9rem;
            color: var(--text-medium);
            line-height: 1.6;
        }
        .teacher-section {
            background: linear-gradient(135deg, var(--udea-green-dark) 0%, var(--udea-green) 100%);
            padding: 100px 24px;
            position: relative;
            overflow: hidden;
        }
        .teacher-section::before {
            content: '';
            position: absolute;
            inset: 0;
            background-image: radial-gradient(circle at 30% 50%, rgba(255,255,255,0.05) 0%, transparent 50%);
        }
        .teacher-section .section {
            position: relative;
            z-index: 2;
            padding: 0;
        }
        .teacher-section .section-header .section-title,
        .teacher-section .section-header .section-label { color: white; }
        .teacher-section .section-header .section-subtitle { color: rgba(255,255,255,0.7); }
        .teacher-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255,255,255,0.2);
            border-radius: var(--radius);
            padding: 48px;
            display: flex;
            gap: 40px;
            align-items: center;
            max-width: 900px;
            margin: 0 auto;
        }
        .teacher-avatar {
            width: 140px; height: 140px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--udea-green-accent), var(--udea-green-light));
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            border: 4px solid rgba(255,255,255,0.3);
        }
        .teacher-avatar i { font-size: 3.5rem; color: white; }
        .teacher-info h3 {
            font-size: 1.6rem;
            font-weight: 700;
            color: white;
            margin-bottom: 4px;
        }
        .teacher-info .teacher-role {
            color: var(--udea-green-accent);
            font-weight: 600;
            font-size: 0.95rem;
            margin-bottom: 8px;
            display: block;
        }
        .teacher-info .teacher-creds {
            color: rgba(255,255,255,0.7);
            font-size: 0.85rem;
            margin-bottom: 16px;
            display: block;
            line-height: 1.5;
        }
        .teacher-info p {
            color: rgba(255,255,255,0.8);
            font-size: 0.95rem;
            line-height: 1.7;
            margin-bottom: 20px;
        }
        .teacher-contact {
            display: flex;
            gap: 16px;
            flex-wrap: wrap;
        }
        .teacher-contact a {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            color: white;
            text-decoration: none;
            font-size: 0.9rem;
            padding: 10px 20px;
            background: rgba(255,255,255,0.15);
            border-radius: 50px;
            transition: all 0.3s;
            border: 1px solid rgba(255,255,255,0.2);
        }
        .teacher-contact a:hover {
            background: rgba(255,255,255,0.25);
            transform: translateY(-2px);
        }
        .bib-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }
        .bib-column h3 {
            font-size: 1.1rem;
            font-weight: 700;
            color: var(--text-dark);
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .bib-column h3 i { color: var(--udea-green); }
        .bib-list {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .bib-item {
            background: white;
            padding: 16px 20px;
            border-radius: var(--radius-sm);
            border: 1px solid var(--border);
            box-shadow: var(--shadow);
            transition: all 0.3s;
            display: flex;
            gap: 12px;
            align-items: flex-start;
        }
        .bib-item:hover {
            border-color: var(--udea-green);
            transform: translateX(4px);
        }
        .bib-item i {
            color: var(--udea-green);
            font-size: 1rem;
            margin-top: 2px;
            flex-shrink: 0;
        }
        .bib-item div strong {
            display: block;
            font-size: 0.9rem;
            color: var(--text-dark);
            margin-bottom: 2px;
        }
        .bib-item div span {
            font-size: 0.8rem;
            color: var(--text-light);
        }
        .footer {
            background: var(--udea-green-dark);
            padding: 80px 24px 40px;
            color: white;
        }
        .footer-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 60px;
            margin-bottom: 60px;
        }
        .footer-brand img {
            height: 60px;
            margin-bottom: 20px;
            filter: brightness(0) invert(1);
        }
        .footer-brand p {
            color: rgba(255,255,255,0.7);
            font-size: 0.9rem;
            line-height: 1.7;
            max-width: 300px;
        }
        .footer-col h4 {
            font-size: 1rem;
            font-weight: 700;
            margin-bottom: 20px;
            color: white;
        }
        .footer-col ul { list-style: none; }
        .footer-col ul li { margin-bottom: 12px; }
        .footer-col ul li a {
            color: rgba(255,255,255,0.7);
            text-decoration: none;
            font-size: 0.9rem;
            transition: color 0.3s;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .footer-col ul li a:hover { color: white; }
        .footer-col ul li a i { font-size: 0.8rem; }
        .footer-bottom {
            max-width: 1200px;
            margin: 0 auto;
            padding-top: 30px;
            border-top: 1px solid rgba(255,255,255,0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 16px;
        }
        .footer-bottom p {
            color: rgba(255,255,255,0.5);
            font-size: 0.85rem;
        }
        .footer-social {
            display: flex;
            gap: 12px;
        }
        .footer-social a {
            width: 40px; height: 40px;
            border-radius: 50%;
            background: rgba(255,255,255,0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            transition: all 0.3s;
        }
        .footer-social a:hover {
            background: var(--udea-green-accent);
            transform: translateY(-3px);
        }
        @media (max-width: 1024px) {
            .modules-grid { grid-template-columns: repeat(2, 1fr); }
            .hero-content {
                grid-template-columns: 1fr;
                text-align: center;
            }
            .hero-text p { margin: 0 auto 32px; }
            .hero-cta { justify-content: center; }
            .hero-visual { display: none; }
            .hero-info-cards {
                position: relative;
                bottom: auto; left: auto;
                transform: none;
                margin-top: 40px;
                flex-wrap: wrap;
                justify-content: center;
            }
        }
        @media (max-width: 768px) {
            .nav-links {
                display: none;
                position: absolute;
                top: 100%; left: 0; right: 0;
                background: white;
                flex-direction: column;
                padding: 20px;
                gap: 16px;
                box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            }
            .nav-links.active { display: flex; }
            .menu-toggle { display: block; }
            .hero-text h1 { font-size: 2.2rem; }
            .about-grid, .eval-grid, .bib-grid { grid-template-columns: 1fr; }
            .modules-grid { grid-template-columns: 1fr; }
            .teacher-card { flex-direction: column; text-align: center; }
            .teacher-contact { justify-content: center; }
            .footer-grid { grid-template-columns: 1fr; gap: 40px; }
            .section { padding: 60px 20px; }
            .section-title { font-size: 1.8rem; }
            .about-features { grid-template-columns: 1fr; }
            .hero-info-cards { flex-direction: column; align-items: center; }
            .info-card { width: 100%; max-width: 280px; }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header class="header" id="header">
        <div class="header-inner">
            <div class="logo-area">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Escudo_Universidad_de_Antioquia.svg/1200px-Escudo_Universidad_de_Antioquia.svg.png" alt="Universidad de Antioquia">
                <div class="logo-text">
                    <span>Universidad de Antioquia</span>
                    <strong>Facultad de Educación</strong>
                </div>
            </div>
            <nav class="nav-links" id="navLinks">
                <a href="#inicio">Inicio</a>
                <a href="#curso">El Curso</a>
                <a href="#modulos">Módulos</a>
                <a href="#evaluacion">Evaluación</a>
                <a href="#docente">Docente</a>
                <a href="#contacto" class="btn-contact">Contactar</a>
            </nav>
            <button class="menu-toggle" id="menuToggle" aria-label="Menú">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </header>

    <!-- Hero -->
    <section class="hero" id="inicio">
        <div class="hero-bg-pattern"></div>
        <div class="hero-wave">
            <svg viewBox="0 0 1440 120" preserveAspectRatio="none">
                <path fill="#ffffff" d="M0,60 C360,120 720,0 1080,60 C1260,90 1380,30 1440,60 L1440,120 L0,120 Z"></path>
            </svg>
        </div>
        <div class="hero-content">
            <div class="hero-text">
                <div class="hero-badge">
                    <i class="fas fa-star"></i>
                    <span>Licenciatura en Ciencias Naturales</span>
                </div>
                <h1>Física Biológica <span>II</span></h1>
                <p>Explora los principios físicos que rigen los fenómenos biológicos. Desde el movimiento ondulatorio hasta la termodinámica del metabolismo, descubre la física detrás de la vida.</p>
                <div class="hero-cta">
                    <a href="#modulos" class="btn-primary">
                        <i class="fas fa-book-open"></i>
                        Ver material de clase
                    </a>
                    <a href="#contacto" class="btn-outline">
                        <i class="fas fa-envelope"></i>
                        Contactar al docente
                    </a>
                </div>
            </div>
            <div class="hero-visual">
                <div class="hero-circle">
                    <div class="orbit">
                        <div class="orbit-dot"></div>
                        <div class="orbit-dot"></div>
                        <div class="orbit-dot"></div>
                    </div>
                    <div class="hero-circle-inner">
                        <i class="fas fa-atom hero-icon"></i>
                    </div>
                </div>
            </div>
        </div>
        <div class="hero-info-cards">
            <div class="info-card animate">
                <i class="fas fa-calendar-alt"></i>
                <div>
                    <strong>Inicio</strong>
                    <span>3 de agosto</span>
                </div>
            </div>
            <div class="info-card animate animate-delay-1">
                <i class="fas fa-clock"></i>
                <div>
                    <strong>Intensidad</strong>
                    <span>4h semanales</span>
                </div>
            </div>
            <div class="info-card animate animate-delay-2">
                <i class="fas fa-graduation-cap"></i>
                <div>
                    <strong>Créditos</strong>
                    <span>4 créditos</span>
                </div>
            </div>
            <div class="info-card animate animate-delay-3">
                <i class="fas fa-chalkboard-user"></i>
                <div>
                    <strong>Modalidad</strong>
                    <span>Presencial</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Sobre el curso -->
    <section class="section" id="curso">
        <div class="section-header animate">
            <div class="section-label">
                <i class="fas fa-microscope"></i>
                Sobre el curso
            </div>
            <h2 class="section-title">¿Qué aprenderás?</h2>
            <p class="section-subtitle">Un curso que conecta la física con la biología a través de la observación, el experimento y el razonamiento matemático.</p>
        </div>
        <div class="about-grid">
            <div class="about-text animate">
                <p>En este curso básico de Física Biológica II estudiaremos y analizaremos principios de la física y veremos su aplicación con la biología. Cuando vemos los principios de la óptica tratamos el ojo como sistema biológico. Cuando estudiamos las leyes de la termodinámica, las usamos para explicar cómo funciona el metabolismo de nuestro organismo.</p>
                <p>La tarea de la ciencia es penetrar más allá de lo inmediato y visible hacia lo desconocido, colocando lo visible en un contexto nuevo y más general. Aquí abordamos fenómenos físicos asociados con fenómenos ondulatorios desde marcos no Newtonianos.</p>
                <div class="about-features">
                    <div class="feature-item">
                        <i class="fas fa-wave-square"></i>
                        <div>
                            <strong>Ondas y Vibraciones</strong>
                            <span>M.A.S, resonancia, ondas estacionarias</span>
                        </div>
                    </div>
                    <div class="feature-item">
                        <i class="fas fa-eye"></i>
                        <div>
                            <strong>Óptica</strong>
                            <span>Geométrica y ondulatoria aplicada</span>
                        </div>
                    </div>
                    <div class="feature-item">
                        <i class="fas fa-temperature-high"></i>
                        <div>
                            <strong>Termodinámica</strong>
                            <span>Metabolismo, entropía y calor</span>
                        </div>
                    </div>
                    <div class="feature-item">
                        <i class="fas fa-flask"></i>
                        <div>
                            <strong>Laboratorio</strong>
                            <span>Prácticas experimentales activas</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="about-visual animate animate-delay-2">
                <div class="about-visual-main">
                    <h3><i class="fas fa-info-circle"></i> Datos del curso</h3>
                    <div class="stat-row">
                        <span>Código</span>
                        <span>2090304</span>
                    </div>
                    <div class="stat-row">
                        <span>Nivel</span>
                        <span>3</span>
                    </div>
                    <div class="stat-row">
                        <span>Créditos</span>
                        <span>4</span>
                    </div>
                    <div class="stat-row">
                        <span>Docencia directa</span>
                        <span>64h / semestre</span>
                    </div>
                    <div class="stat-row">
                        <span>Trabajo autónomo</span>
                        <span>80h / semestre</span>
                    </div>
                    <div class="stat-row">
                        <span>Total horas</span>
                        <span>192h</span>
                    </div>
                </div>
                <div class="about-visual-badge">
                    <strong>8</strong>
                    <span>Ejes temáticos</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Módulos -->
    <section class="modules-section" id="modulos">
        <div class="section">
            <div class="section-header animate">
                <div class="section-label">
                    <i class="fas fa-layer-group"></i>
                    Contenido programático
                </div>
                <h2 class="section-title">8 Ejes Temáticos</h2>
                <p class="section-subtitle">Cada módulo incluye diapositivas, videos, documentos, guías de laboratorio y quizzes. Haz clic en los botones para acceder al material.</p>
            </div>
            <div class="modules-grid">

                <!-- Módulo 1 -->
                <div class="module-card animate">
                    <div class="module-number">01</div>
                    <h3>Movimiento Vibratorio</h3>
                    <p>Movimiento Armónico Simple, energía, péndulo, sistema masa-resorte, oscilaciones y resonancia.</p>
                    <div class="module-topics">
                        <span>M.A.S</span>
                        <span>Péndulo</span>
                        <span>Resonancia</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>12 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 2 -->
                <div class="module-card animate animate-delay-1">
                    <div class="module-number">02</div>
                    <h3>Movimiento Ondulatorio</h3>
                    <p>Fenómenos ondulatorios, ondas estacionarias, ondas en cuerda, efecto Doppler y pulsaciones.</p>
                    <div class="module-topics">
                        <span>Ondas</span>
                        <span>Doppler</span>
                        <span>Cuerda</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>12 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 3 -->
                <div class="module-card animate animate-delay-2">
                    <div class="module-number">03</div>
                    <h3>Acústica</h3>
                    <p>Características del sonido, anatomía del oído humano y medición de la velocidad del sonido.</p>
                    <div class="module-topics">
                        <span>Sonido</span>
                        <span>Oído</span>
                        <span>Velocidad</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>10 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 4 -->
                <div class="module-card animate animate-delay-3">
                    <div class="module-number">04</div>
                    <h3>Espectro Electromagnético</h3>
                    <p>Reflexión, refracción, leyes de Snell, dispersión y el arco iris como fenómeno físico.</p>
                    <div class="module-topics">
                        <span>Reflexión</span>
                        <span>Refracción</span>
                        <span>Arcoíris</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>12 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 5 -->
                <div class="module-card animate">
                    <div class="module-number">05</div>
                    <h3>Óptica Geométrica</h3>
                    <p>Espejos, lentes, prisma, microscopio, telescopio y el ojo humano como sistema óptico.</p>
                    <div class="module-topics">
                        <span>Lentes</span>
                        <span>Microscopio</span>
                        <span>Ojo</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>10 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 6 -->
                <div class="module-card animate animate-delay-1">
                    <div class="module-number">06</div>
                    <h3>Óptica Ondulatoria</h3>
                    <p>Interferencias, polarización, difracción y aplicaciones en sistemas biológicos.</p>
                    <div class="module-topics">
                        <span>Interferencia</span>
                        <span>Polarización</span>
                        <span>Difracción</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>12 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 7 -->
                <div class="module-card animate animate-delay-2">
                    <div class="module-number">07</div>
                    <h3>Dinámica de Fluidos</h3>
                    <p>Continuidad, Bernoulli, viscosidad, presión sanguínea, calor específico y efecto invernadero.</p>
                    <div class="module-topics">
                        <span>Bernoulli</span>
                        <span>Viscosidad</span>
                        <span>Fluidos</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>14 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

                <!-- Módulo 8 -->
                <div class="module-card animate animate-delay-3">
                    <div class="module-number">08</div>
                    <h3>Termodinámica</h3>
                    <p>Sistemas termodinámicos, leyes 0, 1 y 2, ciclo de Carnot, entropía y máquinas térmicas.</p>
                    <div class="module-topics">
                        <span>Leyes</span>
                        <span>Carnot</span>
                        <span>Entropía</span>
                    </div>
                    <div class="module-hours">
                        <i class="fas fa-clock"></i>
                        <span>14 horas + prácticas</span>
                    </div>
                    <div class="module-links">
                        <a href="#" class="module-link-btn btn-slides disabled" title="Próximamente">
                            <i class="fas fa-file-powerpoint"></i>
                            Diapositivas
                        </a>
                        <a href="#" class="module-link-btn btn-videos disabled" title="Próximamente">
                            <i class="fas fa-play-circle"></i>
                            Videos
                        </a>
                        <a href="#" class="module-link-btn btn-docs disabled" title="Próximamente">
                            <i class="fas fa-file-pdf"></i>
                            Documentos
                        </a>
                        <a href="#" class="module-link-btn btn-lab disabled" title="Próximamente">
                            <i class="fas fa-flask"></i>
                            Guía de laboratorio
                        </a>
                        <a href="#" class="module-link-btn btn-quiz disabled" title="Próximamente">
                            <i class="fas fa-question-circle"></i>
                            Quiz
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Evaluación -->
    <section class="section" id="evaluacion">
        <div class="section-header animate">
            <div class="section-label">
                <i class="fas fa-clipboard-check"></i>
                Sistema de evaluación
            </div>
            <h2 class="section-title">¿Cómo se evalúa?</h2>
            <p class="section-subtitle">Un sistema integral que combina exámenes, trabajo de laboratorio e investigación para medir tu comprensión.</p>
        </div>
        <div class="eval-grid">
            <div class="eval-table-wrap animate">
                <div class="eval-table-header">
                    <h3><i class="fas fa-percentage"></i> Distribución de notas</h3>
                    <p>Evaluación continua durante el semestre</p>
                </div>
                <table class="eval-table">
                    <tr>
                        <td><i class="fas fa-file-alt" style="color: var(--udea-green); margin-right: 8px;"></i> Examen parcial I (remoto)</td>
                        <td>20%</td>
                    </tr>
                    <tr>
                        <td><i class="fas fa-file-alt" style="color: var(--udea-green); margin-right: 8px;"></i> Examen parcial II (remoto)</td>
                        <td>20%</td>
                    </tr>
                    <tr>
                        <td><i class="fas fa-file-alt" style="color: var(--udea-green); margin-right: 8px;"></i> Examen final (remoto)</td>
                        <td>20%</td>
                    </tr>
                    <tr>
                        <td><i class="fas fa-question-circle" style="color: var(--udea-green); margin-right: 8px;"></i> Quiz I</td>
                        <td>10%</td>
                    </tr>
                    <tr>
                        <td><i class="fas fa-flask" style="color: var(--udea-green); margin-right: 8px;"></i> Informe de laboratorio (grupal)</td>
                        <td>15%</td>
                    </tr>
                    <tr>
                        <td><i class="fas fa-book" style="color: var(--udea-green); margin-right: 8px;"></i> Trabajo final (pareja)</td>
                        <td>15%</td>
                    </tr>
                    <tr class="total">
                        <td><i class="fas fa-calculator" style="color: var(--udea-green); margin-right: 8px;"></i> Total</td>
                        <td>100%</td>
                    </tr>
                </table>
            </div>
            <div class="eval-info">
                <div class="eval-info-card animate animate-delay-1">
                    <h4><i class="fas fa-users"></i> Trabajo en equipo</h4>
                    <p>Los informes de laboratorio se realizan en grupos de 2-3 estudiantes. El trabajo final se desarrolla en parejas sobre un tema de la vida relacionado con la física y las ciencias naturales.</p>
                </div>
                <div class="eval-info-card animate animate-delay-2">
                    <h4><i class="fas fa-laptop"></i> Evaluaciones remotas</h4>
                    <p>Los tres exámenes (dos parciales y el final) se realizan en modalidad remota e individual, permitiéndote demostrar tu comprensión de manera autónoma.</p>
                </div>
                <div class="eval-info-card animate animate-delay-3">
                    <h4><i class="fas fa-lightbulb"></i> Prerrequisitos</h4>
                    <p>Para cursar esta asignatura debes haber aprobado <strong>Física Biológica I</strong> y <strong>Fundamentos de matemática</strong>. El <strong>Cálculo diferencial</strong> es correquisito.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Docente -->
    <section class="teacher-section" id="docente">
        <div class="section">
            <div class="section-header animate">
                <div class="section-label">
                    <i class="fas fa-chalkboard-user"></i>
                    Tu docente
                </div>
                <h2 class="section-title">Conoce a tu profesor</h2>
                <p class="section-subtitle">Un docente comprometido con la enseñanza de la física desde una perspectiva biológica y epistemológica.</p>
            </div>
            <div class="teacher-card animate">
                <div class="teacher-avatar">
                    <i class="fas fa-user-graduate"></i>
                </div>
                <div class="teacher-info">
                    <h3>Hernán Quiroz</h3>
                    <span class="teacher-role">Docente - Física Biológica II</span>
                    <span class="teacher-creds">
                        <i class="fas fa-graduation-cap" style="margin-right:4px;"></i>Ingeniero Químico UdeA<br>
                        <i class="fas fa-graduation-cap" style="margin-right:4px;"></i>Msc. Enseñanza de las Ciencias Exactas y Naturales — Universidad Nacional de Colombia
                    </span>
                    <p>La metodología del curso apunta a abordar los conceptos desde marcos epistemológicos reconocidos y desde posturas críticas de la historia cuando se revisan conceptos físicos. Se realizan prácticas de laboratorio con discusión activa, talleres de aplicación y videos que ayudan a entender los conceptos.</p>
                    <div class="teacher-contact">
                        <a href="mailto:hernan.quiroz@udea.edu.co">
                            <i class="fas fa-envelope"></i>
                            hernan.quiroz@udea.edu.co
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bibliografía -->
    <section class="section" id="bibliografia">
        <div class="section-header animate">
            <div class="section-label">
                <i class="fas fa-book-open"></i>
                Recursos
            </div>
            <h2 class="section-title">Bibliografía del curso</h2>
            <p class="section-subtitle">Textos fundamentales para profundizar en cada uno de los temas del programa.</p>
        </div>
        <div class="bib-grid">
            <div class="bib-column animate">
                <h3><i class="fas fa-star"></i> Bibliografía Básica</h3>
                <div class="bib-list">
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>Cromer, Alan</strong>
                            <span>Física para las Ciencias de la Vida. 2ª Ed. Editorial Reverté, Barcelona, 1982</span>
                        </div>
                    </div>
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>Giancoli, Douglas C.</strong>
                            <span>Física con Principios y Aplicaciones. 4ª Ed. Prentice Hall, México, 1997</span>
                        </div>
                    </div>
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>MacDonald, Simon Burns</strong>
                            <span>Física para las Ciencias de la Vida y de la Salud. Addison Wesley, México, 1989</span>
                        </div>
                    </div>
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>Jou, David</strong>
                            <span>Física para las Ciencias de la Vida. McGraw-Hill, España, 1986</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bib-column animate animate-delay-1">
                <h3><i class="fas fa-bookmark"></i> Bibliografía de Referencia</h3>
                <div class="bib-list">
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>Serway, Raymond</strong>
                            <span>Física Vol. 1-2. 6ª Ed. McGraw-Hill, México, 1992</span>
                        </div>
                    </div>
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>Sears, Zemansky & Young</strong>
                            <span>Física Universitaria. 11ª Ed. Addison Wesley, 2002</span>
                        </div>
                    </div>
                    <div class="bib-item">
                        <i class="fas fa-newspaper"></i>
                        <div>
                            <strong>Revista Nuestro Tiempo</strong>
                            <span>Ensayo Energía Nuclear. Universidad de Navarra, 2009</span>
                        </div>
                    </div>
                    <div class="bib-item">
                        <i class="fas fa-book"></i>
                        <div>
                            <strong>Valtuéña, José A.</strong>
                            <span>Enciclopedia de la Ecología y la Salud</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contacto -->
    <footer class="footer" id="contacto">
        <div class="footer-grid">
            <div class="footer-brand">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Escudo_Universidad_de_Antioquia.svg/1200px-Escudo_Universidad_de_Antioquia.svg.png" alt="Universidad de Antioquia">
                <p>Física Biológica II - Licenciatura en Ciencias Naturales. Facultad de Educación, Universidad de Antioquia. Curso presencial de 4 créditos académicos.</p>
            </div>
            <div class="footer-col">
                <h4>Navegación</h4>
                <ul>
                    <li><a href="#inicio"><i class="fas fa-chevron-right"></i> Inicio</a></li>
                    <li><a href="#curso"><i class="fas fa-chevron-right"></i> El Curso</a></li>
                    <li><a href="#modulos"><i class="fas fa-chevron-right"></i> Módulos</a></li>
                    <li><a href="#evaluacion"><i class="fas fa-chevron-right"></i> Evaluación</a></li>
                    <li><a href="#docente"><i class="fas fa-chevron-right"></i> Docente</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h4>Contacto</h4>
                <ul>
                    <li><a href="mailto:hernan.quiroz@udea.edu.co"><i class="fas fa-envelope"></i> hernan.quiroz@udea.edu.co</a></li>
                    <li><a href="#"><i class="fas fa-map-marker-alt"></i> Universidad de Antioquia</a></li>
                    <li><a href="#"><i class="fas fa-building"></i> Facultad de Educación</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>Universidad de Antioquia · Facultad de Educación · 2025</p>
            <div class="footer-social">
                <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                <a href="#" aria-label="Twitter"><i class="fab fa-x-twitter"></i></a>
                <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                <a href="#" aria-label="YouTube"><i class="fab fa-youtube"></i></a>
            </div>
        </div>
    </footer>

    <script>
        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        });

        const menuToggle = document.getElementById('menuToggle');
        const navLinks = document.getElementById('navLinks');
        menuToggle.addEventListener('click', () => {
            navLinks.classList.toggle('active');
            const icon = menuToggle.querySelector('i');
            icon.classList.toggle('fa-bars');
            icon.classList.toggle('fa-times');
        });

        navLinks.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                navLinks.classList.remove('active');
                const icon = menuToggle.querySelector('i');
                icon.classList.remove('fa-times');
                icon.classList.add('fa-bars');
            });
        });

        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.animate').forEach(el => {
            observer.observe(el);
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    const headerOffset = 80;
                    const elementPosition = target.getBoundingClientRect().top;
                    const offsetPosition = elementPosition + window.pageYOffset - headerOffset;
                    window.scrollTo({
                        top: offsetPosition,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>

</body>
</html>
