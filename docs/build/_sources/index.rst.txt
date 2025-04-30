.. Documentazione_Model_Monitoring documentation master file, created by
   sphinx-quickstart on Wed Mar 26 08:53:49 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Documentazione Model Monitoring
=============================================

Model Monitoring è una libreria che si propone di monitorare vari aspetti di un algoritmo di machine learning attraverso varie metriche aiutando l'utente a monitorare le prestazioni, la spiegabilità e la fairness dei modelli ML nel tempo e il drift dei dati su cui tali modelli fanno inferenza. La libreria fornisce moduli specializzati per:

    *   **Monitoraggio del Data Drift:** Identifica quando i dati su cui il modello fa inferenza iniziano a differire significativamente dai dati di dataset di riferimento.
    *   **Monitoraggio della Fairness:** Calcola metriche chiave di fairness e rileva eventuali variazioni (drift) nel tempo, assicurando che il modello rimanga equo per diversi gruppi.
    *   **Monitoraggio delle Performance:** Calcola metriche di valutazione (per task supervisionati e non) e monitora il loro andamento per rilevare eventuali variazioni (drift) di efficacia del modello.
    *   **Monitoraggio basato su XAI:** Utilizza tecniche di Explainable AI per interpretare il comportamento del modello e per monitorare specificamente il drift nelle spiegazioni o nell'importanza attribuita alle feature.
    *   **Gestione dei Metadati:** Si occupa della creazione e l'utilizzo di metadati essenziali per i processi di monitoraggio.

Moduli
------

.. autosummary:: 
   :toctree: modules
   
   model_monitoring.data_drift
   model_monitoring.fairness_drift
   model_monitoring.fairness_measures
   model_monitoring.model_performance
   model_monitoring.performance_measures
   model_monitoring.reference_metadata
   model_monitoring.XAI
   model_monitoring.XAI_drift

Contenuti
---------
.. toctree::
   :maxdepth: 3
   :caption: Moduli:

   modules/model_monitoring.data_drift
   modules/model_monitoring.fairness_drift
   modules/model_monitoring.fairness_measures
   modules/model_monitoring.model_performance
   modules/model_monitoring.performance_measures
   modules/model_monitoring.reference_metadata
   modules/model_monitoring.XAI
   modules/model_monitoring.XAI_drift

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`