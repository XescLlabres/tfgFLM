# TFG Francesc Llabrés Massanet

Aquest repositori conté tot el codi usat en el TFG "Anàlisi de la incertesa en models d'intel·ligència artificial aplicats a dades biomèdiques". Hem dividit el codi segons en quina de les tres bases de dades s'hi enfoqui. Aquí teniu una taula resum de tots els fitxers:

## Taula d'experiments realitzats

| **Experiment**                                 | **Secció** | **Nom del fitxer**                                   | **Descripció**                                      |
|-----------------------------------------------|------------|----------------------------------------------|--------------------------------------------------|
| Model 1: Regressió logística                 | 3.1.1      | TaulaLOOCV                                  | Preprocessament i entrenament del model 1.     |
| Model 1: Avaluació                            | 3.1.2      | AvaluacioModel                              | Mètriques de rendiment del model 1.            |
| Model 1: Avaluació incertesa                  | 3.1.3      | TPUncertainty                               | Anàlisi sobre la incertesa obtinguda.          |
| Variació intervals creïbles                    | 3.1.4      | INT                                        | Modificar grau de confiança i veure com varia la incertesa. |
| Model 1: Introducció de renou                 | 3.1.5      | RENOU                                      | Introducció de renou i anàlisi de la incertesa. |
| Preprocessament                               | 3.2.1      | dadeshuse                                  | Preprocessament de nova base de dades per pacient. |
| Comprovació de mètodes d'imputació            | 3.2.1      | MitjanaModa, KNNImputer, Gower             | Comprovació i comparació dels 3 mètodes d'imputació de valors buits. |
| Model 2: Regressió logística i LASSO          | 3.2.3      | Gower3                                     | Entrenament del model amb regressió logística i LASSO. |
| Model 2: Introducció de SMOTE                 | 3.2.3      | GowerSMOTE                                 | Mateix model amb tècnica de SMOTE.             |
| Model 3: Random forest                        | 3.2.4      | RandomForest, RFtrainig                    | Entrenament del model amb random forest.       |
| Preprocessament                               | 3.3.1      | preprocestumors                            | Preprocessament de la base de dades per massa tumoral. |
| Model 4: Random forest                        | 3.3.2      | rforestMASSTUMORALS                        | Entrenament del model amb random forest.       |
| Model 5: Regressió logística                  | 3.3.3      | MASSTUMORALS                               | Entrenament del model amb regressió logística. |
| Model 5: Anàlisi incertesa                    | 3.3.4      | AnalisiMASSTUMORALS                        | Avaluació del model i de la incertesa obtinguda. |

