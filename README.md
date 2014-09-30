craft-headerafbeelding
======================

Een twig snippet om headerafbeeldingen te tonen met behulp van Craft.
Je kunt pagina's koppelen aan afbeeldingen. Standaard worden de children vanaf die pagina ook meegenomen.

In Craft doe je het volgende:
* Matrix veld maken met de naam 'Headerafbeelding'
  De velden in deze matrix zijn: 'Afbeelding (type: Bestanden)' en 'Pagina's (type: Inhoud)'
* Maak een Globals set aan met de naam 'Headerafbeelding'. Hierin koppel je het veld: 'Headerafbeelding'
* Let op: De headerafbeelding voor je homepage dient als laatste item in je Matrix veld te staan, als dit niet zo is dan zullen alle headerafbeeldingen die hierna volgen genegeerd worden.
