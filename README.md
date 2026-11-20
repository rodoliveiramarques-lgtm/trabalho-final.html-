# trabalho-final.html-
Apaixonado por Hip Hop desde a infância, uni a programação web ao meu hobby de colecionar clássicos dos anos 2000 para criar este site. A vitrine da MIX MANIA celebra ícones como 50 Cent, Eminem e Snoop Dogg, resgatando a nostalgia dos CDs físicos. Aqui, o código encontra as batidas marcantes que moldaram minha identidade e cultura de rua.


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIX.HIPHOP</title>
    <link rel="stylesheet" href="css/style.css">
     
</head>
<body>
    <header>
        <a href="#" class="logo">MIX MANIA: </a>
        <nav class="navbar">
            <ul>
            <li><a href="#about"></a></li>
            <li><a href="#about">Sobre</a></li>
            <li><a href="#gallery">CDS</a></li>
            <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero"></section>

        <section id="about">
            <h1>Sobre nós</h1>
           <p>A Era de Ouro do Hip Hop de volta às suas mãos.
Nossa loja nasceu da paixão pelos beats pesados, rimas afiadas e a estética inesquecível do Hip Hop dos anos 2000. Aqui você encontra CDs originais e edições clássicas que marcaram uma geração — de 50 Cent e Eminem a Jay-Z, Usher e OutKast. Mais do que mídia física, entregamos nostalgia, cultura de rua e a experiência autêntica de abrir o encarte e dar o play no som.
 </p>
        </section>

        <section id="gallery">
            <h1>Galeria de CDS</h1>
            <img src="img/img.01.jpg" alt="Foto 1"> 
            <img src="img/img.02.jpg" alt="Foto 2">
            <img src="img/img.03.jpg" alt="Foto 3"> 
            <img src="img/img.04.jpg" alt="Foto 4">
            <img src="img/img.05.jpg" alt="Foto 5">

           
                                <hr>
                                <br>
            <h3> 1. Death Row Records (Coletânea / Lendas do G-Funk)

Sobre a Imagem: A icônica formação que definiu o Rap da Costa Oeste nos anos 90 e influenciou toda a geração dos anos 2000, reunindo Snoop Dogg, Dr. Dre, Tupac Shakur (2Pac) e Kurupt sob a lendária gravadora Death Row Records.

Músicas mais tocadas do catálogo: California Love (2Pac feat. Dr. Dre), Nuthin' But A 'G' Thang (Dr. Dre feat. Snoop Dogg) e Ambitionz Az A Ridah (2Pac).</h3><br>
<hr>
<p><br>
    <h3>
2. Snoop Doggy Dogg – Doggystyle (1993)

Sobre a Imagem: O álbum de estreia solo de Snoop Dogg, totalmente produzido por Dr. Dre. A capa ilustrada em estilo quadrinhos (feita por Joe Cool) tornou-se uma das artes mais famosas e colecionáveis da história do Hip Hop, consolidando o som G-Funk.
 Músicas mais tocadas: Gin and Juice, Who Am I (What's My Name)? e Ain't No Fun (If the Homies Can't Have None).

    </h3>
</p>
<br>
<hr>
<p>
    <br>
    <h3>
        
3. 50 Cent – Window Shopper (2005)

- Sobre a Imagem: Single de enorme sucesso lançado na trilha sonora do filme Get Rich or Die Tryin'. A estética minimalista com o rosto em destaque marcou o auge comercial de 50 Cent e da G-Unit na metade dos anos 2000.
- Músicas mais tocadas (Single e Trilha): Window Shopper, Hustler's Ambition e Best Friend.

    </h3>
<br>
</p>
<hr>
<br>
<p>
    <h3>
        
4. Eminem – The Eminem Show (2002)

- Sobre a Imagem: Um dos álbuns mais vendidos da década de 2000 e da história do Rap. A capa mostra Eminem sentado atrás de cortinas vermelhas de teatro, simbolizando o olhar do público sobre sua vida pessoal e fama.
- Músicas mais tocadas: Without Me, Till I Collapse, Cleanin' Out My Closet e Sing for the Moment.

    </h3>
    <br>
</p>
<hr>
<br>
<p>
    <h3>
        
5. Too $hort – Short Dog's in the House (1990)

- Sobre a Imagem: Um clássico fundamental do Rap de Oakland (Bay Area). Conhecido pelas batidas pesadas de grave (bass) feitas para tocar no porta-malas dos carros, este álbum ajudou a moldar a cultura automotiva e o som independente do Hip Hop.
- Músicas mais tocadas: The Ghetto, Short But Funky e Ain't Nothin' But a Word to Me (feat. Ice Cube).
Se você quiser integrar isso diretamente no código do seu site, posso gerar:
- Os cards em HTML e CSS já estilizados com essas imagens, textos e botões de compra.
- Um botão interativo em JavaScript para o cliente ouvir uma prévia ou abrir os detalhes de cada CD em uma janela (Modal).

    </h3>
</p>
<br>
<hr>
<br> 
</h4>
        </section>

        <section id="contact">
            <h1>Contato</h1>
            <form>
                <label>Nome:
                    <input type="text" name="nome">
                </label>
                <label>E-mail:
                    <input type="email" name="email">
                </label>
                <label>Mensagem:
                    <textarea name="mensagem" rows="3"></textarea>
                </label>
                <button type="submit" id="contact-button">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Todos os direitos reservados : Desenvolvido por  R.Marques </p>
    </footer>
    <script src="JS/script.js"></script>

</body>
</html>****

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
JS.SCRIPIT


     const heroSection = document.getElementById('hero');
     if (heroSection) {
        const banners = [
            {
                titulo: " A ERA DE OURO DO HIP HOP ANOS 2000",
                subtitulo: "CDs originais, encartes completos e clássicos inesquecíveis."
            },
            {
                titulo: " RELÍQUIAS PARA SUA COLEÇÃO OU SOM AUTOMOTIVO",
                subtitulo: "De 50 Cent e Eminem a Snoop Dogg e 2Pac."
            },
            {
                titulo: " ENVIO SEGURO PARA TODO O BRASIL",
                subtitulo: "Mídias testadas e embaladas com proteção reforçada."
            }
        ];

        let slideAtual = 0;

        // Cria a caixa de texto dentro do #hero
        const bannerBox = document.createElement('div');
        bannerBox.style.textAlign = 'center';
        bannerBox.style.padding = '60px 20px';
        bannerBox.style.background = 'linear-gradient(135deg, #111 0%, #222 100%)';
        bannerBox.style.color = '#fff';
        bannerBox.style.borderBottom = '3px solid #ffcc00';
        bannerBox.style.transition = 'opacity 0.5s ease';

        heroSection.appendChild(bannerBox);

        function atualizarBanner() {
            bannerBox.style.opacity = '0';
            setTimeout(() => {
                bannerBox.innerHTML = `
                    <h2 style="font-size: 2rem; color: #ffcc00; margin-bottom: 10px;">${banners[slideAtual].titulo}</h2>
                    <p style="font-size: 1.1rem; color: #ddd;">${banners[slideAtual].subtitulo}</p>
                `;
                bannerBox.style.opacity = '1';
                slideAtual = (slideAtual + 1) % banners.length;
            }, 300);
        }

        atualizarBanner();
        setInterval(atualizarBanner, 4000); // Troca a cada 4 segundos
    }

    
    // 2. ZOOM NAS FOTOS DA GALERIA (LIGHTBOX)
    
    const imagensGaleria = document.querySelectorAll('#gallery img');

    // Cria a janela escura (Modal) que fica escondida até clicar na foto
    const modal = document.createElement('div');
    modal.style.display = 'none';
    modal.style.position = 'fixed';
    modal.style.top = '0';
    modal.style.left = '0';
    modal.style.width = '100%';
    modal.style.height = '100%';
    modal.style.backgroundColor = 'rgba(0, 0, 0, 0.9)';
    modal.style.justifyContent = 'center';
    modal.style.alignItems = 'center';
    modal.style.flexDirection = 'column';
    modal.style.zIndex = '9999';
    modal.style.cursor = 'pointer';

    const modalImg = document.createElement('img');
    modalImg.style.maxWidth = '85%';
    modalImg.style.maxHeight = '75%';
    modalImg.style.border = '3px solid #ffcc00';
    modalImg.style.borderRadius = '8px';

    const modalLegenda = document.createElement('p');
    modalLegenda.style.color = '#fff';
    modalLegenda.style.marginTop = '15px';
    modalLegenda.style.fontSize = '1.1rem';

    modal.appendChild(modalImg);
    modal.appendChild(modalLegenda);
    document.body.appendChild(modal);

    // Adiciona o clique em cada foto da galeria
    imagensGaleria.forEach((img, index) => {
        img.style.cursor = 'pointer';
        img.title = 'Clique para ampliar a capa';

        img.addEventListener('click', () => {
            modalImg.src = img.src;
            modalLegenda.textContent = `${img.alt} (Clique em qualquer lugar para fechar)`;
            modal.style.display = 'flex';
        });
    });

    // Fecha o modal ao clicar fora
    modal.addEventListener('click', () => {
        modal.style.display = 'none';
    });

   
    // 3. BOTÃO DE COMPRA RÁPIDA NOS ÁLBUNS
    
    const descricoesAlbuns = document.querySelectorAll('#gallery h3');
    const campoMensagem = document.querySelector('#contact textarea[name="mensagem"]');

    descricoesAlbuns.forEach((h3) => {
        // Pega o título da primeira linha do h3
        const tituloAlbum = h3.innerText.split('\n')[0].trim();

        const btnInteresse = document.createElement('button');
        btnInteresse.textContent = '🛒 Tenho interesse neste CD';
        btnInteresse.style.display = 'block';
        btnInteresse.style.marginTop = '12px';
        btnInteresse.style.padding = '10px 18px';
        btnInteresse.style.backgroundColor = '#ffcc00';
        btnInteresse.style.color = '#111';
        btnInteresse.style.border = 'none';
        btnInteresse.style.borderRadius = '5px';
        btnInteresse.style.fontWeight = 'bold';
        btnInteresse.style.cursor = 'pointer';

        btnInteresse.addEventListener('click', () => {
            if (campoMensagem) {
                campoMensagem.value = `Olá! Gostaria de saber o valor e disponibilidade do CD: ${tituloAlbum}`;
                document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
                campoMensagem.focus();
            }
        });

        h3.appendChild(btnInteresse);
    });

    
    // 4. ENVIO DO FORMULÁRIO DE CONTATO

    const formContato = document.querySelector('#contact form');

    if (formContato) {
        formContato.addEventListener('submit', (evento) => {
            evento.preventDefault(); // Evita que a página recarregue

            const nome = formContato.querySelector('input[name="nome"]').value.trim();
            const email = formContato.querySelector('input[name="email"]').value.trim();
            const mensagem = formContato.querySelector('textarea[name="mensagem"]').value.trim();

            if (!nome || !email || !mensagem) {
                alert(' Por favor, preencha seu Nome, E-mail e a Mensagem antes de enviar!');
                return;
            }

            alert(`✅ Valeu, ${nome}! Recebemos sua mensagem na MIX MANIA. Em breve responderemos no e-mail ${email}.`);
            formContato.reset(); // Limpa os campos após enviar
        });
    }
    (function ativarModoMobile() {
    const header = document.querySelector('header');
    const navbar = document.querySelector('.navbar');
    const listaMenu = document.querySelector('.navbar ul');
    const hero = document.getElementById('hero');

    if (!header || !navbar || !listaMenu) return;

    // Cria o botão hambúrguer (☰)
    const btnMobile = document.createElement('button');
    btnMobile.innerHTML = '☰';
    btnMobile.setAttribute('aria-label', 'Abrir Menu');
    btnMobile.style.background = 'none';
    btnMobile.style.border = '2px solid #ff0000';
    btnMobile.style.color = '#ffffff';
    btnMobile.style.fontSize = '2.4rem';
    btnMobile.style.padding = '4px 12px';
    btnMobile.style.borderRadius = '6px';
    btnMobile.style.cursor = 'pointer';
    btnMobile.style.display = 'none'; // Escondido no computador

    header.appendChild(btnMobile);

    let menuAberto = false;

    // Abre e fecha o menu ao clicar no botão
    btnMobile.addEventListener('click', () => {
        menuAberto = !menuAberto;
        listaMenu.style.display = menuAberto ? 'flex' : 'none';
        btnMobile.innerHTML = menuAberto ? '✕' : '☰';
    });

    // Fecha o menu automaticamente quando o usuário clica em algum link
    listaMenu.querySelectorAll('a').forEach(link => {
        link.addEventListener('click', () => {
            if (window.innerWidth <= 768) {
                menuAberto = false;
                listaMenu.style.display = 'none';
                btnMobile.innerHTML = '☰';
            }
        });
    });

    // Função que adapta o layout conforme o tamanho da tela
    function ajustarLayoutTela() {
        const ehMobile = window.innerWidth <= 768;

        if (ehMobile) {
            btnMobile.style.display = 'block';
            
            // Transforma a lista de links em menu suspenso vertical
            listaMenu.style.display = menuAberto ? 'flex' : 'none';
            listaMenu.style.flexDirection = 'column';
            listaMenu.style.position = 'absolute';
            listaMenu.style.top = '100%';
            listaMenu.style.left = '0';
            listaMenu.style.width = '100%';
            listaMenu.style.backgroundColor = '#000000';
            listaMenu.style.padding = '15px 0';
            listaMenu.style.borderBottom = '2px solid #ff0000';
            listaMenu.style.textAlign = 'center';
            listaMenu.style.gap = '15px';

            // Ajusta a altura do banner Hero para não cortar demais no celular
            if (hero) hero.style.height = '50vh';
        } else {
            // Restaura o visual original para computador
            btnMobile.style.display = 'none';
            menuAberto = false;
            btnMobile.innerHTML = '☰';

            listaMenu.style.display = 'flex';
            listaMenu.style.flexDirection = 'row';
            listaMenu.style.position = 'static';
            listaMenu.style.width = 'auto';
            listaMenu.style.backgroundColor = 'transparent';
            listaMenu.style.padding = '0';
            listaMenu.style.borderBottom = 'none';
            listaMenu.style.gap = '5px';

            if (hero) hero.style.height = '85vh';
        }
    }

    // Executa ao carregar a página e sempre que a tela mudar de tamanho
    ajustarLayoutTela();
    window.addEventListener('resize', ajustarLayoutTela);
})();
// 5. CONFESSO QUE PRECISEI DE UM POUCO DE AJUDA PARA FAZER NESSE QUESITO JS.SCRIPT.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

CSS

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    width: 100%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    background-color: #000000;
}

html {
    font-size: 62.5%;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1.6rem;
}

main {
    flex: 1;
}

header {
    background-color: #000000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 10px rgba(241, 4, 4, 0.5);
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 100;
    padding: 10px 20px;
    min-height: 60px;
}

.logo {
    color: white;
    text-decoration: none;
    font-size: 3rem;
    font-weight: 700;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.5);
}

.navbar ul {
    display: flex;
    list-style: none;
    gap: 5px;
}

.navbar a:link, .navbar a:visited {
    color: white;
    text-decoration: none;
    font-size: 1.8rem;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.5);
    border-radius: 5px;
    padding: 10px 15px;
    transition: background-color 0.3s ease;
}

.navbar a:hover, .navbar a:active {
    color: black;
    text-shadow: 1px 1px 1px rgba(255, 255, 255, 0.1);
    background-color: #ff0000;
}

section {
    padding: 60px 20px;
    width: 100%;
}

#hero {
    width: 100%;
    height: 200vh;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 0;
    animation: trocarFundoHero 6s infinite ease-in-out;
}

@keyframes trocarFundoHero {
    0%, 28% {
        background-image: url('../img/img.01.jpg');
    }
    33%, 61% {
        background-image: url('../img/img.06.jpg');
    }
    66%, 94% {
        background-image: url('../img/img.07.jpg');
    }
}


h1 {
    text-align: center;
    padding: 20px 0;
    font-size: 3rem;
    color: #ffffff;
}

#about {
    padding: 80px 20px;
    text-align: center;
    background-color: #ff0303;
    color: #c8d8cf;
}

#about p {
    font-size: 2rem;
    line-height: 3rem;
    padding-bottom: 20px;
    max-width: 800px;
    margin: 0 auto;
}


#gallery {
    background-color: #000000;
    text-align: center;
    color: #c8d8cf;
    max-width: 1200px;
    margin: 50px auto;
    padding: 40px 20px;
}

#gallery h1 {
    text-align: center;
    color: #ffffff;
    font-size: 2.8rem;
    margin-bottom: 30px;
    text-transform: uppercase;
    letter-spacing: 1px;
}

#gallery img {
    width: 18%;
    aspect-ratio: 1 / 1; /* Mantém todas as capas quadradas iguais a CDs */
    object-fit: cover;
    margin: 0.8%;
    border-radius: 8px;
    border: 2px solid #2c2c2c;
    background-color: #181818;
    padding: 6px;
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.7);
    transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
    vertical-align: top;
}

#gallery img:hover {
    transform: translateY(-8px) scale(1.03);
    border-color: #ff0000;
    box-shadow: 0 10px 25px rgba(255, 204, 0, 0.25);
}

#gallery hr {
    border: none;
    height: 1px;
    background-color: #2a2a2a;
    margin: 25px 0;
}

#gallery h3 {
    background-color: #161616;
    padding: 25px;
    border-radius: 8px;
    border: 1px solid #282828;
    font-weight: 400;
    font-size: 1.6rem;
    text-align: left;
    color: #fcf9f9;
    line-height: 1.7;
    white-space: pre-line; 
    transition: border-color 0.3s ease;
}

#gallery h3:hover {
    border-color: #f80808;
}

#contact {
    background-color: #ff0000;
    display: flex;
    flex-direction: column;
    align-items: center;
}

#contact form {
    width: 100%;
    max-width: 400px;
    display: flex;
    flex-direction: column;
    text-align: left;
}

#contact input, #contact textarea {
    width: 100%;
    padding: 12px;
    font-size: 1.4rem;
    border: none;
    border-radius: 8px;
    margin-bottom: 20px;
}

#contact-button {
    background-color: #f5f4f3;
    color: #000000;
    font-size: 1.6rem;
    padding: 12px;
    border-radius: 8px;
    border: none;
    cursor: pointer;
    width: 100%;
    transition: background-color 0.3s ease;
}

#contact-button:hover {
    background-color: black;
    color: #ffffff;
}

footer {
    width: 100%;
    background-color: #000000;
    color: #ffffff;
    text-align: center;
    padding: 15px 20px;
    font-size: 1.4rem;
    font-weight: 700;
}
