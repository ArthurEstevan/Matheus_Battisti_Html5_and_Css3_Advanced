# Aprendendo Recurso Novos do Html5

</br>

### Aprendendo Inserir Midia em Html5
Nas primeiras aulas aprendemos como implementar video, aúdio e imagem.

## Video

> **_Abaixo podemo olhar como adicionar um video ao Html5:_**

```
<video width="definimos largura" height="definimos tamanho" controls (coloca os controles de video)>

  <source src="aqui colocamos o caminho do video" type="tipo de arquivo do nosso video ex: video/mp4">
  
</video>
```

## Áudio

> **_Abaixo podemos olhar como adicionar um audio ao Html5:_**

```
<audio controls (coloca os controles de áudio igual em video)>

  <source src="aqui colocamos o caminho do nosso áudio" type="tipo de arquivo do nosso áudio ex: audio/mpeg">
  // mpeg significa que nosso áudio é do tipo .mp3
  
</audio>
```

## Imagem

> **_Abaixo podemos olhar como adicionar uma imagem e um texto logo abaixo dela ao Html5:_**

```
// figure nos permite adicionar textos abaixo da imagem usando a tag <figcaption> TEXTO AQUI </figcaption>

<figure>

	<img src="aqui colocamos o caminho da nossa imagem" alt="definimos uma descrição da imagem">
  
	<figcaption>
		Dentro dessa tag podemos adicionar um texto abaixo da imagem.
	</figcaption>
  
</figure>
```

----------------------------------------

### Aprendendo Atributos de Formulário em Html5
Nessa aula aprendemos como implementar atributos em nossos formulários do Html5.

## Required

```
// validação de formulário antes eram feitas a partir de Javascript, porém, com o novo Html5 podemos usar o atributo required

<input type="text" name="nome" required>
<input type="submit" name="enviar">

// dessa maneira o nosso input precisa ser preenchido para o submit funcionar
```

## Placeholder

```
// Podemos utilizar o placeholder para indicar do que se trata o campo

<label>Nome: </label>
<input type="text" name="nome" required placeholder="informe seu nome">
<input type="submit" name="enviar">
```

## Type="email"

```
// esse type funciona mais como uma validação do novo Html5, permite que a gente valide se o usúario realmente digitou um e-mail

<label>E-mail: </label>
<input type="email" name="email" required placeholder="informe seu e-mail">
<input type="submit" nome="enviar">
```

## Autofocus

```
// permite que quando iniciarmos a página o campo que tiver autofocus será automaticamente selecionado para o usúario digitar

<label>E-mail: </label>
<input type="email" name="email" required placeholder="informe seu e-mail" autofocus>
<input type="submit" nome="enviar">
```

----------------------------------------

### Aprendendo Atributos de Edição em Tempo Real de Parágrafo
Nessa aula apenas aprendemos um atributo chamado contenteditable.

## Contenteditable

```
// esse atributo serve para que possamos editar o parágrafo em tempo real em nosso web site
// lembrando que isso não altera o conteúdo raiz do projeto, apenas altera a visualização na web para o usúario

<p contenteditable="true"> Meu parágrafo que pode ser editado </p>

// por que utlizar isso? 
// r: em uma aplicação de grande nível podemos utilizar do Javascript para captar essas alterções e atualizar o banco de dados
```
----------------------------------------

### Estudando Sobre Tags Semânticas em Html5
Nessa aula um pouco mais teorica aprendemos sobre as tags semânticas do Html5.

## Header
> // essa tag serve para informar o cabeçalho do nosso site, onde o usúario vai entrar e se deparar com a primeira impressão do nosso site
> // dentro dela temos uma das tags bem conhecida em Html5, a nossa navbar que serve para navegação dentro do nosso web site

## Article
> // um nome bem descritivo, indica o artigo principal do nosso site, onde temos as informações do que estamos tentando passar ao público
> // dentro dela podemos ter o nosso figure, exatamente, figure se encaixa como uma tag semântica, então sempre lembre-se de utlizar bem o figure em web sites

## Aside
> // não menos importante que o Article, porém, funciona com um subtexto em nosso site, onde deixamos as informações relevantes do que estamos explicando em primeiro plano

## Footer
> // por fim temos o footer que apresenta o final da nossa página, onde deixamos redes sociais, mensagens de copyright ou até mesmo um seção de contato
