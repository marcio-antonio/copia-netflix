:root{
    --vermelho: #E50914;
    --preta: #141414;
    /*usar cores como variáveis para adiantar modificações quando necessárias*/
}

*{
  margin: 0; /*zerando para não se alterar em cada tipo de navegador*/
  padding: 0;
  box-sizing: border-box;/* limite de tudo que tá aqui dentro*/
}

/*elementos base*/

body{
  background: var(--preta); /*criou uma variável local como função chamando uma global*/
  font-family: 'Arial', Times, serif;
  color: white;
}
/*toda vez que me refiro a elemento html digito o nome, o mesmo pra classe*/
header .container{
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

header .logo{
  margin-left: 5px;
  color: var(--vermelho);
  font-family: 'Arial Black', Times;
  font-size: 40px;
}

header nav a{
  text-decoration: none;
  color: #AAA;
  margin-right: 10px;
}

header nav a:hover{
  color: #fff;
}

/*filme principal*/
.filme-principal{
  font-size: 16px;
  background: linear-gradient(rgba(0,0,0,.50), rgb(0,0,0,.50)100%), url("capa-house.jpg");

  height: 400px;
  background-size: cover;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}

.filme-principal .descricao{
  margin-top: 10px;
  margin-bottom: 40px;
}

.filme-principal .titulo{
  margin-top: 15%;
  font-size: 40px;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.botao{
  background-color: rgba(0,0,0,.50);
  border:none;
  color: white;

  padding: 15px 30px;
  margin-right: 15px;
  font-size: 12px;

  cursor: pointer; /*indica que é botão ao usuário*/
  transition: .3s ease all;/*animação de transição*/
}

.botao:hover{
  background-color: white;
  color: black;
}

.botao i{
  margin-right: 5px;
}

.container{
  margin-left: 20px;
}

.filme-principal .container{ /*só o container do filme principal será alterado, uma vez que linkei ".filme-principal"*/
  width: 70%;
}

/*construção do carrossel*/
.box-filme{
  height: 100%;
  width: 100%;
  display: block;
}

.carrosel-filmes{
  margin-top: 5px;
}