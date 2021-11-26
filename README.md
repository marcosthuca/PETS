# PETS
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mary & Gaby Petshop</title>
    <link rel="stylesheet" href="css/site.css">
</head>

<body>

    <header>
        <h1>
            <img src="img/logo-mari-e-gabi-petshop.svg" alt="Logo Petshop Mari e Gabi">
        </h1>
    </header>

    <nav>
        <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#produtos">Produtos</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li id="itemContato"><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <section class="fundo-verde">
        <div class="conteiner flex-conteiner">
            <div class="col">
                <h2>Sobre nós</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit, fugit deserunt, excepturi ipsam, nihil
                    omnis veritatis rerum nostrum explicabo molestiae magnam porro quibusdam sed repellat tempore
                    similique assumenda nulla eveniet.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio nobis ab nam facere similique
                    pariatur dolorum repellendus fugiat perspiciatis quae rem placeat, optio perferendis nihil explicabo
                    tempora vel ad laborum.</p>
            </div>

            <div class="col">
                <img src="img/img-sobre.jpg" alt="Imagem com cachorrinhos">
            </div>
        </div>
    </section>

    <section id="Produtos">
        <div class="conteiner">
            <h2 class="texto-centralizado">Produtos</h2>
            <p class="texto-centralizado">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Exercitationem dolor
                qui quasi, doloremque earum officia, odit rem pariatur quod quisquam odio similique molestiae totam
                commodi iusto sit molestias eum eligendi.</p>


            <div class="flex-conteiner">

                <article class="produtos">
                    <figure>
                        <img src="img/produto-1.jpg" alt="Produto Pet 1">
                    </figure>
                    <h3>Pet Produto #1</h3>
                    <p>R$ 150,00</p>
                    <a href="#" class="btn-patinha">
                        <img src="img/patinha-preta.png" alt="">
                        Comprar
                    </a>
                </article>
                <article class="produto">
                    <figure>
                        <img src="img/produto-2.jpg" alt="Produto Pet 2">
                    </figure>
                    <h3>Pet Produto #2</h3>
                    <p>R$ 160,00</p>
                    <a href="#" class="btn-patinha">
                        <img src="img/patinha-preta.png" alt="">
                        Comprar
                    </a>
                </article>
                <article class="produto">
                    <figure>
                        <img src="img/produto-3.jpg" alt="Produto Pet 3">
                    </figure>
                    <h3>Pet Produto #3</h3>
                    <p>R$ 170,00</p>
                    <a href="#" class="btn-patinha">
                        <img src="img/patinha-preta.png" alt="">
                        Comprar
                    </a>
                </article>

            </div>
        </div>
    </section>

    <section class="fundo-verde">
        <div class="conteiner flex-conteiner">
            <div class="col">
                <h2>Serviços</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, perspiciatis facilis. Soluta
                    aspernatur mollitia rerum amet quisquam! Laborum sit dolores ipsum itaque iure accusantium earum nam
                    mollitia, hic illo perspiciatis.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In aspernatur sit excepturi molestiae, omnis
                    debitis doloremque temporibus magni enim non magnam, quam tempora nobis labore quibusdam qui
                    repellat accusamus cumque?</p>
            </div>
            <div class="col">
                <img src="img/img-galeria-1.jpg" alt="Cachorro no sofá">
                <img src="img/img-galeria-2.jpg" alt="Fachada da loja">
                <img src="img/img-galeria-3.jpg" alt="Cachorro no banho">
                <img src="img/img-galeria-4.jpg" alt="Cachorros de toalha">
            </div>
        </div>
    </section>

    <section id="contato">
        <div class="conteiner" id contatos>
            <div class="texto-centralizado">
                <h2>Contato</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam distinctio laborum quae illo
                    sequi iure. Harum, dolorem odit fugiat consectetur nam, eaque quis minus magni modi labore, earum ex
                    provident?</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores ipsum temporibus eius aut deleniti
                    minus eligendi earum tempora perspiciatis repellat sint laudantium asperiores cupiditate tempore,
                    esse debitis voluptatem vel ipsa.</p>
            </div>

            <div class="flex-conteiner">
                <div class="col">
                    <form action="">
                        <label for="nome"><strong>Nome:</strong>
                            <input type="text" id="nome" placeholder="Insira o seu nome completo"><br>
                        </label>
                        <label for="email"><strong>E-mail:</strong>
                            <input type="email" id="email" placeholder="exemplo@teste.com.br"><br>
                        </label>
                        <label for="tel"><strong>Telefone:</strong>
                            <input type="tel" id="tel" placeholder="(11) 00000-00000"><br>
                        </label>
                        

                        <label for="assunto"><strong>Assunto:</strong>
                            <input type="text" id="assunto" placeholder="Insira aqui o assunto da mensagem"><br>
                        </label>

                        <label for="msg">
                            <strong>Mensagem:</strong>
                            <textarea name="msg" id="msg" rows="10"
                            placeholder="Insira aqui a sua mensagem"></textarea><br>
                        </label>

                        <div>
                            <button class="btn-patinha"value="enviar">
                                <img src="img/patinha-preta.png" alt="">
                                Enviar
                            </button>
                        </div>

                    </form>
                </div>

                <div class="col">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3653.399970389793!2d-46.768539484913845!3d-23.697406772515766!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5212f9627de5%3A0x1c5ccd29c1a3e96a!2sEtec%20Jardim%20%C3%82ngela!5e0!3m2!1spt-BR!2sbr!4v1637706290313!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                    <p>
                        endereço estrada da baronesa, 1695 - jardim nakamura, são paulo -sp <br>
                        <etrong>CEP</etrong>04941-175 <br>
                        <strong>TEL</strong>(11) 66666-777777
                    </p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="conteiner">
            <p>copyrigh &copy;2019 <strong> </strong> todos os direitos resevados</p>
        </div>
    </footer>



</body>

</html>
