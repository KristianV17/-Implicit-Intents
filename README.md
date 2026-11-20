# Implicit Intents

Android projekt (Android Studio, Java) za vajo uporabe **implicitnih namer (implicit intents)**.

Z implicitno namero aplikacija ne pokliče točno določene aktivnosti, ampak sistemu pove, kaj želi narediti (npr. odpreti spletno stran, poklicati številko, poslati SMS ali e-pošto, odpreti zemljevid). Android nato sam ponudi aplikacijo, ki to zna.

```java
Intent intent = new Intent(Intent.ACTION_VIEW, Uri.parse("https://www.google.com"));
startActivity(intent);
```

## Tehnologije

- Java
- Android Studio
