<!DOCTYPE html>  
<html lang="fr">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Les 4 Piliers Anti-Rechute - Annexes Interactives</title>  
    <link href="https://fonts.googleapis.com/css2?family=The+Seasons&family=Nunito:wght@400;500;600;700&display=swap" rel="stylesheet">  
    <style>  
        * {  
            margin: 0;  
            padding: 0;  
            box-sizing: border-box;  
        }  
        body {  
            font-family: 'Nunito', sans-serif;  
            background: linear-gradient(135deg, #f8f6f2 0%, #e9e4d9 100%);  
            padding: 20px;  
            color: #4a4a4a;  
            line-height: 1.6;  
        }  
        .container {  
            max-width: 1200px;  
            margin: 0 auto;  
            background: white;  
            border-radius: 16px;  
            box-shadow: 0 8px 32px rgba(139, 111, 71, 0.15);  
            overflow: hidden;  
        }  
        header {  
            background: linear-gradient(135deg, #8b6f47 0%, #a0845a 50%, #d4b997 100%);  
            color: white;  
            padding: 40px;  
            text-align: center;  
        }  
        header h1 {  
            font-family: 'The Seasons', cursive;  
            font-size: 2.5em;  
            margin-bottom: 12px;  
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);  
        }  
        header p {  
            font-size: 1.1em;  
            opacity: 0.95;  
            font-weight: 500;  
        }  
          
        /* onglets principaux */  
        .main-tabs {  
            display: flex;  
            background: #f5f3f0;  
            border-bottom: 3px solid #e8d7c3;  
        }  
        .main-tab-btn {  
            flex: 1;  
            padding: 20px;  
            background: none;  
            border: none;  
            cursor: pointer;  
            font-size: 1.1em;  
            font-weight: 600;  
            color: #7a6652;  
            transition: all 0.3s ease;  
            border-bottom: 4px solid transparent;  
            position: relative;  
        }  
        .main-tab-btn.active {  
            background: white;  
            color: #8b6f47;  
            border-bottom: 4px solid #8b6f47;  
        }  
        .main-tab-btn:hover {  
            background: #fafaf7;  
            color: #8b6f47;  
        }  
          
        /* sous-onglets */  
        .sub-tabs {  
            display: flex;  
            background: #fafaf7;  
            border-bottom: 2px solid #e8d7c3;  
            padding: 0 20px;  
        }  
        .sub-tab-btn {  
            flex: 1;  
            padding: 12px 8px;  
            background: none;  
            border: none;  
            cursor: pointer;  
            font-size: 0.9em;  
            font-weight: 500;  
            color: #666;  
            transition: all 0.3s;  
            border-bottom: 2px solid transparent;  
        }  
        .sub-tab-btn.active {  
            color: #8b6f47;  
            border-bottom: 2px solid #8b6f47;  
            background: white;  
        }  
          
        .content {  
            display: none;  
            padding: 0;  
            min-height: 500px;  
        }  
        .content.active {  
            display: block;  
        }  
        .main-content {  
            padding: 30px;  
        }  
        .sub-content {  
            display: none;  
            padding: 30px;  
        }  
        .sub-content.active {  
            display: block;  
        }  
          
        h2 {  
            font-family: 'The Seasons', cursive;  
            color: #8b6f47;  
            font-size: 1.8em;  
            margin-bottom: 20px;  
            padding-bottom: 12px;  
            border-bottom: 3px solid #e8d7c3;  
        }  
        h3 {  
            font-family: 'The Seasons', cursive;  
            color: #a0845a;  
            font-size: 1.3em;  
            margin: 25px 0 15px 0;  
        }  
          
        table {  
            width: 100%;  
            border-collapse: collapse;  
            margin: 20px 0;  
            background: white;  
            border-radius: 8px;  
            overflow: hidden;  
            box-shadow: 0 4px 12px rgba(139, 111, 71, 0.08);  
        }  
        th {  
            background: linear-gradient(135deg, #f0ebe5 0%, #e8d7c3 100%);  
            color: #5a4a3a;  
            padding: 15px;  
            text-align: left;  
            font-weight: 600;  
            font-size: 0.95em;  
            border-bottom: 2px solid #d4b997;  
        }  
        td {  
            padding: 12px 15px;  
            border-bottom: 1px solid #f0ebe5;  
            font-size: 0.9em;  
        }  
        tr:nth-child(even) {  
            background: #fafaf7;  
        }  
          
        input, textarea {  
            width: 100%;  
            padding: 10px;  
            border: 2px solid #d4b997;  
            border-radius: 6px;  
            font-size: 0.9em;  
            font-family: 'Nunito', sans-serif;  
            transition: all 0.3s;  
            background: #fefcf9;  
        }  
        input:focus, textarea:focus {  
            outline: none;  
            border-color: #8b6f47;  
            background: white;  
            box-shadow: 0 0 0 3px rgba(139, 111, 71, 0.1);  
        }  
        textarea {  
            resize: vertical;  
            min-height: 80px;  
        }  
          
        .box {  
            background: linear-gradient(135deg, #fef8f3 0%, #fdf6ef 100%);  
            border-left: 5px solid #d4b997;  
            padding: 20px;  
            margin: 20px 0;  
            border-radius: 8px;  
            box-shadow: 0 2px 8px rgba(212, 185, 151, 0.2);  
        }  
        .box strong {  
            color: #8b6f47;  
            font-weight: 600;  
        }  
          
        .category {  
            background: #fafaf7;  
            padding: 20px;  
            margin: 20px 0;  
            border-left: 4px solid #d4b997;  
            border-radius: 6px;  
        }  
        .category h3 {  
            color: #8b6f47;  
            margin-bottom: 15px;  
        }  
          
        .btn-print {  
            display: block;  
            margin: 40px auto;  
            padding: 15px 40px;  
            background: linear-gradient(135deg, #8b6f47 0%, #a0845a 100%);  
            color: white;  
            border: none;  
            border-radius: 8px;  
            cursor: pointer;  
            font-weight: 600;  
            font-size: 1.1em;  
            font-family: 'Nunito', sans-serif;  
            transition: all 0.3s;  
            box-shadow: 0 4px 15px rgba(139, 111, 71, 0.3);  
        }  
        .btn-print:hover {  
            transform: translateY(-2px);  
            box-shadow: 0 6px 20px rgba(139, 111, 71, 0.4);  
        }  
          
        @media (max-width: 768px) {  
            header h1 { font-size: 2em; }  
            .main-tabs { flex-wrap: wrap; }  
            .main-tab-btn { flex: 1 1 50%; }  
            .sub-tabs { flex-wrap: wrap; }  
            .sub-tab-btn { flex: 1 1 33%; font-size: 0.85em; }  
            table { font-size: 0.85em; }  
            .main-content, .sub-content { padding: 20px; }  
        }  
    </style>  
</head>  
<body>  
    <div class="container">  
        <header>  
            <h1>🏛️ Les 4 Piliers Anti-Rechute</h1>  
            <p>Annexes interactives complètes - Remplis, imprime, réutilise</p>  
        </header>  
  
        <!-- Onglets principaux -->  
        <div class="main-tabs">  
            <button class="main-tab-btn active" onclick="switchMainTab(event, 'pilier1')">Pilier 1</button>  
            <button class="main-tab-btn" onclick="switchMainTab(event, 'pilier2')">Pilier 2</button>  
            <button class="main-tab-btn" onclick="switchMainTab(event, 'pilier3')">Pilier 3</button>  
            <button class="main-tab-btn" onclick="switchMainTab(event, 'pilier4')">Pilier 4</button>  
        </div>  
  
        <!-- PILIER 1 -->  
        <div id="pilier1" class="content active">  
            <div class="sub-tabs">  
                <button class="sub-tab-btn active" onclick="switchSubTab('pilier1', 'p1-1')">Audit Énergétique</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier1', 'p1-2')">Courbe Personnelle</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier1', 'p1-3')">Signaux d'Alerte</button>  
            </div>  
            <div class="main-content">  
                <!-- Sous-content Pilier 1 -->  
                <div id="p1-1" class="sub-content active">  
                    <h2>Audit Énergétique Personnel</h2>  
                    <div class="category">  
                        <h3>Montées d'énergie (✓)</h3>  
                        <input type="text" placeholder="Heures : ex. 8h-11h, 14h-16h">  
                        <textarea placeholder="Activités idéales : ex. création, appels importants"></textarea>  
                    </div>  
                    <div class="category">  
                        <h3>Creux d'énergie (⚠️)</h3>  
                        <input type="text" placeholder="Heures : ex. 11h30-13h, après 17h">  
                        <textarea placeholder="À éviter : ex. décisions lourdes, écran prolongé"></textarea>  
                    </div>  
                </div>  
                <div id="p1-2" class="sub-content">  
                    <h2>Ma Courbe Énergétique</h2>  
                    <table>  
                        <thead>  
                            <tr><th>Heure</th><th>Niveau (1-10)</th><th>Notes</th></tr>  
                        </thead>  
                        <tbody>  
                            <tr><td>7h</td><td><input type="text" placeholder="8"></td><td><input type="text" placeholder="Réveil frais"></td></tr>  
                            <tr><td>9h</td><td><input type="text" placeholder="9"></td><td><input type="text"></td></tr>  
                            <tr><td>11h</td><td><input type="text" placeholder="7"></td><td><input type="text"></td></tr>  
                            <tr><td>13h</td><td><input type="text" placeholder="4"></td><td><input type="text"></td></tr>  
                            <tr><td>15h</td><td><input type="text" placeholder="8"></td><td><input type="text"></td></tr>  
                            <tr><td>17h</td><td><input type="text" placeholder="5"></td><td><input type="text"></td></tr>  
                        </tbody>  
                    </table>  
                </div>  
                <div id="p1-3" class="sub-content">  
                    <h2>Mes Signaux d'Alerte</h2>  
                    <div class="box">  
                        <strong>💡 PHYSIQUES :</strong><br>  
                        <input type="text" placeholder="ex. Tension nuque, douleurs articulaires">  
                    </div>  
                    <div class="box">  
                        <strong>💡 MENTAUX :</strong><br>  
                        <input type="text" placeholder="ex. Brouillard mental, irritabilité">  
                    </div>  
                    <div class="box">  
                        <strong>💡 COMPORTEMENTAUX :</strong><br>  
                        <input type="text" placeholder="ex. Procrastination, oublis">  
                    </div>  
                </div>  
            </div>  
        </div>  
  
        <!-- PILIER 2 -->  
        <div id="pilier2" class="content">  
            <div class="sub-tabs">  
                <button class="sub-tab-btn active" onclick="switchSubTab('pilier2', 'p2-1')">Matrice REA</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier2', 'p2-2')">Fiche de Tri</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier2', 'p2-3')">Mini-Planning</button>  
            </div>  
            <div class="main-content">  
                <div id="p2-1" class="sub-content active">  
                    <h2>Matrice REA des Énergies</h2>  
                    <div class="category">  
                        <h3>🧠 COGNITIVE</h3>  
                        <input type="text" placeholder="1. Emails complexes"><br>  
                        <input type="text" placeholder="2. Réunion"><br>  
                        <input type="text" placeholder="3. Création contenu">  
                    </div>  
                    <div class="category">  
                        <h3>💪 PHYSIQUE</h3>  
                        <input type="text" placeholder="1. Courses"><br>  
                        <input type="text" placeholder="2. Ménage"><br>  
                        <input type="text" placeholder="3. Enfants">  
                    </div>  
                    <div class="category">  
                        <h3>🖱️ NEUROMUSCULAIRE</h3>  
                        <input type="text" placeholder="1. Ordinateur"><br>  
                        <input type="text" placeholder="2. Téléphone"><br>  
                        <input type="text" placeholder="3. Soins">  
                    </div>  
                </div>  
                <div id="p2-2" class="sub-content">  
                    <h2>Fiche de Tri Rapide</h2>  
                    <table>  
                        <thead><tr><th>Tâche</th><th>C/P/N</th><th>Moment idéal</th></tr></thead>  
                        <tbody>  
                            <tr><td><input type="text" placeholder="Tâche 1"></td><td><input type="text" placeholder="C"></td><td><input type="text" placeholder="Montée"></td></tr>  
                            <tr><td><input type="text" placeholder="Tâche 2"></td><td><input type="text" placeholder="P"></td><td><input type="text" placeholder="Creux"></td></tr>  
                            <tr><td><input type="text" placeholder="Tâche 3"></td><td><input type="text" placeholder="N"></td><td><input type="text" placeholder="N'importe"></td></tr>  
                        </tbody>  
                    </table>  
                </div>  
                <div id="p2-3" class="sub-content">  
                    <h2>Mon Planning REA</h2>  
                    <table>  
                        <thead><tr><th>Heure</th><th>Activité REA</th></tr></thead>  
                        <tbody>  
                            <tr><td><input type="text" placeholder="8h-9h"></td><td><input type="text" placeholder="Cognitif montée"></td></tr>  
                            <tr><td><input type="text" placeholder="11h-12h"></td><td><input type="text" placeholder="Physique avant creux"></td></tr>  
                            <tr><td><input type="text" placeholder="14h-15h"></td><td><input type="text" placeholder="Tâches auto"></td></tr>  
                        </tbody>  
                    </table>  
                </div>  
            </div>  
        </div>  
  
        <!-- PILIER 3 -->  
        <div id="pilier3" class="content">  
            <div class="sub-tabs">  
                <button class="sub-tab-btn active" onclick="switchSubTab('pilier3', 'p3-1')">Micro-Pauses</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier3', 'p3-2')">Check-list</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier3', 'p3-3')">Décompression</button>  
            </div>  
            <div class="main-content">  
                <div id="p3-1" class="sub-content active">  
                    <h2>Guide Micro-Pauses</h2>  
                    <table>  
                        <thead><tr><th>Type</th><th>Technique</th><th>Durée</th><th>Effet</th></tr></thead>  
                        <tbody>  
                            <tr><td>🧠 Cognitive</td><td>Respiration 4-7-8</td><td>45s</td><td>Clarté mentale</td></tr>  
                            <tr><td>💪 Physique</td><td>Étirements lombaires</td><td>1min</td><td>Douleur ↓</td></tr>  
                            <tr><td>🖱️ Neuro</td><td>20-20-20 règle</td><td>20s</td><td>Fatigue visuelle ↓</td></tr>  
                        </tbody>  
                    </table>  
                    <div class="box">  
                        <strong>Mes 3 micro-pauses favorites :</strong><br>  
                        <textarea placeholder="1. ..."></textarea>  
                    </div>  
                </div>  
                <div id="p3-2" class="sub-content">  
                    <h2>Check-list Anticipative</h2>  
                    <div class="category">  
                        <h3>Signaux précoces</h3>  
                        <input type="text" placeholder="ex. Yeux qui piquent">  
                    </div>  
                    <div class="category">  
                        <h3>Moments critiques</h3>  
                        <input type="text" placeholder="ex. 14h30-15h30">  
                    </div>  
                </div>  
                <div id="p3-3" class="sub-content">  
                    <h2>Minute Décompression</h2>  
                    <div class="box">  
                        <strong>Script guidé :</strong><br>  
                        <textarea readonly>1. Ferme les yeux  
2. Inspire 4s, retiens 4s, expire 6s (3x)  
3. Détends épaules/nuque/mâchoire  
4. Visualise chaleur dans le bas-ventre  
5. Reviens doucement.</textarea>  
                    </div>  
                    <div class="box">  
                        <strong>Notes post-séance :</strong><br>  
                        <textarea placeholder="Sensation après..."></textarea>  
                    </div>  
                </div>  
            </div>  
        </div>  
  
        <!-- PILIER 4 -->  
        <div id="pilier4" class="content">  
            <div class="sub-tabs">  
                <button class="sub-tab-btn active" onclick="switchSubTab('pilier4', 'p4-1')">Plan Rechute</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier4', 'p4-2')">Déclencheurs</button>  
                <button class="sub-tab-btn" onclick="switchSubTab('pilier4', 'p4-3')">Rituel SOS</button>  
            </div>  
            <div class="main-content">  
                <div id="p4-1" class="sub-content active">  
                    <h2>Plan Anti-Rechute</h2>  
                    <table>  
                        <thead><tr><th>Si symptôme</th><th>Action immédiate</th><th>Prévention</th></tr></thead>  
                        <tbody>  
                            <tr><td><input type="text" placeholder="Douleur +3"></td><td><input type="text" placeholder="Micro-pause 2min"></td><td><input type="text" placeholder="Réduire écran"></td></tr>  
                            <tr><td><input type="text" placeholder="Fatigue mentale"></td><td><input type="text"></td><td><input type="text"></td></tr>  
                        </tbody>  
                    </table>  
                </div>  
                <div id="p4-2" class="sub-content">  
                    <h2>Mes Déclencheurs</h2>  
                    <div class="category">  
                        <h3>Environnementaux</h3>  
                        <textarea placeholder="ex. Stress déménagement, manque sommeil"></textarea>  
                    </div>  
                    <div class="category">  
                        <h3>Habitudes</h3>  
                        <textarea placeholder="ex. Emails soir, pas de pauses"></textarea>  
                    </div>  
                </div>  
                <div id="p4-3" class="sub-content">  
                    <h2>Rituel SOS 5min</h2>  
                    <div class="box">  
                        <strong>Mon kit d'urgence :</strong><br>  
                        <textarea placeholder="1. Huile lavande  
2. Respiration  
3. Étirement  
4. Tisane  
5. ..."></textarea>  
                    </div>  
                </div>  
            </div>  
        </div>  
  
        <button class="btn-print" onclick="window.print()">🖨️ Imprimer Tous les Piliers</button>  
    </div>  
  
    <script>  
        function switchMainTab(event, tabName) {  
            // Main tabs  
            document.querySelectorAll('.content').forEach(c => c.classList.remove('active'));  
            document.querySelectorAll('.main-tab-btn').forEach(b => b.classList.remove('active'));  
            document.getElementById(tabName).classList.add('active');  
            event.target.classList.add('active');  
              
            // Reset sub-tabs  
            const subContents = document.querySelectorAll(`#${tabName} .sub-content`);  
            const subBtns = document.querySelectorAll(`#${tabName} .sub-tab-btn`);  
            subContents.forEach(c => c.classList.remove('active'));  
            subBtns.forEach(b => b.classList.remove('active'));  
              
            // Activate first sub-tab  
            const firstSubContent = document.querySelector(`#${tabName} .sub-content`);  
            const firstSubBtn = document.querySelector(`#${tabName} .sub-tab-btn`);  
            if (firstSubContent && firstSubBtn) {  
                firstSubContent.classList.add('active');  
                firstSubBtn.classList.add('active');  
            }  
        }  
  
        function switchSubTab(pilier, subTabId) {  
            // Sub tabs  
            const subContents = document.querySelectorAll(`#${pilier} .sub-content`);  
            const subBtns = document.querySelectorAll(`#${pilier} .sub-tab-btn`);  
            subContents.forEach(c => c.classList.remove('active'));  
            subBtns.forEach(b => b.classList.remove('active'));  
            document.getElementById(subTabId).classList.add('active');  
            event.target.classList.add('active');  
        }  
    </script>  
</body>  
</html>  
