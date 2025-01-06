# Weather and forecast

![](https://cdn2.iconfinder.com/data/icons/weather-flat-14/64/weather02-512.png)

## Présentation

Weather and forecast est une application développée en HTML/CSS/JS
Elle permet d’afficher la météo du jour et les prévisions sur 5 jours une fois la ville rentrée dans la barre d’adresse.

## Démonstration

Vous pouvez consulter la démo [ICI](https://`)

## Personnalisation

Pour afficher la météo de votre ville il suffit de modifier le nom de la ville dans l'url

```bash
....
```

## Paramètres

L'application appelle l'API de [OpenWeatherMap](https://openweathermap.org/)

#### Récupération de la météo du jour :

```bash
https://api.openweathermap.org/data/2.5/weather?q=${city},fr&lang=fr&appid=c21a75b667d6f7abb81f118dcf8d4611&units=metric
```

#### Récupération des prévisions sur 5 jours :

```bash
https://api.openweathermap.org/data/2.5/forecast?q=${city},fr&lang=fr&appid=c21a75b667d6f7abb81f118dcf8d4611&units=metric
```
