<!DOCTYPE HTML>
<html>
	<head>
		<title>ShopNavi</title> 
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
		<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
		<style>

			.productStyle {
			    float: left;
			    width: 20px;
			    height: 10px;
			    margin: 10px;
			    padding: 10px;
			    /*border: 1px solid black; */
			}
			
			.addButtonBlock {
			    display: block;
			    width: 100%;
			    height: 60px;
			    border: 1px solid #bfbfbf;
			    background-color: white;
			    color: white;
			    padding: 14px 28px;
			    /* font-size: 10px; */
			    cursor: pointer;
			    text-align: center;
			}
			
			* {
			    box-sizing: border-box;
			}

	
			body {
			    font-family: Arial;
			    padding: 10px;
			    background: #f1f1f1;
			    height: 100%;
			}
			
			/* Header/Blog Title */
			.header {
			    padding: 30px;
			    text-align: center;
			    background: #E2E9F4  ;
			}
			
			.header h1 {
			    font-size: 50px;
			    color: #00679E /* #4069AE  */
			}
			
			/* Style the top navigation bar */
			.topnav {
			    overflow: hidden;
			    background-color: #00679E /* #4069AE; */
			}
			
			/* Style the topnav links */
			.topnav a {
			    float: left;
			    display: block;
			    color: #00679E /* #E2E9F4; */
			    text-align: center;
			    padding: 14px 16px;
			    text-decoration: none;
			}
			
			/* Change color on hover */
			.topnav a:hover {
			    background-color: #ddd;
			    color: #00679E /* #2A58A3; */
			}
			
			img.stretchy {
				width: 100%; /*Tells image to fit to width of parent container*/
				}
			.container {
				width: 33%; /*Use this to control width of the parent container, hence the image*/
			}
			

			/* Add a card effect for articles */
			.card {
			    background-color: white;
			    padding: 20px;
			    margin-top: 20px;
			    height:1000px
			}
			
			.leftcolumn {   
			    float: left;
			    width: 100%;
			    height: 100%;
			}
			
			/* Clear floats after the columns */
			.row:after {
			    content: "";
			    display: table;
			    clear: both;
			    height: 100%;
			}
			
			/* Footer */
			.footer {
			    padding: 20px;
			    text-align: center;
			    background: #ddd;
			    margin-top: 20px;
			}

			.searchForm {
			    box-sizing: border-box;
			    height: 3rem /* 2.5rem; */
			    line-height: 2.375rem;
			    border: 1px solid #bfbfbf;
			    background: #ffffff;
			    vertical-align: top;
			    width: 100%;
			    position: relative;
			    padding-left: 0.625rem;
			    padding-right: 4.75rem;
			}
			
			.searchForm:hover {
				border-color : #427cac;
			}
			
			.searchInputField[type='search'] {
			    font-size: 1.375rem;
			}
			
			
			.searchInputField[type="search"] {
				-webkit-appearance: none;
				box-sizing: border-box;
				width: 100%;
			}
			.searchInputField {
			    color: #000000;
			    font-family: "72",Arial,Helvetica,sans-serif;
			    /* font-size: 0.875rem; */
			    background: transparent;
			    /* width: 100%; */
			    height: 2.375rem;
			    border: none;
			    outline: none;
			    padding: 0;
			    margin: 0;
			    text-indent: 0.125rem;
			    vertical-align: top;
			    text-overflow: ellipsis;
			}		
			
			ul {
			    list-style-type: none;
			    margin: 0;
			    padding: 0;
			    overflow: hidden;
			    background-color: transparent;
			}
			
			li a {
			    display: block;
			    color: black;
			    text-align: center;
			    padding: 16px;
			    text-decoration: none;
			}
			
			li a:hover {
			    background-color: #F7F8F8;
			}

			.productsBorderStyle {
			   border-bottom: 1px solid #cccccc;
			   padding: 3px;
			   /* content: "";
			   display: table;
			   clear: both; */
			}
			
			/* Create two equal columns that floats next to each other */
			.column {
			    flex: 50%;
			    padding: 10px;
			    height: 130px; /* Should be removed. Only for demonstration */
			}
			
			/* Clear floats after the columns */
			.row:after {
			    content: "";
			    display: table;
			    clear: both;
			}
			
			/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
			@media screen and (max-width: 100px) {
			    .column {
			        width: 100%;
			    }
			}
			
			.productsPaddingStyle {
			   padding: 5px;
			}

			.addToCartButtonStyle {
			    background-color: white; 
			    color: black; 
			    border: 1px solid #008CBA;
			}
			
			.addToCartButtonStyle:hover {
			    background-color: #D7F2FC;
    			color: white;
			}
			
			.shoppingCartOverviewButtonStyle {
			    background-color: transparent;
			    color: black; 
			    border: none;/* 1px solid #008CBA; */
			}
			
			.shoppingCartOverviewButtonStyle:hover {
			    background-color: #D7F2FC;
    			color: white;
			}
			
			.row1{
				display: flex;
				border-bottom: 1px solid #cccccc;
				padding: 2px;
				border-style: transparent dashed solid double;
			}
			
			
			.row2 {
			    display: flex;
				border-bottom: 1px solid #cccccc;
				padding: 1px;
				border-style: transparent dashed solid double;
				height: 100px;
			}
			
		</style>
		<script>
			
			function goToShopPlan(){
				location.href = "map.html";
			}
			
			function deleteProduct(event){
				debugger;
			}
			
		</script>
	</head>
	<body>
		
		<div id="myModal" class="modal fade" role="dialog">
			<div class="modal-dialog">
			    <div class="modal-content">
			      <div class="modal-header">
			        <button type="button" class="close" data-dismiss="modal">&times;</button>
			        <h4 class="modal-title">Information</h4>
			      </div>
			      <div class="modal-body">
			        <p>Die Daten wurden erfolgreich gespeichert.</p>
			      </div>
			      <div class="modal-footer">
			        <button type="button" class="btn btn-default" data-dismiss="modal">Schließen</button>
			      </div>
			    </div>
			</div>
		</div>
		
		<div class="header">
			<div align="right">
				<form>
					<img role="presentation" aria-hidden="true" alt="" src="https://buddymantra.com/wp-content/uploads/2018/04/user-icon-png-pnglogocom.png" width="30" height="30">
					<i>Hallo, Max Mustermann</i>
				</form>
			</div>
			<h1>ShopNavi &copy;</h1>  <!-- add title ShopNavi --> 
			<p>So einfach Produkte kaufen ging es noch nie </p>
		</div>

		<div>	
			<div class="row2">
				<div class="column"> 
					<h3>Einkaufswagen Übersicht</h3>
				</div>
				<div class="column" style="text-align:right"> 
					<button class="shoppingCartOverviewButtonStyle" title="Zur Karte" onclick="goToShopPlan()">
		    			<img role="presentation" aria-hidden="true" alt="" src="http://files.softicons.com/download/web-icons/awt-travel-blue-icons-by-awt-media/png/64x64/AWT-Location.png" width="30px" height="30px" class="scale-down">
		    		</button>
				</div>
			</div>
		</div>

		<div class="row1"> 
		  <div class="leftcolumn">
		    <div class="card"> 
		    	<ul>
					<li>
						<a>
							<div class="row1">
								<div class="column">
									<div align="left">
					    				<span>1.</span>  
				    				</div>
								</div>
								<div class="column">
									<div align="center">
					    				<img role="presentation" aria-hidden="true" alt="" src="https://www.gutekueche.at/img/artikel/1187/frische-karotten.jpg" width="50" height="50">
				    				</div>
								</div>
								<div class="column">
									<div style="text-align:right">
							    		<span>Frische Karotten, 1 KG</span>  
							    	</div>
									<div style="text-align:right">
		    							<span>1,99</span>  
		    							<span>EUR</span>
		    						</div>
		    						<div style="text-align:right" class="column">
		    							<button title="Produkt löschen" style="background-color:transparent;" onclick="deleteProduct()">
		    								<img role="presentation" aria-hidden="true" alt="" src="https://www.freeiconspng.com/uploads/blue-delete-button-png-29.png" width="25px" height="20px">  
		    							</button>
		    						</div>
								</div>
							</div>
						</a>
					</li>
					<li>
						<a>
							<div class="row1">
								<div class="column">
									<div align="left">
					    				<span>2.</span>  
				    				</div>
								</div>
								<div class="column">
									<div align="center">
					    				<img role="presentation" aria-hidden="true" alt="" src="https://purepng.com/public/uploads/large/purepng.com-oniononionvegetablegenus-alliumallium-fistulosumonions-1701527266381wcbrj.png" width="50" height="40">
				    				</div>
								</div>
								<div class="column">
									<div style="text-align:right">
							    		<span>Zwiebel Hell, 1 KG</span>  
							    	</div>
									<div style="text-align:right">
		    							<span>1,99</span>  
		    							<span>EUR</span>
		    						</div>
		    						<div style="text-align:right" class="column">
		    							<button title="Produkt löschen" style="background-color:transparent;" onclick="deleteProduct()">
		    								<img role="presentation" aria-hidden="true" alt="" src="https://www.freeiconspng.com/uploads/blue-delete-button-png-29.png" width="25px" height="20px">  
		    							</button>
		    						</div>
								</div>
							</div>
						</a>
					</li>
					<li>
						<a>
							<div class="row1">
								<div class="column">
									<div align="left">
					    				<span>3.</span>  
				    				</div>
								</div>
								<div class="column">
									<div align="center">
					    				<img role="presentation" aria-hidden="true" alt="" src="http://www.stickpng.com/assets/images/58bf1e50e443f41d77c734b0.png" width="50" height="50">
				    				</div>
								</div>
								<div class="column">
									<div style="text-align:right">
							    		<span>Petersilie Glat, 100 G</span>  
							    	</div>
									<div style="text-align:right">
		    							<span>1,99</span>  
		    							<span>EUR</span>
		    						</div>
		    						<div style="text-align:right" class="column">
		    							<button title="Produkt löschen" style="background-color:transparent;" onclick="deleteProduct()">
		    								<img role="presentation" aria-hidden="true" alt="" src="https://www.freeiconspng.com/uploads/blue-delete-button-png-29.png" width="25px" height="20px">  
		    							</button>
		    						</div>
								</div>
							</div>
						</a>
					</li>
					<li>
						<a>
							<div class="row1">
								<div class="column">
									<div align="left">
					    				<span>4.</span>  
				    				</div>
								</div>
								<div class="column">
									<div align="center">
					    				<img role="presentation" aria-hidden="true" alt="" src="http://backgroundcheckall.com/wp-content/uploads/2017/12/apple-transparent-background-6.png" width="50" height="40">
				    				</div>
								</div>
								<div class="column">
									<div style="text-align:right">
							    		<span>Äpfel Gala, 1 KG</span>  
							    	</div>
									<div style="text-align:right">
		    							<span>1,99</span>  
		    							<span>EUR</span>
		    						</div>
		    						<div style="text-align:right" class="column">
		    							<button title="Produkt löschen" style="background-color:transparent;" onclick="deleteProduct()">
		    								<img role="presentation" aria-hidden="true" alt="" src="https://www.freeiconspng.com/uploads/blue-delete-button-png-29.png" width="25px" height="20px" style="background-color:transparent;">  
		    							</button>
		    						</div>
								</div>
							</div>
						</a>
					</li>
				</ul>
		    </div>
		  </div>
		</div>
		<script>
			/*document.getElementById("myBtn2").addEventListener("click", myFunction);*/
		</script>
	</body>
</html>
