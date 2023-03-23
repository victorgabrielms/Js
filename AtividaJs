var i, altura, sexo, maioralt = 0, menoralt = 0, mulheres = 0, homens = 0, mediamulheres = 0, contamulheres = 0, contahomens = 0;

		for(i = 1 ;i <= 15; i++) {		
			altura = parseInt(prompt("Informe sua altura["+i+"]:"));
			sexo = prompt("Sexo: M ou F:");
			

			if(i == 1) {
				menoralt = altura;
			} if(altura > maioralt) { 
				maioralt = altura;
			} if(altura < menoralt) { 
				menoralt = altura;
			} if(sexo == 'F') {
				mulheres += altura;
				contamulheres++;
			} else if(sexo == 'M') {
				homens += altura;
				contahomens++;
			}
		}
		mediahomens = homens/contahomens;
		alert("A maior altura é: "+maioralt); 
		alert("A menor altura é: "+menoralt);
		alert("A média dos homens é: "+mediahomens);
		alert("O número de mulheres é: "+contamulheres);
