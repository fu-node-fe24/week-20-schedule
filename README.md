# Schema, vecka 20
###### Backend med Node.js, vecka 1 av 5

## Introduktion

För att bygga moderna webbapplikationer behöver vi en stabil och flexibel backend. 
I denna modul får du lära dig grunderna i Node.js och Express – från att skriva dina första serverrader till att bygga strukturerade och återanvändbara REST API:er. 
När du är klar med denna modul kommer du kunna skapa egna API-endpoints som frontendapplikationer kan kommunicera med!

## Mål för veckan:

1. Kunna bygga en enkel server med Node.js och Express
2. Förstå hur moduler importeras och används (core, externa och egna)
3. Kunna skapa ett REST API med flera endpoints
4. Förstå hur JSON används som dataformat vid HTTP-kommunikation

## Resurser

### Presentationer

* [01 - Kursintro](https://docs.google.com/presentation/d/1_orrDKp8Nkl4lYekqOIBjjvKnB4Zx6Gp/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)
* [02 - Intro till Express](https://docs.google.com/presentation/d/13onMi2u1iAMmKsGmTE0Ex6uw9NZIjlzT/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)

### Inspelade föreläsningar

**LIVE**
* [Kursintro](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/EcVG0TNZuZ9OsPvvO8_w7WQB9UBZZ9-b2vEIoWzTJi6Stw?e=HMDCNe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
* [Intro Node och Express, 12 maj](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/EeWq_0dhcZFDrf01JGQQZKIBSbbfdWwRtvWumC48PBG4iQ?e=Alhei0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
* [Fördjupning Node och Express, 12 maj](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/ERibHKdYE8ZEntrK9Qg_8X4Br7GTM9Il-sK37Jxj3qINGg?e=xpMQAP&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
* [Bygga Film-API med routing, 13 maj](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Distans/EW3NtjMvmnVMmtvdUeJzHh0B9_HecKRMHen-mWpLGAmW1g?e=VcXGlD&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - distans
* [Bygga Fil-API med routing del 1, 14 maj](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/ET-WvCoU07dHmO9r99Tk8kQBCikzggl5TlHswVKFt2DT3w?e=tbxmtq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - Karlstad
* [Bygga Fil-API med routing del 2, 14 maj](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/EWX1XqlCXtVOqjv9iE67K0sB__ovtbS6-DhV03xbmTTg5A?e=UX0A8Z&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - Karlstad

**Förinspelat** (för distansklassen)

* [01 - Intro Node.js](https://vimeo.com/807411701/7a18cffca2) - till måndag
* [02 - API med Express - koncept](https://vimeo.com/807411951/c7161c2d55) - till måndag
* [03 - API med Express - kodexempel](https://vimeo.com/807412052/79ad1cf028) - till måndag
* [04 - REST API](https://vimeo.com/809659071/860888cacb) - till tisdag

### Lektionsrepon

* [12 maj](https://github.com/fu-node-fe24/week-20-lecture-12-maj)
* [13 maj](https://github.com/fu-node-fe24/week-20-lecture-13-maj)
* [14 maj](https://github.com/fu-node-fe24/week-20-lecture-14-maj)

### Filmer


### Länkar

* [Node.js download](https://nodejs.org/en)
* [Express.js dokumentation](https://expressjs.com/)
* [18 most common http status codes](https://drive.google.com/file/d/14l7MH9Zc4aGR9hJVHt6V0W1oAeKUTf5E/view?usp=sharing)
* [Understanding and using REST APIs](https://www.smashingmagazine.com/2018/01/understanding-using-rest-api/)
* [How a RESTful API server reacts to requests](https://www.oreilly.com/content/how-a-restful-api-server-reacts-to-requests/)


### Övningar 

* [Express Bootcamp](https://github.com/fu-node-fe24/week-20-exercise-express-bootcamp)
* [REST API Bootcamp](https://github.com/fu-node-fe24/week-20-exercise-api-bootcamp/tree/main) - veckans Code Review-uppgift
