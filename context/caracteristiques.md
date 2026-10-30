# Característiques inicials

| Funcionalitat | Què fa | Condicionants tècnics | Com ha de funcionar |
|---|---|---|---|
| Gestionar receptes | Crear, editar i eliminar receptes amb ingredients, passos i visibilitat. | Usuari autenticat i dades que es guarden. | Formularis validats, només el propietari pot modificar i no es perden dades. |
| Cercar receptes | Cerca per nom o ingredient en receptes pròpies i públiques. | Consultes amb paràmetres. | Resposta ràpida i mai mostra receptes privades d'altres usuaris. |
| Valorar receptes | Puntuar una recepta pública i veure'n la mitjana. | Valoracions lligades a usuari i recepta. | Una valoració per usuari i recepta, i la mitjana ha de quadrar. |

## Condicionants tècnics

- Front-end amb HTML, CSS i JavaScript.
- Servidor amb Java i Spring Boot.
- Base de dades MySQL.
- Git i GitHub.
- Disseny que s'adapti a mòbil i ordinador.

Són el punt de partida. De moment no hem triat cap framework definitiu.

## Protecció de dades

Guardem dades personals (correu i contrasenya), per tant ens afecten l'RGPD (UE 2016/679), la LOPDGDD (LO 3/2018) i la LSSI (Llei 34/2002). Això vol dir que l'aplicació ha de tenir política de privacitat, demanar el consentiment en registrar-se i tenir unes condicions d'ús. A més, la contrasenya no es pot guardar en text pla.
