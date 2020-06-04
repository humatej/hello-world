# hello-world
<!DOCTYPE html>
<html>
<head>
	<title>Zubrohlava</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.js">
	</script>
	<script src="galleria/galleria-1.5.7.min.js"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous">
	</script>
	<script type="text/javascript">
				// When the user scrolls the page, execute myFunction
window.onscroll = function() {myFunction()};

// Get the navbar
var navbar = document.getElementById("navbar");

// Get the offset position of the navbar
var sticky = navbar.offsetTop;

// Add the sticky class to the navbar when you reach its scroll position. Remove "sticky" when you leave the scroll position
function myFunction() {
  if (window.pageYOffset >= sticky) {
    navbar.classList.add("sticky")
  } else {
    navbar.classList.remove("sticky");
  }
}
	</script>
	<script type="text/javascript">

		var a1=0,a2=0,a3=0;
		function myFunction(el)
		{

			id="b"+el;
			btnId="btn"+el;
			var btn = document.getElementById(btnId);
			var css = document.getElementById(id).style;
			if (btn.innerHTML=="viac") 
			{
				css.height="750px";
				btn.innerHTML="menej";
			}
			else
			{
				css.height="150px";
				btn.innerHTML="viac";
				
			
			}
		}
		var id1_n=1;
		function lf(el)
		{
			id="i"+el;
			var imgChange = document.getElementById(id);
			var ide= imgChange.alt;
			var d_id=ide.substring(1)-1;
			if (imgChange.alt=="r1")
			{
				d_id="5";
			}
			imgChange.alt="r"+d_id;
				switch(el)
				{
					case 1:
					imgChange.src="img/rozhlad"+d_id+".jpg";
					break;
					case 2:
					imgChange.src="img/kycera"+d_id+".jpg";
		     		break;
					case 3:
					imgChange.src="img/moto"+d_id+".jpg";
					break;
					case 4:
					imgChange.src="img/rozhlad"+d_id+".jpg";
					break;
					case 5:
					imgChange.src="img/beh"+d_id+".jpg";
					break;
					case 6:
					imgChange.src="img/dozinky"+d_id+".jpg";
					break;
					case 7:
					imgChange.src="img/betlehem"+d_id+".jpg";
					break;
					case 8:
					imgChange.src="img/pochov"+d_id+".jpg";
					break;
					case 9:
					imgChange.src="img/ormz"+d_id+".jpg";
					break;
					case 10:
					imgChange.src="img/ples"+d_id+".jpg";
					break;
				}
			
		}
		function rf(el) {
		id="i"+el;
			var imgChange = document.getElementById(id);
			var ide= imgChange.alt;
			var d_id=parseInt(ide.substring(1))+1;
			if (imgChange.alt=="r5")
			{
				d_id="1";
			}
				imgChange.alt="r"+d_id;
				switch(el)
				{
					case 1:
					imgChange.src="img/rozhlad"+d_id+".jpg";
					break;
					case 2:
					imgChange.src="img/kycera"+d_id+".jpg";
		     		break;
					case 3:
					imgChange.src="img/moto"+d_id+".jpg";
					break;
					case 4:
					imgChange.src="img/rozhlad"+d_id+".jpg";
					break;
					case 5:
					imgChange.src="img/beh"+d_id+".jpg";
					break;
					case 6:
					imgChange.src="img/dozinky"+d_id+".jpg";
					break;
					case 7:
					imgChange.src="img/betlehem"+d_id+".jpg";
					break;
					case 8:
					imgChange.src="img/pochov"+d_id+".jpg";
					break;
					case 9:
					imgChange.src="img/ormz"+d_id+".jpg";
					break;
					case 10:
					imgChange.src="img/ples"+d_id+".jpg";
					break;
				}
			}
			
	</script>
</head>
<div style="height: 200px;background-color: black" >

</div>
<body>
	<nav id="navbar" class="navbar navbar-dark navbar-expand-sm bg-dark-green ">
		<ul class="navbar-nav">
			<li class="nav-item">
				<a href="#domov" class="nav-link">Domov</a>
			</li>
			<li class="nav-item">
				<a href="#history" class="nav-link">Historia</a>
			</li>
			<li class="nav-item">
				<a href="#miesta" class="nav-link">Miesta</a>
			</li>
			<li class="nav-item">
				<a href="#podujatia" class="nav-link">Podujatia</a>
			</li>
		</ul>
		<ul class="navbar-nav ml-md-auto">
			<li class="nav-brand float-right">
				<a href="index.html" class="nav-link"><img src="img/logo.png"></a>
			</li>
		</ul>
	</nav>
	<div id="domov" class="container pt-4 pb-4">
		<div id="history" class="row">
			<div id="d_1" class="col-sm-6 my-auto">
					<h1>Základné informácie</h1>
					<p>
					Zubrohlava je dedina nachádzajúca sa na severe Oravy. Dedina má okolo 2400 obyvateľov. Je to obec s bohatou <strong>platenickóu históriou</strong>. Okrem toho z nej pochádzajú známy rodáci ako napríklad <strong>Ján Gustiny</strong>. Nachádzajú sa tu taktiež zaujímavé miesta, ktoré by bolo dobre ak by ste ich navštívili . Dúfam, že vám táto stránka pomôže spoznať <strong>Zubrohlavu</strong> bližsie<div class="ico"></div>
					</p>
			</div>
			<div class="col-sm-6">
				<div class="gmap_canvas img-thumbnail">
					<iframe width="600" height="300" id="gmap_canvas" src="https://maps.google.com/maps?q=Zubrohlava&t=k&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0">
					
					</iframe>
					<a href="https://www.crocothemes.net"></a>
				</div>
			</div>
		</div>
	</div>
	<div id="history"class="jumbotron text-center bg-my-y text-light">
			<h1>História</h1>
	</div>
	<div id="historia" class="container-fluid">
		<div class="flex">
			<div class="row justify-content-center ">
			<div class="col-sm-3">
				<div class="col-sm-12 pt-4">
					<img src="img/17-zub.jpg" class="col-sm-12 my-auto img-fluid">
				</div>
				<h2 class="text-center">16-17 str.</h2>
				<p class="ml border" id="b1">
					Prvá písomná zmienka o obci pochádza z roku <strong>1550.</strong> Pôvodný názov bol <strong><q>Zbracslaua.</q></strong> V roku 1599 bolo v dedine 6 domov. V nasledujúcich rokoch počet zdanených domov klesal.<br>
					<br>
					V roku 1605 sa aj na Oravu rozšírilo<strong> povstanie Štefana Bočkaja</strong>, ktoré kruto zasiahlo do života našej obce. Bočkajovi hajdúsi vyplienili takmer celú Oravu, medzi nimi i našu obec. Po skončení povstania bol v r. 1608 v Zubrohlave na zdanenie súci iba jeden dom. Stará dedina v Bučkách zanikla a osídlila sa na novom mieste, kde sa nachádza aj v súčasnosti. V roku 1609 mala obec už aj mlyn na jeden kameň, ale v novej dedine boli ešte len 4 domy.
					<br>
					<br>4. októbra 1683, mesiac po bitke pri Viedni vtrhli na Oravu zadné voje poľského kráľa Jána Sobieskeho pod velením litovského hajtmana Kazimíra Sapiehu. Dobyli Oravský hrad, kuruckej posádke poodtínali hlavy a okolo hradu ich narazili na koly. Na celej Orave pálili, lúpili, vraždili. Čo neulúpili, to spálili. Na Orave vypálili 27 dedín, medzi nimi aj obec Zubrohlavu. Po porážke Turkov cisárske vojská znovu obsadili územie Slovenska. Obce však boli <strong>vyplienené</strong>, na jar 1685 nebolo čo siať.
				</p>
				<button onclick="myFunction(1)" class="text-center btn btn-dark text-light" id="btn1" style="font-weight: bold;">viac</button>
			</div>
			<div class="col-sm-3">
				<div class="col-sm-12 pt-4">
				<img src="img/19-zub.png"  class="col-sm-12 my-auto img-fluid">
			</div>
				<h2 class="text-center">18-19 str.</h2>
				<p id="b2" class="ml border">
					 V roku 1720 už na šoltýskych raliach žilo 11 osadníkov. Rozrastajúce sa rodiny oravská zem nedokázala uživiť. Už v roku 1728 Zubrohlavčania chodili na zárobky na juh: ako<strong>kupci s plátnom</strong>, alebo na sezónne práce v poľnohospodárstve. V Zubrohlave bolo 33 predavačov plátna, ktorí ho rozvážali na vozoch.<br>
					 <br>
					 V roku 1783 sa v Zubrohlave prvýkrát uvádza nová rastlina (zemiaky) <strong>„nejaká repka, švábka nazývaná, ktorá sa rozmáha“.</strong> Rozmach plátenníctva od pestovania ľanu, po výrobu nití, tkania plátna, jeho bielenia a farbenia spôsobil, že aj v našej obci v roku 1788 postavil budovu mangľa Žid Jozef Kunst, ktorý konvertoval na katolícku vieru. Od roku 1873 funguje poštový úrad.Po zániku poddanstva bol v roku 1850 prvýkrát zameraný zubrohlavský chotár.<br>
					 <br>
					 V roku 1871 vznikol obvodný notársky úrad v Bobrove, prvým notárom sa stal Matej Tomaštík zo Zubrohlavy. V roku 1895 vznikli civilné matričné úrady v mieste farností. Prvým matrikárom v Zubrohlave bol Michal Bohucký, po ňom Vendelín Krššák.
				</p>
				<button onclick="myFunction(2)"  class="text-center btn btn-dark text-light" id="btn2" style="font-weight: bold;">viac</button>
			</div>
			<div class="col-sm-3">
				<div class="col-sm-12 pt-4">
				<img src="img/20-zub.jpg"  class="col-sm-12 my-auto img-fluid">
			</div>
				<h2 class="text-center">20-21 str.</h2>
				<p id="b3" class="ml border">
					sdafsakjfklasjfkljda
					gdsagsdkjflaôks
					gddasgsdafgags
					gdsagsdkjflaôks
					gddasgsdafgags
					adsffasgdsagsdkjflaôks
					gddasgsdafgags
					adsffas
				</p>
				<button onclick="myFunction(3)" class="text-center btn btn-dark text-light" id="btn3" style="font-weight: bold;">viac</button>
			</div>
		</div>
	  </div>
	</div>
	<div class="jumbotron text-center bg-my-b text-light">
		<h1>Miesta ktoré musíte navštíviť</h1>
	</div>
	<div id="miesta" class="container-fluid">
		<div class="row">
			<div class="col-sm-6 my-auto">
				<h2 class="ml-4">Rozhľadňa</h2>
				<p class="col-sm-11 ml-2">Ku tejto nedávno postavenej rozhľadni vedie spevnená makadámová cesta. Taktiež sa tu nachádza malý altánok zo stolmi takže sa budete  mať najesť a odýchnuť &#128512;. V rozhľadni nechýba horopis podľa, ktorého zistite vlastne čo to je za nádhera na, ktorú sa pozeráte. Je znej nádherný výhľad na Západné Tatry, čiže <strong>Roháče</strong>. Ak by ste pokračovvali ďalej dostanete sa tu <strong>Kýčere</strong></p>
			</div>
			<div class="galery col-sm-6 flex justify-content-center">
				<img id="i1"src="img/rozhlad1.jpg" class=" float-right  mt-4 img-thumbnail" alt="r1">
					<button onclick="lf(1)" class="l-button mx-auto btn btn-dark text-light" style="font-size: 120%;font-weight: 900"><</button>
					<button onclick="rf(1)" class="r-button mx-auto btn btn-dark text-light" style="font-size: 120%;font-weight: 900">></button>

			</div>
			<div class="col-sm-6 my-auto">
				<h2 class="ml-4">kaplnka Sedembolestnej Panny Márie - Kýčera</h2>
				<p class="col-sm-11 ml-2">Cesta ku <strong>Kýčere</strong> je rovnaká ako ku rozhľadni avšak je dlhšia od Rozhľadne je to iba kúsok navyše &#128512;. Na mieste kde sa nachádza kaplnka v minulosti vznikla samotná Zubrohlava. Teraz sú ku kaplne pristavené Dva altánky. Jeden ako pódium a druhý ako <strong>cykloprístrešok</strong> pre väčšiu skupinu ľudí. Taktiež tu nájdete zatvorený ihlan na opekanie a mnoho stolou po vonku. Nechýbajú tu ani kadibudky a je tu nádherná lúka na, ktorej sa dajú uskutočnovať rôzne podujatia. Nájdete tu aj <strong>malé ihrisko</strong>. Ak by ste pokračovali ďalej dostali by ste sa <strong>cez cyklotrasu</strong> do Rabčíc odkiaľ ide cyklotrasa do Poľska  </p>
			</div>
			<div class="galery col-sm-6 flex justify-content-center">
				<img id="i2" src="img/kycera1.jpg" class="float-right mt-4 img-thumbnail" alt="r1">
				
					<button onclick="lf(2)" class="l-button mx-auto btn btn-dark text-light" style="font-size: 120%;font-weight: 900"><</button>
					<button onclick="rf(2)" class="r-button mx-auto btn btn-dark text-light" style="font-size: 120%;font-weight: 900">></button>

			</div>
			<div class="col-sm-6 my-auto">
				<h2>motocross </h2>
				<p >sdafsakjfklasjfkljda
					gdsagsdkjflaôks
					gddasgsdafgags
					gdsagsdkjflaôks
					gddasgsdafgags
					adsffasgdsagsdkjflaôks
					gddasgsdafgags
					adsffas</p>
			</div>
			<div class="galery col-sm-6 flex justify-content-center">
				<img id="i3" src="img/moto1.jpg" class="float-right mt-4 img-thumbnail" alt="r1">
				
					<button onclick="lf(3)" class="l-button mx-auto btn btn-dark text-light" style="font-size: 120%;font-weight: 900"><</button>
					<button onclick="rf(3)" class="r-button mx-auto btn btn-dark text-light" style="font-size: 120%;font-weight: 900">></button>

			</div>

		</div>	
	</div>
	<div id="podujatia"class="jumbotron text-center mt-4">
		<h1>Podujatia</h1>
	</div>
	<div id="podujatia" class="container-fluid">
		<div class="row">
			<div class="col-sm-4">
				<h2 class="text-center"> Beh Zubrohlavským Chotárom</h2>
				<p class="col-sm-12">
					Beh sa beží na pamiatku zomrelého <strong>Petra Stoklasu</strong>, ktorý zomrel počas behu. Akcia sa koná každý rok začiatkom septembra. Na vyber sú dve trasi <strong>5km a 11km</strong>. Každý rok pri kúpe registračného čísla dostanete nejakú pamätnú vec &#128512;. Samozrejme výhra neostane bez odmeny.  Zaregistrovať sa dá tu: <a href="http://www.behzubrohlava.sk/" target="_blanked">behzubrohlava.sk</a>
				</p>
				<div class="galery col-sm-12 flex justify-content-center">
				<img id="i5" src="img/beh1.jpg" class=" img-thumbnail" alt="r1">
				
					<button onclick="lf(5)" class="l-button  l-button-smmx-auto btn btn-dark text-light" style="font-weight: 900"><</button>
					<button onclick="rf(5)" class="r-button r-button-sm mx-auto btn btn-dark text-light" style="font-weight: 900">></button>

			</div>

			</div>
			<div class="col-sm-4">
				<h2 class="text-center"> Dožinková slávnosť</h2>
				<p class="col-sm-12">
					Alebo inač povedané <strong>poďakovanie za úrodu</strong>, ktoré je sprevádzané sv. omšou pri Kýčere. Je tu postarané o jedlo a nápoje v podobe gulášu a piva alebo kofoly. Taktiež tu bývajú rôzne stánky a nechýba tu kultúrny program v podobe miestnych spevokolov. Pre deti tu je <strong>prechádzka na koči</strong>. A k tomu všetkému je z Kyčery nádherný výhľad na<strong>Babiu horu</strong>.
				</p>
				<div class="galery col-sm-12 flex justify-content-center">
				<img id="i6" src="img/dozinky1.jpg" class=" img-thumbnail" alt="r1">
				
					<button onclick="lf(6)" class="l-button l-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900"><</button>
					<button onclick="rf(6)" class="r-button r-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900">></button>

				</div>
			</div>
			<div class="col-sm-4">
				<h2 class="text-center">Betlehemy Babej hory</h2>
				<p class="col-sm-12">
					Táto udalosť zatiaľ funguje 7 rokov. Každoročne cez zimu je tu súťaž o to kto spravý krajší betlehém. Rozdeľuje sa to na rôzne kategórie ako juniory a, dospelý a podobne. Súťaž prebieha hlasovacou formou. Počas výstavy nechýba niečo na občerstvenie a pitie. Taktiež tu býva<strong> bohatý kultúrny program</strong>. A minulý rok bol napríklad aj betlehém z živími ovcami.
				</p>
				<div class="galery col-sm-12 flex justify-content-center">
				<img id="i7" src="img/betlehem1.jpg" class=" img-thumbnail" alt="r1">
				
					<button onclick="lf(7)" class="l-button l-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900"><</button>
					<button onclick="rf(7)" class="r-button r-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900">></button>

				</div>
			</div>
			<div class="col-sm-4">
				<h2 class="text-center">Pochovávanie basy</h2>
				<p class="col-sm-12">
					Samotný názov už hovorí za všetko je to akcia kde rozhodne nechýba jedlo, nápoje a zábava. Každoročne sa toto pochovavanie basy koná  kultúrnom dome. Najdete tu kopu mäsa, klobások, syrom... Samozrejme, že je tu postarané o kultúrny zážitok v podobe miestnych muzikantou</a>
				</p>
				<div class="galery col-sm-12 flex justify-content-center">
				<img id="i8" src="img/pochov1.jpg" class=" img-thumbnail" alt="r1">
				
					<button onclick="lf(8)" class="l-button l-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900"><</button>
					<button onclick="rf(8)" class="r-button r-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900">></button>

				</div>

			</div>
			<div class="col-sm-4">
				<h2 class="text-center"> Akcie ORMZ</h2>
				<p class="col-sm-12">
					V Zubrohlave funguje <strong>Organizácia rady mládeže Zubrohlava </strong>alebo <strong>ORMZ</strong>. Je to skupina Mladých ľudí, ktorá zveľaduje život v dedine v podobe rôznych akcíi. Od <strong>športových, prednáškových, filmových a iných </strong>. Rada sa hlavne venuje mládeži ale taktiež pomáha dobrovoľníckou činnosťou iným orgánom obce. Má taktiež svoju <strong>Klubovňu</strong>
				</p>
				<div class="galery col-sm-12 flex justify-content-center">
				<img id="i9" src="img/ormz1.jpg" class=" img-thumbnail" alt="r1">
				
					<button onclick="lf(9)" class="l-button l-button-sm mx-auto btn btn-dark text-light" style="font-weight: 900"><</button>
					<button onclick="rf(9)" class="r-button r-button-sm  mx-auto btn btn-dark text-light" style="font-weight: 900">></button>

				</div>
			</div>
			<div class="col-sm-4">
				<h2 class="text-center">Mládežnický ples</h2>
				<p class="col-sm-12">
					Každoročne býva Január-Február.Tejto úlohy organizovať ples sa uchopila partia mladých zo Zubrohlavy. Tento ples je veľmi žiadaný a každý rok býva <strong>rýchlo vypredané</strong>, väčšinou už iba prvý deň keď sa dajú kúpiť vstupenky. O zábavu sa postará DJ a taktiež su tu rôzne hry. Jedlo a pitie je v cene. tento ples je <strong>bez alkoholu</strong>
				</p> 
				<div class="galery col-sm-12 flex justify-content-center">
				<img id="i10" src="img/ples1.jpg" class=" img-thumbnail" alt="r1">
				
					<button onclick="lf(10)" class="l-button l-button-sm mx-auto btn btn-dark text-light" style="font-weight: 900"><</button>
					<button onclick="rf(10)" class="r-button r-button-sm mx-auto btn btn-dark text-light" style="font-weight: 900">></button>

				</div>
			</div>
	</div>
	<div class="bg-dark container-fluid" >
		<p>ads</p>
	</div>
</body>
</html>
