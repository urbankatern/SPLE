1. Kaj pomeni kratica HTML?
    HyperText Markup Language

2. Kateri je osnovni namen jezika HTML pri razvoju spletnih strani?
    Opisuje strukturo in pomen vsebine spletnih strani.

3. Katera deklaracija mora biti zapisana v prvi vrstici vsakega veljavnega HTML5 dokumenta?
    <!DOCTYPE html>

4. Cemu sluzi deklaracija "<!DOCTYPE html>"?
    Brskalniku sporoca, da je dokument napisan v HTML5, zato ga prikaze v standardnem nacinu namesto v "quirks" nacinu, ki posnema stare brskalnike.

5. Kateri krovni korenski element zaobjema celotno kodo spletne strani?
    <html>

6. Kaksna je bistvena razlika med vlogo elementa "<head>" in elementa "<body>"?
    <head> vsebuje metapodatke, ki se ne prikazejo na strani, medtem ko <body> vsebuje zgolj vidno vsebino.

7. Kateri element znotraj glave dokumenta doloca naslov, ki se izpise na zavihku brskalnika?
    <title>

8. S katerim elementom oznacimo najpomembnejsi (glavni) naslov na strani?
    <h1>

9. Koliko hierarhicnih nivojev naslovov ponuja HTML in kateri nivo predstavlja najmanj pomemben naslov?
    6 nivojev (<h1> do <h6>), najmanj pomemben je <h6>.

10. Kateri element uporabljamo za oznacevanje navadnih odstavkov besedila?
    <p>

11. Katero prazno (samozapiralno) znacko uporabimo za enojni prelom vrstice znotraj odstavka?
    <br>

12. Kateri element vrine vodoravno crto oziroma tematski prelom v vsebini?
    <hr>

13. Kateri element uporabljamo za ustvarjanje "hipertekstovnih" povezav?
    <a>

14. Kateri atribut elementa "<a>" doloca ciljni spletni naslov (URL) povezave?
    href

15. Kako v kodi HTML pravilno zapisemo komentar?
    <!-- to je komentar -->

16. Katera dva atributa sta obvezna pri elementu "<img>" za pravilen in veljaven prikaz slike?
    "src" in "alt"

17. Kaj je primarna vloga atributa "alt" pri sliki?
    Je nadomestno besedilo, ce slike ni mogoce prikazati.

18. Kateri element uporabimo za izdelavo neurejenega seznama (z alinejami)?
    <ul>

19. Kateri element uporabimo za izdelavo urejenega (ostevilcenega) seznama?
    <ol>

20. Kateri element predstavlja posamezno postavko znotraj poljubnega seznama?
    <li>

21. Kaj je znacilnost blokovnih "block-level" elementov glede na preloma in sirine?
    Zacnejo se v novi vrstici in privzeto zavzamejo celotno razpolozljivo sirino nadrejenega elementa. Sirino in visino jim lahko nastavimo.

22. Kaj je znacilnost vrsticnih "inline" elementov glede preloma in sirine?
    Ne zacnejo nove vrstice, tecejo znotraj besedila in zavzamejo le toliko sirine, kot jo potrebuje vsebina. Sirine in visine jim ne moremo nastavljati.

23. Kateri genericni blokovni element najpogosteje uporabljamo za zdruzevanje drugih elementov?
    <div>

24. Kateri genericni vsticni element uporabljamo za oblikovanje ali manipulacijo dela besedila znotraj odstavka?
    <span>

25. Kje v kodi vedno zapisemo atribute elementa?
    V odpiralni znacki elementa, za njegovim imenom, npr.: <a href="...">.

26. Kako zapisemo posebno HTML entiteto za nelomljivi presledek?
    &nbsp;

27. Kateri element predstavlja krovni okvir za tabelo?
    <table>

28. Kateri element definira posamezno vrstico v tabeli?
    <tr>

29. Kateri element definira navadno podatkovno celico v tabeli?
    <td>

30. Kateri element definira naslovno celico v tabeli (privzeto krepka in sredinsko poravnana pisava)?
    <th>

31. Kaksna je razlika med elementoma "<b>" in "<strong>"
    <b> je zgolj vizualno krepko (brez dodatnega pomena). <strong> pomeni, da je vsebina semanticno pomembna, zato jo bralniki zaslona lahko poudarijo. Brskalnik obe prikaze krepko.

32. Kaksna je razlika med elementoma "<i>" in "<em>"
    <i> je posevno besedilo brez poudarka (tuje besede, strokovni izrazi, misli). <em> pomeni poudarek v pomenu (emphasis), ki spremeni naglas stavka in ga prepoznajo bralniki zaslona.

33. Pojasni delovanje in namen elementov "<sub>" in "<sup>" ter navedi primer za vsakega.
    <sub> prikaze besedilo kot podpisano (spodaj), <sup> pa kot nadpisano (zgoraj): H2O in x^2

34. Kako z elementom "<a>" odpremo povezavo v novem zavihku in kateri zascitni atribut moramo ob tem dodati?
    Z atributom target="_blank" (nov zavihek), ob tem pa dodamo rel="noopener noreferrer" (zascitni atribut).
        <a href="https://www.vegova.si" target="_blank" rel="noopener noreferrer">Vegova</a>

35. Kaj je sidrna povezava (zaznamek / *bookmark*) in kako jo vzpostavimo v kodi?
    Povezava na dolocen del iste ali druge strani. Cilju dodamo id povezavi pa href="#id".
        <a href="#kontakt">Pojdi na kontakt</a>
        ...
        <h2 id="kontakt">Kontakt</h2>

36. Napisi kodo za povezavo, ki ob kliku odpre privzeti e-postni program z naslovom 'tajnistvo@vegova.si'.
    <a href="mailto:tajnistvo@vegova.si">Pisite nam</a>

37. Napisi kodo za povezavo, ki na mobilni napravi omogoca neposreden klic na neko telefonsko stevilko, npr. "+38612345678".
    <a href="tel:+38612345678">Poklicite nas</a>

38. Opisi strukturo in namen opisnega seznama "<dl>". Iz katerih pod gradnikov je sestavljen?
    Uporablja se za pare izraz-opis (slovar). Sestavljen je iz:
    * <dt> - izraz (definition term)
    * <dd> - opis (definition description)
        <dl>
            <dt>HTML</dt>
            <dd>Program za izdelavo spletnih strani</dd>
        </dl>

39. Zakaj je priporocljivo pri elementu "<img>" vedno eksplicitno navesti atributa "width" in "height"?
    Brskalnik tako vnaprej rezervira prostor za sliko, zato se vsebina med nalaganjem ne premika.

40. Kaj stori atribut /loading="lazy"/ pri sliki in zakaj izboljsa delovanje spletisca?
    Brskalnik nalozi sliko sele, ko se pribliza vidnemu obmocju. Tako zmanjsa zacetno kolicino prenesenih podatkov in pospesi nalaganje strani.

41. Kako v tabeli vertikalno zdruzimo tri sosednje celice v isti vrstici? Navedi primer znacke.
    Z atributom colspan:
        <td colspan="3">Zdruzena celica</td>

42. Kako v tabeli vertikalno zdruzimo celico skozi dve vrstici? Navedi primer znacke.
    Z atributom rowspan:
        <td rowspan="3">Zdruzena celica</td>

43. Katere tri strukturne sklope tabele poznamo in kaksen je njihov pomen za dostopnost?
    * <thead> - naslovi stolpcev
    * <tbody> - podatki
    * <tfoot> - povzetki

44. Cemu sluzi atribut "scope" pri celici "<th>" in kateri dve vrednosti najpogosteje zavzame?
    Doloca, ali <th> celica sluzi kot glava za stolpec, vrstico oz. skupino stolpcev, vrstic. Najpogostejsi vrednosti sta col in row

45. Kako element "<label>" pravilno povezemo z vnosnim poljem "<input>"? Napisi primer.
    Z atributoma for in id.
        <label for="ime">Ime:</label>
        <input type="text" id="ime" name="ime">

46. Zakaj atribut "placeholder" v obrazcih ne more nadomestiti elementa "<label>"?
    Ker izgine, ko uporabnik zacne tipkati, ima slab kontrast, ni zanesljivo prebran z bralniki zaslona in ne povecuje klikalnega obmocja polja.

47. Kako zagotovimo, da lahko uporabnik v skupini izbirnih gumbov /type="radio"/ izbere natanko eno moznost.
    Vsi gumbi v skupini morajo imeti enak atribut name, vsak pa drugacen value.

48. Kaksna je vloga elementov "<fieldset>" in "<legend>" v spletnih obrazcih?
    <fieldset> zdruzuje sorodna polja obrazca v skupino, <legend> pa ji doda naslov (opis). Izboljsa preglednost in dostopnost, saj bralnik zaslona ob vsakem polju pove tudi naslov skupine.

49. Napisi kodo za spustni meni "<select>", ki vsebuje dve moznosti: "Vegova" in "Druga sola".
    <select name="sola">
        <option value="vegova">Vegova</option>
        <option value="druga">Druga sola</option>
    </select>

50. Kaj omogoca element "<datalist>" v kombinaciji z elementom "<input>"?
    Ponudi seznam predlogov za <input> (samodejno dopolnjevanje), uporabnik pa lahko vpise tudi poljubno vrednost. Povezava poteka prek list in id.
