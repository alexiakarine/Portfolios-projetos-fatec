## :blue_car: 4º Projeto - Hey Alexia
* [GIT Equipe SanjaValley](https://github.com/EquipeFatec/api) 

 <img src = "https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/logoSANJA.png" width= "20%"/>

## :bulb: Projeto 
 <img src = "https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/logoHeyAlexia.PNG" width= "25%"/>

## :briefcase: A empresa
A Oracle Corporation é uma empresa multinacional de tecnologia e informática norte-americana , especializada no desenvolvimento e comercialização de hardware e softwares e de banco de dados.

![logo_empresa](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/oracle-logo.png)

## :clipboard: Solicitação 
Problema
Uma empresa de calçados tem necessidade de conhecer melhor os seus clientes e segmentá-los para descobrir novas demandas de produtos, melhorando a visibilidade da base de clientes. Essa aplicação também pode auxiliar na tomada de decisões dos gerentes e diretores com relação a campanhas e compras de determinados produtos.

## :pushpin: Solução apresentada pelo grupo
Criado pela equipe Sanja Valley, este projeto visa desenvolver uma aplicação para Análise de Dados da empresa de Calçados denominada Hey Alexia, com a importação de arquivos para segmentação e verificação das informações, a fim de auxiliar a gestão da empresa ao permitir visualizar gráficos e dados referentes à estas segmentações.

## :art: Wireframes
<details>
<summary>Protótipos</summary>

Tela do usuário<br>
![tela_PERFIL](https://github.com/alexiakarine/Projeto-integrador/blob/master/Iconss/wireframe_perfil.png)

Tela dashboard<br>
![tela_cadastro_dev](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/wireframe_dashboard.png)

Tela cadastro e login<br>
![tela_inicial](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/wireframe_login.png)

Tela de upload de arquivos <br>
![tela_upload1](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/wireframe_upload.png)

Tela de upload de arquivos
![tela_upload2](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/Grafico_01.png)

Tela de upload de arquivos
![tela_upload](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/Grafico_02.png)
</details>

## :computer: Tecnologias Utilizadas
- GitHub (Utilizado como repositório)
- Linguagem de Programação: Java (Utilizada nos códigos back-end da aplicação)
- Spring Framework (Utiilizado para criar a aplicação)
- IntelliJ (Utilizado como editor de código back-end)
- IDE Vs Code (Utilizado como editor de código front-end)
- VueJS (Utilizada nos códigos front-end da aplicação)
- Oracle | Oracle Clound (Utilizado para armazenamento de dados)

## :books: Contribuições Pessoais

No front-end, usando o Vue.JS, escolhemos a biblioteca Primefaces como apoio para desenvolver toda a parte visual do projeto. Além do axios para a integração do front com o back, na tela principal foram colocados vários gráficos e tabelas afim de exibir os dados parametrizados por grupos específicos de clientes.

<details>
<summary>Códigos da tela Home</summary>
  
A Utilização da biblioteca Splitter e SplitterPanel possibilitou a tela de Login e Cadastro na mesma visualização. Na imagem abaixo, mostra como essa biblioteca foi utilizada junto a as referências dos components Login e Cadastro.

Código home<br>
![register-HOME](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/codigoHOME.PNG)
<br>

No VueJs, as importações das bibliotecas ocorrem em duas etapas, na primeira, é utilizado o import disponibilizazdo pelo primefaces na tag Script, junto aos imports dos components de Login e Cadastro e em seguida é declarado como componente no export default como exibido na imagem abaixo.

![register_HOME](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/codigoHome_.PNG)
<br>

</details>

No menu foi colocado as opções de perfil(possibilitando ao usuário editar os dados como telefone e e-mail por exemplo), manual do usuário (contendo os passos de como utilizar o sistema), upload de arquivos com extensão csv e download dos relatórios gerados pelo sistema espelhando os gráficos.

<details>
<summary>Códigos do component Menu</summary>


Além das bibliotecas citadas anteriormente, foi utilizazdo o conceito de components para o menu lateral exibido na tela principal, assim, a alteração poderia ser realizazda apenas em um local, e utilizazda em mais de uma tela. O Modal na tela Menu foi usado de forma intencional afim de evitar os diversos direcionamentos de tela, uma vez que, neste projeto um dos requisitos funcionais foi a utilização de routers. Inicialmente o modal é chamado dentro da tag Dialog, onde só é exibido no click do botão, nas imagnes abaixo são exibidas essa estrutura.


Código components do menu<br>
![register_2](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/menu.PNG)
<br>

![register1](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu2.PNG)
<br>

![register2](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu3.PNG)
<br>

![register3](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu4.PNG)
<br>


A função do Modal é desenvolvida na parte JavaScript do código, onde inicialmente são declaradas no return do data() como false e no methods passamos o modal como true, desta forma, quando ele só abrirá se for requisitado ao clicar no botão do menu
 
![register4](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu5.PNG)
<br>

![register5](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu6.PNG)
<br>

Por fim, na tag style, temos toda a estilização do dos components usando css.

![register8](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu8.PNG)
<br>

![register9](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu9.PNG)
<br>

![register10](https://github.com/alexiakarine/Projeto-integrador/blob/master/Icons/componenteMenu10.PNG)
<br>
</details>

#### Hard Skills Efetivamente Desenvolvidas
* GitHub (Proeficiência: Sei sem ajuda)
* JavaScript (Proeficiência: Sei fazer com ajuda)
* SpringBoot (Proeficiência: Sei fazer com ajuda)
* Oracle clound (Proeficiência: Sei fazer com ajuda)


#### Soft Skills Efetivamente Desenvolvidas
* Autonomia para desenvolver o front-end utilizando o aprendido em sala de aula
* Trabalho em equipe aprendendo com as dificuldades em prol do objetivo final
* Empatia para entender os limites de cada colega
