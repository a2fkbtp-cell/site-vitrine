[index.html](https://github.com/user-attachments/files/24110882/index.html)
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A2FK – Valorisation CEE Projets Tertiaires</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap');
        
        * {
            font-family: 'Inter', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .scroll-smooth {
            scroll-behavior: smooth;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .fade-in-up {
            animation: fadeInUp 0.8s ease-out;
        }
        
        .stat-number {
            font-size: 3.5rem;
            font-weight: 800;
            line-height: 1;
        }
        
        .section-title {
            font-size: 2.5rem;
            font-weight: 800;
            margin-bottom: 1rem;
        }
        
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full bg-white/95 backdrop-blur-sm shadow-sm z-50">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold gradient-text">A2FK</div>
            <div class="hidden md:flex space-x-8">
                <a href="#principe" class="text-gray-700 hover:text-purple-600 transition">Le principe</a>
                <a href="#valorisation" class="text-gray-700 hover:text-purple-600 transition">Valorisation</a>
                <a href="#process" class="text-gray-700 hover:text-purple-600 transition">Process</a>
                <a href="#faq" class="text-gray-700 hover:text-purple-600 transition">FAQ</a>
                <a href="#contact" class="bg-purple-600 text-white px-6 py-2 rounded-full hover:bg-purple-700 transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg text-white pt-32 pb-20 px-6">
        <div class="max-w-7xl mx-auto text-center fade-in-up">
            <h1 class="text-5xl md:text-6xl font-bold mb-6">
                Transformez vos rénovations<br>en trésorerie
            </h1>
            <p class="text-xl md:text-2xl mb-8 text-purple-100 max-w-3xl mx-auto">
                Valorisation CEE pour projets tertiaires : de 50 000 € à 300 000 € de primes sur vos travaux de rénovation énergétique
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center items-center">
                <a href="/cdn-cgi/l/email-protection#addbc2d9dfc8edc8c0ccc4c183cec2c092ded8cfc7c8ced990e9c8c0ccc3c9c88dc9c88dc9c4cccac3c2ded9c4ce8deee8e88bcfc2c9d490efc2c3c7c2d8df8debccdfc4c981889de9889dec889de9889dece7c88ddec2d8c5ccc4d9c88dc2cfd9c8c3c4df8dd8c38dc9c4cccac3c2ded9c4ce8deee8e88dddc2d8df8dc0c2c38ddddfc2c7c8d983889de9889dec889de9889deceec2dfc9c4ccc1c8c0c8c3d981" class="bg-white text-purple-600 px-8 py-4 rounded-full font-semibold text-lg hover:bg-gray-100 transition">
                    Analyser mon projet
                </a>
                <a href="#principe" class="border-2 border-white text-white px-8 py-4 rounded-full font-semibold text-lg hover:bg-white/10 transition">
                    Comment ça marche ?
                </a>
            </div>
            
            <!-- Stats -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-16 max-w-4xl mx-auto">
                <div class="text-center">
                    <div class="stat-number text-white">90%</div>
                    <p class="text-purple-100 mt-2">des porteurs de projets passent à côté</p>
                </div>
                <div class="text-center">
                    <div class="stat-number text-white">0€</div>
                    <p class="text-purple-100 mt-2">d'avance de frais pour vous</p>
                </div>
                <div class="text-center">
                    <div class="stat-number text-white">48h</div>
                    <p class="text-purple-100 mt-2">pour un diagnostic complet</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Le Principe -->
    <section id="principe" class="py-20 px-6 bg-white">
        <div class="max-w-7xl mx-auto">
            <h2 class="section-title text-center mb-4">Le principe des CEE</h2>
            <p class="text-xl text-gray-600 text-center mb-16 max-w-3xl mx-auto">
                Les Certificats d'Économies d'Énergie (CEE) constituent un dispositif réglementaire créé en 2006 et renforcé progressivement par l'État français dans le cadre de la transition énergétique. 
                Le principe est simple : Les fournisseurs d'énergie (appelés "obligés") - EDF, Total Énergies, Engie, Leclerc, Auchan, Carrefour, etc. - sont contraints par la loi de financer des économies d'énergie sous peine de lourdes pénalités financières. Pour remplir leurs obligations, ils achètent des certificats générés par des travaux d'économies d'énergie réalisés par des professionnels comme vous. Ces certificats se mesurent en kWh cumac (kilowattheure cumulé et actualisé sur la durée de vie des équipements).
            </p>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="card-hover bg-gradient-to-br from-purple-50 to-purple-100 p-8 rounded-2xl">
                    <div class="text-4xl mb-4">🏛️</div>
                    <h3 class="text-2xl font-bold mb-3">Qui finance ?</h3>
                    <p class="text-gray-700">
                        De 50 000 € à 300 000 € selon votre opération.
                        Concrètement pour votre projet : Chaque lot technique de votre rénovation génère des kWh cumac selon des fiches d'opérations standardisées (référentiel PNCEE 2023-2024) : - Isolation thermique Enveloppe (toiture, murs, planchers) - Systèmes CVC performants - Menuiseries hautes performances - Éclairage LED avec détection de présence - ECS solaire thermique ou thermodynamique - Gestion Technique du Bâtiment (GTB) - VMC double flux Ces kWh cumac sont ensuite valorisés auprès des obligés, qui vous versent une prime proportionnelle aux économies d'énergie générées.
                    </p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-2xl">
                    <div class="text-4xl mb-4">💰</div>
                    <h3 class="text-2xl font-bold mb-3">Combien ?</h3>
                    <p class="text-gray-700">
                        De 50 000 € à 300 000 € selon votre opération. Isolation, CVC, éclairage LED, ECS solaire, GTB... Chaque lot technique génère des primes.
                    </p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-green-50 to-green-100 p-8 rounded-2xl">
                    <div class="text-4xl mb-4">⏰</div>
                    <h3 class="text-2xl font-bold mb-3">Quand ?</h3>
                    <p class="text-gray-700">
                        <strong>Tant que les travaux ne sont pas facturés.</strong> Au-delà, la fenêtre se referme définitivement. L'intervention précoce maximise les gisements.
                    </p>
                </div>
            </div>
            
            <div class="mt-16 bg-red-50 border-l-4 border-red-500 p-6 rounded-lg max-w-4xl mx-auto">
                <p class="text-red-900 text-lg">
                    ⚠️ <strong>Point critique :</strong> Une fois les travaux facturés, impossible de valoriser les CEE. La plupart des promoteurs découvrent ce dispositif... trop tard.
                </p>
            </div>
        </div>
    </section>

    <!-- Valorisation -->
    <section id="valorisation" class="py-20 px-6 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <h2 class="section-title text-center mb-4">Exemples de valorisation</h2>
            <p class="text-xl text-gray-600 text-center mb-16 max-w-3xl mx-auto">
                Ces montants sont des primes réelles, versées en trésorerie. Pas de la théorie.
            </p>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Hôtel -->
                <div class="card-hover bg-white p-8 rounded-2xl shadow-lg">
                    <div class="text-5xl mb-4">🏨</div>
                    <h3 class="text-2xl font-bold mb-3">Hôtel 3★ – 80 chambres</h3>
                    <p class="text-gray-600 mb-6">Côte d'Azur, réhabilitation lourde</p>
                    <div class="border-t border-gray-200 pt-4 mb-4">
                        <div class="text-sm text-gray-600 mb-2">Lots valorisables :</div>
                        <ul class="text-sm text-gray-700 space-y-1">
                            <li>✓ Isolation toiture + murs</li>
                            <li>✓ CVC performant</li>
                            <li>✓ ECS solaire thermique</li>
                            <li>✓ LED + détection présence</li>
                            <li>✓ GTB centralisée</li>
                        </ul>
                    </div>
                    <div class="text-3xl font-bold gradient-text">180 000 – 220 000 €</div>
                </div>
                
                <!-- Bureaux -->
                <div class="card-hover bg-white p-8 rounded-2xl shadow-lg">
                    <div class="text-5xl mb-4">🏢</div>
                    <h3 class="text-2xl font-bold mb-3">Immeuble de bureaux</h3>
                    <p class="text-gray-600 mb-6">2 500 m², Paris, restructuration</p>
                    <div class="border-t border-gray-200 pt-4 mb-4">
                        <div class="text-sm text-gray-600 mb-2">Lots valorisables :</div>
                        <ul class="text-sm text-gray-700 space-y-1">
                            <li>✓ Isolation façade (ITE)</li>
                            <li>✓ CVC avec récupération</li>
                            <li>✓ LED bureau + parking</li>
                            <li>✓ Menuiseries hautes perf.</li>
                        </ul>
                    </div>
                    <div class="text-3xl font-bold gradient-text">90 000 – 120 000 €</div>
                </div>
                
                <!-- Logements -->
                <div class="card-hover bg-white p-8 rounded-2xl shadow-lg">
                    <div class="text-5xl mb-4">🏘️</div>
                    <h3 class="text-2xl font-bold mb-3">Logements collectifs</h3>
                    <p class="text-gray-600 mb-6">30 lots, rénovation énergétique</p>
                    <div class="border-t border-gray-200 pt-4 mb-4">
                        <div class="text-sm text-gray-600 mb-2">Lots valorisables :</div>
                        <ul class="text-sm text-gray-700 space-y-1">
                            <li>✓ ITE complète</li>
                            <li>✓ Menuiseries PVC/alu</li>
                            <li>✓ VMC double flux</li>
                            <li>✓ ECS thermodynamique</li>
                            <li>✓ LED parties communes</li>
                        </ul>
                    </div>
                    <div class="text-3xl font-bold gradient-text">150 000 – 180 000 €</div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <p class="text-lg text-gray-600 mb-6">Ces estimations sont basées sur le référentiel PNCEE 2023-2024 et des projets réels.</p>
                <a href="/cdn-cgi/l/email-protection#99eff6edebfcd9fcf4f8f0f5b7faf6f4a6eaecfbf3fcfaeda4dceaedf0f4f8edf0f6f7b9e9ebf6f3fcedb9dadcdcbffbf6fde0a4dbf6f7f3f6ecebb9dff8ebf0fdb5bca9ddbca9d8bca9ddbca9d8d3fcb9eaf6ecf1f8f0edfcb9ecf7fcb9fceaedf0f4f8edf0f6f7b9dadcdcb9e9f6ecebb9f4f6f7b9e9ebf6f3fcedb9a3bca9ddbca9d8bca9ddbca9d8b4b9cde0e9fcb9a3b9bca9ddbca9d8b4b9d5f6faf8f5f0eaf8edf0f6f7b9a3b9bca9ddbca9d8b4b9caecebfff8fafcb9a3b9bca9ddbca9d8b4b9dbecfdfefcedb9edebf8eff8ece1b9a3b9bca9ddbca9d8bca9ddbca9d8daf6ebfdf0f8f5fcf4fcf7edb5" class="inline-block bg-purple-600 text-white px-8 py-4 rounded-full font-semibold text-lg hover:bg-purple-700 transition">
                    Estimer mon projet
                </a>
            </div>
        </div>
    </section>

    <!-- Process -->
    <section id="process" class="py-20 px-6 bg-white">
        <div class="max-w-7xl mx-auto">
            <h2 class="section-title text-center mb-4">Mon accompagnement de A à Z</h2>
            <p class="text-xl text-gray-600 text-center mb-16 max-w-3xl mx-auto">
                Mandataire technique CEE, je pilote l'intégralité du processus pour maximiser vos primes et sécuriser juridiquement vos dossiers.
            </p>
            
            <div class="grid md:grid-cols-2 gap-12 items-start">
                <!-- Timeline -->
                <div class="space-y-8">
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold text-xl">1</div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Audit technique & identification</h3>
                            <p class="text-gray-600">Analyse de vos documents (devis, CCTP, plans) et identification précise des gisements CEE selon le référentiel PNCEE 2025.</p>
                        </div>
                    </div>
                    
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold text-xl">2</div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Calculs & simulations</h3>
                            <p class="text-gray-600">Calculs kWh cumac détaillés, simulations financières et optimisation du montage pour maximiser les primes.</p>
                        </div>
                    </div>
                    
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold text-xl">3</div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Vérification de conformité</h3>
                            <p class="text-gray-600">Contrôle des mentions obligatoires sur devis, validation des performances techniques, sécurisation des jalons documentaires.</p>
                        </div>
                    </div>
                    
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold text-xl">4</div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Interface entreprises</h3>
                            <p class="text-gray-600">Coordination directe avec vos entreprises pour ajuster les devis et garantir la conformité CEE avant signature/facturation.</p>
                        </div>
                    </div>
                    
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold text-xl">5</div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Constitution & dépôt</h3>
                            <p class="text-gray-600">Montage complet des dossiers (preuves, attestations, photos) et dépôt auprès des obligés/délégataires partenaires.</p>
                        </div>
                    </div>
                    
                    <div class="flex gap-4">
                        <div class="flex-shrink-0 w-12 h-12 bg-purple-600 text-white rounded-full flex items-center justify-center font-bold text-xl">6</div>
                        <div>
                            <h3 class="text-xl font-bold mb-2">Valorisation finale</h3>
                            <p class="text-gray-600">Suivi jusqu'au versement des primes sur votre compte. Reporting transparent à chaque étape.Une application nouvelle génération est en cours de développement pour délivrer une expérience utilisateur remarquable et parfaitement adaptée à vos besoins.🚀</p>
                        </div>
                    </div>
                </div>
                
                <!-- Sidebar -->
                <div class="space-y-6">
                    <div class="bg-gradient-to-br from-purple-600 to-purple-800 text-white p-8 rounded-2xl">
                        <h3 class="text-2xl font-bold mb-4">Mon modèle économique</h3>
                        <div class="space-y-4">
                            <div class="flex items-start gap-3">
                                <div class="text-2xl">✓</div>
                                <div>
                                    <p class="font-semibold">Zéro avance de frais</p>
                                    <p class="text-purple-100 text-sm">Vous n'investissez rien</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="text-2xl">✓</div>
                                <div>
                                    <p class="font-semibold">Rémunération sur résultat</p>
                                    <p class="text-purple-100 text-sm">Je ne facture que les primes obtenues</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="text-2xl">✓</div>
                                <div>
                                    <p class="font-semibold">Pas de prime = pas de facturation</p>
                                    <p class="text-purple-100 text-sm">Zéro risque financier pour vous</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-blue-50 border-2 border-blue-200 p-6 rounded-2xl">
                        <h4 class="font-bold text-lg mb-3">⏱️ Délais d'intervention</h4>
                        <ul class="space-y-2 text-gray-700">
                            <li><strong>Projets en cours :</strong> Diagnostic sous 48-72h</li>
                            <li><strong>Projets à venir :</strong> Intégration dès la phase conception</li>
                            <li><strong>Valorisation :</strong> 4-8 mois après facturation des travaux</li>
                        </ul>
                    </div>
                    
                    <div class="bg-green-50 border-2 border-green-200 p-6 rounded-2xl">
                        <h4 class="font-bold text-lg mb-3">🎯 Profils d'opérations</h4>
                        <ul class="space-y-2 text-gray-700">
                            <li>✓ Hôtels, bureaux, commerces</li>
                            <li>✓ Logements collectifs</li>
                            <li>✓ Bâtiments publics</li>
                            <li>✓ Budget travaux min. : 300 000 €</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="py-20 px-6 bg-gray-50">
        <div class="max-w-4xl mx-auto">
            <h2 class="section-title text-center mb-4">Questions fréquentes</h2>
            <p class="text-xl text-gray-600 text-center mb-16">
                Tout ce que vous devez savoir sur la valorisation CEE
            </p>
            
            <div class="space-y-6">
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold mb-3">Pourquoi 90% des porteurs de projets passent à côté ?</h3>
                    <p class="text-gray-700">Parce que valoriser les CEE exige une expertise technique pointue (référentiel PNCEE), une connaissance des fiches d'opérations standardisées, un pilotage documentaire rigoureux, et un timing serré. Sans mandataire spécialisé, c'est quasiment impossible.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold mb-3">Mon projet est déjà en cours, c'est trop tard ?</h3>
                    <p class="text-gray-700">Non, tant que les travaux ne sont pas facturés ! J'ai besoin d'analyser rapidement vos devis signés pour vérifier la conformité et identifier les ajustements nécessaires. Mais attention : au-delà de la facturation, la fenêtre se referme définitivement.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold mb-3">Quels types de travaux génèrent des primes ?</h3>
                    <p class="text-gray-700">Tous les travaux d'amélioration énergétique : isolation (toiture, murs, planchers), menuiseries, CVC performant, ECS solaire/thermodynamique, LED, GTB, VMC double flux, etc. Chaque lot a ses fiches CEE spécifiques avec des exigences de performance.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold mb-3">Combien de temps pour obtenir les primes ?</h3>
                    <p class="text-gray-700">Le versement intervient généralement 1 à 2 mois après la facturation complète des travaux et la validation des dossiers par les obligés. Je gère l'intégralité du suivi jusqu'au paiement final.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold mb-3">Quel est le budget minimum pour que ce soit rentable ?</h3>
                    <p class="text-gray-700">À partir de 300 000 € de travaux, le montage CEE devient intéressant. En dessous, les primes potentielles ne justifient pas toujours le temps de constitution des dossiers. Mais chaque projet est unique, contactez-moi pour une évaluation.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold mb-3">Pourquoi travailler avec vous plutôt qu'un autre mandataire ?</h3>
                    <p class="text-gray-700">Expertise tertiaire spécifique (hôtels, bureaux, logements collectifs), modèle sans risque (pas de prime = pas de facturation), accompagnement personnalisé (cercle restreint de projets), et relations directes avec les principaux obligés pour optimiser les valorisations.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 px-6 gradient-bg text-white">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-4xl font-bold mb-6">Prêt à valoriser votre projet ?</h2>
            <p class="text-xl mb-8 text-purple-100">
                Chaque jour sans analyse CEE, c'est potentiellement des dizaines de milliers d'euros qui s'évaporent.
            </p>
            <a href="/cdn-cgi/l/email-protection#2e58415a5c4b6e4b434f4742004d4143115d5b4c444b4d5a136a4b434f404a4b0e4a4b0e4a474f4940415d5a474d0e6d6b6b0e495c4f5a5b475a084c414a57136c414044415b5c0e684f5c474a020b1e6a0b1e6f0b1e6a0b1e6f644b0e5d415b464f475a4b0e5b400e4a474f4940415d5a474d0e6d6b6b0e495c4f5a5b475a0e5e415b5c0e4341400e5e5c41444b5a000b1e6a0b1e6f0b1e6a0b1e6f674048415c434f5a4741405d0e140b1e6a0b1e6f030e7a575e4b0e4a4b0e5e5c41444b5a0e140e0b1e6a0b1e6f030e62414d4f42475d4f5a4741400e140e0b1e6a0b1e6f030eeda75a4f5a0e4a094f584f404d4b434b405a0e140e0b1e6a0b1e6f0b1e6a0b1e6f6d415c4a474f424b434b405a02" class="inline-block bg-white text-purple-600 px-10 py-5 rounded-full font-bold text-lg hover:bg-gray-100 transition shadow-xl">
                Demander un diagnostic gratuit
            </a>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-20 px-6 bg-white">
        <div class="max-w-4xl mx-auto">
            <h2 class="section-title text-center mb-4">Parlons de votre projet</h2>
            <p class="text-xl text-gray-600 text-center mb-12">
                Envoyez-moi vos documents (devis, CCTP, plans) et je vous fais un retour sous 48-72h
            </p>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <div class="bg-gradient-to-br from-purple-50 to-purple-100 p-8 rounded-2xl mb-6">
                        <h3 class="text-2xl font-bold mb-4">Envoyez-moi un email</h3>
                        <p class="text-gray-700 mb-6">
                            Pour un diagnostic CEE rapide, envoyez-moi directement vos documents et informations projet par email.
                        </p>
                        <a href="/cdn-cgi/l/email-protection#f68099828493b6939b979f9ad895999bc98583949c939582cbb2939b97989293d69293d6929f9791989985829f95d6b5b3b3d09499928fcbb499989c998384d6b097849f92dad3c6b2d3c6b7d3c6b2d3c6b7bc93d68599839e979f8293d699948293989f84d68398d6929f9791989985829f95d6b5b3b3d686998384d69b9998d68684999c9382d8d3c6b2d3c6b7d3c6b2d3c6b7bf989099849b97829f999885d68684999c9382d6ccd3c6b2d3c6b7dbd6a28f8693d69293d68684999c9382d6ccd6d3c6b2d3c6b7dbd6ba9995979a9f8597829f9998d6ccd6d3c6b2d3c6b7dbd6a5838490979593d697868684998e9f9b97829f8093d6ccd6d3c6b2d3c6b7dbd6b48392919382d68284978097838ed69385829f9b355fd6ccd6d3c6b2d3c6b7dbd6357f829782d692d19780979895939b939882d6ccd6d3c6b2d3c6b7d3c6b2d3c6b7b59984929f979a939b939882da" class="block w-full bg-purple-600 text-white px-8 py-4 rounded-lg font-semibold text-lg hover:bg-purple-700 transition text-center">
                            📧 Envoyer un email
                        </a>
                    </div>
                    
                    <div class="bg-white border-2 border-gray-200 p-6 rounded-xl">
                        <h4 class="font-bold text-lg mb-3">📋 Documents à joindre (si disponibles)</h4>
                        <ul class="space-y-2 text-gray-700 text-sm">
                            <li>✓ Devis signés ou versions de travail</li>
                            <li>✓ CCTP / Descriptifs techniques</li>
                            <li>✓ Plans (si pertinent)</li>
                            <li>✓ Planning de facturation</li>
                        </ul>
                    </div>
                </div>
                
                <div class="space-y-6">
                    <div class="bg-gray-50 p-6 rounded-xl">
                        <h3 class="font-bold text-lg mb-4">Coordonnées directes</h3>
                        <div class="space-y-3 text-gray-700">
                            <p><strong>Farid Khemici</strong></p>
                            <p>📞 06 50 57 83 88</p>
                            <p>✉️ a2fkbtpgmail;com</p>
                            <p>📍 Spécialiste projets tertiaires et Réhabilitations complexes</p>
                        </div>
                    </div>
                    
                    <div class="bg-purple-50 border-2 border-purple-200 p-6 rounded-xl">
                        <h3 class="font-bold text-lg mb-3">⚡ Diagnostic express</h3>
                        <p class="text-gray-700 mb-4">Pour un premier retour immédiat, envoyez-moi par email :</p>
                        <ul class="space-y-2 text-gray-700 text-sm">
                            <li>✓ Devis signés (ou versions de travail)</li>
                            <li>✓ CCTP / Descriptifs techniques</li>
                            <li>✓ Surface et localisation</li>
                            <li>✓ Planning facturation</li>
                        </ul>
                    </div>
                    
                    <div class="bg-green-50 border-2 border-green-200 p-6 rounded-xl">
                        <p class="text-gray-800 font-semibold">
                            💡 Vous connaissez d'autres porteurs de projets ? Transférez-leur ce site !
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-12 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-3 gap-8 mb-8">
                <div>
                    <div class="text-2xl font-bold text-white mb-4">A2FK</div>
                    <p class="text-gray-400">Mandataire technique CEE<br>Valorisation énergétique projets tertiaires</p>
                </div>
                <div>
                    <h4 class="font-bold text-white mb-4">Liens rapides</h4>
                    <ul class="space-y-2">
                        <li><a href="#principe" class="hover:text-purple-400 trans
