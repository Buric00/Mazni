Knjiga_ulaznih_racuna(v1):	-Ovdje je implementiran samo dizajn

Knjiga_ulaznih_racuna(v2):	-Izrada obrazaca za unos u poslovne knjige.
				-Svaki redni broj i broj računa je jedinstven.
				-Izračun ukupnog iznosa na temelju zbrajanja vrijednosti sa PDV-om.
				-Datum otvorenog obrasca je trenutni datum.
				-Validacija: -RB: sastoji se od minimalno 1 znamenke i samo cjelobrojnog unosa
				-BrojRačuna: sastoji se od minimalno 1 znamenke i samo cjelobrojnog unosa
				-Oznaka: sastoji se od minimalno 4 znamenke, moguć unos znakova i brojeva
				-Partner: minimalno 3 slova
				-Adresa: minimalno 1 slovo, omogućen unos slova (više riječi s razmacima) i također brojeva
				-Mjesto: minimalno 3 slova
				-OIB: se sastoji od točno 11 cjelobrojnih znamenki
				-Vrijednost: sastoji se minimalno od 2 brojke, omogućen unos decimalnih brojeva ali samo koristeći točku(zarez 						nije moguće koristiti zbog funkcije zbroji)
				-PDV: sastoji se od minimalno 2 brojke(decimalne)
				-DatumNaplate: unos datuma u formatu: dd-mm-yyyy
				-Iznos: računa se sam nakon pritiska tipke Unesi i prikazuje nam vrijednost koja je unjeta u bazu


Pregled_i_unos_partnera(v1):	-dovrsen pregled i unos (jos ne sve validacije)
				-u database.cs je dodano za update dictionary<string, string> vrstu unosa, i dodano je za delete reda u 					odabranoj tablici

obracunPlaca(v2):		-implementirane validacije polja za unos, provjere i izračun plaće.
				-korisnik ne može unijeti ništa osim slova i razmaka u polje za ime i prezime radnika i ništa osim brojeva i 						zareza u polje za unos bruto iznosa.
				-funkcionalnost 'Obračunaj' i 'Izlaz' su u potpunosti realizirane.
				-funkcionalnost 'Spremi' će biti realizirana u sljedećoj iteraciji.
