@media screen and (max-width: 700px){ /*quando passar de 700px, a tela obedecerá a regra estabelecida no main.css*/
    header .container{
      display: flex;
      flex-direction: column;
    }

    .botao{
      margin-top: 5px;
      width: 300px;
    }
}
/*@media, então, seria um if - else para o css/html/js*/
@media screen and (min-widht:1000px){
  .descricao{
    width: 50%;
  }
}