////////////////////////////////////////////////////////////////////////////////////////////
La ley dice que es un crimen para un Estadounidense vender armas a naciones
hostiles. Corea del Sur, enemigo de Estados Unidos, tiene algunos misiles, y todos
sus misiles les fueron vendidos por el Coronel West, quien es Estadounidense.
Pruebe que el Col. West es un criminal.
///////////////////////////////////////////////////////////////////////////////////////////

//eres criminal si vendes armas a a enemigo si erea estado unidence
//el coronel west es de estados unidos
//el coronel west vende armas
//corea del sur es enemigo de estados unidos

//el coronel west es criminal, si y solo si, vende armas a corea del sur

estadounidence(west).
hostil(corea_del_sur).
tiene(corea_del_sur, m1).
misil(m1).


arma(X) :-
  misil(X).
vendio(west, X, corea_del_sur) :-
    misil(X),
    tiene(corea_del_sur, X).
criminal(X) :-
    estadounidence(X),
    arma(Y),
    vendio(X, Y, Z),
    hostil(Z).
