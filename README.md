
<div>
  <img src="https://user-images.githubusercontent.com/97187822/172213833-7e4e132b-8f03-4ca9-a3f6-5ff1739bfba3.gif" width="400px" height="150px" />
  </div>
  
<p> Fico feliz que esteja aqui vendo meu projeto :wink: </p>
<p> Este foi meu primeiro projeto Web desenvolvido do zero, com dados reais, foi e esta sendo muito importante pra mim </p>

<h2> O projeto está como privado, pois contem dados sensíveis, por esse motivo aqui consta somente a apresentação dele </h2>
<h3> :construction: Projeto Portaria :construction: </h3>

<h3> Objetivo </h3>

<p> O projeto foi criado para auxiliar no controle de entrada e saída dos associados em nossas bases espalhadas pelo pais <p/>

<h3> Tela de Login </h3>

<p> Nessa primeira tela fiz as seguintes validações </p>

<ul>
  <li> Verificação de usuário cadastrado </li>
  <li> O usuário terá acesso à funcionalidade conforme cadastrado no banco </li>
  <li> Utilizei Claims Types como autenticação de cada usuários, assim conseguimos controlar os conteúdos que ele tem acesso e qual base poderá fazer o registro </li>
</ul>
  
<div>
  <img src="https://user-images.githubusercontent.com/97187822/172205609-ec731063-8551-44d4-8a5b-9f3fbe4307a1.png" />
  </div>
  
<h3> Tela inicial </h3>
<p> Aqui podemos ver os conteúdos liberados conformes o registro de cada usuário, cada um possui uma cidade em que podem fazer os registros </p>

<div>
  <img src="https://user-images.githubusercontent.com/97187822/172209065-3715ef70-017b-4685-9413-43ae779194b9.gif" />
  </div>
  
  <h3> Layout </h3>
  <h5> Este layout está sendo mostrado com o usuário administrador logado na plicação apenas para mostrar as funcionalidades </h5>
  <p> Podemos notar que no canto superior esquerdo possui as seguintes funcionalidades: </p>
  
  <ul>
  <li> Inicio da aplicação </li>
  <li> Às duas cidades que possuem as bases e seu registros </li>
  <li> Usuarios: somente o administrador tem acesso, usado para criação de cadastros e alterações </li>
  <li> Chegada: registrar a chegada do veiculo </li>
  <li> Saida: registrar a saida do veiculo </li>
  </ul>
  
  <div>
  <img src="https://user-images.githubusercontent.com/97187822/172211244-904cac1f-a345-407d-a696-5e0434f6463b.gif" />
  </div>
  <h4> Observação </h4>
  <p> As funcionalidades de chegada e saída não tenho permissão para mostrar, pois, envolve dados sigilosos da minha empresa,
  Ela são as principais funções até aqui, possuem algumas validações como: </p>
  
  <ul>
  <li> Função Chegada possui a verificação se ele já está estacionado, se já saiu ou se existe no banco </li>
  <li> Função Saida possui a verificação bem parecida, verifica se o associado possui um registro de chegada e se essa placa não está com pendências </li>
  </ul>
  
  <h3> Atualização V 1.0.1 { 24/06/2022 }</h3>
  
  <h4> Agora minha aplicação conta com geração de relatórios do Crystal Reports :star_struck: </h4>
  
  <p> Agora nosso analista não precisara mais ficar gerando relatórios e enviando para o solicitante, todo usuário com acesso pode 
  exportar os relatórios que desejar </p>
  
  <div>
  <img src="https://user-images.githubusercontent.com/97187822/175658804-5a465f8e-30ad-4d2d-9c05-ef865bf8877c.gif" />
  </div>
  
  <h5> Todos os relatórios possuem parametros e estão prontos, com isso facilita muito na hora da mudança no formulario, sendo necessario 
  a troca somente do arquivo RPT </h5>
  
  <p> Para executá-lo, desenvolvi um formulário de preenchimento conforme os parâmetros do relatório, após preenchido enviamos para um controlador
  que vai coletar os dados e depois passar como parâmetro para o arquivo do relatório, logo em seguida o convertemos para PDF e disponibilizamos para o usuário
  </p>
  
  <p> ⚠️: Foi um dos meus maiores desafio até aqui... </p>
  
  <div>
  <img src="https://user-images.githubusercontent.com/97187822/175660591-fab056ab-817b-4771-8c64-17290ee6022f.gif" />
  </div>
  
  
  
  
  
  
  
  
  
  
