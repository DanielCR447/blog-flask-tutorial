| Ruta (endpoint) | Mètodes HTTP | Funció |
|---|---|---|
| `/hello` | GET | Mostra «Hello, World!». |
| `/` | GET | Mostra totes les publicacions. |
| `/auth/register` | GET, POST | Registra un usuari nou. |
| `/auth/login` | GET, POST | Inicia sessió d'un usuari. |
| `/auth/logout` | GET | Tanca la sessió de l'usuari. |
| `/create` | GET, POST | Crea una publicació nova. |
| `/<int:id>/update` | GET, POST | Modifica una publicació existent. |
| `/<int:id>/delete` | POST | Elimina una publicació existent. |