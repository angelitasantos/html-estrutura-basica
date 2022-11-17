### Digital Innovation One - HTML Estrutura Básica
#### Aula pratica de tags estruturais e básicas do HTML 03 de julho de 2020
#### Atualizado em 16 de novembro de 2022 (Python/Django)
#### HTML (Estrutura e tags básicas)

[w3schools](https://www.w3schools.com/tags/ref_byfunc.asp)


<h1>HTML Tags Básicas</h1>

<br>
<h2>Cabeçalhos</h2>
<h1 align="center">Cabeçalho h1</h1>
<h2 align="right">Cabeçalho h2</h2>
<h3 align="left">Cabeçalho h3</h3>
<h4 align="center">Cabeçalho h4</h4>
<h5 align="right">Cabeçalho h5</h5>
<h6 align="left">Cabeçalho h6</h6>
<br>
<hr>
<h2>Parágrafos</h2>

<p align="justify">Ao contrário do que se acredita, Lorem Ipsum não é simplesmente um texto
    randômico. Com
    mais de 2000 anos, suas raízes podem ser encontradas em uma obra de literatura latina
    clássica datada de 45 AC. Richard McClintock, um professor de latim do Hampden-Sydney
    College na Virginia, pesquisou uma das mais obscuras palavras em latim, consectetur,
    oriunda de uma passagem de Lorem Ipsum, e, procurando por entre citações da palavra na
    literatura clássica, descobriu a sua indubitável origem. Lorem Ipsum vem das seções
    1.10.32 e 1.10.33 do "de Finibus Bonorum et Malorum" (Os Extremos do Bem e do Mal),
    de Cícero, escrito em 45 AC. Este livro é um tratado de teoria da ética muito popular
    na época da Renascença.</p>

<p align="justify">O trecho padrão original de Lorem Ipsum, usado desde o século XVI,
    está reproduzido
    abaixo para os interessados. Seções 1.10.32 e 1.10.33 de "de Finibus Bonorum et
    Malorum" de Cicero também foram reproduzidas abaixo em sua forma exata original,
    acompanhada das versões para o inglês da tradução feita por H. Rackham em 1914.</p>
<hr>

<h2>Textos com frases separadas com a tag "br" </h2>
Existem muitas variações disponíveis de passagens de Lorem Ipsum, mas a maioria
sofreu algum tipo de alteração, seja por inserção de passagens com humor, ou palavras
aleatórias que não parecem nem um pouco convincentes. Se você pretende usar uma passagem
de Lorem Ipsum, precisa ter certeza de que não há algo embaraçoso escrito escondido no
meio do texto. Todos os geradores de Lorem Ipsum na internet tendem a repetir pedaços
predefinidos conforme necessário, fazendo deste o primeiro gerador de Lorem Ipsum
autêntico da internet. Ele usa um dicionário com mais de 200 palavras em Latim combinado
com um punhado de modelos de estrutura de frases para gerar um Lorem Ipsum com aparência
razoável, livre de repetições, inserções de humor, palavras não características, etc.
<br>
<br>
É um fato conhecido de todos que um leitor se distrairá com o conteúdo de texto legível
de uma página quando estiver examinando sua diagramação. A vantagem de usar Lorem Ipsum
é que ele tem uma distribuição normal de letras, ao contrário de "Conteúdo aqui, conteúdo
aqui", fazendo com que ele tenha uma aparência similar a de um texto legível. Muitos
softwares de publicação e editores de páginas na internet agora usam Lorem Ipsum como
texto-modelo padrão, e uma rápida busca por 'lorem ipsum' mostra vários websites ainda
em sua fase de construção. Várias versões novas surgiram ao longo dos anos, eventualmente
por acidente, e às vezes de propósito (injetando humor, e coisas do gênero).<br>
<hr>

<h2>Formatação de textos</h2>
Uma parte do texto em <strong>negrito</strong>: <br>
<strong>Lorem Ipsum</strong> é simplesmente uma simulação de texto da indústria tipográfica
e de impressos, e vem sendo utilizado desde o século XVI, quando um impressor desconhecido
pegou uma bandeja de tipos e os embaralhou para fazer um livro de modelos de tipos. Lorem
Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica,
permanecendo essencialmente inalterado.<br><br>

Uma parte do texto em <em>itálico</em>: <br>
<em>Lorem Ipsum</em> é simplesmente uma simulação de texto da indústria tipográfica e de
impressos, e vem sendo utilizado desde o século XVI, quando um impressor desconhecido pegou
uma bandeja de tipos e os embaralhou para fazer um livro de modelos de tipos. Lorem Ipsum
sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica,
permanecendo essencialmente inalterado.<br><br>

Uma parte do texto com <u>underline</u>: <br>
<u>Lorem Ipsum</u> é simplesmente uma simulação de texto da indústria tipográfica e de
impressos, e vem sendo utilizado desde o século XVI, quando um impressor desconhecido pegou
uma bandeja de tipos e os embaralhou para fazer um livro de modelos de tipos. Lorem Ipsum
sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica,
permanecendo essencialmente inalterado.<br><br>

Uma parte do texto <strike>errada</strike>: <br>
<strike>Lorem Ipsum</strike> é simplesmente uma simulação de texto da indústria tipográfica
e de impressos, e vem sendo utilizado desde o século XVI, quando um impressor desconhecido
pegou uma bandeja de tipos e os embaralhou para fazer um livro de modelos de tipos. Lorem
Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica,
permanecendo essencialmente inalterado.<br><br>
<hr>

<h2>Listas ordenadas e não ordenadas</h2>

<h3>Não ordenadas</h3>
Type: circle<br>
<ul type="circle">
    <li>Esportes</li>
    <li>Músicas</li>
    <li>Filmes</li>
</ul>
Type: square<br>
<ul type="square">
    <li>Esportes</li>
    <li>Músicas</li>
    <li>Filmes</li>
</ul>
Type: disc (padrão)<br>
<ul type="disc">
    <li>Esportes</li>
    <li>Músicas</li>
    <li>Filmes</li>
</ul>

<h3>Ordenadas</h3>
Type: 1 "numeração sequencial" (padrão)<br>
<ol type="1">
    <li>Principais conceitos</li>
    <li>Veja alguns exemplos</li>
    <li>Referência bibliográfica</li>
</ol>
Type: A "letras maiúsculas sequenciais"<br>
<ol type="A">
    <li>Principais conceitos</li>
    <li>Veja alguns exemplos</li>
    <li>Referência bibliográfica</li>
</ol>
Type: a "letras minúsculas sequenciais"<br>
<ol type="a">
    <li>Principais conceitos</li>
    <li>Veja alguns exemplos</li>
    <li>Referência bibliográfica</li>
</ol>
Type: I "números romanos maiúsculos sequenciais"<br>
<ol type="I">
    <li>Principais conceitos</li>
    <li>Veja alguns exemplos</li>
    <li>Referência bibliográfica</li>
</ol>
Type: i "números romanos minúsculos sequenciais"<br>
<ol type="i">
    <li>Principais conceitos</li>
    <li>Veja alguns exemplos</li>
    <li>Referência bibliográfica</li>
</ol>
<hr>

<h2>Imagens</h2>
<img src="/static/image.jpg" width="400px" height="300">
<hr>

<h2>Links</h2>
Site para criar textos aleatórios:
<a href="https://br.lipsum.com/" target="_blank">Clique aqui</a>

<p>Separar links:</p>
<a href="https://br.lipsum.com/" target="_blank">Home</a>
|
<a href="https://br.lipsum.com/" target="_blank">Quem somos</a>
|
<a href="https://br.lipsum.com/" target="_blank">Fale conosco</a>
<hr>

<h2>Tabelas</h2>
<table border="3" width="600" align="center">
<tr>
    <th>Descricao</th>
    <th>Link</th>
    <th>Quantidade</th>
    <th>Preco Unitario</th>
    <th>Preço Total</th>
</tr>

<tr>
    <td>Lençol para solteiro</td>
    <td><a href="https://br.lipsum.com/" target="_blank">Mais Detalhes</a> </td>
    <td align="center">50</td>
    <td align="right">R$ 10,00</td>
    <td align="right">R$ 500,00</td>
</tr>

<tr>
    <td>Lençol para casal</td>
    <td><a href="https://br.lipsum.com/" target="_blank">Mais Detalhes</a> </td>
    <td align="center">75</td>
    <td align="right">R$ 10,00</td>
    <td align="right">R$ 750,00</td>
</tr>

<tr>
    <td colspan="2">Cupom de desconto</td>
    <td colspan="2" align="center">CPM15022020</td>
    <td align="right">(-) R$ 50,00</td>
</tr>

<tr>
    <td colspan="4">Total a pagar</td>
    <td align="right">R$ 1.200,00</td>
</tr>

<tr>
    <td colspan="5" align="center"><img src="/static/image.jpg" width="400" height="300"></td>
</tr>

</table>

<br>

<hr>

<h2>Formulários</h2>

<form>
Login: <input type="text" name="Login" placeholder="Digite seu login"><br><br>
Senha: <input type="password" name="Senha" placeholder="Digite sua senha"><br><br>
<input type="Button" value="Logar Button">
ou
<input type="Submit" value="Logar Submit"><br><br>

<br>Sexo:<br>
<input type="radio" name="sexo" value="M">Masculino<br>
<input type="radio" name="sexo" value="F">Feminino<br>

<br>Interesses:<br>
<input type="checkbox" name="interesses" value="Futebol">Futebol<br>
<input type="checkbox" name="interesses" value="Música">Música<br>
<input type="checkbox" name="interesses" value="Filmes">Filmes<br>
<input type="checkbox" name="interesses" value="Exposições">Esposições<br>

<br>Estado:<br>
<select>
    <option value="MG">MG</option>
    <option value="SP">SP</option>
    <option value="RJ">RJ</option>
    <option value="ES">ES</option>
</select><br>

<br>Dúvidas ou Sugestões:<br>
<textarea>Deixe aqui seu comentário</textarea><br><br>
<hr>
</form>

<h2>Caracteres especiais (characteres entities e unicode)</h2>

Sites com alguns caracteres especiais:
<a href="http://www.erikasarti.com/html/acentuacao-caracteres-especiais/" target="_blank">Clique aqui</a>
<br>
<br>
Alguns caracteres especiais: &laquo; &raquo; &brvbar; &quot; &ordf; &ordm; &sect; &amp; &copy; &reg; &euro; &pound;
&yen;
<hr>

<br><br>Arquivo: index.html<br><br>
Contém as tags básicas do HTML5<br><br>
Curso: UDEMY Desenvolvimento WEB<br><br>
Instrutor: Jamilton Damasceno<br><br>