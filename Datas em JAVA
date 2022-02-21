
#Ano, mes e dia.
public static void main(String[] args) {
		
		LocalDate hoje = LocalDate.now();
		System.out.println(hoje); //Formato ISO (internacional)
		
		LocalDate ano_novo =  LocalDate.of(2023, Month.JANUARY,1);
		System.out.println(ano_novo);
		
		int ano = ano_novo.getYear();
		Month mes = ano_novo.getMonth();
		int dia = ano_novo.getDayOfMonth();
		
		System.out.println("O ano novo será em " + dia + " de " + mes + " de " + ano);
		
		Period periodo = Period.between(hoje, ano_novo);
		System.out.println(periodo);
		
		System.out.println("Faltam " + periodo.getYears()  + " anos " + periodo.getMonths() + " meses e " + periodo.getDays() + " Dias para o ano novo " );
		
		
	}
