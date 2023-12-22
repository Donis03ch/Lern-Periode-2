Grob-Planung

Brandon Spaqi

20.10.2023 bis 22.12.2023 (🎄 Weihnachtsferien)

## Leit-Satz

In meinem zweiten Projekt... (x Wörter)

## Arbeitspakete für 20.10.2023

- [x] Ich werde fertig mit meinem M431 Portfolio.
- [ ] Ich bearbeite Handlungsziel 4 im M319 für das Portfolio.
- [ ] Ich bearbeite Handlungsziel x im M319 für das Portfolio. 

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich erfolgreich das Portfolio für die OBA von Modul 431 fertig gestellt. Leider konnte ich, wegen dem Aufwand für Modul 431, aber auch wegen dem Anfang der Session, 
keinen der Handlungsziele für die LB von Modul 319 bearbeiten. Ich konnte sehr konzentriert an den Arbeitspaketen arbeiten. (46 Wörter)

## Arbeitspakete für 27.10.2023

- [ ] Ich werde fertig mit dem Hz4 im Portfolio für das LB-M319.
- [x] Ich werde fertig mit dem Hz5 im Portfolio für das LB-M319.
- [ ] Ich werde fertig mit dem Hz6 im Portfolio für das LB-M319.
- [x] Ich werde fertig mit dem Hz1 im Portfolio für das LB-M319.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich das Handlungsziel 1 fertig erstellt. Noch habe ich das Handlungsziel 5 auch fertig, schaffen können. Die beiden Handlungsziele waren die einfachen für heute, denn die HZ 4 & 6 sind die grösseren, d.h. sie benötigen mehr Zeit. Das HZ 4 habe ich sonst, aber fast fertig. Das programmieren von Beispielcode für die Kompetenznachweise waren nicht so schwer, wie ich dachte. (57 Wörter)

## Arbeitspakete für 03.11.2023

- [ ] Ich werde die Map erstellen in Unity. 
- [ ] Ich werde eine Spielfigur erstellen. 
- [ ] Ich werde Items/Equiptment ins Spiel integrieren.
- [ ] Ich werde das Gameplay noch optimieren.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich vielmehr das Movement für die Spielfigur erstellt. Ich werde über das Wochenende noch wegen der Map schauen, was ich da so schönes machen kann. Die Spielfigur lasse ich für das nächste mal. (~35 Wörter)

```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class PlayerController : MonoBehaviour
{
    public float speed;
    public Transform weapon;
    public float offset;

    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        // Player Movement
        Vector3 playerInput = new Vector3(playerInput.GetAxisRaw("Horizontal"), playerInput.GetAxisRaw("Vertical"), 0);
        transform.position += playerInput.normalized * speed * Time.deltaTime;

        // weapon Rotation
        Vector3 displacement = weapon.position - Camera.main.ScreenToWorldPoint(Input.mousePosition);
        float angle = Mathf.Atan2(displacement.y, displacement.x) * Mathf.Rad2Deg;
        weapon.rotation = Quaternion.Euler(0f, 0f, angle + offset);

    }
}
```

## Arbeitspaket für 10.11.2023

- [ ] Ich werde die Map erstellen in Unity. 
- [ ] Ich werde eine Spielfigur erstellen. 
- [ ] Ich werde Items/Equiptment ins Spiel integrieren.
- [ ] Ich werde das Gameplay noch optimieren.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich mit meiner Gruppe für die Projektarbeit an der Alten Kanti gearbeitet. Ich habe mit WinForms die ersten Darstellung bereit gestellt. Sehr viel Zeit habe ich heute an die Schnittstelle gebraucht. Die Schnittstelle habe ich nicht fertig gestellt, da sie schwer zu verstehen ist. Das Projekt für mich alleine (Top-Down Shooter), werde ich verschieben müssen. (~56 Wörter)

## Arbeitspakete für 17.11.2023

- [x] Ich werde die API Schittstelle fertig stellen. 
- [ ] Ich werde ein Array für die Währungen bereitstellen.
- [ ] Ich werde das Debugging durchführen, um Fehler zu beheben.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich... (x Wörter) 

## Arbeitspakete für 24.11.2023

- [ ] Ich werde ein Array für die Währungen bereitstellen.
- [ ] Ich werde das Debugging durchführen, um Fehler zu beheben.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich einen Array für mindestens 5 Währungen erstellt. Die Schnittstelle musste ich erneut einfügen, da das Programm letztens nicht den Speicher übernahm. An der GUI muss ich noch die Interaktionen besser gestalten. Die Arbeiten heute, habe ich selbständig bearbeitet soweit.  (42 wörter) 

## Arbeitspakete für 01.12.2023

- [ ] Ich werde das erste Rätsel vom AoC lösen.
- [ ] Ich werde den Rechner fertig stellen.
- [ ] Ich werde debuggen.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich meinen Rechner in Winforms veruscht zum laufen zu bringen. Das Programm startet, jedoch wird es nicht umgerechnet. Das Array sollte funktionieren. Bei der Schnittstelle bin ich mir nicht ganz sicher ob diese funktioniert, da eben die Kurse nicht umgerechnet werden.  (43 wörter)

## Arbeitspaket für 08.12.2023

- [ ] Ich werde eine kleine Map erstellen.
- [ ] Ich werde Mobs (Slime) hinzufügen.
- [ ] Ich werde eine Spielfigur integrieren.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich... (x Wörter) 

## Arbeitspaket für 15.12.2023

- [x] Ich werde eine kleine Map erstellen.
- [ ] Ich werde Mobs (Slime) hinzufügen.
- [x] Ich werde eine Spielfigur integrieren.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich die kleine Karte fertiggestellt und bereits das Bewegungsset für meine Spielfigur erstellt. Leider funktioniert es noch nicht wie gewünscht. Beim nächsten Versuch werde ich eine andere Funktion dafür verwenden. Das Hinzufügen der Mobs sollte auch nicht schwer sein, denke ich.  (41 Wörter) 

## Arbeitspaket für 22.12.2023

- [ ] Ich werde Mobs (Slime) hinzufügen.
- [ ] Ich werde das movement der Charaktere verbessern.
- [ ] Ich werde eine Lebensanzeige hinzufügen.

| Nummer | Vorbereitung | Eingabe | Erwartete Ausgabe | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |     |     |     |     |

Heute habe ich... (x Wörter) 

## Reflexion

Das Projekt verzeichnete variablen Fortschritt, beginnend mit der Fertigstellung des Portfolios für die OBA von Modul 431. Dies erforderte konzentrierte Arbeit, während die Handlungsziele für die LB von Modul 319 aufgrund des Zeitaufwands und des Sessionbeginns nicht bearbeitet werden konnten. Anschließend wurden konkrete Schritte zur Erfüllung der Handlungsziele im Portfolio für das LB-M319 dokumentiert, wobei größere Handlungsziele mehr Zeit in Anspruch nahmen.

Die Erstellung einer Map in Unity und einer Spielfigur konzentrierte sich zunächst auf das Movement der Spielfigur. Die Zusammenarbeit in einer Gruppe für ein Projekt an der Alten Kanti beeinflusste die Fortschritte, wobei festgestellt wurde, dass die Schnittstelle schwer zu verstehen war. Anschließend konzentrierte sich die Arbeit auf die Fertigstellung der API-Schnittstelle sowie das Erstellen eines Arrays für Währungen. Es wurde festgestellt, dass die Schnittstelle erneut eingefügt werden musste, da das Programm den Speicher nicht übernahm.

Weitere Anstrengungen wurden unternommen, um das erste Rätsel vom AoC zu lösen und den Rechner fertigzustellen. Es wurde jedoch festgestellt, dass das Programm startete, aber die Umrechnung nicht durchgeführt wurde und die Kurse nicht stimmten. Insgesamt zeigt sich eine klare Zuversicht und Bereitschaft, Probleme aktiv anzugehen und verschiedene Lösungsansätze zu verfolgen. (198 Wörter)

Für die nächste Lernperiode nehme ich mir vor, meine Arbeitsweise zu verbessern, indem ich meine Zeit- und Ressourcenverwaltung optimiere. Ich möchte aktiv daran arbeiten, klare Prioritäten zu setzen und realistische Zeitpläne zu erstellen, die es mir ermöglichen, meine Aufgaben effektiver zu bewältigen. Zudem plane ich, meine Kommunikationsfähigkeiten zu stärken, um erfolgreich in Gruppenprojekten zu arbeiten und eventuelle Missverständnisse zu minimieren. Darüber hinaus beabsichtige ich, eine proaktive Herangehensweise bei der Bewältigung von Problemen zu verfolgen, indem ich frühzeitig Unterstützung suche, wenn ich auf Hindernisse stoße. Durch diese Verbesserungen strebe ich danach, nicht nur meine Effizienz, sondern auch meine Fähigkeit zur Zusammenarbeit und Problemlösung zu steigern.
