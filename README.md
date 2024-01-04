# News
Projekt AHE Łódź
Dlaczego wiadomości i aplikacja są po angielsku
Program wykorzystuje News API (https://newsapi.org/)
Aplikacja na początku miała być w polskiej wersji językowej wraz z nazwą, kategoriami i wiadomościami. Niestety podczas programowania natrafiłem na problem, który leży po stronie API i nie mogłem go naprawić,
mianowicie w kodzie aplikacji można zmienić wiadomości na inny język dostępny, który oferuje api (w tym polski), jednak po zmianie na polskie wiadomości miniatury newsów nie wyświetlają się. Ma to związek z
samą strukturą API. W polskiej wersji językowej i wielu innych pozycja „urlToImage”  posiada wartość „null”, a w angielskiej i japońskiej wersji jest podana wartość i miniaturki się pojawiają.
Wygląda to w ten sposób

![Zrzut ekranu 2024-01-04 104732](https://github.com/Wozowk/News/assets/57195132/df55bfc9-763c-409c-8a00-17fa9a40ba9c)


Miałem do wyboru albo zrobić apkę po angielsku albo zrobić uboższą wersję aplikacji po polsku,
gdzie nie wyświetlają się miniaturki a wiadomości byłyby tylko w postaci listy.
Wybrałem pierwszą opcje z tego powodu, że po prostu lepiej wygląda wizualnie.

![Zrzut ekranu 2024-01-04 103204](https://github.com/Wozowk/News/assets/57195132/3dfddb17-9956-4ada-8e8e-750d9cba5d48)
