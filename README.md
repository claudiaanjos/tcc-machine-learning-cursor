# Introdução ao Machine Learning com R

### Trabalho de Conclusão de Curso da Turma de Maio/22 do Curso R

O trabalho consiste em prever quem irá fazer compras na Loja Virtual Google no próximo mês.
O banco de dados original é da competição [Kaggle Google Analytics Customer Revenue Prediction](https://www.kaggle.com/c/ga-customer-revenue-prediction).

- **Task:** Classificação
- **Resposta:** target - coluna comprou
- **Critério:** AUC



**Data Fields**

fullVisitorId - A unique identifier for each user of the Google Merchandise Store.

channelGrouping - The channel via which the user came to the Store.

date - The date on which the user visited the Store.

device - The specifications for the device used to access the Store.

geoNetwork - This section contains information about the geography of the user.

socialEngagementType - Engagement type, either "Socially Engaged" or "Not Socially Engaged".

totals - This section contains aggregate values across the session.

trafficSource - This section contains information about the Traffic Source from which the session originated.

visitId - An identifier for this session. This is part of the value usually stored as the _utmb cookie. This is only unique to the user. For a completely unique ID, you should use a combination of fullVisitorId and visitId.

visitNumber - The session number for this user. If this is the first session, then this is set to 1.

visitStartTime - The timestamp (expressed as POSIX time).

hits - This row and nested fields are populated for any and all types of hits. Provides a record of all page visits.

customDimensions - This section contains any user-level or session-level custom dimensions that are set for a session. This is a repeated field and has an entry for each dimension that is set.

totals - This set of columns mostly includes high-level aggregate data.



