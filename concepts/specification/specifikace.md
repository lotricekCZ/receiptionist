# Cíl
Cílem je vytvořit systém, který je schopen evidovat účtenky a shlukovat ve chtěných časových úsecích.
Účel je zpřehlednit účetnictví a zajistit efektivnější správu odesílaných financí.

# Uživatelé a permise
Systém musí dát možnost vytvořit uživatelský účet. Každý uživatel si dále může založit své finanční účty, ke kterým může nastavit přístupnost pro ostatní uživatele ve formě náhledu, návrhů a úprav.

# účtenka
Účtenka shlukuje prvky a ukládá jejich počet, mimo to i další metadata (datum vystavení, FIK, DIČ)

# prvek
Prvek je elementární část účtenky, má své označení, cenu, proplacenou částku, název produktu, případně kategorii a hodnotu dph. Nemůže existovat bez účtenky


# koeficienty platby
Jde o uživatelem určené koeficienty které určují kolik % požadované ceny prvku hodlá proplatit, přičemž každý koeficienty pro tyto prvky stanovuje individuálně.

# Vstup
Systém musí být schopen
- zadat účtenku a přiřadit jí prvky
- dát možnost určit plátce
- zpracovat uživatelské koeficienty pro určité typy zboží

# Nezbytné
Proplatil-li někdo nějakou částku, poté mu tento vstup musí být viditelný i při případném odebrání přístupu. 
Takový prvek poté lze smazat pouze administrátorem / shodou s plátcem/i
Může vzniknout platba i mimo pokryté účtenky, např. pro pokrytí inflace, nebo budoucích výdajů