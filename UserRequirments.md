  ##                    Kerkesat e sistemit

> **Nje regjistrim i hollesishem i takon dhe kompanise e cila regjistron te dhena rreth**:
1.   Kodit te saj(identifikator dhe unik)(M) (funksionale)
2.   Kodit te secilit filial(edhe ky identifikator dhe unik)(M) (funksionale)
3.   Kodit te punonjesve(identifikator dhe unik)(M) (funksionale)
4.   Kodit te produktit(identifikator dhe unik)(M) (funksionale)
 +   Aplikacioni i identifikon pjestaret nepermjet nje id(M)
>ID eshte unike por dhe e dallueshme per punonjesit,nenpunesit dhe perdoruesit
>Pasi identifikohen ne sistem perdoruesit mund te kryejne veprimet sipas autoresise qe aplikacioni i jep
>Punonjesit(Menaxheret) logohen nepermjet kodit te tyre(M)
>Emrit,mbiemrit,adreses,numrit te telefonit,adreses se email(N)
>Ata menaxhojne te dhenat te dhenat rreth nenpunesve,klienteve dhe produkteve(N)
>Per te shtuar,modifikuar fshure te dhena rreth nenpunesve menaxheret duhet te nderhyjne ne te dhenat e tyre
+    _Nenpunesit logohen nepermjet kodit te tyre(M)_
> +  Emrit,mbiemrit,adreses,numrit te telefonit,adreses se email(N)
>Ata menaxhojne informacionin rreth klienteve dhe produkteve(N)
>Produktet regjistrohen nepermjet numrit te identifikimit(unik)
> +  Emrit,numrit te serise,gjendjes se stokut
>Per te shtuar,modifikuar dhe shtuar informacion rreth nje klienti te caktuar,do te kene toolbar e caktuar me veprimet tek aplikacioni(M)
>Gjithashtu per shtuar,modifikuar dhe shtuar informacion rreth produkteve,do te kene nje toolbar me komandat e duhuara(M)
>Perdoruesi logohet si klient i perhershem ose mund te bej sign in si klient jo i perhershem(M)
>Ai merr informacion rreth pajisjeve nepermjet nje nderfaqeje te ofruar nga aplikacioni(M)
>Pasi mbaron viziten e tij ne dyqan ai jep nje vleresim rreth produkteve dhe sherbimit te ofruar(N)
