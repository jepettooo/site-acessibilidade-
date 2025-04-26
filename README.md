<!DOCTYPE html> 
<title>Acessibilidade</title>
<img src = https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3Po83Aa-g3oU1fFPjhywTi49p-PDZUoptbw&s > 

<head> <strong> <h1>HISTÓRIA DO BASQUETE</h1> </strong> </head>

<body>

<p> o Basquetebol é um esporte coletivo de invasão praticado entre duas equipes. O jogo é disputado com uma bola, tendo como objetivo colocá-la no cesto fixado nas extremidades da quadra.
    Atualmente, o basquetebol é um dos esportes olímpicos mais populares no mundo. </p> Nas escolas, é um dos esportes mais praticados nas aulas de educação física. </p>
    <p><strong> Você sabia? </strong>
    O termo “basquetebol” vem da língua inglesa, onde “basket” significa “cesto” e “ball”, bola. Portanto, no inglês é Basketball.</p>

    <p>  <h1> Origem e História </h1>
        O basquetebol foi criado pelo professor de Educação Física canadense James Naismith (1861-1940), em 1891. 
        Sua invenção foi desenvolvida quando ele publicou as 13 regras para jogar basquetebol, em 1892.</p>
        <p>Na época, ele trabalhava na Associação Cristã de Moços de Springfield, Massachusetts, nos Estados Unidos.
        A modalidade feminina foi inserida pela professora de educação física Senda Berenson (1868-1954). </p>

        <p>Foi também em 1896 que o esporte chegou ao Brasil, trazido pelo norte-americano Augusto Louis. </p>

        <p> notar que, no início, o esporte era praticado com uma bola semelhante à de futebol. Somente em 1984 que a bola de basquete, tal qual conhecemos hoje, foi desenvolvida.
        O primeiro jogo de basquetebol nas Olimpíadas aconteceu nos Jogos Olímpicos de Berlim, em 1936. No feminino, o basquetebol foi incluído nos Jogos Olímpicos em 1976, em Montreal.
        Esse momento representou uma grande conquista para a disseminação do esporte pelo mundo.</p>

        <p>Em 1932, foi fundada a Federação Internacional de Basquetebol (FIBA), a qual é responsável por organizar os eventos relacionados com o basquetebol ao nível mundial. 
        Atualmente, sua sede está localizada em Genebra, na Suíça, e conta com cerca de 200 países filiados à FIBA.</p> </body>

        <body


        <p> <h1> Regras do Basquetebol </h1>
    No basquetebol o objetivo é inserir a bola no cesto correspondente à sua equipe. Portanto, há dois cestos em cada extremidade de quadra a 3,05 metros do chão. O local onde está o cesto é chamado de tabela.
    Vence a equipe que fizer o maior número de pontos.</p>

    <p>Os pontos variam de acordo com o local em que é realizado o arremesso. Por exemplo, se um lance livre é convertido, é somado um ponto. Lançamentos de dentro da área, são somados dois pontos ao placar.
    Há ainda, os lançamentos que valem três pontos.</p> <p>Estes são contabilizados quando o lançamento convertido é realizado de fora da linha circular, localizada a 6,75 metros de cada cesto.
    O jogo está dividido em 4 tempos, sendo 10 minutos úteis para cada, ou seja, o cronômetro do jogo só avança quando a bola se encontra em jogo.</p>

    <p>Os passes de bola podem ser: passe com a mão, passe de peito, passe quicado, passe de ombro e passe por cima da cabeça.</p>

    <p> Já os arremessos mais utilizados são a bandeja e o jump. As chamadas "enterradas" ocorrem mediante um salto e a colocação da bola no cesto.</p>
</body>

    <p> <h1> Faltas</h1>
        Num jogo de basquete, um jogador não pode fazer mais que 5 faltas. Se isso acontecer, como punição, ele está expulso do jogo. As faltas podem ser cometidas quando há:
        contato ilegal entre os jogadores;
        agressões entre jogadores;
        comportamentos antidesportivos.</p>

        <p> <h1> Jogadores</h1>
            O basquetebol é disputado entre duas equipes de 5 jogadores cada. São classificados em armadores, alas e pivôs.</p>
            <p> Os <strong> Armadores</strong> são responsáveis por organizar o jogo; como característica, 
            geralmente são os jogadores mais baixos do time, mas muito habilidosos, rápidos, com excelentes capacidades de passe.</p>
            <p> Os<strong> Alas</strong> são os jogadores que ficam próximos das linhas laterais. Além da capacidade física, suas principais características são os dribles e os lançamentos de média-longa distância.</p>
            <p> Já os <strong> Pivôs</strong> são responsáveis por defender e atacar o mais perto possível da cesta. Além disso, eles têm como função consegui ganhar os duelos aéreos perto da cesta, por exemplo, rebote. Como característica, geralmente são os atletas mais altos e fortes da equipe. Utilizando essas características físicas e com suas habilidades de jogo, geralmente os pivôs tornam-se grandes pontuadores também
            </p>


<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Controle de Zoom e Fonte</title>
    <style>
        :root {
            --font-size: 16px;
            --zoom-level: 1;
        }
        
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            transition: all 0.3s ease;
            font-size: var(--font-size);
            transform: scale(var(--zoom-level));
            transform-origin: top left;
            width: calc(100% / var(--zoom-level));
            height: calc(100% / var(--zoom-level));
        }
        
        .controls {
    position: fixed;
    top: 20px;       /* Alterado de bottom para top */
    right: 20px;
}
        
        
        .control-group {
            display: flex;
            align-items: center;
            margin: 10px 0;
        }
        
        button {
            padding: 5px 10px;
            margin: 0 5px;
            cursor: pointer;
        }
        
        .value-display {
            min-width: 50px;
            display: inline-block;
            text-align: center;
        }
    </style>
</head>
<body>
   
    
    <div class="controls">
        <div class="control-group">
            <button id="zoom-out">-</button>
            <span id="zoom-value" class="value-display">100%</span>
            <button id="zoom-in">+</button>
            <span>Zoom</span>
        </div>
        <div class="control-group">
            <button id="font-decrease">-</button>
            <span id="font-value" class="value-display">16px</span>
            <button id="font-increase">+</button>
            <span>Fonte</span>
        </div>
        <button id="reset-all">Resetar</button>
    </div>

    <script>
        // Configurações iniciais
        let fontSize = 16;
        let zoomLevel = 1;
        const zoomStep = 0.1;
        const fontStep = 1;
        const minZoom = 0.5;
        const maxZoom = 2;
        const minFont = 12;
        const maxFont = 24;
        
        // Elementos do DOM
        const zoomInBtn = document.getElementById('zoom-in');
        const zoomOutBtn = document.getElementById('zoom-out');
        const zoomValue = document.getElementById('zoom-value');
        const fontIncreaseBtn = document.getElementById('font-increase');
        const fontDecreaseBtn = document.getElementById('font-decrease');
        const fontValue = document.getElementById('font-value');
        const resetBtn = document.getElementById('reset-all');
        
        // Atualizar zoom
        function updateZoom() {
            document.documentElement.style.setProperty('--zoom-level', zoomLevel);
            zoomValue.textContent = `${Math.round(zoomLevel * 100)}%`;
        }
        
        // Atualizar fonte
        function updateFont() {
            document.documentElement.style.setProperty('--font-size', `${fontSize}px`);
            fontValue.textContent = `${fontSize}px`;
        }
        
        // Event listeners
        zoomInBtn.addEventListener('click', () => {
            if (zoomLevel < maxZoom) {
                zoomLevel += zoomStep;
                updateZoom();
            }
        });
        
        zoomOutBtn.addEventListener('click', () => {
            if (zoomLevel > minZoom) {
                zoomLevel -= zoomStep;
                updateZoom();
            }
        });
        
        fontIncreaseBtn.addEventListener('click', () => {
            if (fontSize < maxFont) {
                fontSize += fontStep;
                updateFont();
            }
        });
        
        fontDecreaseBtn.addEventListener('click', () => {
            if (fontSize > minFont) {
                fontSize -= fontStep;
                updateFont();
            }
        });
        
        resetBtn.addEventListener('click', () => {
            zoomLevel = 1;
            fontSize = 16;
            updateZoom();
            updateFont();
        });
        
        // Inicialização
        updateZoom();
        updateFont();
    </script>
</body>
</html>
