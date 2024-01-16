Gépjárműkölcsönző követelményspecifikáció:

    1. Windows személyi számítógépen legyen egyszerű és kezelhető felületen. Könnyű program, nem kell energiaforrás a futtatáshoz. Csak személyesen lesz használható szigorúan a cégen belül.
    2. Lokális administrációs szoftver, amely képes dinamikus adatkezelésre.
        2.1. Program futási ideje közben lehessen bérelni, visszavinni (bérlésből) és műhelybe küldeni (nem használható). Le lehessen foglalni egy gépjárművet előre.
        2.2. Program futási ideje közben fel lehessen vinni új gépjárművet vagy törölni egy meglévőt.
        2.3. A program bezárásakor mentse el az adatokat. 
        2.4. A program induláskor kérje le az eltárolt adatokat.
        2.5. A program induláskor kérdezze meg a jelenlegi állapotát a műhelyben lévő / lefoglalt gépjárművet.
    3. Visszaállítási lehetőség ajánlása. Abban az esetben amennyiben vissza kellene állítani az adatokat egy előző verzióra, legyen legalább 4 ( 3 biztonsági mentés + 1 alaphelyzeti visszaállítás)

    4. kölcsönzéskor közölje a kölcsönzés árának „ előnézetét ” ( Ft / megtett km )
    5. visszavitelkor közölje a kölcsönzés árát
    6. kölcsönzéskor kölcsönző szélyi profil igénylése ( és létrehozása )


követelmény lista:

        K01. felasználók kezelése
            ▪ adminisztrátori fiók
                • műhelybe küldés
                • új gépjármű
                • megllévő gépjármű eladása
            ▪ dolgozói fiók
                • általános funkciók használata
                    ◦ kölcsönzés
                    ◦ visszavitel
                    ◦ stb…
            ▪ kölcsönzők profiljai
                • azonosító adatokat tartalmazó fiók
                    ◦ név
                    ◦ szül. év
                    ◦ …
                    ◦ fizetett összeg

        K02. gépjárművek kezelése
            ▪ kölcsönzés
            ▪ kölcsönzés utánni visszavitel
            ▪ műhely / lefoglalás funkciók implementálása
            ▪ gépjármű eladása
        K03. Egyszerű kezelőfelület
            ▪ ...

        K04. Pontos adatkezelés
            ▪ mentse el az akkori helyzetet a program bezárásakor
            ▪ nyissa meg az előző session által használt adatbankot

        K05. adatok visszaállítása
            ▪ …

        K06. kiváló működés
            1. a program ne fusson hibákba futás közben / előtt / után

        K07. lehetőség bővíthetőségre
            1. modulárisan programozott
            2. később egyszerűen módosítható 
            3. könnyen átlátható programkód

szükséges funkciók listája:
    • kölcsönzési ár kiszámítása
    • kölcsönző személy profiljának lementése
    • új gépjármű hozzáadása
    • meglévő gépjármű
        ◦ kölcsönzése
        ◦ visszavitele
        ◦ eladása ( admin fiók )
        ◦ műhelybe küldése
        ◦ lefoglalása
    • session lementése a program bezárásakor
    • visszaállítás


* session : a program futásától a program leállásáig tartott program használata
