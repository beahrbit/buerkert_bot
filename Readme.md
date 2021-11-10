Cmd ->  conda activate installing_rasa
        rasa shell      (bot in der SHell)
        rasa run        (Server start)
        rasa train      (Bot neu trainieren)
        rasa train nlu  (nlu neun trainieren (Sprachänderung))

Notizen:
- Wenn eine Story angefangen ist, kann man keine Andere mehr starten??
- ?? ExpecTED lässt nur vorgegebene Wege/Stories zu - UnexpecTED rät welche Antwort am besten passt ??

ToDo:
- Rasa X einbinden
- Policies verstehen (z.B. UnexpecTED)
- Rasa Forms: https://www.youtube.com/watch?v=pzvBJtwCW4I 

Rasa X installation:
- cmd als Admin
- im Projektordner Conda Env aktivieren
- 'pip install SQLAlchemy==1.3.22'
- 'pip install rasa-x==0.39.3 --extra-index-url https://pypi.rasa.com/simple'
- Falls bereits vorhanden: rasa.db und events.db löschen
- 'rasa x' -> Rasa X start