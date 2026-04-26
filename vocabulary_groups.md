# Тематические группы слов для генерации текстов TELC B1–B2

## Научная база (зачем именно так)

Группировка построена на исследованиях по усвоению лексики L2:

- **Tinkham (1993, 1997)** и **Waring (1997)**: слова, объединённые в **семантические кластеры** (одна категория: рука, нога, плечо, локоть; красный, синий, зелёный) учатся **на 50% медленнее** из‑за интерференции — мозг путает похожие элементы.
- **Тематические кластеры** (слова вокруг одной СЦЕНЫ: lekarz–recepta–gabinet–ból–leczyć–apteka) учатся **легче**, чем даже несвязанные слова — они образуют сценарий и помогают друг другу всплывать в памяти.
- **Контекстуальное обучение** (Frontiers, 2022): слова в связном тексте/диалоге → +retention.
- **Spaced repetition** (Cambridge SLA): повторение с интервалами лучше "массовой" зубрёжки.

**Вывод для генерации текстов:** один текст ≈ одна сцена ≈ одна тематическая группа (8–15 слов). Не смешивать в одном тексте слова из 5 разных тем.

---

## Как использовать (для агента-репетитора)

1. Выбираешь **одну группу** ниже (или комбинируешь 2 близкие, если мало слов).
2. Привязываешь к **одной из тем TELC T01–T14** (см. `TELC_B1_B2_ustny_agent_guide.md`).
3. Генерируешь текст 1–2 абзаца, в котором ВСЕ слова группы появляются естественно.
4. После проработки — отмечаешь группу как пройденную, переходишь к следующей.

Группы перекрываются с темами TELC, но не идентичны им: одна тема экзамена может покрываться 2–3 сценами (например, "здоровье" = сцена "у врача" + сцена "здоровый образ жизни" + сцена "стресс и сон").

---

## SC01 — У врача / болезнь (T05 Zdrowie)

oddech, ciśnienie, piersi, ramię, kolana, gardło, prysznic, bolało, skrzywdzić, czuć, chronić, ratować, ocalić, uratować, mózgu, ust

## SC02 — Здоровый образ жизни / эмоции (T05 + T11)

zazdrosny, wściekły, gniew, dumna, smutne, śmieszne, okropne, okropnie, kiepsko, niezwykle, niewiarygodny, niesamowity, cudowny, doskonały, ładnie, wesołych, tęsknię, pragnę, pragnie, uwielbiam, nienawidzę, błagam

## SC03 — Деньги / покупки / экономия (T06 Pieniądze)

dolarów, kieszeni, pożyczyć, posiada, dostaliśmy, zakład, oszalałeś, skarb, skarbie, kradzież, ukraść, ukradł, wyrzucić, oddech (выдох ситуации), zaproszenie

## SC04 — Свадьба / семейные события (T03 Rodzina + T08 Tradycje)

ślub, pierścionek, randka, pocałować, mąż, wujek, tatuś, oboje, obie, dzieciaka, kumpel, laski, gość, koleś, chłopie, panowie, witaj, żegnaj, pożegnać, przeprosiny, przeprosić, wybacz

## SC05 — Семейный конфликт / ссора (T03 Rodzina)

zachowujesz, zachowywać, udawaj, kłamstwo, plotki, przeszkadza, przeszkadzam, przejmuj, obchodzi, wątpię, wątpliwości, zgadzam, zgadza, zgadnij, owszem, ależ, czyżby, niby, lecz, jakoś, niezupełnie

## SC06 — Путешествие / транспорт / корабль (T09 Podróże)

statek, okręt, łódź, pokład, pokładzie, załogi, dowódca, dowodzi, kapitana (poruczniku, majorze — общий регистр обращений), pociąg, wozu, wsiadaj, wysiadaj, włąź, wyłaź, zejdź, zejść, dotrzeć, przeszedł, minął, minęło, prędkość, leci, spadamy, spadł, gwiazdy

## SC07 — Дом / квартира / интерьер (T09 Mieszkanie)

łóżka, łazience, drzwiami, dachu, ściany, dziurę, pudełko, kółko, koło, rogu, środku, dół, pokład, biura, sali, terenie, teren

## SC08 — На улице / поиски / направление (T09 + общая)

stąd, stamtąd, dokąd, tędy, indziej, gdziekolwiek, kiedykolwiek, ktokolwiek, kimkolwiek, gdziekolwiek, około, koło, poprzez, pomiędzy, przeciwko, ode, poza, między, tuż, niemal, ledwo, akurat, prędzej

## SC09 — Преступление / полиция / суд (T13 Urzędy + T14 Nowiny)

morderstwo, zabójstwo, morderca, zabójca, zbrodni, kradzież, napad, oskarżony, sędzia, prawnikiem, nakaz, śledztwo, namierzyć, sprawdź, sprawdzam, więzienie, obwiniaemy, ofiary, krzywdy, przemocy, broń, strzał, strzały, strzelaj, walka, uderzyć, złapać

## SC10 — Опасность / спасение / угроза (T14 Nowiny)

ratunku, ratować, uratować, ocalić, uwolnić, uniknąć, przetrwać, ucieczka (uciec), powstrzymać, zniszczyć, pułapka, ostrzeżenie, koszmar, potwór, zwłoki, martwy, śmierci, umrzeć, umrze, zabić, zabójca, padnij, pożar

## SC11 — Армия / военные / приказы (T14 — реже, но новостной фон)

żołnierz, dowódca, dowodzi, rozkaz, kazał, jednostka, członków, członkiem, wycofać, walka, broń, obóz, władze, rządzi, królowa, króla

## SC12 — Эмоции страха / тревоги (T05 + T11)

przeraża, przeczucie, obaw, wątpię, zastanawiam, zastanawiałem, podejrzewać (przypuszczam), wyobraź, pojęcie, obecność, oszalałeś, szalona, szaleni, szaleństwo, wariat, dziwna, dziwnie

## SC13 — Время и порядок (служебная — обязательна для всех тем)

chwili, chwilkę, dotąd, póki, dopóki, odkąd, znów, przedtem, akurat, kiedykolwiek, prędzej, oby, niedługo (wnet), nadszedł, naadejdzie, nadchodzi, nadchodzą, zapewne, miejmy, zaledwie

## SC14 — Модальность и долженствование (служебная)

powinieneś, mógł, mógłbym, byłoby, gdybym, żebyś, żebym, żebyście, abyś, abym, abyśmy, musieli, mieliście, dasz, wezmę, biorę, bierzesz, bierz, weź, weźmiemy, wzięli, zechce, zechcesz, zechce

## SC15 — Просьбы и команды (диалог — для всех тем)

spójrz, patrz, mów, rób, bądź, bądźcie, zostaw, zostań, wyjść, wejść, wejdzie, włóż, połóż, postaw, odłóż, odsuń, zdejmij, zdjąć, puść, puszczaj, dotykaj, dotykać, sprawdź, pozwól, chodźmy

## SC16 — Социальная фраза / вежливость (диалог)

witaj, żegnaj, pożegnać, przeprosić, przeprosiny, dziękuję (powodzenia, zaproszenie), zaszczyt, gratuluję (zaproszenie, randka), miłość (uwielbiam), niech (oby), proszę, dosyć

## SC17 — Чувства и оценки (T11 Wartości — оценочная)

świetnie (doskonały), fajna, kiepsko, ładnie, śmiało, serio, niezupełnie, nieźle, niezwykle, dosyć, wystarczająco, niemal, ledwo, akurat, prawdziwie (prawdę), oczywiście (owszem), wątpliwie (wątpię)

## SC18 — Рабочая ситуация / руководство (T02 Praca)

biura, wydział, jednostka, zaproszenie, sprzęt, urządzenie, połączenie, nagranie, wykonać, wykonanie, sprawdzić, sprawdzam, przekazać, nadaje, zawiera, badań, śledztwo, zgłosić

## SC19 — Чтобы / союзы и связки (служебная)

żeby (żebyś, żebym, żebyście), aby (abyś, abym, abyśmy), gdyby (gdybym), dopóki, póki, odkąd, choćby, wraz, względu, powodu, imieniu, podstawie, zasadzie, trakcie, ogóle, rzeczywistości, stanie

## SC20 — Чувства/реакции на новости (T14 + диалог)

owszem, ależ, czyżby, niby, oby, jezu, cholera, szlag, gówno, miejmy, zapewne, niewiarygodny, niesamowity, niezwykle, okropne, okropnie

## SC21 — Природа / погода / стихии (T10 Ekologia)

ziemi, nieba, słońce, wodzie, liście, gwiazdy, pustyni, wyspę, pożar, dziurę, prędkość, ciśnienie, oddech

## SC22 — Школа / тесты / документы (T01 Edukacja)

odpowiedzi, badań, sprawdź, sprawdzam, wyjaśnię, przekazać, posiada, zawiera, wykonać, dotrzeć, postaram, upewnić, zapewniam, zapewnić

## SC23 — Здания / помещения / места (T09 Mieszkanie)

biura, sali, terenie, teren, pokład, więzienie, kieszeni, łazience, środku, rogu, dachu, drzwiami, ścianami (ściany), bramę

## SC24 — Жесты тела / физические действия (повседневная)

pocałować, uderzyć, dotknąć, dotykać, dotykaj, trzymać, bierz, podnieść (włóż, zdjąć), usiąść, wstać (powstrzymać), spojrzeć, patrzeć (patrz), przyjąć, przekazać, wyciągnąć, wyciągnij, padnij, ruszać, ruszać się

## SC25 — Эмоциональные восклицания (диалог)

jezu, cholera, szlag, oto, ależ, czyżby, oby, błagam, umoraj (błagam), miejmy, śmiało, wyluzuj, spadaj, oczywiście (owszem)

---

## Грамматическая база (вне тем — учить отдельно, по спискам)

### G1 — Местоимения / падежи

niczego, niczym, czymś, kimś, kimkolwiek, ktokolwiek, jaką, jakąś, swego, twego, własne, samego, oboje, obie, dwaj, tacy, wasza, żadnego, żadnych, wszelkie, niczego

### G2 — Частицы / эмфаза

oto, owszem, ależ, czyż, czyżby, niby, akurat, oby, choćby, wraz, prędzej, niemal, ledwo, niezwykle, niezupełnie, zapewne, miejmy, zaledwie, odrobinę, kiepsko, nieźle, śmiało, serio

### G3 — Глагольные модификаторы

powinieneś, mógł, mógłbym, byłoby, musieli, mieliście, miewa, zdarza, zdarzyło, dzieje, leci, znów, przedtem, dotąd, dopóki, odkąd, póki

---

## Не покрытые группами слова (личный лонг-тейл)

Часть слов из топ‑527 не вписывается ни в одну сцену чисто (например: liczy, własne, pora, gość, parę, pewien, kapelusz, płaszcz, spodnie, ryba, anioł, dusza, odciski, urządzenie, sprzęt, ładunek, taśmę, wieści, opowieść, randka, pora, prysznic, kapelusz, łatwe, ciężki, gruby, ślepy, zdolności, zdolny, możliwe).

**Рекомендация:** их вкраплять по 2–3 слова в тексты по соседним сценам, чтобы не учить вне контекста.

---

## Чек‑лист генерации текста по группе

1. Назвать сцену (например, SC01 "У врача").
2. Указать тему TELC (T05 Zdrowie).
3. Текст 80–150 слов (B1) или 150–220 (B2).
4. Все слова группы — естественно, не списком.
5. В конце абзаца — список этих слов на польском **без перевода** (по правилу из `AGENTS.md`).
6. Не смешивать с другой сценой.
