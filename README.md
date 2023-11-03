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
