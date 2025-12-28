Spam‑vs.-Ham‑Modelltraining
(Portfolio‑Abschnitt – Deutsch)
1. Definition: Spam‑vs.-Ham‑Klassifikation
In der maschinellen Textklassifikation bezeichnet Spam vs. Ham eine binäre Entscheidung:
• 	Spam = unerwünschte, schädliche, betrügerische oder irrelevante Nachrichten
• 	Ham = legitime, erwünschte und sinnvolle Nachrichten
Dieses Klassifikationsproblem ist zentral für E‑Mail‑Filter, Messaging‑Plattformen, Betrugserkennung und Content‑Moderation.

2. Ziel des Modells
Ein Spam/Ham‑Modell soll automatisch unterscheiden zwischen:
• 	Nachrichten, die blockiert, gefiltert oder markiert werden müssen
• 	Nachrichten, die an den Nutzer zugestellt werden sollen
Das Modell lernt sprachliche, strukturelle und statistische Muster, die schädliche Inhalte von normaler Kommunikation unterscheiden.

3. Anforderungen an Trainingsdaten
A) Spam‑Beispiele
Typische Spam‑Nachrichten umfassen:
• 	Phishing‑Versuche
• 	betrügerische Angebote
• 	Massenmarketing
• 	Malware‑Links
• 	Identitätsbetrug
• 	automatisierte Bot‑Nachrichten
B) Ham‑Beispiele
Legitime Nachrichten umfassen:
• 	persönliche Kommunikation
• 	geschäftliche E‑Mails
• 	Transaktionsbenachrichtigungen
• 	verifizierte Newsletter
• 	Kundenservice‑Nachrichten
Ein ausgewogenes Dataset ist entscheidend, um Verzerrungen zu vermeiden.

4. Typische Merkmale (Features)
A) Textmerkmale
• 	Schlüsselwort‑Häufigkeit (z. B. „gratis“, „dringend“, „Gewinn“)
• 	ungewöhnliche Interpunktion oder Großschreibung
• 	verdächtige URLs
• 	sprachliche Muster typischer Bot‑Nachrichten
B) Metadaten
• 	Reputation des Absenders
• 	Versandfrequenz
• 	Domain‑/IP‑Historie
• 	zeitliche Muster
C) Verhaltensmerkmale
• 	Interaktionshistorie
• 	Klick‑Anomalien
• 	Routing‑Muster
Moderne Modelle kombinieren oft alle drei Kategorien.

5. Häufig verwendete Algorithmen
• 	Naive Bayes (klassischer Standard für Spamfilter)
• 	Logistische Regression
• 	Support Vector Machines (SVM)
• 	Random Forests
• 	Deep‑Learning‑Modelle (LSTMs, Transformer)
Naive Bayes bleibt beliebt, da Spam‑Erkennung stark von probabilistischen Annahmen und schneller Verarbeitung profitiert.

6. Evaluationsmetriken
Da Spam‑Datasets oft unausgewogen sind, stehen folgende Kennzahlen im Fokus:
• 	Precision (vermeidet fälschliche Spam‑Markierungen legitimer Nachrichten)
• 	Recall (erkennt möglichst viel Spam)
• 	F1‑Score (Balance zwischen Precision und Recall)
• 	ROC‑AUC
Besonders kritisch sind False Positives:
Legitime Nachrichten dürfen nicht blockiert werden.

7. Herausforderungen im Spam/Ham‑Training
• 	sich ständig weiterentwickelnde Spam‑Taktiken
• 	adversarial content (absichtliche Verschleierung)
• 	mehrsprachiger Spam
• 	bildbasierter Spam
• 	kontextuelle Grauzonen (z. B. Marketing vs. Betrug)
Modelle müssen kontinuierlich mit aktuellen Daten nachtrainiert werden.

8. Anwendung in meinem Portfolio
Dieses Thema zeigt meine Kompetenz in:
• 	überwachtem maschinellen Lernen
• 	binärer Klassifikation
• 	Feature Engineering
• 	Umgang mit unausgewogenen Datensätzen
• 	Evaluationsmetriken
• 	realistischen Herausforderungen bei KI‑Modellen
Es unterstreicht meine Fähigkeit, technische Konzepte klar zu erklären und auf praktische KI‑Szenarien anzuwenden — eine Schlüsselkompetenz im modernen KI‑Arbeitsumfeld.
