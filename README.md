<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NBA WORLD | Univers Basketball</title>

<style>
* {
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #101522;
    color: white;
    line-height: 1.7;
}

header {
    background: linear-gradient(120deg, #06142e, #164b8c, #e87520);
    text-align: center;
    padding: 45px 15px;
}

header h1 {
    font-size: 42px;
    margin: 0;
}

header p {
    font-size: 18px;
}

nav {
    background: #080c15;
    padding: 15px 8px;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 5px 10px;
    display: inline-block;
    font-weight: bold;
}

nav a:hover {
    color: #ff8c32;
}

.hero {
    min-height: 350px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    padding: 25px;
    background:
    linear-gradient(#0009, #000b),
    url("https://images.unsplash.com/photo-1546519638-68e109498ffc?w=1400")
    center/cover;
}

.hero h2 {
    font-size: 38px;
}

.btn {
    display: inline-block;
    background: #f47b20;
    color: white;
    text-decoration: none;
    padding: 12px 22px;
    border-radius: 6px;
    margin-top: 12px;
    font-weight: bold;
}

section {
    padding: 30px 18px;
    max-width: 1150px;
    margin: auto;
}

h2 {
    color: #ff963d;
    border-bottom: 2px solid #ff963d;
    padding-bottom: 8px;
}

h3 {
    color: #ffbd7c;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: #1b2537;
    border-radius: 12px;
    overflow: hidden;
    padding-bottom: 15px;
    box-shadow: 0 5px 15px #0005;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
}

.card h3,
.card p {
    padding: 0 15px;
}

.info {
    background: #1b2537;
    border-left: 4px solid #ff963d;
    padding: 15px;
    margin: 15px 0;
    border-radius: 6px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 15px;
}

th, td {
    padding: 12px;
    border: 1px solid #45516a;
    text-align: left;
}

th {
    background: #263b5d;
}

tr:nth-child(even) {
    background: #1b2537;
}

footer {
    background: #080c15;
    text-align: center;
    padding: 25px;
    margin-top: 30px;
}

.small {
    color: #c4ccda;
    font-size: 14px;
}

@media(max-width: 600px) {
    header h1 {
        font-size: 32px;
    }

    .hero h2 {
        font-size: 28px;
    }

    nav a {
        font-size: 13px;
        margin: 4px;
    }
}
</style>
</head>

<body>

<header>
    <h1>🏀 NBA WORLD</h1>
    <p>La passion du basketball commence ici !</p>
    <p>Actualités • Joueurs • Équipes • Histoire</p>
</header>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#histoire">Histoire</a>
    <a href="#equipes">Équipes</a>
    <a href="#joueurs">Joueurs</a>
    <a href="#regles">Règles</a>
    <a href="#records">Records</a>
</nav>

<div class="hero" id="accueil">
    <h2>WELCOME TO THE NBA</h2>
    <p>Découvre la plus grande ligue de basketball au monde.</p>
    <a class="btn" href="#histoire">Explorer la NBA</a>
</div>

<section id="histoire">
    <h2>📚 1. L'histoire de la NBA</h2>

    <p>
        La NBA signifie National Basketball Association.
        C'est une ligue professionnelle de basketball masculin
        basée en Amérique du Nord, principalement aux États-Unis.
    </p>

    <div class="info">
        <h3>Les dates importantes</h3>
        <ul>
            <li><strong>1946 :</strong> création de la Basketball Association of America (BAA).</li>
            <li><strong>1949 :</strong> la BAA et la National Basketball League fusionnent ; la NBA adopte son nom actuel.</li>
            <li><strong>Années 1980 :</strong> rivalité historique entre Magic Johnson et Larry Bird.</li>
            <li><strong>Années 1990 :</strong> Michael Jordan et les Chicago Bulls deviennent emblématiques.</li>
            <li><strong>Années 2000 :</strong> Kobe Bryant, Tim Duncan et Shaquille O'Neal marquent la ligue.</li>
            <li><strong>Années 2010 :</strong> LeBron James, Stephen Curry et les Warriors dominent une grande partie de la décennie.</li>
            <li><strong>Aujourd'hui :</strong> la NBA rassemble des joueurs internationaux et des millions de fans.</li>
        </ul>
    </div>

    <img
        src="https://images.unsplash.com/photo-1504450758481-7338eba7524a?w=1000"
        alt="Terrain de basketball"
        style="width:100%;max-height:400px;object-fit:cover;border-radius:12px;"
    >
</section>

<section id="equipes">
    <h2>🏆 2. Quelques grandes équipes NBA</h2>

    <p>
        La NBA compte 30 équipes, réparties entre la Conférence Est
        et la Conférence Ouest.
    </p>

    <div class="grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc?w=600"
                 alt="Basketball en salle">
            <h3>Los Angeles Lakers</h3>
            <p>Une franchise historique associée à des légendes comme Magic Johnson, Kobe Bryant et LeBron James.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1504450758481-7338eba7524a?w=600"
                 alt="Terrain de basketball">
            <h3>Boston Celtics</h3>
            <p>Une franchise historique réputée pour sa tradition collective et ses nombreux titres.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1519861531473-9200262188bf?w=600"
                 alt="Ballon de basketball">
            <h3>Golden State Warriors</h3>
            <p>Une équipe connue pour Stephen Curry et son influence sur le jeu à trois points.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc?w=600"
                 alt="Match de basketball">
            <h3>Chicago Bulls</h3>
            <p>La franchise associée à Michael Jordan et à six titres remportés dans les années 1990.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1519861531473-9200262188bf?w=600"
                 alt="Ballon de basket">
            <h3>Miami Heat</h3>
            <p>Une équipe connue pour sa culture de travail et ses grandes campagnes en playoffs.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1504450758481-7338eba7524a?w=600"
                 alt="Terrain de sport">
            <h3>Milwaukee Bucks</h3>
            <p>Une franchise associée à Giannis Antetokounmpo, champion NBA en 2021.</p>
        </div>

    </div>

    <div class="info">
        <h3>Les deux conférences</h3>
        <p><strong>Conférence Est :</strong> Boston Celtics, New York Knicks, Miami Heat, Chicago Bulls, Milwaukee Bucks et d'autres.</p>
        <p><strong>Conférence Ouest :</strong> Los Angeles Lakers, Golden State Warriors, Denver Nuggets, Phoenix Suns, Dallas Mavericks et d'autres.</p>
    </div>
</section>

<section id="joueurs">
    <h2>🌟 3. Les légendes et les stars du basketball</h2>

    <p>
        Les joueurs NBA se distinguent par leur technique,
        leur intelligence de jeu, leur condition physique
        et leur capacité à travailler en équipe.
    </p>

    <div class="grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1519861531473-9200262188bf?w=600"
                 alt="Ballon de basketball">
            <h3>Michael Jordan</h3>
            <p>Considéré comme l'une des plus grandes légendes de l'histoire du basketball. Il a remporté six titres NBA avec Chicago.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc?w=600"
                 alt="Terrain de basketball">
            <h3>LeBron James</h3>
            <p>Reconnu pour sa polyvalence, sa longévité et son influence sur plusieurs générations de joueurs.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1519861531473-9200262188bf?w=600"
                 alt="Ballon de basket">
            <h3>Stephen Curry</h3>
            <p>Une référence du tir à trois points et l'un des joueurs les plus influents du basketball moderne.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1504450758481-7338eba7524a?w=600"
                 alt="Terrain de basketball">
            <h3>Kobe Bryant</h3>
            <p>Une légende des Lakers, célèbre pour sa technique, sa compétitivité et ses cinq titres NBA.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc?w=600"
                 alt="Basketball en salle">
            <h3>Giannis Antetokounmpo</h3>
            <p>Une superstar grecque d'origine nigériane connue pour sa puissance et ses performances polyvalentes.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1504450758481-7338eba7524a?w=600"
                 alt="Terrain de basket">
            <h3>Nikola Jokić</h3>
            <p>Un pivot serbe réputé pour ses passes, sa vision du jeu et ses qualités de marqueur.</p>
        </div>

    </div>

    <p class="small">
        Note : les photos ci-dessus illustrent le basketball ;
        elles ne représentent pas nécessairement les joueurs cités.
    </p>
</section>

<section id="regles">
    <h2>📖 4. Les règles essentielles de la NBA</h2>

    <div class="info">
        <h3>Durée d'un match</h3>
        <p>Un match NBA comporte quatre quart-temps de 12 minutes, soit 48 minutes de jeu réglementaire. Les arrêts de jeu prolongent la durée réelle.</p>
    </div>

    <div class="info">
        <h3>Comment marquer des points ?</h3>
        <ul>
            <li><strong>1 point :</strong> lancer franc réussi.</li>
            <li><strong>2 points :</strong> panier marqué à l'intérieur de la ligne des trois points.</li>
            <li><strong>3 points :</strong> panier marqué derrière la ligne des trois points.</li>
        </ul>
    </div>

    <div class="info">
        <h3>Les principales violations</h3>
        <ul>
            <li><strong>Marcher :</strong> déplacer ses pieds illégalement en contrôlant le ballon.</li>
            <li><strong>Reprise de dribble :</strong> recommencer à dribbler après avoir arrêté son dribble.</li>
            <li><strong>Retour en zone :</strong> ramener illégalement le ballon dans sa zone arrière après avoir établi le contrôle en zone avant.</li>
            <li><strong>Violation des 24 secondes :</strong> ne pas tenter un tir conforme dans le délai imparti.</li>
        </ul>
    </div>

    <div class="info">
        <h3>Les postes des joueurs</h3>
        <ul>
            <li><strong>Meneur (PG) :</strong> organise le jeu et distribue les passes.</li>
            <li><strong>Arrière (SG) :</strong> apporte souvent du tir et de la création offensive.</li>
            <li><strong>Ailier (SF) :</strong> joue un rôle polyvalent en attaque et en défense.</li>
            <li><strong>Ailier fort (PF) :</strong> participe au rebond et au jeu intérieur.</li>
            <li><strong>Pivot (C) :</strong> protège souvent le panier et participe au rebond.</li>
        </ul>
    </div>
</section>

<section id="records">
    <h2>📊 5. Quelques records et faits historiques</h2>

    <table>
        <tr>
            <th>Joueur</th>
            <th>Fait historique</th>
        </tr>

        <tr>
            <td>Michael Jordan</td>
            <td>6 titres NBA avec les Chicago Bulls.</td>
        </tr>

        <tr>
            <td>LeBron James</td>
            <td>Meilleur marqueur de l'histoire de la saison régulière NBA.</td>
        </tr>

        <tr>
            <td>Stephen Curry</td>
            <td>Référence historique du tir à trois points.</td>
        </tr>

        <tr>
            <td>Bill Russell</td>
            <td>11 titres NBA comme joueur avec les Boston Celtics.</td>
        </tr>

        <tr>
            <td>Wilt Chamberlain</td>
            <td>100 points marqués dans un match en 1962.</td>
        </tr>
    </table>

    <p class="small">
        Les statistiques et records peuvent évoluer. Consulte les sources officielles pour les données les plus récentes.
    </p>
</section>

<section id="playoffs">
    <h2>🔥 6. Comment fonctionnent les playoffs ?</h2>

    <p>
        À la fin de la saison régulière, les équipes qualifiées
        participent aux playoffs. Les équipes s'affrontent dans
        des séries où il faut généralement remporter quatre matchs
        pour passer au tour suivant.
    </p>

    <div class="info">
        <h3>Les grandes étapes</h3>
        <ol>
            <li>Saison régulière.</li>
            <li>Tournoi de play-in pour certaines places qualificatives.</li>
            <li>Premier tour des playoffs.</li>
            <li>Demi-finales de conférence.</li>
            <li>Finales de conférence.</li>
            <li>Finales NBA.</li>
        </ol>
    </div>

    <img
        src="https://images.unsplash.com/photo-1504450758481-7338eba7524a?w=1000"
        alt="Terrain de basketball"
        style="width:100%;max-height:400px;object-fit:cover;border-radius:12px;"
    >
</section>

<section id="vocabulaire">
    <h2>🎓 7. Le vocabulaire du basketball</h2>

    <div class="grid">

        <div class="card">
            <h3>🏀 Dunk</h3>
            <p>Action de marquer en envoyant directement le ballon dans le panier par-dessus le cercle.</p>
        </div>

        <div class="card">
            <h3>🎯 Three-pointer</h3>
            <p>Tir réussi derrière la ligne des trois points.</p>
        </div>

        <div class="card">
            <h3>🛡️ Block</h3>
            <p>Action défensive consistant à contrer un tir.</p>
        </div>

        <div class="card">
            <h3>🤝 Assist</h3>
            <p>Passe qui mène directement à un panier marqué par un coéquipier.</p>
        </div>

        <div class="card">
            <h3>💪 Rebound</h3>
            <p>Récupération du ballon après un tir manqué.</p>
        </div>

        <div class="card">
            <h3>⚡ Steal</h3>
            <p>Interception ou récupération légale du ballon sur l'adversaire.</p>
        </div>

    </div>
</section>

<section id="liens">
    <h2>🌐 8. Pour en apprendre davantage</h2>

    <div class="info">
        <p>🏆 <a href="https://www.nba.com/" target="_blank" rel="noopener" style="color:#ffbd7c;">Site officiel de la NBA</a></p>
        <p>📊 <a href="https://www.basketball-reference.com/" target="_blank" rel="noopener" style="color:#ffbd7c;">Statistiques et histoire du basketball</a></p>
        <p>🏀 <a href="https://www.fiba.basketball/" target="_blank" rel="noopener" style="color:#ffbd7c;">FIBA : basketball international</a></p>
    </div>
</section>

<footer>
    <h3>🏀 NBA WORLD</h3>
    <p>Le basketball, une passion mondiale.</p>
    <p>Site éducatif créé en HTML et CSS.</p>
    <p class="small">© 2026 NBA WORLD — Site indépendant, non affilié à la NBA.</p>
</footer>

</body>
</html>
# News-word
