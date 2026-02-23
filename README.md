# Schwäbische Rechtschreibprüafong für LaTeX
## Swabian spellchecker for LaTeX - Schwäbisches Korrekturprogramm zur Rechtschreibprüfung für LaTeX

Wer kennt des net? Mr will obedengt a Gedicht oder a Gschichtle am Rechner auf onsera hiesiga Språch schreiba, aber dia Kist vôr dr aegena Nås kå bloß Englisch oder Schriftdeutsch?!?

Drom han i en mühhafter Hådarbaet ågfanga, für LaTeX (ond dådrmit ao für OpenOffice) a brandneus Wörterbuach zom schreiba. Tatsächlich håt mir dia Autokorrektur scho bei etwa 170 Wörter ågfanga, maene ôegene Tippfehler zom korrigiera. Mittlerweile send s über 3000 (dreitausad) Wörter, Tendenz steigend.

> [!NOTE]
> Dåhanna ischd a Erklärvideo auf YouTube: [https://youtu.be/roqyOnkvLRM?si=AUTqqdz6NCFPoDeE](https://youtu.be/roqyOnkvLRM?si=AUTqqdz6NCFPoDeE)


## Ålôetong (TeXstudio)
- LaTeX Distribution ralada ond installiera: [https://miktex.org/download](https://miktex.org/download),
-> drauf achta, dass mr bei dr Installation bei "Install packages on the fly" `yes` ågwählt wird, 
- TeXstudio ralada ond installiera: [https://www.texstudio.org](https://www.texstudio.org),
- Dia zwôe Dateia "schwaebisch.dic" ond "schwaebisch.aff" dåhanna ralada ond em Ordner `C:\Program Files\texstudio\dictionaries` abspeichera (Admin-Rechte notwendig),
- Em TeXstudio auf `Optionen` -> `TeXstudio konfigurieren` -> lenks-onta bei `Erweiterte Optionen` a Häkle naemacha, nå -> `Sprache prüfen` -> bei `Standardsprache` *schwaebisch* auswähla,
- TeXstudio neu starta.

## Allgemaene Hinweise
- Wann mr mit dene Wörterbüacher schafft, muaß mr d Kodierong auf **uft8** setza.  Em Zweifelsfall em Editor nômål d Kodierong prüafa.
- Des Wörterbuach ischd (bis auf kloene Åpassonga) übernomma aus dr Bibel für Schwoba (Leseprob vom Verlag: [https://shop.schwaben-kultur.de/produkt/bibel-fuer-schwoba-download](https://shop.schwaben-kultur.de/produkt/bibel-fuer-schwoba-download)).




- Der Standard håt Zaeche, mô s em Schriftdeutscha net (ond em Englischa erst recht net) geit:
  - Å, Ô, å, ô, ë.
  - Weil: s Schwäbische håt - ähnlich wia s Französische (dia hent halt 3, mir hent 2 drvo) - Nasallaute, mô mr em Schriftdeutscha net wiedergea kå.

## Nächste Schritt (en Planong):

- Weitere Wörter auffülla,
- Grammatikübersicht zsemastella (pdf),
- Grammatik weiter ausdefiniera für dia `schwaebisch.aff` Datei (z. B. Verba, mô als Aegeschaftswort vrwendat werat),
- Übersicht über dia Abweichonga aus dr Bibel für Schwoba zsemastella (pdf),  
- Oregelmäßige Tunwörter durchtschecka, vôr ällam ob se konsistent mit `schwaebisch.dic` Datei send.