# Cómo buscar un resultado del prode

1. Lanzá **al menos 5 búsquedas web en paralelo** (en el mismo turno), con fraseos y fuentes distintas:
   - `<Local> <Visitante> resultado final`
   - `<Local> venció / cayó / empató con <Visitante>` (o "ganó", "perdió", "igualaron")
   - Una apuntada a agregadores de resultados: Promiedos, 365Scores, Sofascore, FotMob, Flashscore, ESPN.
   - Una apuntada a diarios: Olé, TyC Sports, Infobae, La Nación, Clarín, Página 12, Cadena 3, La Voz, La Capital, diarios del club o de la ciudad.
   - Para partidos de afuera, una en el idioma local (italiano, portugués, alemán, inglés) con medios de allá (Gazzetta, Corriere dello Sport, Globo Esporte/ge, Lance, Kicker, BBC, Marca, AS, Mundo Deportivo).
   - Para el Ascenso: Mundo Ascenso, Solo Ascenso, La Nación (fichas de Primera Nacional), diarios locales.
2. Cargá el resultado apenas UNA nota de cualquier medio lo dé como terminado (crónica, "resultado final", "venció", "cayó", "empataron", "full-time", "finale", "Endstand"). Si hay contradicción entre notas finales, usá la que tenga más fuentes.
3. No uses notas en vivo ("en vivo", "live", "minuto a minuto" con marcador parcial).
4. Cargar: en `index.html`, bloque DATOS, completar `res` ("L"/"E"/"V" según el local del prode) y `gol` ("x-y" local-visitante), actualizar `ACTUALIZADO` con la hora argentina, commit y push a `main`.
5. Si no está, programá otra búsqueda en 5 minutos con send_later. No esperes a que el usuario avise.
